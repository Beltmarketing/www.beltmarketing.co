<script setup>
import Header from "@/components/Header.vue";
import CustomCursor from "@/components/CustomCursor.vue";
import { Analytics } from '@vercel/analytics/vue';
</script>

<template>
  <Analytics/>
  <router-view ></router-view>
  <CustomCursor/>
</template>

<style scoped>
body {
  cursor: none;
}
</style>
