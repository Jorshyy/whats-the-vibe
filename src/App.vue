<template>
  <h1>Guess {{ guessCount }}</h1>

  <SearchBar />

</template>

<script>
import SearchBar from './components/SearchBar.vue'

export default {
  components: {
    SearchBar,
  },
  data() {
    return {
      guessCount: 0
    }
  }
}
</script>

<style scoped>

</style>
