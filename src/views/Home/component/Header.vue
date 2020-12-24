<template>
  <div class="header">
      <div class="header-left">
          <div class="iconfont back-icon">&#xe622;</div>
      </div>
      <div class="header-center">
          <span class="iconfont">&#xe641;</span>
          输入城市/景点/游玩主题
          </div>
      <div class="header-right">城市<span class="iconfont downicon">&#xe64a;</span></div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl';
.header{
    display: flex;
    height: .86rem;
    line-height: .86rem;
    background-color: $bgColor;
    
}
.header-left{
    width:.64rem;
}
.header-center{
    padding-left: .2rem;
    flex-grow: 1;
    height: .64rem;
    line-height: .64rem;
    margin-top:.12rem ;
    margin-left: .2rem;
    background: #fff;
    border-radius: .1rem;
    color: #ccc;
}
.header-right{
    width:1.24rem;
    text-align: center;
    color: #fff;
}
.back-icon{
    text-align: center;
    font-size: .4rem;
}
.downicon{

    font-size: .2rem;
}
</style>