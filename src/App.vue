<script>
import AppJumboVue from './components/AppJumbo.vue';

export default {
  data(){
    return{
      title: "Ciao io sono Uffa",
    }
  },
  components:{
    AppJumboVue
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
  height: 20vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
header h1{
  font-family: sans-serif;
  color: antiquewhite;
  font-size: 50px;
}
</style>
