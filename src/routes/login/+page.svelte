<script>
</script>

<div class="pt-12 lg:pt-24">
	<div
		class="max-w-4xl w-full bg-zinc-800/50 flex justify-center items-center lg:justify-between lg:items-stretch rounded-xl mx-auto"
	>
		<div
			class="relative rounded-l-xl hidden lg:flex lg:flex-col lg:space-y-6 bg-green-500 w-full lg:w-2/5"
		>
			<div class="mt-12 px-8">
				<h1 class="text-5xl font-black text-zinc-900 mb-4">Login an account</h1>
				<p class="text-md font-normal text-zinc-800">
					Get access to endless opportunities as a affiliate
				</p>
			</div>
			<div class="absolute mt-12 left-0 bottom-0">
				<img src="/auth.png" alt="auth" class="w-auto h-auto" />
			</div>
		</div>
		<div
			class="rounded-r-xl w-full bg-transparent lg:w-3/5 p-5 flex flex-col space-y-6 items-center"
		>
			<div class="justify-between flex items-center space-x-24 md:space-x-32 py-6">
				<a href="signup"  class="text-lg font-black text-zinc-600 pb-4 text-center inline-flex">Sign up</a>
				<a href="login"  class="text-lg font-black text-green-500 pb-4 border-b-4 border-green-500 text-center inline-flex">Sign in</a>
			</div>
			<form class="w-full flex flex-col space-y-4 justify-start px-4">
				<div
					class="w-full flex flex-row space-x-2 bg-zinc-700/50 rounded-xl text-zinc-400 border-2 border-transparent focus:border-green-500 hover:border-green-500 focus:text-green-500 hover:text-green-500"
				>
					<div class="w-4 p-4">
						<i class="fal fa-at text-2xl" />
					</div>
					<input
						type="text"
						placeholder="Email Address"
						class="w-full p-4 bg-transparent border-none shadow-none outline-none select-none appearance-none placeholder:text-zinc-400 text-sm text-zinc-100 font-bold"
					/>
				</div>
				<div
					class="w-full flex flex-row space-x-2 bg-zinc-700/50 rounded-xl text-zinc-400 border-2 border-transparent focus:border-green-500 hover:border-green-500 focus:text-green-500 hover:text-green-500"
				>
					<div class="w-4 p-4">
						<i class="fal fa-lock text-2xl" />
					</div>
					<input
						type="password"
						placeholder="Your password"
						class="w-full p-4 bg-transparent border-none shadow-none outline-none select-none appearance-none placeholder:text-zinc-400 text-sm text-zinc-100 font-bold"
					/>
				</div>
				<div class="pt-8 pb-4">
					<button
						class="w-full py-5 bg-green-500 text-center text-md font-bold text-zinc-800 rounded-xl"
						>Sign In</button
					>
				</div>
				<p class="text-center font-bold text-lg text-green-600">
					<a href="reset-password">Forgot Password?</a>
				</p>
			</form>
		</div>
	</div>
</div>
