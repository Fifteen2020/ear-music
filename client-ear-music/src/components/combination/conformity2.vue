<template>
<section class="icon">
<el-row >
  <el-col :span="3"><div class="grid-content bg-purple">.</div></el-col>
  <el-col :span="18" ><div class="grid-content bg-purple">
      <el-page-header @back="goBack" content="遇见不同">
</el-page-header>
        <img src="../../img/mv1.jpg" alt="" height="220px" width="450px" style="padding-top:50px">
        <img src="../../img/mv2.jpg" alt="" height="220px" width="450px" style="padding-left:100px">
      <ss :tableData = "music"></ss>
      <img src="../../img/longimg3.jpg" alt="" width="100%" height="80px">
      </div></el-col>
  <el-col :span="3"><div class="grid-content bg-purple">.</div></el-col>
</el-row>
    </section>
</template>
<script>
import ss from '../ss'
export default {
    data(){
        return{
          music: [{
        date: '1',
        name: '演员',
        address: '4:21',
        names:'薛之谦',
      },{
          date: '2',
          name: '刚刚好',
          address: '4:10',
          names:'薛之谦',
          
        },
        {
          date: '3',
          name: '平凡的一天',
          address: '4:41',
          names:'薛之谦',
          
        },
        {
          date: '4',
          name: '感觉自己是巨星',
          address: '3:10',
          names:'毛不易',
          
        },
         {
          date: '5',
          name: '光年之外',
          address: '3:55',
          names:'邓紫棋',
          
        },
         {
          date: '6',
          name: '倒数',
          address: '3:49',
          names:'邓紫棋',
          
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
        ss
              },
}
</script>
<style  scoped>

</style>