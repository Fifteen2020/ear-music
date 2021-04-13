<template>
<section class="icon">
<el-row >
  <el-col :span="3"><div class="grid-content bg-purple">.</div></el-col>
  <el-col :span="18" ><div class="grid-content bg-purple">
      <el-page-header @back="goBack" content="耳遇专栏">
</el-page-header>
<h1>音乐人的专属对话</h1>
<el-divider><i class="el-icon-headset"></i></el-divider>
<h3><i class="el-icon-d-arrow-right"></i>最新资讯</h3>
<!--最新资讯-->
    <el-row style="margin-top:20px;">
         <el-col :span="10" style="margin-left:30px;"><div class="grid-content bg-purple" >
             <img src="../../img/zf.jpg" alt="" >
             </div></el-col>
         <el-col :span="5" style="margin:30px;"><div class="grid-content bg-purple" >
                <img src="../../img/zf2.jpg" alt="" width="100%" >
                <p>与陈奕迅的独特对话:我们终身都在寻觅爱</p>
             </div></el-col>
         <el-col :span="5" style="margin:30px;"><div class="grid-content bg-purple">
             <img src="../../img/zf5.jpg" alt="" width="100%" height="140px">
             <p>CNK专访：昨天以前，我也以为他们只是偶像练习生</p>
             </div></el-col>
    </el-row>
    <h3><i class="el-icon-d-arrow-right"></i>热门推荐</h3>
    <!--热门推荐-->
    <el-row style="margin-top:40px;">
        <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple" >
            <img src="../../img/zf3.jpg" alt="" width="100%" height="170px"><p>旅行团乐队：从城市到海岛，奔向生活的B面</p></div></el-col>
              <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple" >
            <img src="../../img/zf6.jpg" alt="" width="100%" height="170px"><p>张碧晨：遁入全新人生星轨 用突破打碎既定规则</p></div></el-col>
              <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple" >
            <img src="../../img/zf7.jpg" alt="" width="100%" height="170px"><p>邓紫棋：「摩天动物园」的生存法则</p></div></el-col>
    </el-row>
       <el-row style="">
        <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple">
            <img src="../../img/zf8.jpg" alt="" width="100%" height="170px"><p>今日主厨沙楠杰 摄入音乐「卡路里」</p></div></el-col>
              <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple" >
            <img src="../../img/zf9.jpg" alt="" width="100%" height="170px"><p>制造标准之外的声音，多元音乐视角阐述全新自我</p></div></el-col>
              <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple" >
            <img src="../../img/zf10.jpg" alt="" width="100%" height="170px"><p>林彦俊：有一种恋爱叫棋逢「对手」</p></div></el-col>
    </el-row>
    <el-row style="margin-top:40px;">
        <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple">
            <img src="../../img/zf11.jpg" alt="" width="100%" height="170px"><p>梁静茹：二十年歌迷变朋友，霸气喊话多听专辑</p></div></el-col>
              <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple" >
            <img src="../../img/zf4.jpg" alt="" width="100%" height="170px"><p>陈奕迅：eason and the duo band，与你与我常在</p></div></el-col>
              <el-col :span="7" style="margin-left:30px;"><div class="grid-content bg-purple" >
            <img src="../../img/zf12.jpg" alt="" width="100%" height="170px"><p>“神曲制躁机”Tungevaag & Raaban 独家专访</p></div></el-col>
    </el-row>
     
      </div></el-col>
  <el-col :span="3"><div class="grid-content bg-purple">.</div></el-col>
</el-row>
    </section>
</template>
<script>
export default {
    data(){
        return{
            
        }
    },
    methods:{
 goBack() {
     this.$router.go(-1);
 }
    },
      components: {
              },
}
</script>
<style  scoped>
    .c{
        
    }
</style>