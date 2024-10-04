<script lang="ts">
  import Threes from '$lib/Threes.svelte';
  import BranchAdder from '$lib/BranchAdder.svelte';
</script>

<main>
  <h1>Mind Map</h1>
  <div class="mind-map-container">
    <Threes />
    <BranchAdder />
  </div>
</main>

<style>
  .mind-map-container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-top: 2rem;
  }
</style>