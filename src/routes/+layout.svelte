<script lang="ts">
	import './layout.css';
	import favicon from '/images/favicon.png';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>ship projects, get prizes</title>
</svelte:head>

{@render children()}
