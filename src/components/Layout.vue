<template>
  <div class="fixed top-0 left-0 z-40 h-screen">
    <Sidebar class="pt-[70px]" />
  </div>
  <Navbar />
</template>

<script setup>
import Navbar from "../components/Navbar.vue";
import Sidebar from "../components/Sidebar.vue";
</script>
