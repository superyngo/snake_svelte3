<script lang="ts">
  import Snake from "./lib/snake.svelte";
</script>

<div class="wrapper">
  <Snake canvasWidth={10} canvasHeight={10} speed={3} />
</div>

<style>
  .wrapper {
    position: relative;
    height: 100vh;
  }
</style>
