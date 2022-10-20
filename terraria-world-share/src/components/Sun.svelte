<div class="sun-wrapper">
    <img class="sun" src="/images/sun.png" alt="sun" />
</div>

<style>

    .sun{
        width: 50px;
        height: 50px;
    }
    .sun-wrapper {
        position: absolute;
        z-index: 4;
        width: 140vw;
        height: 1vh;
        top: 90%;
        left: -20%;
        animation: rotateSun linear 8s infinite;
    }

    @keyframes rotateSun {
        0% {
            transform: rotate(0deg);
        }
        10% {
            transform: rotate(50deg);
        }
        80% {
            transform: rotate(130deg);
        }
        90% {
            transform: rotate(270deg);
        }
        100% {
            transform: rotate(360deg);
        }

    }
</style>