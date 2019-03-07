<template>
    <div>
        <h2>Layout Train</h2>
        <hr>

        <el-row>
            <el-col :span="24" class="grid-content bg-purple-dark"></el-col>
        </el-row>
        <el-row>
            <el-col :span="12" class="grid-content bg-purple"></el-col>
            <el-col :span="12" class="grid-content bg-purple-light"></el-col>
        </el-row>
        <el-row>
            <el-col :span="8" class="grid-content bg-purple"></el-col>
            <el-col :span="8" class="grid-content bg-purple-light"></el-col>
            <el-col :span="8" class="grid-content bg-purple"></el-col>
        </el-row>
        <el-row>
            <el-col :span="6" class="grid-content bg-purple"></el-col>
            <el-col :span="6" class="grid-content bg-purple-light"></el-col>
            <el-col :span="6" class="grid-content bg-purple"></el-col>
            <el-col :span="6" class="grid-content bg-purple-light"></el-col>
        </el-row>
        <el-row>
            <el-col :span="4" class="grid-content bg-purple"></el-col>
            <el-col :span="4" class="grid-content bg-purple-light"></el-col>
            <el-col :span="4" class="grid-content bg-purple"></el-col>
            <el-col :span="4" class="grid-content bg-purple-light"></el-col>
            <el-col :span="4" class="grid-content bg-purple"></el-col>
            <el-col :span="4" class="grid-content bg-purple-light"></el-col>
        </el-row>

        <el-row :gutter="10">
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>
        <el-row :gutter="10">
            <el-col :span="16"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="8"><div class="grid-content bg-purple"></div></el-col>
        </el-row>
        <el-row :gutter="10">
            <el-col :span="8"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="8"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
        </el-row>
        <el-row :gutter="10">
            <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="16"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10">
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6" :offset="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10">
            <el-col :span="6" :offset="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6" :offset="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10">
            <el-col :span="12" :offset="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10" type="flex" class="row-bg">
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10" type="flex" class="row-bg" justify="center">
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10" type="flex" class="row-bg" justify="end">
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10" type="flex" class="row-bg" justify="space-between">
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10" type="flex" class="row-bg" justify="space-around">
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
            <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
        </el-row>

        <el-row :gutter="10">
            <el-col :xs="8" :sm="6" :md="4" :lg="3" :xl="1"><div class="grid-content bg-purple"></div></el-col>
            <el-col :xs="4" :sm="6" :md="8" :lg="9" :xl="11"><div class="grid-content bg-purple"></div></el-col>
            <el-col :xs="4" :sm="6" :md="8" :lg="9" :xl="11"><div class="grid-content bg-purple"></div></el-col>
            <el-col :xs="8" :sm="6" :md="4" :lg="3" :xl="1"><div class="grid-content bg-purple"></div></el-col>
        </el-row>
    </div>
</template>

<script>
    export default {
        name: "LayoutTrain"
    }
</script>

<style scoped>
    .el-row {
        margin-bottom: 20px;
    &:last-child {
         margin-bottom: 0;
     }
    }
    .el-col {
        border-radius: 4px;
    }
    .bg-purple-dark {
        background: #99a9bf;
    }
    .bg-purple {
        background: #d3dce6;
    }
    .bg-purple-light {
        background: #e5e9f2;
    }
    .grid-content {
        border-radius: 4px;
        min-height: 36px;
    }
    .row-bg {
        padding: 10px 0;
        background-color: #f9fafc;
    }
</style>