<script lang="ts">
	import { page } from '$app/stores';
</script>

<div class="h-screen bg-gray-950 text-blue-50">
	<div class="flex h-screen flex-col justify-center text-center">
		{#if $page.error}
			<h1 class="text-3xl font-bold tracking-tighter">{$page.status} {$page.error.message}</h1>
			{#if $page.status === 404}
				<p class="text-sm">
					What were you looking for? <a href="/" class="font-medium underline">Go back</a>
				</p>
			{/if}
		{/if}
	</div>
</div>
