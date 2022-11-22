<template>
 <div class="demo">
    <h2>学生：{{name}}</h2>
    <h2>年龄：{{age}}</h2>
</div>
</template>

<script>
    export default {//直接暴露组件的配置对象，省掉new VC
        name:"Student",//这里跟文件名最好保持一致
        data(){
            return {
                name:'cathy',
                age:"18"
            }
        },

 }
</script>

<style>
    .demo{
        background-color:orange;
    }
</style>