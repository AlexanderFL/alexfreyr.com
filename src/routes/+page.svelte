<div class="bg-gradient-to-tr from-slate-800 to-slate-900">
	<div class="h-screen flex flex-col justify-center text-center text-blue-50">
		<main>
			<h2>For any inquiries</h2>
			<h1 class="font-bold text-3xl">
				<a href="mailto:alex@alexfreyr.com">
					<span class="un">alex@alexfreyr.com</span>
				</a>
			</h1>
		</main>
	</div>
</div>

<style lang="postcss">
	:global(html) {
		font-family: 'Inter', 'sans-serif';
	}

	.un {
		display: inline-block;
		padding-bottom: 2px;
		background-image: linear-gradient(theme(colors.slate.50) 0 0);
		background-position: 0 100%;
		background-size: 0% 2px;
		background-repeat: no-repeat;
		transition: background-size 0.3s, background-position 0s 0.3s;
	}

	.un:hover {
		background-position: 100% 100%;
		background-size: 100% 2px;
	}
</style>
