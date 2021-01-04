<template>
  <div id="app">
    <Header></Header>
    <Body></Body>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Body from './components/Body.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Body,
    Footer
  }
};



require('@/assets/css/frontend/bootstrap.min.frontend.css'),
require('@/assets/css/frontend/home.css'),
require('@/assets/css/frontend/font-awesome.min.css'),
require('@/assets/css/frontend/footer.css')


</script>




