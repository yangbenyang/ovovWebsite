<template>
    <el-container class="h-full">
        <el-header class="border-solid border-red-500 border-2">
            <Navbar></Navbar>
        </el-header>
        <el-container>
            <el-aside width="200px" class="border-2 border-red-500 border-solid">
                <Sidebar></Sidebar>
            </el-aside>
            <el-main>
                <AppMain></AppMain>
            </el-main>
        </el-container>
    </el-container>
</template>

<script setup>
import AppMain from './AppMain/index.vue'
import Navbar from './Navbar/index.vue'
import Sidebar from './Sidebar/index.vue'
</script>
  