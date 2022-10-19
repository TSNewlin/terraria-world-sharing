<div class="sun-wrapper">
    <img src="/images/sun.png" alt="sun" />
</div>

<style>
    .sun-wrapper {
        position: absolute;
        z-index: 0;
        width: 90vw;
        height: 1vh;
        top: 50%;
		left: 50%;
        animation: rotateSun linear 5s infinite;
    }

    .sun-wrapper, .sun-wrapper > img {
        overflow: hidden;
    }

    @keyframes rotateSun {
        from {
            transform: rotate(0deg);
        }
        to {
            tranform: rotate(360deg);
        }
    }
</style>