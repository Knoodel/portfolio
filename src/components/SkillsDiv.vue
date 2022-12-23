<template>
    <div class="skills">
        <SkillCard v-for="(source, index) in sources" :key="index" :source="require('../assets/img/' + source)" />
    </div>
</template>
<script>
import SkillCard from './SkillCard.vue';

export default {
    data() {
        return {
            sources: [
                "javascript.png",
                "html.png",
                "vue.png",
                "php.png",
                "sql.png",
                "python.png"
            ]
        }
    },
    components: {
        SkillCard
    }
}
</script>
<style>
    .skills {
        width: fit-content;
        height: fit-content;
        display: grid;
        grid-template-columns: 30vh 30vh 30vh;
        gap: 50px;
        margin: 1em;
    }
    @media only screen and (max-width: 900px) {
        .skills {
            grid-template-columns: 20vw 20vw 20vw;
        }
    }

    @media only screen and (max-width: 500px) {
        .skills {
            grid-template-columns: 35vw 35vw;
        }
    }
</style>