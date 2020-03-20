<template>
  <v-app>
    <v-content>
      <!-- <Home/> -->
      <!-- <Banner/>
      <Banner/>
      <Banner/> -->
      <!-- <Cards/> -->
      <Description/>
    </v-content>
  </v-app>
</template>

<script>
//import Home from './components/Home';
// import Banner from './components/Banner';
// import Cards from './components/Cards';
import Description from './components/Description';

export default {
  name: 'App',

  components: {
    // Home,
    // Banner,
    // Cards,
    Description,
  },

  data: () => ({
    //
  }),
};
</script>
