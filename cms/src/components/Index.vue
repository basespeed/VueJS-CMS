<template>
  <div class="home">
    <div class="container">
      <h2>Index</h2>
      <button @click="EventTigger()">Click</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    EventTigger () {
      alert(this.msg)
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .home .container{
    background: red;
  }
</style>
