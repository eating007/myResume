<template>
  <div class="hello">
     <div id = "mainPageBackground">
       <div id="mainPageLeft">
         <p>
       </div>
       <div id="mainPageRight"></div>
     </div>
  </div>
</template>

<script>
export default {
  name: 'mainPage',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
#mainPageLeft{
  height: 100%;
  flex: 1;
}
#mainPageRight{
  height: 100%;
  flex: 1;
}
#mainPageBackground{
  height: 100%;
  background-color:#1E8186;
  display: flex;
}
.hello{
  height: 100%;
}
</style>
