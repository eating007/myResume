<template>
  <div id="app">
    <div id = "topLine"></div>
    <router-view></router-view>
    <div id = "bottomLine"></div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#topLine{
  position: fixed;
  width: 100%;
  height: 10em;
  background-color: #393E46;
  box-shadow: 0px 0px 15px;
}
#bottomLine{
  position: fixed;
  width: 100%;
  bottom: 0em;
  height: 10em;
  background-color: #393E46;
  box-shadow: 0px 0px 15px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}
body,ol,ul,h1,h2,h3,h4,h5,h6,p,th,td,dl,dd,form,fieldset,legend,input,textarea,select{margin:0;padding:0} 
body{font:12px"宋体","Arial Narrow",HELVETICA;background:#fff;-webkit-text-size-adjust:100%; height: 100%; } 
a{color:#2d374b;text-decoration:none} 
a:hover{color:#cd0200;text-decoration:underline} 
em{font-style:normal} 
li{list-style:none} 
img{border:0;vertical-align:middle} 
table{border-collapse:collapse;border-spacing:0} 
p{word-wrap:break-word} 
html{height: 100%}
</style>
