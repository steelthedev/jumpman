<template>

    <v-toolbar  class="bg-white mx-auto text-center text-uppercase font-weight-medium text-body-2" color="dark">

      <div class="logo mx-7">
        <v-icon icon="mdi-infinity" size="x-large"></v-icon>
      </div>

          <div class="middle text-uppercase mx-auto d-none d-sm-flex">
            <span class="mx-7">Shop</span>
            <span class="mx-7">collections</span>
            <span class="mx-7">blog</span>
          </div>
      
      <div class="mr-10 d-none d-sm-flex">
         <span>
          Cart
          <v-icon end icon="mdi-cart-outline text-right"></v-icon>
        </span>
      </div>
    
      <v-spacer class=" d-sm-flex d-md-none"></v-spacer>
          <v-icon icon="mdi-filter-variant float end d-sm-flex d-md-none mx-6 text-h4" ></v-icon>
  </v-toolbar>

  <section class="hero">
    <v-container class="mb-0 hero">
    <v-row class="align-center justify-center" no-gutters>
      <v-col cols="12" md="6" lg="6" class="text-md-justify mx-auto text-center">
        <span class="text-body-1">Basketball Shoe</span>
        <h2 class="text-h1 hero-h1 font-weight-bold text-primary mb-6" color="primary">Jumpman</h2>
        <p class="">Inspired by the design of the latest Air Jordan game shoe.
        The Jordan
          Jumpman 2021 helps up-and-coming players take control and level up their game.</p>
 
        <v-btn class="rounded-pill  bg-primary text-uppercase font-weight-light px-8 mt-4 text-button-1 "  flat color="white">
          shop now
        </v-btn>
      </v-col>
      <v-col cols="12" md="6" lg="6"  align-center >
        <v-img
        class="bg-white  text-center"
        
        width="500"
        :aspect-ratio="1"
        src="jumpman.png"
        cover
        ></v-img>
      </v-col>
    </v-row>
  </v-container>
  </section>


  
</template>

<script>
import { defineComponent } from 'vue';


import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
  },
});
</script>
<style scoped>
@media screen and (max-width:960px) {
  .hero .hero-h1{
    font-size:70px !important;
}


}

</style>