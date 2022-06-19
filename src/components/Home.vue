<template>
  <div >
    <h1>{{ msg }}</h1>
    
  </div>
</template>

<script>
export default {
  name: 'HomeComponent',
  props: {
    msg: String
  }
}
</script>