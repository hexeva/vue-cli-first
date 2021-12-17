<template>
    <section>
             <h1>{{ title }}</h1>
      
    </section>
</template>

<script>
export default {
  name: "Title",
  data: function(){
      return{
          title:'La mia prima app con Vue Cli'
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

</style>
