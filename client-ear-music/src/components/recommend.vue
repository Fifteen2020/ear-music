<template>
    <section class="recommend">
         <div class="recommend"><!--推荐left-->
            <div class="recommend-text">
               分类
            </div>
            <div class="recommend-img">
                <img src="../img/img2.jpg" alt="" class="img">
                <img src="../img/background2.png" alt="" class="img2">
                <el-button style="width:120px;margin-top:10px;" @click="$router.push('/song1')">飙升榜</el-button>
                <!--  -->
            </div>
            <div class="recommend-img">
                <img src="../img/play1.jpg" alt="" class="img">
                <img src="../img/background1.png" alt="" class="img2">
                <el-button style="width:120px;margin-top:10px;" @click="$router.push('/song2')">网络热曲</el-button>
            </div>
            <div class="recommend-img">
                <img src="../img/img3.jpg" alt="" class="img">
                <img src="../img/background3.png" alt="" class="img2">
                <el-button style="width:120px;margin-top:10px;" @click="$router.push('/song1')">原创榜</el-button>
                <!--  -->
            </div>
            <div class="recommend-img">
                <img src="../img/img1.jpg" alt="" class="img">
                 <el-button style="width:120px;margin-top:10px;">经典怀旧</el-button>
            </div>
          </div>
    </section>
</template>
<style  scoped>
.recommend{
    width: 200px;
    height: 400px;
     box-shadow: 0 7px 4px rgba(5, 33, 70, 0.12), 0 0 6px rgba(0, 0, 0, .04);
     float: left;
     border-right: solid rgb(84, 103, 122) 1px;

}
.recommend-img{
    margin-top: 30px;
    position: relative;

}
.img{
    float:left;
    width:80px;
    height:60px;
}
.img2{
    position: absolute;
    display: block;
    width: 80px;
    height: 60px;
    opacity:0.7;
}
.recommend-text{
    font-size: 18px;
    text-align: center;
    /* background: #7EB9C6; */
    background:linear-gradient(#fff1eb,#77B3DE);
    opacity:0.7;
    font-weight: bold;
    color: #6E8DA3;
    
}
</style>