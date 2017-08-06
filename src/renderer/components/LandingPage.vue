<template>
  <div id="wrapper" class="wrapper">
    <div class="button-group">
      <div class="button-group-item">

      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'landing-page'
  }
</script>

<style>
  .wrapper {
    color: #1F2D3D;
    height: 100%;
    background-color: #F9FAFC;
  }

  .button-group {
    background-color: #8492A6;
    height: 30px;
    width: 100%;
    position: fixed;
    right: 0;
    top: 0;
    -webkit-app-region: drag;
    .button-group-item {
      float: right;
      width: 50px;
      height: 30px;
      background: #475669 url("../assets/close.png") no-repeat center;
    }
  }
</style>
