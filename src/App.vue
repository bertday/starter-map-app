<script setup>
import Navbar from './components/Navbar.vue';
import OptionsPanel from './components/OptionsPanel.vue';
import MapPanel from './components/MapPanel.vue';
</script>

<template>
  <div class="flex flex-col h-screen">
    <Navbar />

    <main class="flex flex-grow">
      <OptionsPanel />
      <MapPanel />
    </main>
  </div>
</template>
