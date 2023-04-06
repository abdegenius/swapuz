<script>
	import { goto } from '$app/navigation';

	let menu;
	$: menu = false;
</script>

<header class="fixed h-16 w-full bg-zinc-900 z-40 mx-auto top-0">
	<nav class="flex justify-center items-center ">
		<div class="flex pt-6 flex-row justify-between items-center w-full px-4 sm:px-12 max-w-6xl">
			<div class="w-1/5 md:hidden flex justify-start items-start">
				<div
					on:click|preventDefault={() => (menu = true)}
					class="inline-flex text-center px-2 py-1 bg-zinc-800 rounded-md"
				>
					<i class="fas fa-1x text-2xl fa-bars text-primary" />
				</div>
			</div>
			<div class="w-3/5 md:w-1/4 lg:w-1/5 xl:w-1/6 flex justify-center md:justify-start">
				<h1 class="text-white text-2xl font-black">LOGO</h1>
			</div>
			<div
				class="hidden max-w-none md:w-2/4 lg:w-3/5 xl:w-4/6 md:flex justify-center items-center md:space-x-4 lg:space-x-8 xl:space-x-12"
			>
				<span
					class="text-sm xl:text-md font-bold text-white cursor-pointer"
					on:click={() => {
						menu = false;
						goto('/');
					}}>Home</span
				>
				<span
					class="text-sm xl:text-md font-bold text-white cursor-pointer"
					on:click={() => {
						menu = false;
						goto('/about-us');
					}}>About</span
				>
				<span
					class="text-sm xl:text-md font-bold text-white cursor-pointer"
					on:click={() => {
						menu = false;
						goto('/contact-us');
					}}>Contact</span
				>
				<span
					class="text-sm xl:text-md font-bold text-white cursor-pointer"
					on:click={() => {
						menu = false;
						goto('/login');
					}}>Log In</span
				>
			</div>
			<div class="w-1/5 md:w-1/4 lg:w-1/5 xl:w-1/6 flex justify-end items-center">
				<div class="inline-flex justify-between items-center space-x-4">
					<img src="/flag.png" alt="naija flag" class="w-6 h-4" />
					<span class="hidden md:block text-primary text-sm font-bold">Nigeria</span>
					<span class="block md:hidden text-white cursor-pointer text-sm font-bold">NG</span>
				</div>
			</div>
		</div>
	</nav>
</header>
<div class="w-full my-6 block"></div>
<div
	class="{menu
		? 'block'
		: 'hidden'} fixed top-0 left-0 inset-0 w-screen min-h-screen z-50 bg-zinc-900 md:hidden"
>
	<div class="flex justify-between items-center p-4">
		<div class="w-fit flex justify-start items-center space-x-4 bg-zinc-800 px-4 py-2 rounded-md">
			<div class="inline-flex justify-between items-center space-x-4">
				<img src="/flag.png" alt="naija flag" class="w-6 h-4" />
				<span class="text-primary text-md font-bold">Nigeria</span>
			</div>
		</div>
		<div on:click|preventDefault={() => menu = false}
			class="w-fit flex justify-end items-center space-x-4 bg-zinc-800 px-4 py-1 rounded-md"
		>
			<i class="fas fa-1x text-2xl fa-times text-primary" />
		</div>
	</div>

	<div
		class="flex flex-col mx-auto space-y-6 justify-center items-center inset-y-0 absolute inset-x-0"
	>
		<span
			class="text-lg font-bold text-white cursor-pointer"
			on:click={() => {
				menu = false;
				goto('/');
			}}>Home</span
		>
		<span
			class="text-lg font-bold text-white cursor-pointer"
			on:click={() => {
				menu = false;
				goto('/about-us');
			}}>About</span
		>
		<span
			class="text-lg font-bold text-white cursor-pointer"
			on:click={() => {
				menu = false;
				goto('/contact-us');
			}}>Contact</span
		>
		<span
			class="text-lg font-bold text-white cursor-pointer"
			on:click={() => {
				menu = false;
				goto('/login');
			}}>Log In</span
		>
	</div>
</div>
