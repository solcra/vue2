<template lang="pug">
  li
    h2: a(v-bind:href="artist2.url" target="_black") {{artist2.name}}
    a(v-bind:href="artist2.url" target="_black")
      img(v-bind:src="artist2.image[2]['#text']")
</template>

<script>
  export default {
    name: 'artist2',
    props: ['artist2']
  }
</script>

<style lang="stylus" scoped>
  li
    display block
    margin 10px 0
</style>
