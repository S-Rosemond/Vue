<template>
  <div id="app">
    <Header></Header>
    <router-view/>
  </div>
</template>


<script>
import Header from "./components/layout/Header.vue";

export default {
  name: "app",
  components: {
    Header
  }
};
</script>


<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}

.btn {
  display: inline-block;
  border: none;
  background: #555;
  color: #fff;
  padding: 12px 20px;
  cursor: pointer;
}
.btn:hover {
  background: #666;
}
</style>
