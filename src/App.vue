<template>
  <div id="app">
    <Title />
    <h2>Io sono un h2 nell'app</h2>
    <Jumbotron />

    
  </div>
</template>

<script>

import Title from "./components/Title";
import Jumbotron from "./components/Jumbotron";



export default {
  name: "App",
  components: {
    Title,
    Jumbotron
  },
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  background-color:blueviolet;
  
}
h2{
  text-align: center;
}

</style>
