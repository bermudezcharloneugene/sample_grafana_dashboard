<script setup lang="ts">
//Placeholder
const EMBEDDED_LINK =
  'https://ramosbermudezcharloneugene.grafana.net/d-solo/f41e046e-928f-4c5e-9a12-cd1fbd79609e/business-health?orgId=1&from=1712973328456&to=1712994928456&panelId=7'
</script>

<template>
  <div class="dashboard-wrapper" id="dashboard">
    <iframe v-bind:src="EMBEDDED_LINK" frameborder="1" :width="'100%'" :height="'1200px'"></iframe>
  </div>
</template>

<style>
.dashboard-wrapper {
  width: 100%;
}
</style>
