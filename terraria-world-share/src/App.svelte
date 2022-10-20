<script>
	import MenuList from "./components/MenuList.svelte";
	import Tasks from "./components/Tasks.svelte";
	import Airship from "./components/Airship.svelte";

	// const backgrounds = ["corruption", "crimson", "forest", "hallow", "jungle", "mountain", "mushroom"];
	// const randBackground = backgrounds[Math.floor(Math.random() * backgrounds.length)];
	const backgroundUrl = `/images/corruption-bg.png`;
	const foregroundUrl = `/images/corruption-fg.png`
</script>

<main style="background-image:url({backgroundUrl})">
	<Tasks/>
	<Airship/>
	<div class="foreground" style="background-image:url({foregroundUrl})" />
	<MenuList />
</main>

<style>
	main, .foreground {
		background-repeat: no-repeat;
		background-size: cover;
		height: 100%;
		background-position: center center;
		background-attachment: fixed;
	}


</style>