<template>
    <div class="page">
        <MyPhoto />
        <MyName />
    </div>
</template>
<script>
import MyPhoto from './MyPhoto.vue';
import MyName from './MyName.vue';

export default {
    components: {
        MyPhoto,
        MyName,
    }
}
</script>
<style scoped>
    .page {
        height: 100vh;
        padding: 0;
        background-color: var(--primary-color);
    }

    @media only screen and (max-width: 900px) {
        .page {
            height: fit-content;
            padding: 50px 0;
        }   
    }
</style>