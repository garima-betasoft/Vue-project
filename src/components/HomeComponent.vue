<template>
    <div>
        <h1>hello from home components</h1>
        <h1>{{ data }}</h1>
        <h1>{{ msg }}</h1>

    </div>
   
</template>
<script>
export default{
    name:'HomeComponent',
    props:{
        data:String,
        msg:String
    }
}
</script>
