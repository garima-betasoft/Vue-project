<template>
    <div>
    <h1>{{ data }}</h1>
   <button v-on:click="click()">submit</button>
   </div>
    </template>
    <script>
    export default{
        name:"ButtonClick",
        props:{
            data:String
        },methods:{
            click()
            {
                alert("submit your details")
            }
        }
    }
</script>