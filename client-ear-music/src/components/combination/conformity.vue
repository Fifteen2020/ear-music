<template>
<section class="icon">
<el-row >
  <el-col :span="3"><div class="grid-content bg-purple">x</div></el-col>
  <el-col :span="18"><div class="grid-content bg-purple">
      <el-page-header @back="goBack" content="每日推荐">
</el-page-header>
      <long-img :imgsrc="sr"></long-img>
      <ss :tableData = "music"></ss>
      </div></el-col>
  <el-col :span="3"><div class="grid-content bg-purple">x</div></el-col>
</el-row>
    </section>
</template>
<script>
// import longimg from './img'
import longimg from '../img'
import ss from '../ss'
export default {
    data(){
        return{
            sr:require('../../img/longimg.jpg'),
             music: [{
        date: '1',
        name: '歌曲标题',
        address: '4:20',
        names:'华晨宇',
      },{
          date: '2',
          name: '将故事写成我们',
          address: '5:35',
          names:'林俊杰',
        },
        {
          date: '3',
          name: '我们很好',
          address: '4:29',
          names:'林俊杰',
        },
        {
          date: '4',
          name: '平淡日子里的刺',
          address: '3:46',
          names:'宋冬野',
        },
         {
          date: '5',
          name: 'SOSO',
          address: '3:18',
          names:'Winner',
        },
          {
          date: '6',
          name: '卡比巴拉的海',
          address: '4:24',
          names:'宋冬野',
        },
          {
          date: '7',
          name: '富士山下',
          address: '4:19',
          names:'陈奕迅',
        },
      ],
        }
    },
    methods:{
 goBack() {
     this.$router.go(-1);
 }
    },
      components: {
        //   longnimg
        "long-img":longimg,
        ss
              },
}
</script>
<style  scoped>

</style>