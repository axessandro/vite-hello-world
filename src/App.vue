<script>
import AppJumboVue from './components/AppJumbo.vue';

export default {
  data(){
    return{
      title: "Ciao io sono Uffa",
    }
  },
}
</script>

<template>
  <header>
    <h1>{{title}}</h1>
  </header>
  
  <AppJumboVue />
  
</template>

<style scoped>

header{
  width: 100%;
}
header h1{
  text-align: center;
  font-family: sans-serif;
  color: antiquewhite;
}
</style>
