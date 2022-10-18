<script></script>

<ul class="menu-list">
    <li>Download World</li>
    <li>Upload World</li>
    <li>Todos</li>
    <li><a href="https://terraria.wiki.gg/wiki/Terraria_Wiki" target="#">Terraria Wiki</a></li>
</ul>

<style>
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
        font-size: 3rem;
        color: #909194;
        -webkit-text-stroke: 1.5px black;
	}

    .menu-list > li {
        transition: 0.2s;
        padding: 10px;
    }

    .menu-list > li > a {
        color: inherit;
        text-decoration: none;
        font-size: inherit;
        -webkit-text-stroke: inherit;
    }

    .menu-list > li:hover {
        color: #ffd700;
        font-size: 4rem;
        -webkit-text-stroke: 2px black;
    }
</style>