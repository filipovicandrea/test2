<script setup lang="ts">
import { RouterView } from 'vue-router'
import SidebarMenu from './components/SidebarMenu.vue'
import MainHeader from './components/MainHeader.vue'
</script>

<template>
  <div>
    <SidebarMenu/>   
    <MainHeader/>
    <div class="w-full h-[calc(100vh-50px)] main">
      <RouterView/>
    </div>
  </div>

</template>

<style scoped>
#app{
  text-align: center;
}
.main-content {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}
</style>
