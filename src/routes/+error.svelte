<script lang="ts">
	import { page } from '$app/stores';
</script>

<div class="bg-gray-950 h-screen text-blue-50">
    <div class="h-screen flex flex-col justify-center text-center">
        {#if $page.error}
            <h1 class="text-3xl font-bold tracking-tighter">{$page.status} {$page.error.message}</h1>
            {#if $page.status === 404}
                <p class="text-sm">What were you looking for? <a href="/" class="underline font-medium">Go back</a></p>
            {/if}
        {/if}
    </div>
</div>
