<template>
  <div>
    {{ title }}
    {{ students }}
    <ul>
      <li v-for="(student,index) in students" :key="index">{{ index }}{{ student.name }}</li>
    </ul>
  </div>
</template>

<script>
export default {
 data(){
   return{
     title:"Abdullajon",
     students:[
       {name: "aaa", age:1},
       {name: "aaa", age:1},
       {name: "aaa", age:1},
     ]
   }
 }
}
</script>
<style scoped>

</style>
