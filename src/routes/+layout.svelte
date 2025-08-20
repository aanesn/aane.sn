<script lang="ts">
	import Header from "$lib/components/Header.svelte"
	import "../app.css"

	let { children } = $props()
</script>

<div class="container mx-auto max-w-2xl scroll-smooth px-6">
	<Header />
	{@render children?.()}
</div>
