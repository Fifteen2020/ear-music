<template>
    <section>
        <div style="margin-top:100px;">
            <el-row >
           <el-col :span="3"><div class="grid-content bg-purple" >.</div></el-col>
           <el-col :span="18"><div class="grid-content bg-purple" >
            <el-page-header @back="goBack" content="音乐人">
</el-page-header>
            <div>
                <h2>全部分类</h2>
                <el-row   class="text">
                <el-col :span="2" style="background:#A0CFFF"><div class="grid-content bg-purple" >地区</div></el-col>
                <el-col :span="1" ><div class="grid-content bg-purple">内地</div></el-col>
                <el-col :span="1" ><div class="grid-content bg-purple">港台</div></el-col>
                <el-col :span="1" ><div class="grid-content bg-purple">欧美</div></el-col>
                <el-col :span="1" ><div class="grid-content bg-purple">日本</div></el-col>
                <el-col :span="1" ><div class="grid-content bg-purple">韩国</div></el-col>
                <el-col :span="1" ><div class="grid-content bg-purple">其他</div></el-col>
                </el-row>       
                 <el-row   class="text">
                <el-col :span="2" style="background:#A0CFFF"><div class="grid-content bg-purple">个性</div></el-col>
                <el-col :span="1" ><div class="grid-content bg-purple">流行</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">嘻哈</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">民谣</div></el-col>
                <el-col :span="2"><div class="grid-content bg-purple">轻音乐</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">爵士</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">古典</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">乡村</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">蓝调</div></el-col>
                </el-row>
                <el-row   class="text">
                <el-col :span="2" style="background:#A0CFFF"><div class="grid-content bg-purple">类别</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">男</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">女</div></el-col>
                <el-col :span="1"><div class="grid-content bg-purple">组合</div></el-col>
                </el-row>
                
            </div>
            <!--歌手图片-->
            <div >
                 <el-row  >
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer2.jpg" alt="薛之谦" class="imgs" width="140px" height="140px"><p>薛之谦</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer5.jpg" alt="薛之谦" class="imgs"  width="140px" height="140px"><p>陈奕迅</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer6.jpg" alt="薛之谦" class="imgs"  ><p>张国荣</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer7.jpg" alt="薛之谦" class="imgs" ><p>宋冬野</p></div></el-col>
                </el-row>
                  <el-row  >
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer9.jpg" alt="薛之谦" class="imgs" ><p>雨僮</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer10.jpg" alt="薛之谦" class="imgs"  ><p>毛不易</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer4.jpg" alt="薛之谦" class="imgs"  ><p>李荣浩</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer11.jpg" alt="薛之谦" class="imgs"  ><p>张杰</p></div></el-col>
                </el-row>
                 <el-row  >
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer12.jpg" alt="薛之谦" class="imgs" ><p>吴亦凡</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer13.jpg" alt="薛之谦" class="imgs"  ><p>陈立农</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer14.jpg" alt="薛之谦" class="imgs"  ><p>易烊千玺</p></div></el-col>
                <el-col :span="3" class="imglist"><div class="grid-content bg-purple"><img src="../img/singer15.jpg" alt="薛之谦" class="imgs"  ><p>王嘉尔</p></div></el-col>
                
                </el-row>
            </div>
            <!--分页-->
           <el-pagination
  background
  layout="prev, pager, next"
  :total="50"
  style="padding-left:35%;padding-top:40px">
</el-pagination>
            </div></el-col>
            
           <el-col :span="3"><div class="grid-content bg-purple">.</div></el-col>
             </el-row>
        </div>

    </section>
</template>
<style  scoped>
    .text{
        text-align: center;
        margin-left:40px;
        margin-top: 10px;
    }
    .imgs{
        border-radius:50%;
        width: 140px;
        height: 140px;
       
    }
    .imglist{
        margin-top: 50px;
        margin-left: 100px;
        text-align: center;
    }
</style>