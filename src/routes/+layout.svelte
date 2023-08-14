<script>
	import '../app.css';
</script>

<nav class="bg-slate-800">
	<a href="/">home</a>
	<a href="/user">users</a>
</nav>
<slot />

<style>
	nav {
		border-radius: 10px;
		margin: 5px;
		padding: 5px;
	}
	a {
		margin: 5px;
		color: white;
		text-decoration: none;
	}
</style>
