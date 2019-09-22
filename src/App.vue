<template>
  <div id="app">
    <div class="container">

      <div class="logo-div">
        <a href=""><img alt="Vue logo" src="./assets/determined.png"></a>
      </div>

      <div class="menu-div">
        <RaghadMenu msg="Raghad Alafeef " /> 
      </div>

      <div class="content-div">
        <works msg="Raghad Alafeef"/>
      </div>
      
      <!-- logo="../assets/determined.png" -->
      
    </div>
  </div>
</template>

<script>
import works from './components/works.vue'
import RaghadMenu from './components/RaghadMenu.vue'


export default {
  name: 'app',
  components: {
    works,
    RaghadMenu
  },
  data () {
    return {

    }
  }
}
</script>

<style>
#app {
  font-family: "Lucida Console", "Lucida Sans Typewriter", monaco, "Bitstream Vera Sans Mono", monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}

.container {
  width: 100%;
  height: auto;
}
.logo-div {
  width: 15%;
  float: left;
}
.menu-div {
  margin-left: 17%;
  height: 90px;
}
.content-div {
  margin-top: 1%;
  height: 100%;

}

.logo-div img {
  max-width: 70%;
}
</style>
