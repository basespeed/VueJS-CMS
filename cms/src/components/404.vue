<template>
  <div>
    <h2>{{msg}}</h2>
  </div>
</template>

<script>
export default {
  name: 'error',
  data () {
    return {
      msg: 'Page not found !'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2{
  color: red;
}
</style>
