<template>
  <div id="app">
   <Header />
    <router-view/>
  </div>
</template>

<script>
import Header from './components/layout/Header'
export default {
  name: "app",
  components:{
    Header
  }
}
</script>
<style scoped>

 form {
    display: flex;
  }

 input[type="text"] {
    flex: 10;
    padding: 5px;
  }
  input[type="submit"] {
    flex: 2;
  }
   .btn {
    display: inline-block;
    border: none;
    background: #555;
    color: #fff;
    padding: 7px 20px;
    cursor: pointer;
  }
  .btn:hover {
    background: #666;
  }
</style>

