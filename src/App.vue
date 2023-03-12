<template>
  <div>
    <Navbar></Navbar>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Main from './components/Main.vue';
import Navbar from './components/Navbar.vue';
import Footer from '@/components/Footer.vue';

  export default {
    components: {
    Navbar,
    Main,
    Footer
}
}
</script>

<style>
  *{ 
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: arial;
  }
  a {
    text-decoration: none;
  }
  ul {
    list-style: none;
  }
  .container {
    max-width: 1140px;
    width: 100%;
    padding: 0 15px;
    margin: 0 auto;
  }

</style>