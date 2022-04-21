<template>
  <img alt="Vue logo" src="./assets/bird.png">
  <HelloWorld msg="hello"/>
</template>

<script>
/*HelloWorld.vue'からインポートしてる*/
import testhello from './components/HelloWorld.vue'
/*import {articlre} from './components/HelloWorld.vue'*/
/*let a=new articlre();*/
/*console.log(titletest());*/

/*export default をやることによって、外部から参照できるものになる*/
export default {
  name: 'App',
  components: {
   testhello
}



}


</script>

<style>
body{
 margin:0px 100px 0px 100px;
 }
 h1{
   font-size: 30px;
 }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img{
  width:20%;
  height:auto;
}
</style>
