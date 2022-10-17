<script>
	import MenuList from "./components/MenuList.svelte";

	const backgrounds = ["corruption", "crimson", "forest", "hallow", "jungle", "mountain", "mushroom"];
	const randBackground = backgrounds[Math.floor(Math.random() * backgrounds.length)];
	const url = `/images/${randBackground}.png`;
</script>

<main style="background-image:url({url})">
	<MenuList />
</main>

<style>
	main {
		background-repeat: no-repeat;
		background-size: 100% auto;
		height: 100%;
	}
</style>