<script>
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import '../app.css';
</script>

<Header />
<div class="relative w-full min-h-screen bg-zinc-900">
	<div class="flex flex-col space-y-4 mx-auto px-4 sm:px-12 max-w-6xl pt-12 md:pt-24 pb-24 md:pb-48">
		<slot />
	</div>
</div>
<Footer />
