<!-- This layout applies to any route at the same depth in this folder. -->
<script lang="ts">
	import Header from '$lib/header/index.svelte';
	import Footer from '$lib/footer/index.svelte';
	import '../app.css';
</script>

<div class="flex flex-col h-screen">
	<Header />
	<main class="grow">
		<slot />
	</main>
	<Footer />
</div>
