<template>
  <div id="Aside">
    <!-- 这是主页面左边的模块 -->
    <el-container>
      <!-- 这是主页面左上方的div -->
      <div>
        <el-header style="height: 30px">
          <span class="aside-top-header">全部产品</span>
        </el-header>
        <el-main>
          <p><strong>PC产品</strong></p>
          <div class="mainFont">
            <p>数据统计</p>
            <p>数据预测</p>
            <p>流量分析</p>
            <p>广告发布</p>
          </div>
        </el-main>
      </div>
      <!-- 这是主页面左中方的div -->
      <div>
        <el-main>
          <p><strong>手机应用类</strong></p>
          <div class="mainFont">
            <p>91助手</p>
            <p>产品助手</p>
            <p>只能地图</p>
            <p>团队语音</p>
          </div>
        </el-main>
      </div>
      <!-- 这是主页面左下方的div -->
      <div>
        <el-header id="bottomHeader" style="height: 30px">
          <span class="aside-top-header">最新消息</span>
        </el-header>
        <el-main>
          <div class="mainFont">
            <p>新闻条目1</p>
            <p>新闻条目2</p>
            <p>新闻条目3</p>
            <p>新闻条目4</p>
          </div>
        </el-main>
      </div>
      </el-container>
  </div>
</template>

<style scoped>
#bottomHeader{
  margin-top: 10px;
}
.el-main{
  padding: 10px;
  height: 200px;
}
.el-header{
  background-color: #41b883;
  line-height: 30px;
  font-size: 14px;
}
.aside-top-header{
  float: left;
}
.el-main > p{
  font-size: 14px;
}
.mainFont{
  font-size: 14px;
}
.mainFont > p{
  position: relative;
  left: 7px;
}
</style>