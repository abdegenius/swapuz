<script>
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import '../app.css';
</script>

<div class="relative w-full min-h-screen bg-zinc-900">
	<div class="flex flex-col space-y-4 mx-auto px-4 sm:px-12 max-w-6xl">
        <Header />
		<slot />
	</div>
	<Footer />
</div>
