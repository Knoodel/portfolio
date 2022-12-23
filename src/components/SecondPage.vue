<template>
    <div class="page">
        <h1>Moje umiejętności</h1>
        <div class="skills-container">
            <Skills />
        </div>
    </div>
</template>
<script>
import Skills from './SkillsDiv.vue';
export default {
    components: {
        Skills
    }
}
</script>
<style scoped>
    .page {
        background-color: var(--secondary-color);
        justify-content: flex-start;
    }
    .skills-container {
        width: 100vw;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    h1 {
        margin-bottom: 50px;
    }
</style>