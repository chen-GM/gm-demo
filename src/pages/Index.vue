<template>
    <div class="container">
        首页

        <el-row justify="center" type="flex" :gutter="10">
            <el-col :span="11">
                <div class="box">11</div>
            </el-col>
            <el-col :span="11">
                <div class="box">11</div>
            </el-col>

        </el-row>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    .container{
        width: 80%;
        margin: 0 auto;
        border: 1px solid #ccc;
    }
    .box{
        background: pink;
        border: 1px solid red;
    }
</style>