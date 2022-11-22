<template>
 <div class="demo">
    <h2>学校名称：{{schoolName}}</h2>
    <h2>学校地址：{{address}}</h2>
    <button @click="showName">点我提示学校名</button>
</div>
</template>

<script>
    export default {//直接暴露组件的配置对象，省掉new VC
        name:"school",//这里跟文件名最好保持一致
        data(){
            return {
                schoolName:'尚硅谷',
                address:"北京"
            }
        },
       methods:{
        showName(){
            alert(this.schoolName)
        }
       }
 }
</script>

<style>
    .demo{
        background-color:orange;
    }
</style>