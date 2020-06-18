<template>
  <div id="app">
    <el-container>
      <el-header height='100px'>
        <Header></Header>
      </el-header>
      <el-container>
        <el-aside width="200px">
          <aside-top></aside-top>
        </el-aside>
        <el-container>
          <el-main id="AppMain">Main</el-main>
          <el-footer id="AppFooter" height='50px'>Footer</el-footer>
        </el-container>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import Header from '../src/components/Header'
import AsideTop from '../src/components/AsideTop'

export default {
  components: {
    Header,
    AsideTop
  }
}
</script>>

<style>
  #AppFooter{
    margin: 20px 0 0 20px;
  }
  #AppMain{
    margin: 20px 0 0 20px;
  }
  .el-header, .el-footer {
    background-color: #567596;
    color: #333;
    text-align: center;
    line-height: 50px;
  }
  
  .el-aside {
    background-color: white;
    color: #333;
    /* text-align: center; */
    /* line-height: 200px; */
    margin-top: 20px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    /* text-align: center; */
    /* line-height: 160px; */
    height: 400px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, .12), 0 0 6px rgba(0, 0, 0, .04)
  }
  
  body > .el-container {
    margin-bottom: 40px;
  }
  
  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 260px;
  }
  
  .el-container:nth-child(7) .el-aside {
    line-height: 320px;
  }
</style>
