<!--
 * @Author: your name
 * @Date: 2020-11-11 08:11:39
 * @LastEditTime: 2020-11-11 08:14:42
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \日考2\app\src\App.vue
-->
<template>
  <div id="app">
    <Home></Home>
  </div>
</template>

<script>
import Home from "@/components/Home"

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

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
