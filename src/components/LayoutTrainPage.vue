<template>
    <div class="root_div">
        <el-row class="navigator_bg">
            <el-row class="navigator_bar">
                <el-col :span="6"><div class="navigator_title">360 Global Fintech</div></el-col>
                <el-col :span="2"><div class="navigator_title">我们正在招聘</div></el-col>
                <el-col :span="2"><div class="navigator_title">关于我们</div></el-col>
                <el-col :span="2"><div class="navigator_title">联系我们</div></el-col>
            </el-row>
            <el-row class="navigator_tips">
                <el-col offset="2"><div class="navigator_tips_text">App很容易</div></el-col>
            </el-row>
        </el-row>
        <el-row class="why_bg">
            <el-row class="why_bg_el-row"><div>为什么选择360 Global Fintech</div></el-row>
            <el-row class="why_bg_el-row"><div>高效智能的零售金融解决方案</div><div>金融机构和企业提供服务</div></el-row>
            <el-row class="why_bg_el-row why_bg_el-row_last" :gutter="10" type="flex" justify="center">
                <el-col :span="6"><div class="why_bg_el-row_last_el-col">1</div></el-col>
                <el-col :span="6"><div class="why_bg_el-row_last_el-col">2</div></el-col>
                <el-col :span="6"><div class="why_bg_el-row_last_el-col">3</div></el-col>
            </el-row>
        </el-row>
        <el-row></el-row>
        <el-row></el-row>
    </div>
</template>

<script>
    export default {
        name: "LayoutTrainPage"
    }
</script>

<style scoped>
    .root_div {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        box-sizing: border-box;
    }
    .navigator_bg {
        width: 100%;
        height: 100%;
        position: absolute;
        background-image: url('./../assets/headbanner.jpg');
        background-size: 100% 100%;
    }
    .navigator_bar {
        margin-top: 20px;
        height: 10%;
    }
    .navigator_title {
        text-align: center;
        color: white;
    }
    .navigator_tips {
        height: 90%;
        display: flex;
        align-items: center;
    }
    .navigator_tips_text{
        color: white;
        text-align: left;
        font-size: 35px;
    }
    .why_bg {
        height: 400px;
    }
    .why_bg_el-row {
        margin-top: 25px;
    }
    .why_bg_el-row_last {
        height: 50%;
    }
    .why_bg_el-row_last_el-col {
        box-shadow: 5px 5px 5px #888888;
        border: 1px solid #ff0000;
        height: 100%;
    }



</style>