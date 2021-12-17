<template>
  <div id="app">
    <Title />
    <Background />

    
  </div>
</template>

<script>

import Title from "./components/Title";
import Background from "./components/Background";



export default {
  name: "App",
  components: {
    Title,
    Background
  },
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}




</style>
