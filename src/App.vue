<template>
  <v-app>
    <v-main>
      <Top/>
      <HelloWorld/>
    </v-main>
    <BottomNav/>
  </v-app>
</template>

<script>
import Top from './components/Top';
import HelloWorld from './components/HelloWorld';
import BottomNav from './components/BottomNav'

export default {
  name: 'App',

  components: {
    Top,
    HelloWorld,
    BottomNav
  },

  data: () => ({
    //
  }),
};
</script>
