<script>
	export let name;
</script>

<main class="text-center p-4 m-0 max-w-xs sm:max-w-none">
	<h1 class="uppercase text-red-600 text-7xl font-thin">Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>