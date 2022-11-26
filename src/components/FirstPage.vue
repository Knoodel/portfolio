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
        background-color: var(--primary-color);
    }
</style>