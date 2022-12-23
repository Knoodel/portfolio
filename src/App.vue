<template>
  <FirstPage />
  <SecondPage />
  <FooterBar />
</template>

<script>
import FirstPage from './components/FirstPage.vue';
import SecondPage from './components/SecondPage.vue';
import FooterBar from './components/FooterBar.vue';

export default {
  name: 'App',
  components: {
    FirstPage,
    SecondPage,
    FooterBar
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
    padding: 50px 0;
    height: fit-content;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  h1, h2, h3 {
    font-family: var(--font-family);
    color: var(--font-color);
    user-select: none;
    text-shadow: 2px 2px 5px black;
    text-align: center;
  }

  h1 {
    font-size: 80px; 
  }

  h2 {
    font-size: 60px;
  }

  h3 {
    font-size: 30px;
  }

  @media only screen and (max-width: 900px) {
    h1 {
      font-size: 60px;
    }

    h2 {
      font-size: 45px;
    }

    h3 {
      font-size: 25px;
    }
  }

  @media only screen and (max-width: 600px) {
    h1 {
      font-size: 40px;
    }

    h2 {
      font-size: 30px;
    }

    h3 {
      font-size: 20px;
    }
  }

  @media only screen and (max-height: 650px) {
    h1 {
      font-size: 60px;
    }

    h2 {
      font-size: 45px;
    }

    h3 {
      font-size: 25px;
    }
  }
</style>
