<template>
  <div id="solar-system" class="earth">
    <sun></sun>
    <slot></slot>
  </div>
</template>

<script>
  import Sun from './Sun'

  export default {
    name: 'SolarSystem',
    components: { Sun }
  }
</script>
