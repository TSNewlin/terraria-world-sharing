<script>
	import MenuList from "./components/MenuList.svelte";

	// const backgrounds = ["corruption", "crimson", "forest", "hallow", "jungle", "mountain", "mushroom"];
	// const randBackground = backgrounds[Math.floor(Math.random() * backgrounds.length)];
	const backgroundUrl = `/images/corruption-bg.png`;
	const foregroundUrl = `/images/corruption-fg.png`
</script>

<main style="background-image:url({backgroundUrl})">
	<div class="foreground" style="background-image:url({foregroundUrl})" />
	<MenuList />
</main>

<style>
	main, .foreground {
		background-repeat: no-repeat;
		background-size: 100% auto;
		height: 100%;
	}
</style>