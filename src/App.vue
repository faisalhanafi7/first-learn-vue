<!-- <template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js "/>
  </div>
</template>

<script>
import HelloWolrd from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
 -->
 <template>
   <div id="app">
     <Han msg="halo hanafi"/>
   </div>
 </template>

 <script type="text/javascript">
   import Han from './components/Han.vue'

   export default {
    name : 'App',
    components : {
      Han
    }
   }
 </script>