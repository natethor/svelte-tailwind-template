<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<div class="flex items-center justify-center">
  <button
    type="button"
    class="bg-orange-900 border rounded-md mx-1 hover:bg-orange-600 hover:scale-105 transition duration-150 ease-in-out"
    on:click={increment}
  >
    <div class="p-1">Increment</div>
  </button>
  Count: {count}
</div>
