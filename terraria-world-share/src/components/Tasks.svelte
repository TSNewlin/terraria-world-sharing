<script></script>

<div class="task-wrapper">
    {#each Array(40) as _}
        <img src="/images/inventory.webp"/>
    {/each}
</div>

<style>
    .task-wrapper {
        width: 2vw;
        position: absolute;
        top: 1vh;
        left: 1vw;
        display: grid;
        grid-template-columns: repeat(10, 1fr);
    }

    .task-wrapper img {
        margin: 2px 2px;
        width: 2vw;
    }
</style>