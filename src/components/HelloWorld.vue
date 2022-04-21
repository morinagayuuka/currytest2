<template>
  <a href="#underjump" rel="noopener">jump↓↓↓</a>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <p>
      花粉症の季節になりましたね。
      <br>のどがかゆいです
      <br>目もかゆいです
      <br>耳もかゆいです
    
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
     <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
     <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul id="underjump">

      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>-->
  </div>
</template>

<script>
/*スクリプトのとこに定数を指定*/
const sdata={ a: 1 }
/*export default をやることによって、外部から参照できるものになる*/
export default {
  /*エクスポートしてる*/
  name: 'HelloWorld',
  

  //プロパティの略
  props: {
  //ストリング//
    msg: String,
  //タイプとナンバー//  
    age: { type: Number,
     default: 0,
     }
  },
  /*dataとして返しているってことか*/
  data(){
        return{
            msg2: "been",
            titletest: "holiday",
             /*dataとして定数を返しているってことか*/
            sdata:{ a: 1 },
             count: 0
        }
      }
  
}


       console.log(sdata);

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button{
    position: relative;
    top:491px;
  display: inline-block;
  font-weight: bold;
  padding: 0.25em 0.5em;
  text-decoration: none;
  color: rgb(65, 41, 25);
  background: #ECECEC;
  transition: .4s;
}
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
a {
  color: rgb(214, 122, 127);
  text-decoration: none;
}
p{
  font-weight:bold;
}
</style>
