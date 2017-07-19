<template>
  <div id="controls">
    <label class="set-view">
      <input type="checkbox">
    </label>
    <label class="set-zoom">
      <input type="checkbox">
    </label>
    <label>
      <input type="radio" class="set-speed" name="scale" checked>
      <span>Speed</span>
    </label>
    <label>
      <input type="radio" class="set-size" name="scale">
      <span>Size</span>
    </label>
    <label>
      <input type="radio" class="set-distance" name="scale">
      <span>Distance</span>
    </label>
  </div>
</template>

<script>
  export default {
    name: 'Controls'
  }
</script>