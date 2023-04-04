<script>
	import Features from '$lib/components/Features.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import Header from '$lib/components/Header.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import InstallApp from '$lib/components/InstallApp.svelte';
</script>

<div class="flex flex-col space-y-4 px-4 sm:px-8 md:px-16 lg:px-24 xl:px-60">
	<Header />
	<Hero />
	<Features />
	<InstallApp />
</div>
<Footer />