<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import List from '../components/List.vue'
</script>

<template>
    <a-layout>
    <a-layout-header :style="{ position: 'fixed', zIndex: 1, width: '640px', height: '120px', background:'#fff' }"><!-- color:#4CC764 -->
    找美食
      <a-input-search
      v-model:value="value"
      placeholder="input search text"
      enter-button="Search"
      size="large"
      @search="onSearch"
    />
    </a-layout-header>
    <a-layout-content :style="{ padding: '0 50px', marginTop: '120px' }"><List /></a-layout-content>
    <a-layout-footer :style="{background:'#fff'}">Footer</a-layout-footer>
  </a-layout>
</template>
 
 