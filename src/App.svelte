<script>
	import Grid from './Grid.svelte';
	import Sidebar from './Sidebar.svelte';
	import Gamebar from './Gamebar.svelte';
</script>
<style>
	:global(body){
		background-color: #111d26;
		color: #bfc2c7;
		font-family: sans-serif;
		margin: 0%;
	}
</style>
<main>
	<Sidebar/>
	<Grid/>
	<Gamebar/>
</main>