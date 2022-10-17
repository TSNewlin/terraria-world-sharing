<script>
	const backgrounds = ["corruption", "crimson", "forest", "hallow", "jungle", "mountain", "mushroom"];
	const randBackground = backgrounds[Math.floor(Math.random() * backgrounds.length)];
	const url = `/images/${randBackground}.png`;
</script>

<main style="background-image:url({url})">
	<ul>
		<li>Download World</li>
		<li>Upload World</li>
		<li>Todos</li>
		<li>Terraria Wiki</li>
	</ul>
</main>

<style>
	main {
		background-repeat: no-repeat;
		background-size: 100% auto;
		height: 100%;
	}
</style>