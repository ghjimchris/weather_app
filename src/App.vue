import { RouterView } from 'vue-router';
<template>
  <div class="flex-col min-h-screen font-Roboto bg-wheather-primary">
    <SiteNavigation />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from "vue-router";
import SiteNavigation from "./components/SiteNavigation.vue";
</script>
