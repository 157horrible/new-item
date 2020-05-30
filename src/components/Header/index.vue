<template>
  <div class="top">
    <!-- <div>
      <a>登录/注册</a>|<a>我的订单</a>|<a>会员</a>|<a>甄选家</a>|<a>企业采购 ...</a>|<a>客户服务 ...</a>|<span class="imge"></span><a>APP</a>
    </div> -->
    <img class="top-img" src="./img/ia_100000007305.png">
    <div class="top-sousuo">
      <img class="top-left" src="./img/0314790e-8a67-47e0-9394-9213dcdfefac.png">
      <div class="top-center" >
        <img src="./img/ia_300000053.png"><span>搜索商品共111111款好物</span>
      </div>
      <div class="top-right">登录</div>
    </div>
    <div class="top-button">
      <div class="inner">
        <div class="list">
          <a>推荐</a>
          <a>居家生活</a>
          <a>服饰鞋包</a>
          <a>美食酒水</a>
          <a>个护清洁</a>
          <a>母婴亲子</a>
          <a>运动旅行</a>
          <a>数码家电</a>
          <a>严选全球</a>
          <a>为你严选</a>
          <a>众筹</a>
        </div>
      </div>

      <span></span>
      <div class="toggle">
        <img class="icon" src="./img/ia_300000054.png">
      </div>
    </div>
    <!-- 轮播图 -->
    <van-swipe class="my-swipe" :autoplay="2000" indicator-color="white">
      <van-swipe-item>1</van-swipe-item>
      <van-swipe-item>2</van-swipe-item>
      <van-swipe-item>3</van-swipe-item>
      <van-swipe-item>4</van-swipe-item>
    </van-swipe>
  </div>
</template>
<script>
import tools from '../../../tools/rem2'
export default {
  name:'Header',
  data(){
    return{

    }
  },
  components:{

  }
}
</script>
<style >
  .top{
    width: 100%;
    height: .5rem;
    font-size: .1rem;
  }
  .top .top-img{
    width: 100%;
  }
  .top .top-sousuo{
    display: flex;
    justify-content: space-around;
    align-items:center;
    margin-top: .2rem;
  }
  .top .top-sousuo .top-left{
    width: 2rem;
  }
  .top .top-sousuo .top-center{
    width: 6.5rem;
    height: .8rem;
    line-height: .8rem;
    border-radius: .1rem;
    background-color:	#F5F5F5 ;
    color: black;
    display: flex;
    align-items:center;
  }
  .top .top-sousuo .top-center img{
    height: .4rem;
    margin: 0 .1rem 0 .6rem;
  }
  .top .top-sousuo .top-right{
    height: .6rem;
    width: 1.2rem;
    border: .5px solid red;
    text-align: center;
    line-height: .6rem;
    border-radius:.1rem ;
    color: red;
    font-size: .4rem;
  }
  .top .top-button{
    position: relative;
  }
  .top .top-button .inner{
    width: 80%;
    height: .8rem;
    overflow: hidden;
    position: relative;
    margin: .2rem 0 0 0;
  }
  .top .top-button .inner .list{
    position: absolute;
    left: -3.35rem;
    width: 33rem;
    height: .8rem;
    overflow: hidden;
    text-align: center;
  }
  .top .top-button .list a{
    width: 3rem;
    font-size: .4rem;
    padding: 0 .41333rem;
  }
  .top .top-button span{
    width: 1.5rem;
    position: absolute;
    left: .2rem;
    border-bottom:.1rem solid red ;
  }
  .top .top-button .toggle{
    position: absolute;
    right: 0;
    top: 0;
    flex: 1;
    width: 10%;
    height: .8rem;
    height: 1rem;
    background-color:white ;
    display: flex;
    justify-content: center;
    align-items:center
  }
  .top .top-button .toggle .icon{
    height: .5rem;
    width: .5rem;
  }
</style>
<style>

</style>
