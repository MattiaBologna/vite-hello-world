<script>
export default {
  data () {
    return {
      message: 'My first Vite App'
    }
  },
  methods: {
    sayHello () {
      console.log('ciao')
    }
  }
}
</script>

<template>
  <h1 class="title"> {{ message }}</h1>
</template>

<style>
.title {
  color: violet;
}
</style>
