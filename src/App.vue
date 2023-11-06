<!--
 * @Author: cbw
 * @Date: 2023-11-06 19:06:42
 * @LastEditors: cbw
 * @LastEditTime: 2023-11-06 19:08:46
 * @Description: 
-->
<template>
  <div id="app">
    <DropDown>
      <h1>你好</h1>
      <h1>你好</h1>
      <h1>你好</h1>
      <h1>你好</h1>
      <h1>你好</h1>
      <h1>你好</h1>

      <div slot="overlay" class="menu"></div>
    </DropDown>
  </div>
</template>

<script>


export default {
    name: 'App',
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

.menu{
  background-color: rosybrown;
  width: 100px;
  height: 100px;
}
</style>
