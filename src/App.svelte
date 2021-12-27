<script>
	import NavBar from "./library/navbarComponents/NavBar.svelte";
	 let name = "fuck!! it works!";
</script>
<NavBar />

<main>
	<h1>Bollocks!!</h1>
	<p>{name}</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>