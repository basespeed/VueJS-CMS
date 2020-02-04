<template>
  <div class="dashboard">
    <div class="dash_menu">
      <div class="inside">
        <div class="logo">
          <h1><i class="far fa-snowflake"></i> CMS</h1>
          <div class="toogle_menu"><i class="fas fa-bars"></i></div>
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
    background: #FFF;
    box-shadow: 0 0 2rem 0 rgba(136,152,170,.15);
    position: relative;
  }
  .logo{
    display: flex;
    justify-content: left;
    align-items: center;
    color: #FFF;
    padding: 25px 25px;
    position: relative;
    z-index: 100;
    font-weight: 700;
  }
  .logo h1{
    font-size: 40px;
    font-weight: bold;
    margin: 0;
    margin-left: 10px;
    color: #5E72E4;
    text-shadow: 1px 1px 1px #dedede,
    1px 2px 1px #dedede,
    1px 3px 1px #dedede,
    1px 4px 1px #dedede,
    1px 8px 6px rgba(16,16,16,0.4);
    flex-grow: 1;
  }
  .logo img{
    width: 30px;
    height: 30px;
  }
  .logo h1 svg{
    width: 30px;
  }
  .toogle_menu{
    display: flex;
    align-items: center;
    cursor: pointer;
  }
  .toogle_menu svg{
    font-size: 20px;
    color: #000;
  }
</style>
