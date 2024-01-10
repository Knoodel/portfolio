<template>
    <footer>
        <a href="mailto:lukasz.osmanski1@gmail.com"><AtIcon size="48" /></a>
        <a href="https://github.com/Knoodel/" target="_blank"><GithubIcon size="48" /></a>
    </footer>
</template>
<script>
import AtIcon from 'vue-material-design-icons/At.vue';
import GithubIcon from 'vue-material-design-icons/Github.vue';

export default {
    components: {
        AtIcon,
        GithubIcon
    }    
}
</script>
<style scoped>
    footer {
        width: 100%;
        height: 70px;
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: var(--primary-color);
        color: var(--font-color);
    }
    a {
        text-decoration: none;
        color: var(--font-color);
        cursor: default;
        margin: auto 10px;
    }
    span:hover {
        color: var(--secondary-color);
        cursor: pointer;
    }
</style>