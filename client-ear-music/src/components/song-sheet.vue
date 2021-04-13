<template>
    <section class="songsheet">
        <div class="songlist">
          
        <div>
            <el-row >
            <el-col :span="3"><div class="grid-content bg-purple" >.</div></el-col>
           <el-col :span="18"><div class="grid-content bg-purple" >
            <el-page-header @back="goBack" content="热门歌单">
            </el-page-header>
            <div>
                <!-- Mozilla/5.0 (Windows NT 6.1; Trident/7.0; rv:11.0) like Gecko -->
                <el-row >
  <el-col :span="8" class="img"><div class="grid-content bg-purple" >
        <img src="../img/songlist1.jpg" alt="X" width="100%" height="250px">
      </div></el-col>
  <el-col :span="16" class="imgtext"><div class="grid-content bg-purple">
      <div style="padding-left:40px;padding-top:10px"><span class="headtext">以你命名的行星</span>
      <p><i class="el-icon-user-solid"></i>歌手:林俊杰</p>
      <p>发行时间:2020/1/20</p><span>语种:国语</span>
      </div>
      <div style="padding-left:40px;padding-top:20px;">
          <el-button type="primary"><i class="el-icon-caret-right"></i>播放全部</el-button>
           <el-button type="info" plain><i class="el-icon-star-on"></i>主要按钮</el-button>
          <el-button type="info" plain><i class="el-icon-s-comment"></i>评论(99+)</el-button>
          <el-button type="info" plain><i class="el-icon-more"></i>更多</el-button>
      </div>
      </div></el-col>
</el-row>
 <el-divider></el-divider>
        <div class="text">
            
            <span class="textsong"><i class="el-icon-d-arrow-right
"></i>全部歌曲</span>
        </div>
        <!-- 歌单 -->
        <div style="margin-left:100px">
            <ss :tableData = "music"></ss>
            </div>
            <!-- 评论 -->
            <div style="margin-top:50px;">
                <p class="headtext"><i class="el-icon-d-arrow-right
"></i>用户评论</p>
                <el-input
  type="textarea"
  :rows="7"
  placeholder="请输入内容"
  v-model="textarea" class="inptext">
</el-input>

            </div>

<el-button type="primary" round style="margin-left:80%;margin-top:10px;">发表评论</el-button>
<!-- 评论列表 -->
<div>
    <p class="headtext">评论列表</p>
    <!-- 评论1 -->
    <el-divider></el-divider>
    <div>
        <el-row >
  <el-col :span="3"><div class="grid-content bg-purple" style="height:100px">
      <img src="../img/login1.jpg" alt="" width="50%" height="50%" style="padding-left:40px;padding-top:10px"></div></el-col>
  <el-col :span="21"><div class="grid-content bg-purple" style="height:100px">  <el-link type="primary">城管大队小老弟</el-link><p>真不错啊!!</p>
       
  <div><span style=" color: darkgray; float: left;">2020/1/1</span> <p  class="texticon">
     <img src="../img/songicon1.png" alt="" width="20px">(99+)丨<img src="../img/songicon3.png" alt="" width="20px">(999+)
</p></div>
 
      </div></el-col>
        </el-row>
    </div>
    <!-- 评论2 -->
<el-divider></el-divider>
    <div>
        <el-row >
  <el-col :span="3"><div class="grid-content bg-purple" style="height:100px">
      <img src="../img/login2.jpg" alt="" width="50%" height="50%" style="padding-left:40px;padding-top:10px"></div></el-col>
  <el-col :span="21"><div class="grid-content bg-purple" style="height:100px">  <el-link type="primary">城管大队后勤部</el-link><p>xxxxxxxx</p>
       
  <div><span style=" color: darkgray; float: left;">2020/1/1</span> <p  class="texticon">
     <img src="../img/songicon1.png" alt="" width="20px">(99+)丨<img src="../img/songicon3.png" alt="" width="20px">(999+)
</p></div>
 
      </div></el-col>
        </el-row>
    </div>
    <!-- 评论3 -->
<el-divider></el-divider>
    <div>
        <el-row >
  <el-col :span="3"><div class="grid-content bg-purple" style="height:100px">
      <img src="../img/login4.jpg" alt="" width="50%" height="50%" style="padding-left:40px;padding-top:10px"></div></el-col>
  <el-col :span="21"><div class="grid-content bg-purple" style="height:100px">  <el-link type="primary">城管大队话痨积极分子</el-link><p>叽叽喳喳叽叽喳喳</p>
       
  <div><span style=" color: darkgray; float: left;">2020/1/1</span> <p  class="texticon">
     <img src="../img/songicon1.png" alt="" width="20px">(99+)丨<img src="../img/songicon3.png" alt="" width="20px">(999+)
</p></div>
 
 
      </div></el-col>
        </el-row>
    </div>


</div></div>
               </div></el-col>
           <el-col :span="3"><div class="grid-content bg-purple" >.</div></el-col>
</el-row>
        </div>
        </div>
    </section>
</template>
<script>
import ss from "./ss";
export default {
  components: { ss },
    data(){
        return{
            textarea:'',
        music: [{
        date: '1',
        name: '歌曲标题',
        address: '4:20',
        names:'华晨宇',
      },{
          date: '2',
          name: '爱人错过',
          address: '4:52',
          names:'告五人',
        },
        {
          date: '3',
          name: 'AH YEAH',
          address: '2:56',
          names:'Winner',
        },
        {
          date: '4',
          name: '交换余生',
          address: '4:36',
          names:'林俊杰',
        },
        {
          date: '5',
          name: '我很好',
          address: '3:48',
          names:'刘大壮',
        },
        {
          date: '6',
          name: '信仰',
          address: '4:16',
          names:'张信哲',
        },
        {
          date: '7',
          name: '情深深雨蒙蒙',
          address: '4:45',
          names:'赵薇',
        },
        {
          date: '8',
          name: '可惜不是你',
          address: '4:49',
          names:'梁静茹',
        },
      ],
      
        }
    },
    methods:{
        goBack() {
     this.$router.go(-1);
 },
    }
}
</script>
<style  scoped>
    .songlist{
        margin-top: 100px;
    }
    .img{
        margin-top: 50px;
        margin-left: 30px;
        height: 250px;
        width: 25%;
    }
    .imgtext{
        margin-top: 50px;
        margin-left: 30px;
        height: 250px;
    }
    .textsong{
        font-size: 20px;
        font-weight: bold;
    }
    .text{
        padding-top: 40px;
    }
    .inptext{
        width:80%;
        padding-left: 10%;
        padding-top: 10px;
    }
    .headtext{
        font-size: 20px;
    }
    .texticon{
    font-size:15px;
    padding-left:70%;
    color: darkgray;
    }
    .headtext{
        font-size: 31px;
    }
</style>
