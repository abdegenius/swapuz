<script>
</script>

<div class="pt-12 lg:pt-24">
	<div
		class="max-w-4xl w-full bg-zinc-800/50 flex justify-center items-center lg:justify-between rounded-xl mx-auto"
	>
		<div
			class="relative rounded-l-xl hidden lg:flex lg:flex-col lg:space-y-6 bg-primary w-full lg:w-2/5"
		>
			<div class="mt-12 px-8">
				<h1 class="text-5xl font-black text-zinc-900 mb-4">Reset password</h1>
				<p class="text-md font-normal text-zinc-800">
					Please follow the instructions in your mailbox to reset the password
				</p>
			</div>
			<div class="mt-12 left-0 bottom-0">
				<img src="/auth.png" alt="auth" class="w-auto h-auto" />
			</div>
		</div>
		<div
			class="rounded-r-xl w-full bg-transparent lg:w-3/5 p-5 flex flex-col space-y-6 items-center"
		>
			<form class="w-full flex flex-col space-y-4 justify-start px-4">
				<div
					class="w-full flex flex-row space-x-2 bg-zinc-700/50 rounded-xl text-zinc-400 border-2 border-transparent focus:border-primary hover:border-primary focus:text-primary hover:text-primary"
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
				<div class="pt-8 pb-4">
					<button
						class="w-full py-5 bg-primary text-center text-md font-bold text-zinc-800 rounded-xl"
						>Continue</button
					>
				</div>
				<p class="text-center font-bold text-lg text-primary">
					<a href="login">Back to login</a>
				</p>
			</form>
		</div>
	</div>
</div>
