<template>
<div class="home">
    
    <secComp />   

</div>
</template>
<script>
import secComp from './secComp.vue'
export default{
    home:"firstComp",
    components:{
        secComp
    }
}
</script>
<style scoped>
.home
{
    background-color:aquamarine;
    height:500px;
}</style>
