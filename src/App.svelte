<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>

<script lang="ts">
  export let name: string;
</script>

<main class="flex items-center justify-center h-screen">
  <div>
    <h1 class="text-7xl mb-4">Hello {name}!</h1>
    <p class:bg-red-100="{true}">
      Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.
    </p>
  </div>
</main>
