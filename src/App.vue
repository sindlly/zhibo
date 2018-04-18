<template>
  <div id="wrapper">
    <div class="title">
      <p>中移物联网有限公司第一届</p>
      <p>"幸福1+1阳光心飞YOUNG"员工运动会</p>
      <p>第二季篮球比赛</p>
    </div>
    <div>
      <router-view></router-view>
    </div>

  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style>
  body{
    width: 100%;
    position: absolute;
    margin: 0;
    background: #eee;
  }
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #fff;
    margin-top: 60px;
  }
  .container{

  }
  p{
    margin:0 ;
  }
  #wrapper{
    position: absolute;
    width: 100%;
  }
  .title{
    /*height: 150px;*/
    width: 100%;
    padding: 20px 0;
    text-align: center;
    font-size: 1.2rem;
    color: #333;
    background: #fff;

  }
</style>
