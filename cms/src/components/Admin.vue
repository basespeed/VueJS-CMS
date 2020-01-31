<template>
  <div class="dashboard">
    <div class="dash_menu" :style="{'background-image': 'url(' + require('../assets/images/sidebar-1.jpg') + ')'}">
      <div class="inside">
        <div class="logo">
          <img src="../assets/logo.png" alt="Logo" />
          <h1>Dashboard</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Admin',
  data () {
    return {
      msg: 'Admin'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .dash_menu{
    width: 300px;
    height: 100vh;
    background: red;
    position: relative;
  }
  .dash_menu:before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    background: rgba(0,0,0,0.6);
  }
  .logo{
    display: flex;
    justify-content: center;
    align-content: center;
    color: #FFF;
    padding: 25px 0;
    position: relative;
    z-index: 100;
  }
  .logo h1{
    font-size: 24px;
    margin-left: 10px;
  }
  .logo img{
    width: 30px;
  }
</style>
