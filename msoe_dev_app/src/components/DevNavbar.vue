<template>
  <el-aside>
    <el-menu
      default-active="1"
      class="el-menu-vertical-demo"
      @open="handleOpen"
      @close="handleClose"
    >      
      <el-menu-item index="1">
        <template slot="title">
          <i class="el-icon-info"></i>
          <span>About</span>
        </template>
      </el-menu-item>
      <el-menu-item index="2" disabled>
        <i class="el-icon-check"></i>
        <span>Sign Up</span>
      </el-menu-item>
      <el-submenu index="3" disabled>
        <template slot="title">
          <i class="el-icon-document"></i>
          <span>Resume Templates</span>
        </template>
        <el-menu-item-group >
          <el-menu-item index="3-1">item one</el-menu-item>
          <el-menu-item index="3-2">item one</el-menu-item>
        </el-menu-item-group>
        </el-submenu>
    </el-menu>
  </el-aside>
</template>

<script>
export default {
  name: "DevNavbar",
  data() {
    return {
      activeIndex: "1"
      }
    },
     methods: {
        handleOpen(key, keyPath) {
          console.log(key, keyPath);
        },
        handleClose(key, keyPath) {
          console.log(key, keyPath);
        },
        handleSelect(key, keyPath) {
          console.log(key, keyPath);
        }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
