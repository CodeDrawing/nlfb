<template>
  <div id="menu">
<el-row class="tac">
  <el-col :span="12">
    <h5>能力风暴</h5>
    <el-menu
      default-active="2"
      class="el-menu-vertical-demo"
      @open="handleOpen"
      @close="handleClose">
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>学生管理</span>
        </template>
        <el-menu-item-group>
          <el-menu-item index="1-1">学生信息查询</el-menu-item>
          <el-menu-item index="1-2">学生管理</el-menu-item>
          <el-menu-item index="1-3">添加学生</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
      <el-menu-item index="2">
        <i class="el-icon-menu"></i>
        <span slot="title">员工管理</span>
        <el-menu-item-group>
          <el-menu-item index="2-1">员工信息查询</el-menu-item>
          <el-menu-item index="2-2">员工管理</el-menu-item>
          <el-menu-item index="2-3">添加员工</el-menu-item>
        </el-menu-item-group>
      </el-menu-item>
      <el-menu-item index="3">
        <i class="el-icon-menu"></i>
        <span slot="title">后台管理</span>
        <el-menu-item-group>
          <el-menu-item index="3-1">管理员登陆</el-menu-item>

        </el-menu-item-group>
      </el-menu-item>
    </el-menu>
  </el-col>
</el-row>
  </div>
</template>
<script>
  export default {
    methods: {
      handleOpen(key, keyPath) {
        console.log(key, keyPath);
      },
      handleClose(key, keyPath) {
        console.log(key, keyPath);
      }
    }
  }
</script>
<style>
  menu {
    padding-top: 20%;
    width: 30%;
  }
</style>
