<template>
  <FirstPage />
  <SecondPage />
</template>

<script>
import FirstPage from './components/FirstPage.vue';
import SecondPage from './components/SecondPage.vue';

export default {
  name: 'App',
  components: {
    FirstPage,
    SecondPage
  }
}
</script>

<style>
@import './assets/styles/variables.css';
  * {
    margin: 0;
  }
  .page {
    width: 100vw;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  h1, h2 {
    font-family: var(--font-family);
    color: var(--font-color);
    user-select: none;
  }
  h1 {
    font-size: 5rem;
    text-shadow: 2px 2px 5px black;
  }
  h2 {
    font-size: 4rem;
    text-shadow: 2px 2px 5px black;
  }
</style>
