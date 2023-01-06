<template>
    <div class="card">
        <img :src="source" >
    </div>
</template>
<script>
export default {
    props: {
        source: String
    }
}
</script>
<style>
    .card {
        justify-self: center;
        height: 30vh;
        width: 30vh;
        min-width: 120px;
        min-height: 120px;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: var(--font-color);
        border-radius: 20px;
        box-shadow: 5px 5px 5px 1px var(--primary-color);
        transition: all 300ms ease;
        overflow: hidden;
    }
    @media only screen and (max-width: 900px) {
        .card {
            width: 20vw;
            height: 20vw;
        }
    }
    @media only screen and (max-width: 500px) {
        .card {
            width: 35vw;
            height: 35vw;
        }
    }
    @media (pointer: fine) {
        .card:hover {
            transform: scale(115%);
        }
    }
    .card img {
        width: 90%;
    }
</style>