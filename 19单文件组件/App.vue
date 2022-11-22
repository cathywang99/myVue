<template>
 <div>
    <School></School>
    <Student></Student>
</div>
</template>

<script>
//引入组件
import School from "./School.vue"
import Student from "./School.vue"

    export default {
    name:"App",//这里跟文件名最好保持一致
    components:{
    School,
    Student
}

 }
</script>

<style>

</style>