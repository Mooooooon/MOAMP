<template>
    <div id="app" class="app">
        <router-view></router-view>
    </div>
</template>

<script>
  export default {
    name: 'moamp'
  }
</script>

<style>
    @import "~normalize.css";

    html, body, .app {
        height: 100%;
        width: 100%;
    }
</style>
