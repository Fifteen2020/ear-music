<template>
    <section class="mv">
        <div class="mv">
            <h2 style="text-align: center;">MV精选</h2>
         <el-row >
            <el-col :span="10"  class="mv1"><div class="grid-content bg-purple">
            <!-- <img :src="imgsrc1"  alt="" width="100%" height="220px" > -->
            <video  width="100%" height="220px" controls > 
                <source src="https://apd-3b8a15b48c4a25f4f0e10a86c94c0a3c.v.smtcdns.com/mv.music.tc.qq.com/A0jjesK_k7gJzRZBaHDfr01YN0KFlV-3vnKApvTbJFK4/E9121CF71B698D21F38121897ABEAEC3356067FCC7A4608E96D198B4269CF9CD5AC7197A49F8A169DF51D59D4F3B33D0ZZqqmusic_default/qmmv_0b6bkuaboaaac4aczy7ubrpviviac5kqaf2a.f9844.mp4?fname=qmmv_0b6bkuaboaaac4aczy7ubrpviviac5kqaf2a.f9844.mp4" type="video/mp4" >
            </video>
            </div></el-col>
            <el-col :span="10" style="margin-left:50px;" class="mv1"><div class="grid-content bg-purple">
             <!-- <img :src="imgsrc2" alt="" width="100%" height="220px">   -->
                <video  width="100%" height="220px" controls > 
                <source src="https://apd-ec526d075fc9d95df034a72c8ef608a0.v.smtcdns.com/mv.music.tc.qq.com/AGL6xSl0Ql5ABxW3oNr8hJir6Qy0p0SMH0hGcGL7hF5U/5C41E14237ABDB3D35B11623A958ED2811EFAE535390C5CFE531247F0364670E7EFAA84E03701B82405A24C630E595D2ZZqqmusic_default/qmmv_0b6bsqaaiaaa5iaeanqjijqfjfaaaskaabca.f9844.mp4?fname=qmmv_0b6bsqaaiaaa5iaeanqjijqfjfaaaskaabca.f9844.mp4" type="video/mp4" >
            </video>
            </div></el-col>
            </el-row>

        </div>
           
    </section>
</template>
<script>

export default {
//   props: ["imgsrc1,imgsrc2"],

    data(){
        return{
        }
    },
    methods:{

    }   ,
}
</script>
<style scoped>
    .mv{
        width: 100%;
        height: 300px;
    }
    .mv1{
        margin-left:50px;
       
    }
    .mv1 :hover{
         opacity:0.9;

    }
</style>