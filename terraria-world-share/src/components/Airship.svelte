<script></script>

<div class="airship-wrapper">
    <img class="airship" src="/images/airship.gif"/>
</div>

<style>
    .airship-wrapper {
        position: absolute;
        top: 20vh;
        transform: translateX(101vw);
        will-change: transform;
        animation: moveShip 30s linear infinite;
    }
    .airship {
        width: 7vw;
    }

    @keyframes moveShip {
        from {
            transform: translateX(-8vw);
        }
        to {
            transform: translateX(101vw);
        }
    }
</style>