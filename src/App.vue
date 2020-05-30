<template>
  <div>
    <Header/>
    <Center/>
    <Footer/>
  </div>
</template>
<script>
import Header from './components/Header'
import Footer from './components/Footer'
import Center from './components/Center'
export default {
  name: 'App',
  //注册组件
  components:{
    Header,
    Center,
    Footer
  },
  // 页面加载后的生命周期回调
  mounted(){
    // 通过dispatch提交对应的action,获取分类信息数据(没有必要发多次请求)
    // this.$store.dispatch('getBaseCategoryList')
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
</style>
