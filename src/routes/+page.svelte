<div class="bg-gradient-to-tr from-slate-800 to-slate-900">
	<div class="flex h-screen flex-col justify-center text-center text-blue-50">
		<main>
			<h2>For any inquiries</h2>
			<h1 class="text-3xl font-bold">
				<a href="mailto:alex@alexfreyr.com">
					<span class="un">alex@alexfreyr.com</span>
				</a>
			</h1>
		</main>
	</div>

	<footer class="fixed bottom-4 w-full">
		<div class="float-right mr-4 flex flex-row gap-4">
			<a href="https://github.com/AlexanderFL/alexfreyr.com">
				<img
					src="./github-mark-white.png"
					alt="github-logo"
					class="w-[30px] opacity-70 transition duration-500 ease-in-out hover:opacity-100"
				/>
			</a>
			<a href="https://stackoverflow.com/users/5258419/alexander-freyr">
				<img
					src="./so-logo.png"
					alt="github-logo"
					class="w-[30px] opacity-70 transition duration-500 ease-in-out hover:opacity-100"
				/>
			</a>
		</div>
	</footer>
</div>

<style lang="postcss">
	:global(html) {
		font-family: 'Inter', 'system-ui', 'sans-serif';
	}

	.un {
		display: inline-block;
		padding-bottom: 2px;
		background-image: linear-gradient(theme(colors.blue.50) 0 0);
		background-position: 0 100%;
		background-size: 0% 2px;
		background-repeat: no-repeat;
		transition:
			background-size 0.3s,
			background-position 0s 0.3s;
	}

	.un:hover {
		background-position: 100% 100%;
		background-size: 100% 2px;
	}
</style>
