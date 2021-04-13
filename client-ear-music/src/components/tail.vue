<template>
<div id="tail">
    <section class="tail">
        <div class="bott">
          <el-divider >遇见耳朵</el-divider>
          <el-row>
  <el-col :span="10" class="tail" style=""><div class="grid-content bg-purple" >
    <p class="textdown">下载客户端</p>
     
    <div class="icon">
      <span>
      <img src="../img/tail1.png" alt="" width="50%" style="padding-top:15px">
      Android版</span>
    </div>
    <div class="icon" >
       <span>
      <img src="../img/tail22.png" alt="" width="50%" style="padding-top:15px">
      iPhone</span>
    </div>
    <div class="icon" >
       <span>
      <img src="../img/tail3.png" alt="" width="50%" style="padding-top:15px">
      Windows版</span>
    </div>
    <div class="icon" >
       <span>
      <img src="../img/tail4.png" alt="" width="50%" style="padding-top:15px">
       Linux..</span>
    </div>
    </div></el-col>
  <el-col :span="6" class="tail"><div class="grid-content bg-purple">
    <p class="textdown">关于耳遇</p>
    <ul class="wu">
      <li><p>组织:第五小组</p></li>
      <li><p>本产品由第五小组全权负责</p></li>
      <li><p>联系我们 - 进行反馈</p></li>
    </ul>
  </div></el-col>
  <el-col :span="8" class="tail"><div class="grid-content bg-purple">
    <p class="textdown">关注我们</p>
        <div class="icon2">
      <img src="../img/tail5.png" alt="" width="25%" style="padding-top:15px;" class="iconimg">
     <span class="icon2text">GitHub</span>
    </div>
    <div class="icon2">
     
      <img src="../img/tail6.png" alt="" width="25%" style="padding-top:15px;" class="iconimg">
     <span class="icon2text">微博</span>
    </div>
    <div>
    </div>
    </div></el-col>
</el-row>
<div  class="endtext"><p>关于腾讯 | About Tencent | 服务条款 | 用户服务协议 | 隐私政策 | 权利声明 | 广告服务 | 腾讯招聘 | 客服中心 | 网站导航</p>
<p>Copyright © 1998 - 2021 Tencent. All Rights Reserved.</p></div>
        </div>
        
    </section>
</div>
</template>
<script>

export default {
name:"tail",
  data() {
    return {};
  },
    components: {
      
  },
};
</script>
<style  scoped>
    .bott{
        width: 1340px;
        height: 400px;  
        margin-top:50px ;
        background:#282828;
        
    }
    .icon{
      width: 100px;
      height: 100px;
      
      background: #303133;
      float: left;
      margin-left:30px;
      text-align: center;
    }
  .icon2{
    width: 200px;
    height: 100px;
    margin-left: 10px;
    background: #303133;
    float: left;
  }
  .iconimg{
    padding-top: 30px;
    padding-left: 20px;
  }
  .endtext{
    text-align:center;
    padding-top:30px;
    font-size:14px;
    color: dimgray;
  }
    .textdown{
      font-size: 18px;
      color: #DAE5E7;
      padding-left: 20px;
    }
    .icon2text{

    }
    .wu{
      font-size: 15px;
      color: dimgray;
      list-style:none;
      border:none;
    }
</style>