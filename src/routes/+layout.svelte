<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<div class="mx-auto xl:max-w-3/4">
    <h1 class="text-center text-2xl sm:text-3xl font-semibold font-[Space_Grotesk_Variable] mb-2 mt-3">Svelte News</h1>
</div>

{@render children()}