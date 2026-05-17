<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import NavBar from '$lib/components/shared/NavBar.svelte';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<NavBar />
<div class="container max-w-5xl mx-auto">
	{@render children()}
</div>
