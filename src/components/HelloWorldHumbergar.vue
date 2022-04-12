<template>
  <div class="hello">
    <h1>{{ msg3 }}</h1>
    <button type="button" class="menu-btn" v-on:click="open=!open">
      <i class="fa fa-bars" aria-hidden="true"></i>
    </button>
    <div class="menu" v-bind:class="{'is-active' : open }">
      <div class="menu__item">brown</div>
      <div class="menu__item">Tea</div>
      <div class="menu__item">Time</div>
      <!--<div class="menu__item">CONTACT</div>-->
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorldsq1',
  props: {
    msg3: {String:"22f"}
  },
data: function() {
  return {open: false}
}
}

  
   /*data(){
        return{
    open: true
  }*/
 
/*let app=new Vue({
  el:"#app2",
  data:{
    message:'wwww'
  }
});*/
/*
new Vue({
  el:"#app2",
  data:{
     props: 'wwww'
  }
});*/



</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

p{
  display:inline-block;
  white-space: nowrap;
}
h3 {
  margin: 40px 0 0;
 
  white-space: nowrap;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.menu-btn{
  position: fixed;
  top: 125px;
  left: 93px;
  z-index: 3;
  width: 40px;
  height: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
  background: rgb(80, 44, 15);
  color: #fff;
}

/*----------------------------
* メニュー本体
*----------------------------*/
.menu{
  position: fixed;
  top: 326px;
  right: 0;
  z-index: 1;
  width: 100vw;
  height: 34vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background:rgba(224, 128, 67,0.5);
}
.menu__item{
  width: 100%;
  height: auto;
  padding: .5em 1em;
  text-align: center;
  color: #fff;
  box-sizing: border-box;
}

/*----------------------------
* アニメーション部分
*----------------------------*/

/* アニメーション前のメニューの状態 */
.menu{
  transform: translateX(100vw);
  transition: all .3s linear;
}
/* アニメーション後のメニューの状態 */
.menu.is-active{
  transform: translateX(0);
}
</style>
