<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<script>
	import {count} from "$lib/store"
</script>

<h1>user</h1>
<p>count is {$count}</p>
<button on:click={()=>$count++} >add +</button>