<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import Counter from "./components/Counter.svelte";

  export let name: string;
</script>

<main class="min-w-max p-1 flex items-center">
  <div class="space-y-2 justify-items-center">
    <div class="flex items-center space-x-2">
      <a href="https://svelte.dev" target="_blank">
        <img src={svelteLogo} class="logo" alt="Svelte Logo" />
      </a>
      <h1 class="uppercase text-orange-600 font-bold text-5xl">Hello {name}!</h1>
    </div>
    <p>
      Visit the
      <a class="font-bold hover:font-extrabold" href="https://svelte.dev/tutorial">
        Svelte tutorial
      </a>
      to learn how to build Svelte apps.
    </p>
    <Counter />
  </div>
</main>
