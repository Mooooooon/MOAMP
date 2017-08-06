<template>
    <div id="app" style="-webkit-app-region: drag">
        <router-view></router-view>
    </div>
</template>

<script>
  export default {
    name: 'moamp'
  }
</script>

<style>
    button {
        -webkit-app-region: no-drag;
    }
</style>
