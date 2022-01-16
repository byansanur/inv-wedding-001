<template>
  <v-app>
    <v-main>
      <Top/>
      <br/>
      <br/>
      <Opening/>
      <br/>
      <br/>
      <Mempelai/>
      <br/>
      <br/>
      <EventDate/>
      <br/>
      <br/>
      <Story/>
      <br/>
      <br/>
      <Gallery/>
    </v-main>
    <BottomNav/>
  </v-app>
</template>

<script>
import Top from './components/Top'
import Opening from './components/Openning'
import Mempelai from './components/Mempelai'
import EventDate from './components/EventDate'
import Story from './components/Story'
import Gallery from './components/Gallery'
import BottomNav from './components/BottomNav'

export default {
  name: 'App',

  components: {
    Top,
    Opening,
    Mempelai,
    EventDate,
    Story,
    Gallery,
    BottomNav
  },
};
</script>
