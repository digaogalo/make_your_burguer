<template>
  <div>
    <Navbar :pizzaicon="pizzaicon_src" :alt="app_name" />
      <router-view/>
    <Footer />
  </div>
</template>
<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

export default {
  data() {
    return {
      pizzaicon_src: "/img/pizzaicon.png",
      app_name: "Pizza"
    }
  },
  components: {
    Navbar,
    Footer
  }
}
</script>

<style>

  * {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  .main-container {
    margin: 50px;
    min-height: 250px;
  }

  h1 {
    text-align: center;
    font-size: 38px;
    margin-bottom: 10px;
    margin-top: 5px;
    color: #222;
  }
</style>