<template>
  <div id="app" style="height: 100vh">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
ul {
  list-style: none;
}
a {
  text-decoration: none;
}
* {
  margin: 0;
  padding: 0;
}
#app {
  height: 100vh;
  font-family: "Microsoft YaHei", "Helvetica", "Tahoma", "Geneva", "Arial",
    sans-serif;
  background-color: #eee;
}
</style>
