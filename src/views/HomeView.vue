<template>
  <div>
      <Banner />
      <div class="main-container">
      <h1>Monte seu Hamburguer:</h1>
      <BurguerForm />
      </div>
  </div>

</template>

<script>
import Banner from '@/components/Banner.vue';
import BurguerForm from '@/components/BurguerForm.vue';

  export default{
    name:'HomeView',
    
    components:{
      Banner,
      BurguerForm
    },

  }
</script>
