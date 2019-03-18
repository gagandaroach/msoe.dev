<template>
<div>
    <DevHeader/>
  <el-container>
      <DevNavbar/>
      <el-main>
        <el-row>
          <el-alert
            :span="24"
            title="Site is a Work in Progress. Contact gagandaroach@gmail.com with any questions or suggestions."
            type="warning"
          ></el-alert>
        </el-row>
        <About />
      </el-main>
  </el-container>
</div>
</template>

<script>
import About from "./components/About.vue";
import DevHeader from "./components/DevHeader.vue";
import DevNavbar from "./components/DevNavbar.vue";

console.log("Starting instance @ " + Date(Date.now()));

export default {
  name: "app",
  components: {
    About,
    DevHeader,
    DevNavbar
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
