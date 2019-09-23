<template>
  <v-app>
    <v-content>
      <movie-grid :films="films"></movie-grid>
    </v-content>
  </v-app>
</template>

<script>
import MovieGrid from './components/MovieGrid';
import { films } from './assets/films'

export default {
  name: 'App',
  components: {
    MovieGrid,
  },
  data: () => {
    return {
      films
    }
  },
};
</script>
