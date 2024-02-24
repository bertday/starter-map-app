<script setup>
import maplibregl from 'maplibre-gl';
import { onMounted } from 'vue';
import 'maplibre-gl/dist/maplibre-gl.css';

let map;

onMounted(() => {
  map = new maplibregl.Map({
    container: 'map',
    style: `https://demotiles.maplibre.org/style.json`,
    center: [-75, 40],
    zoom: 7,
    minZoom: 6,
    maxZoom: 17,
  });
});
</script>

<template>
  <div class="bg-blue-950 flex-grow">
    <div id="map" class="h-full" />
  </div>
</template>
