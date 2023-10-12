<template>
    <ChildUser />
</template>
<script>
import ChildUser from './ChildUser.vue'
export default{
    name:"ParentUser",
    components:{
        ChildUser
    }
}
</script>
