<!-- 展示模板 -->
<template>
  <div id="app">
    <Header></Header>
    <Home></Home>
  </div>
</template>

<script>
// 导入组件
// import './jq/jquery-1.8.3.min.js'
// import Hello from './components/Hello'

import Home from './home/Home'
export default {
  name: 'app',
  components: {
    Home
  }
}
</script>
<!-- 样式代码 -->
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>
