<script>
	import {count} from "$lib/store"
</script>

<h1>user</h1>
<p>count is {$count}</p>
<button on:click={()=>$count++} >add +</button>
