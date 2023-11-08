<template>
  <div id="app">
    <div class="header">
      <DropDown>
        <h1>点击</h1>
        <template v-slot:overlay>
          <div class="show"></div>
        </template>
      </DropDown>
    </div>
    <div class="left">
      <DropDown>
        <h1>点击</h1>
        <template v-slot:overlay>
          <div class="show"></div>
        </template>
      </DropDown>
    </div>

    <div class="content">
      <DropDown>
        <h1>点击</h1>
        <template v-slot:overlay>
          <div class="show"></div>
        </template>
      </DropDown>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  width: 100%;
  height: 100%;
  display: flex;
  flex-wrap: wrap;
}
.header {
  height: 100px;
  width: 100%;
  background-color: antiquewhite;
}

.left {
  width: 100px;
  height: calc(100% - 100px);
  background-color: burlywood;
}

.content {
  flex: 1;
  background-color: rgb(153, 161, 158);
}

html,
body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}

.show {
  width: 60px;
  height: 100px;
  background-color: #00eeff5b;
}
</style>
