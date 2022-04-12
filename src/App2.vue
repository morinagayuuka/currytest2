<template>
  <HelloWorlds msg="been"/>
</template>
<script>
/*インポートしてる*/
import HelloWorlds from './components/HelloWorldButton.vue'

export default {
  name: 'App',
  components: {
    HelloWorlds
  }
}
</script>

<style>
body{
 margin:0px 100px 0px 100px;
 }
#app2 {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.coffeePosition{
  padding-left:125px;
  }
</style>
