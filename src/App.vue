<template>
  <div id="app">
    <router-view/>
    <div>你的jhjj</div>
    <div>asd de344</div>
     <div>asd </div>
    <app-header></app-header>
    <users></users>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import Users from './components/Users'  //局部组件注册
  import Header from './components/Header'
  import Footer from './components/Footer'
  export default {
  name: 'App',
  components:{
    'users':Users,
    'app-header':Header,
    'app-footer':Footer
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;

}
</style>
