<template>
    <div class="page">
        <h2>Moje umiejętności:</h2>
        <div class="skills">
            <div class="card">
                <img src="../assets/img/javascript.png" />
            </div>
            <div class="card">
                <img src="../assets/img/html.png" />
            </div>
            <div class="card">
                <img src="../assets/img/vue.png" />
            </div>
            <div class="card">
                <img src="../assets/img/php.png" />
            </div>
            <div class="card">
                <img src="../assets/img/sql.png" />
            </div>
            <div class="card">
                <img src="../assets/img/python.png" />
            </div>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
    .page {
        background-color: var(--secondary-color);
        justify-content: flex-start;
    }
    h2 {
        margin: 1rem 0 4rem 0;
    }
    .skills {
        width: 100vw;
        height: 100vh;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
    }
    .card {
        justify-self: center;
        height: 15rem;
        width: 15rem;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: var(--font-color);
        border-radius: 20px;
        box-shadow: 5px 5px 5px 1px var(--primary-color);
        transition: all 300ms ease;
    }
    .card:hover {
        transform: scale(115%);
    }
    .card img {
        width: 90%;
    }
</style>