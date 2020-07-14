<template>
  <v-app>
    <v-app-bar
      app
      color="teal darken-1"
      dark
    >
      <div class="d-flex align-center">
         <span class="headline font-weight-bold  text-uppercase amber--text font-weigth-light ">Jovens Gênios</span>
      </div>

    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
