<script setup>
import Sidebar from"./components/Sidebar.vue"
import Rightside from "./components/Rightside.vue"
</script>



<template>
  <div class="flex">
    <div class="w-1/6">
      <Sidebar/>
      </div>
    <div class="w-5/6">
      <Rightside/>
      
    </div>
  </div>
</template>