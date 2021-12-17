<template>
    <section>
             <h1>{{ title }}</h1>
             <h2>{{ secondTitle }}</h2>
      
    </section>
</template>

<script>
export default {
  name: "Title",
  data: function(){
      return{
          title:'La mia prima app con Vue Cli',
          secondTitle:'Io sono un h2 nel componente Title'
      }
  }
  
};
</script>

<style scoped>
h1{
    text-transform: uppercase;
    color:red;
    text-align: center;
    margin: 30px 0;
    font-size: 40px;
}
h2{
    color:white;
    text-transform: uppercase;
}

</style>
