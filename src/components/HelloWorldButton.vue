<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

  </div>
</template>

<script>
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


export default {
  name: 'HelloWorlda',
  props: {
    msg: String
  }
}
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

</style>
