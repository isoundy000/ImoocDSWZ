
<!-- 脚部组件 -->

<template>
  <footer class="footer">
    <div class="inner-c">

      <!-- 网站信息 s -->
      <p class="info">
        <a href="javascript:;">慕课简介</a>
        <span>|</span>
        <a href="javascript:;">慕课公告</a>
        <span>|</span>
        <a href="javascript:;">招纳贤士</a>
        <span>|</span>
        <a href="javascript:;">联系我们|客服热线：400-675-1234</a>
      </p>
      <!-- 网站信息 e -->

      <!-- 版权信息 s -->
      <p class="copyright">
        Copyright © 2006 - 2014&nbsp;慕课版权所有&nbsp;&nbsp;&nbsp;京ICP备09037834号&nbsp;&nbsp;&nbsp;京ICP证B1034-8373号&nbsp;&nbsp;&nbsp;某市公安局XX分局备案编号：123456789123
      </p>
      <!-- 版权信息 e -->

      <!-- 底部小图标 s -->
      <div class="footerIcon">
        <a href="javascript:;" class="footerIcon-1">经营性网站备案中心</a>
        <a href="javascript:;" class="footerIcon-2">可信网站信用评估</a>
        <a href="javascript:;" target="_blank" class="footerIcon-3">网络警察提醒您</a>
        <a href="javascript:;" class="footerIcon-4">诚信网站</a>
        <a href="javascript:;" target="_blank" class="footerIcon-5">中国互联网举报中心</a>
        <a href="javascript::" target="_blank" class="footerIcon-6">网络举报APP下载</a>
      </div>
      <!-- 底部小图标 e -->

    </div>
  </footer>
</template>

<script>
  export default {

    //组件名称
    name: 'footerBar'
  };
</script>

<style scoped>
  .footer {
    width: 100%;
    height: 224px;
    margin-top: 40px;
    background-color: #d4d4d4;
    font-family: "新宋体";
    text-align: center;
    color: #000;
    display: table;
  }

  .footer .info {
    padding: 56px 0 12px 0;
  }

  .footer .copyright {
    padding-bottom: 38px;
  }

  .footerIcon a {
    width: 103px;
    height: 32px;
    background: url("../assets/images/icon/ico_footer.png");
    background-repeat: no-repeat;
    text-indent: -1000px;
    overflow: hidden;
    display: inline-block;
  }

  .footerIcon .footerIcon-1 {
    background-position: 0 -151px;
  }

  .footerIcon .footerIcon-2 {
    background-position: -104px -151px;
  }

  .footerIcon .footerIcon-3 {
    background-position: 0 -184px;
  }

  .footerIcon .footerIcon-4 {
    background-position: -105px -184px;
  }

  .footerIcon .footerIcon-5 {
    background-position: 0 -217px;
  }

  .footerIcon .footerIcon-6 {
    background-position: -104px -217px;
  }

  .footer a {
    color: #000;
  }
</style>
