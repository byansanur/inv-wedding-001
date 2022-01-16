<template>
  <v-container
    class="overflow-hidden mx-auto"
    height="200"
    max-width="500"
  >
    <v-bottom-navigation
    v-model="value"
    :background-color="color"
    dark
    shift
    fixed
    hide-on-scroll
  >
    <v-btn large plain @click="clickToHome">
      <span>Home</span>

      <v-icon>mdi-television-play</v-icon>
    </v-btn>

    <v-btn large plain @click="clickToWho">
      <span>Who</span>

      <v-icon>mdi-music-note</v-icon>
    </v-btn>

    <v-btn large plain @click="clickToDate">
      <span>Date</span>

      <v-icon>mdi-book</v-icon>
    </v-btn>

    <v-btn large plain @click="clickToStory">
      <span>Story</span>

      <v-icon>mdi-image</v-icon>
    </v-btn>
  </v-bottom-navigation>
  </v-container>
</template>

<script>
// import Home from './Openning.vue'
export default {
  name: "BottomNav",
  data: () => ({
      value: 0
  }),
  computed: {
    color () {
      switch (this.value) {
        case 0: return 'blue-grey'
        case 1: return 'teal'
        case 2: return 'brown'
        case 3: return 'indigo'
        default: return 'blue-grey'
      }
    }
  },
  methods: {
    clickToHome() {
    },
    clickToWho() {

    },
    clickToDate() {

    },
    clickToStory() {

    }
  }
}
</script>