<script>
export default{
    data(){
        return{
            imgName: 'uffa.JPG'
        }
    },
    methods:{
        getImagePath(){
            return new URL(`../assets/img/(this.imgName)`, import.meta.utl).href;
        }
    }
}
</script>

<template>
<div class="jumbo">
    <img :src="getImagePath()" alt="Uffa">
</div>

</template>

<style>
.jumbo{
  width: 100%;
  height: 50vh;
}
.jumbo img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>