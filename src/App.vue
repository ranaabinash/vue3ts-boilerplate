<script lang="ts">
  import { defineComponent, onMounted } from '@vue/runtime-core'

  export default defineComponent({
    setup() {},
  })
</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <router-view></router-view>
</template>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
