<template>
    <div id="app" class="app" style="-webkit-app-region: drag">
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

    button {
        -webkit-app-region: no-drag;
    }

    .titlebar {
        -webkit-user-select: none;
        -webkit-app-region: drag;
    }
</style>
