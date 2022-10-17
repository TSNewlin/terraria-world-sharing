<script>
	const backgrounds = ["corruption", "crimson", "forest", "hallow", "jungle", "mountain", "mushroom"];
	const randBackground = backgrounds[Math.floor(Math.random() * backgrounds.length)];
	const url = `/images/${randBackground}.png`;
</script>

<main style="background-image:url({url})">
	<ul class="menu-list">
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

	@font-face {
		font-family: andy;
		src: url("/fonts/andyb.TTF")
	}

	.menu-list {
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		display: flex;
		align-items: center;
		flex-direction: column;
		font-family: andy;
	}
</style>