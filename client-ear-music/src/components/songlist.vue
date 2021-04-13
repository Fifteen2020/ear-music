<template>
  <section class="song">
    <div
      style="
        padding-top: 20px;
        box-shadow: 0 7px 4px rgba(5, 33, 70, 0.12), 0 0 6px rgba(0, 0, 0, 0.04);
      "
    >
      <h2 style="padding-left: 30px" v-show="bool != 'false'">热门歌单</h2>
      <el-row>
        <el-col :span="10" class="songmax">
          <div class="grid-content bg-purple">
            <div class="dynamic">
              <img
                src="../img/songlist1.jpg"
                alt=""
                width="100%"
                height="200px"
              />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                  @click="$router.push('/songsheet')"
                />
              </div>
            </div>
          </div>
        </el-col>

        <el-col :span="4" class="songmax2"
          ><div class="grid-content bg-purple">
            <div class="dynamic">
              <img src="../img/songlist2.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div>
            <span>未闻花名</span>
          </div></el-col
        >
        <el-col :span="4" class="songmax2"
          ><div class="grid-content bg-purple">
             <div class="dynamic">
              <img src="../img/songlist3.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div>
            <span>生活是条沉船，但我们别忘了在救生艇上高歌</span>
          </div></el-col
        >
        <el-col :span="4" class="songmax2"
          ><div class="grid-content bg-purple">
             <div class="dynamic">
              <img src="../img/songlist4.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div><span
              >嘻哈 | 一字一句，我的浪漫密语</span
            >
          </div></el-col
        >
      </el-row>
      <el-row v-show="bool != 'false'" style="margin-top: 20px">
        <el-col :span="10" class="songmax3"
          ><div class="grid-content bg-purple" style="margin-left: 20px">
            <el-col :span="10" class="songmax3"
              ><div class="grid-content bg-purple">
                 <div class="dynamic">
              <img src="../img/songlist5.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div><span
                  >欧美 | 小众私藏，拯救歌荒</span
                >
              </div></el-col
            >
            <el-col :span="10" class="songmax3"
              ><div class="grid-content bg-purple">
                 <div class="dynamic">
              <img src="../img/songlist6.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div><span>粤语旋律的入坑指南</span>
              </div></el-col
            >
          </div></el-col
        >
        <el-col :span="4" class="songmax3"
          ><div class="grid-content bg-purple">
            <div class="dynamic">
              <img src="../img/songlist7.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div><span>社畜贤者时间の音乐大放送</span>
          </div></el-col
        >
        <el-col :span="4" class="songmax3"
          ><div class="grid-content bg-purple">
             <div class="dynamic">
              <img src="../img/songlist8.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div><span
              >浪漫宇宙 人间日常</span
            >
          </div></el-col
        >
        <el-col :span="4" class="songmax3"
          ><div class="grid-content bg-purple">
             <div class="dynamic">
              <img src="../img/songlist9.jpg" alt="" width="100%" />
              <div class="play-btn">
                <img
                  src="../img/play.png"
                  alt=""
                />
              </div>
            </div><span
              >快乐</span
            >
          </div></el-col
        >
      </el-row>
    </div>
  </section>
</template>
<script>
export default {
  props: ["bool"],
  data() {
    return {};
  },
};
</script>
<style scoped>
.songmax {
  margin-left: 20px;
  height: 110px;
}
.songmax2 {
  margin-left: 10px;
  padding-top: 10px;
}
.songmax3 {
  margin-left: 14px;
}
.dynamic {
  position: relative;
}
.dynamic:hover img{
  opacity: 0.8;
}

.play-btn {
  width: 100%;
  height: 200px;
  position: absolute;
  left: 0;
  top: 0;

  display: flex;
  justify-content: center;
  align-items: center;
}
.play-btn img {
  width: 80px;
  height: 80px;
  display: none;
}
.play-btn:hover img {
  display: block;
}
</style>