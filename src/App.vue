<template>
  <img alt="Vue logo" src="./assets/images/logo.png">
  <HomeComponent msg="Home"/>
</template>

<script>
import HomeComponent from './components/Home.vue'

export default {
  name: 'App',
  components: {
    HomeComponent,
  }
}
</script>