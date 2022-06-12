<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import List from '../components/List.vue'
</script>

<template>
    <a-layout>
    <a-layout-header :style="{ position: 'fixed', zIndex: 1, width: '100%', background:'#4CC764' }">找美食</a-layout-header>
    <a-layout-content :style="{ padding: '0 50px', marginTop: '64px' }"><List /></a-layout-content>
    <a-layout-footer :style="{background:'#4CC764'}">Footer</a-layout-footer>
  </a-layout>
</template>
 
 