<template>
  <div class="container">
    <!-- start for header  -->
    <Header />
    <!-- end for header  -->

    <!-- start for banner  -->
    <Banner />
    <!-- end for banner  -->

    <!-- start for footer  -->
    <Footer />
    <!-- end for footer  -->
  </div>
</template>
<script>
import Header from './components/Header.vue';
import Banner from './components/Banner.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components:{
    Header,
    Banner,
    Footer
  },
  data() {
    return {
    }
  }
}
</script>
<style scoped>

</style>

