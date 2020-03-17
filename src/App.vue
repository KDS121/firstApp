<template>
  <v-app>
    <v-content>
      <Home/>
      <!-- <Banner/>
      <Banner/>
      <Banner/> -->
      <Cards/>
      
    </v-content>
  </v-app>
</template>

<script>
import Home from './components/Home';
// import Banner from './components/Banner';
import Cards from './components/Cards';

export default {
  name: 'App',

  components: {
    Home,
    // Banner,
    Cards,
  },

  data: () => ({
    //
  }),
};
</script>
