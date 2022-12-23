<template>
    <img src="../assets/img/my_photo.jpg" />
</template>
<script>
export default {

}
</script>
<style scoped>
    img {
        width: 50vh;
        height: 50vh;
        border-radius: 50%;
        border: 3px solid var(--secondary-color);
        box-shadow: 0px 0px 50px var(--secondary-color);
    }
    
    @media only screen and (max-width: 900px) {
        img {
            width: 250px;
            height: 250px;
        }
    }
</style>