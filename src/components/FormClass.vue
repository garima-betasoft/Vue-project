<template>
    <div>
 <h1>class details!!</h1>
 <label for="rollno">Enter your RollNo</label><br><br>
 <input type="text" v-model="input1"/><br><br>
 <label for="class" >Choose your class</label><br><br>
 <input type="radio" value="BCA" v-model="input2"/>
 <label for="bca">BCA</label>
 <input type="radio" value="MCA" v-model="input2"/>
 <label for="mca">MCA</label>
 <input type="radio" value="BBA" v-model="input2"/>
 <label for="bba">BBA</label>
 <input type="radio" value="MBA" v-model="input2"/>
 <label for="Mba">MBA</label><br><br>
 <p>Your Rollno is:{{ input1 }}</p>
 <p>Your Class is:{{ input2 }} </p>
  </div>
</template>
<script>
export default{
    name:"FormClass",
    data()
    {
        return {
            input1:"",
            input2:""
        }
    }

}
</script>