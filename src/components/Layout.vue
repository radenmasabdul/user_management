<template>
  <div class="fixed top-0 left-0 z-40 h-screen">
    <Sidebar class="pt-[70px]" />
  </div>
  <Navbar />
  <div class="pt-20 sm:pl-[350px] sm:pr-8">
    <ContentVue />
  </div>
</template>

<script setup>
import Navbar from "../components/Navbar.vue";
import Sidebar from "../components/Sidebar.vue";
import ContentVue from "./Content.vue";
</script>
