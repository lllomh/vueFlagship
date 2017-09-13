<template id="">
  <div class="header_top">
      <div class="header_guanggao">
          <div class="dingwei_tow">
            <div class="logo"> <a href="index.html"><img src="/static/images/top_08.png" /></a>
              </div>
              <div class="header_top_gg">
                  <ul>
                      <li><a href="Child pages/BB.html"><img src="/static/images/top_10.png"/></a></li>
                        <li class="top_12_lianjie"><a href="Child pages/Lipstick.html"><img src="/static/images/top_12.png" /></a></li>
                        <li><a href="Child pages/BB.html"><img src="/static/images/top_14.png" /></a></li>

                    </ul>
                </div>
            </div>
        </div>
      <div class="header_daohanlan">
  <ul class="nav">
    <li><a href="index.html">首页有礼</a></li>
      <li><a href="Child pages/baby.html">所有宝贝<img src="/static/images/HOT.gif" /></a>
        <ul class="second-nav">
          <li><a href="Child pages/Lipstick.html">果冻口红<img src="/static/images/H_tow.gif" /></a>

                            </li>

          <li class="second-nav-tow"><a href="Child pages/Facial mask.html">面膜<img src="/static/images/H_tow.gif" / style="margin:8px 2px 2px 2px"></a></li>
                            <li><a href="Child pages/Make-up-box.html">明星彩妆系列<img src="/static/images/H_tow.gif" /></a></li>
                            <li><a href="Child pages/cc.html">水光气垫CC<img src="/static/images/H_tow.gif" /></a></li>
                            <li><a href="Child pages/Eye shadow.html">眼影<img src="/static/images/H_tow.gif" /></a></li>

        </ul>
      </li>
    <li><a href="#">热卖单品<img src="/static/images/HOT.gif" /></a>
      <ul class="second-nav">
        <li><a href="Child pages/cc.html">水光气垫CC</a></li>
        <li><a href="Child pages/Lipstick.html">果冻口红</a></li>
      </ul>
    </li>
  </ul>
        </div>
    </div>
</template>


<script>

$(function(){
  var _this1=null;
  $('.nav>li').hover(function(){
    _this1=$(this);
    _this1.find('.second-nav').show();
    var _this2=null;
    _this1.find('.second-nav').find('li').hover(function(){
      _this2=$(this);
      _this2.find('.third-nav').show();
      _this2.find('.third-nav').hover(function(){
        $(this).show();
      },function(){
        $(this).hide();
      });
    },function(){
      _this2.find('.third-nav').hide();
    });
  },function(){
    _this1.find('.second-nav').hide();
  });
});
</script>
