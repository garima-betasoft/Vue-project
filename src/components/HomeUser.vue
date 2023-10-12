<template>
    <div>
        <button @click="Emitdata">click </button>
    </div>
</template>
<script>
export default{
    name:"HomeUser",
    data(){
        return {
            data:"my name is garima"//this is payload
        };
    },
    methods:{
        Emitdata(){
            console.log("this is emit data");
            this.$emit('dataPassed',this.data);
        },
    },
};
</script>
