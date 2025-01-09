<script>
	import Header from '../stories/Header.svelte';
	let { children } = $props();
</script>

<Header />

{@render children()}
