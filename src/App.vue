<template>
  <div class="container">
    <site-header></site-header>
    <h2>{{title}}</h2>
    <site-footer></site-footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  components:{
    'site-header': Header,
    'site-footer': Footer
  },
  data(){
    return{
      title:'Langing Page'
    }
  }

}

</script>

<style lang="scss">

</style>
