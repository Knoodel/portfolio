<template>
    <footer>
        <a href="mailto:lukasz.osmanski1@gmail.com">Kontakt: <span>lukasz.osmanski1@gmail.com</span></a>
    </footer>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    footer {
        width: 100%;
        height: 50px;
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
    }
    span:hover {
        color: var(--secondary-color);
        cursor: pointer;
    }
</style>