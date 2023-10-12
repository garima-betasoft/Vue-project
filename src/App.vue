<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <HomeComponent data="garima" msg="learning vuejs"/>
    <firstComp />-->
    <DataBind />
    <ButtonClick data="submit your details"/>
    <FormClass />
    <HomeUser @dataPassed="showdata"/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
//import HomeComponent from './components/HomeComponent.vue'
//import firstComp from'./components/firstComp.vue'
import DataBind from'./components/DataBind.vue'
import ButtonClick from './components/ButtonClick.vue'
import FormClass from './components/FormClass.vue'
import HomeUser from'./components/HomeUser.vue'
export default {
  name: 'App',
  components: {
    //HelloWorld,
    //HomeComponent,
    //firstComp,
    DataBind,
    ButtonClick,
    FormClass,
    HomeUser
  },
  methods:{
    showdata(val){
      console.log('emitted value',val);
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
