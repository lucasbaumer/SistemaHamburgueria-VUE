<template>
  <div>
  <navBar :logo="logo_src" :alt="app_name"/>
  <Footer />
</div>

</template>

<script>
import navBar from './components/navBar.vue';
import Footer from './components/Footer.vue';

export default{
  components:{
    navBar,
    Footer,
  },
  
  data(){
      return{
        logo_src: '/img/logo.png',
        app_name: 'Make your burguer'
      }
    }

}

</script>

<style>
*{
  font-family: Helvetica;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.main-container{
  margin: 50px;
  min-height: 36.2em;
}

h1{
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color:#222;
}

</style>
