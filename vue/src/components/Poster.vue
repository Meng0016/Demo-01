<template>
<div >
  <img style="width: 100%;height:60px" src="https://img.zcool.cn/community/018d755bebde64a801209252b9ab10.jpg?x-oss-process=image/auto-orient,1">
</div>
  <div class="box">
    <div class="search-box">

      <input type="text" class="search-left" placeholder="请输入要搜索的内容"/>
      <el-button class="search-right"><el-icon><Search /></el-icon>搜索</el-button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Poster"
}
</script>

<style scoped>
.box{
  text-align:center;
 font-size: 0;
}
.search-box{
  margin:0 auto;
  width: 750px;
}
.search-left{
  text-indent: 20px;
  width:80%;
  height:50px;
  border: rgb(211, 109, 78) 1px solid;
  float:left;
  margin-top:20px;
  border-bottom-left-radius:25px;
  border-top-left-radius:25px;
  outline:none;
 /*text-align: 20px ;*/
}
.search-right{
  width:19%;
  height:50px;
  background: rgb(234, 96, 20);
  color: #ffeeee;
  border:none;
  margin-top:20px;
  border-bottom-right-radius:25px;
  border-top-right-radius:25px;
  outline:none;
}
</style>