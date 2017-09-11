<!-- 展示模板 -->
<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <Header></Header>
  </div>
</template>

<script>
// 导入组件
import Hello from './components/Hello'
import Header from './header/Header'
export default {
  name: 'app',
  components: {
    Hello,
    Header
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
  margin-top: 60px;
}
</style>
