<html lang="ko">
<head>
<meta charset="UTF-8">
<title>Document</title>
<link rel="stylesheet" href="https://www.newmedu.com/common/css/owl.carousel.min.css" >
<link rel="stylesheet" href="animate.min.css" >
<script src="https://code.jquery.com/jquery-2.2.4.min.js" integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44=" crossorigin="anonymous"></script>
<script src="https://www.newmedu.com/common/js/owl.carousel.js"></script>
<link>
<style>
.container-lg {max-width: 100%;}
.px-3, .my-5 {margin: 0 !important; padding: 0 !important;}
.markdown-body h1 {display: none;}
.markdown-body ul, .markdown-body ol {margin: 0; padding: 0;}
.markdown-body li+li {margin: 0;}
* {margin: 0; padding: 0; box-sizing: border-box;}
body {font-family: 'Noto Sans KR', sans-serif;}
ul {list-style: none; }
a {text-decoration: none;}
table {border-collapse: collapse; width: 100%;}
table caption {width: 0; height: 0; font-size: 0;}
.cont_wrap {display: inline-block; width: 100%;}
.section_cont {width: 1100px; height: 100%; margin: 0 auto; font-size: 16px; }
.section_cont > h3 {display: inline-block; width: 100%; margin-bottom: 25px; padding-bottom: 10px; border-bottom: 1px solid #d0d0d0;}
.section_inner {padding: 50px 0 75px 0;}
.f_left {float: left;}
.f_right {float: right;}
.cont_w2, .cont_w3, .cont_w4 {float: left; display: inline-block;}
.cont_w2 {width: 49%; margin-left: 2%;}
.cont_w3 {width: 32%; margin-left: 2%;}
.cont_w4 {width: 23.5%; margin-left: 2%;}
.cont_w2:first-child, .cont_w3:first-child, .cont_w4:first-child {margin-left: 0;}
.tab_container .tab_content {width:100%;}
.tab_content {display: none;}
.tabs ul {display: inline-block; width: 100%;}
.tabs li {float: left; width: 20%; text-align: center; border: 1px solid #aaa; background: #f8f8f8;}
.tabs li:nth-child(1) {border-right: none;}
.tabs li a {display: block; width: 100%; line-height: 2; color: #333;}
.tabs li.active {border-bottom-color: #fff; background: #fff;}
.tabs li.active a {font-weight: bold;}
.owl-nav, .owl-dots {display: block; text-align: center;} 
.owl-nav .owl-prev, .owl-nav .owl-next{ display:inline-block; } 
.owl-dots .owl-dot {display: inline-block;} 
.owl-controls .owl-page span.owl-numbers {display: block; width: auto; height: auto; font-size: 20px;}    
header, footer {min-width: 1100px;}
header {position: relative;}
.header_top {height: 50px;}
.header_menu {position: absolute; top: 50px; left: 0; display: inline-block; width: 100%; height: 55px; border-top: 1px solid #bbb; border-bottom: 1px solid #bbb; background: #202020; z-index: 9;}
.header_menu_fixed {position: fixed; top: 0;}
.ul_mainmenu {}
.ul_mainmenu > li {float: left; display: inline-block; border-right: 1px solid #555;}
.ul_mainmenu > li:first-child {border-left: 1px solid #555;}
.ul_mainmenu > li > a {display: inline-block; height: 53px; padding: 15px 30px; line-height: 1; color: #f2f2f2; text-decoration: none;}
.ul_mainmenu > li > a:hover {background: #114de3;}
.ul_mainmenu li > a:after {display:block; width: 100%; padding-bottom: 4px; content: ''; border-bottom: solid 2px #eee; transform: scaleX(0); transition: transform 250ms ease-in-out;}
.ul_mainmenu li > a:hover:after, .ul_mainmenu li > a:focus:after {transform: scaleX(1);}
footer {background: #ddd;}
main {padding-top: 55px;}
.main_container {height: 300px;}
.section01, .section02 {height: 500px;}
.section01 {background: #f2f2f2;}
.section02 {}
.section02-owl-wrapper {position: relative;}
.section02-owl-wrapper .owl-dots {position: absolute; bottom: 10px; right: 60px;}
.section03 {border-top: 1px solid #ccc;}
.btn_wh {position: relative; display: inline-block; width: 200px; height: 40px; line-height: 36px; text-align: center; background: #fff; border: 1px solid #ccc; border-radius: 2px;}
.btn_wh > p {position: absolute; top: 0; left: 0; width: 100%; height: 100%;}
.btn_wh:hover p.btn_text {color: #222; z-index: 1;}
.btn_wh:hover p.btn_bg {animation: roll_img 1s; animation-fill-mode: both; width: 0; background: #ccc;}
 @keyframes roll_img{0%{width: 0}100%,to{width: 200px}}
.banner_right {position: absolute; right: 20px; top: 85px; width: 130px; margin-top: 400px; z-index: 9;}
.banner_right_fixed {position: fixed; margin-top: 0;}    
.banner_wrap { border: 1px solid #ccc; background: #fff; border-radius: 10px;}
.ul_rmenu > li {border-top: 1px dotted #ccc;}
.ul_rmenu > li:first-child {border-top: none;}
.ul_rmenu > li > a {display: inline-block; width: 100%; line-height: 2; text-align: center; color: #333;}
</style>
<script>
$(document).ready( function() {
    $('.main-carousel').owlCarousel({
        autoplay: true,
        autoplayHoverPause: true,
        autoplayTimeout: 5000,
        autoplaySpeed: 800,
        center: true,
        items: 1,
        stagePadding: 0,
        loop: true,
        margin: 0,
        nav: false,
//        navText:['<span class="ic_slider_prev02"></span>', '<span class="ic_slider_next02"></span>'],
        navgation: true,
        pagination: false,
        paginationNumbers: false,
        dots: true
    });
    $('.section02-carousel').owlCarousel({
        autoplay: true,
        autoplayHoverPause: true,
        autoplayTimeout: 5000,
        autoplaySpeed: 800,
        center: true,
        items: 3,
        stagePadding: 0,
        loop: true,
        margin: 10,
        nav: false,
        navgation: true,
        pagination: true,
        paginationNumbers: true,
        dots: true
    });
    $(".tab_container").each(function () {
      $(this).children(".tabs li:first").addClass("active");
      $(this).children(".tab_content").first().show();
    });
    $(".tabs li a").click(function () {
      $(this).parent().siblings("li").removeClass("active");
      $(this).parent().addClass("active");
      $(this).parent().parent().parent().parent().find(".tab_content").hide();
      var activeTab = $(this).attr("title");
      $("#" + activeTab).show();
    });
});
$(window).scroll( function() {
      if($(document).scrollTop() > $('.main_container').offset().top + 300) {
        $('.banner_right').addClass('banner_right_fixed');
      }
      else {
        $('.banner_right').removeClass('banner_right_fixed');
      }
});    
$(window).scroll( function() {
      if($(document).scrollTop() > 50) {
        $('.header_menu').addClass('header_menu_fixed');
      }
      else {
        $('.header_menu').removeClass('header_menu_fixed');
      }
}); 
$(window).on('load', function() {
    $(".section_main video").trigger("play");
});
</script>
</head>
<body>
<header>
    <div class="header_top">
        header_top
    </div>
    <div class="header_menu">
        <div class="section_cont">
            <ul class="ul_mainmenu">
                <li><a href="#">menu01</a></li>
                <li><a href="#">menu02</a></li>
                <li><a href="#">menu03</a></li>
                <li><a href="#">menu04</a></li>
                <li><a href="#">menu05</a></li>
            </ul>
        </div>
    </div>
</header>
<main>
    <div class="main_container">
        <div class="owl-wrapper main-owl-wrapper">
            <div class="main-carousel owl-carousel owl-theme">
              <div class="item">01</div>
              <div class="item">02</div>
            </div>
        </div>
    </div>
    <div class="section01 section_inner">
        <div class="section_cont">
            <h3>section01</h3>
            <div class="cont_wrap">
              <div class="cont_w4">
                <p><img src="https://newmedu.com/common/img/edu/section02_event02.jpg" alt="" /></p>
                <a href="#" class="btn_wh"><p class="btn_text">more</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
                <p><img src="https://newmedu.com/common/img/edu/section02_event02.jpg" alt="" /></p>
                <a href="#" class="btn_wh"><p class="btn_text">more</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
                <p><img src="https://newmedu.com/common/img/edu/section02_event02.jpg" alt="" /></p>
                <a href="#" class="btn_wh"><p class="btn_text">more</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
                <p><img src="https://newmedu.com/common/img/edu/section02_event02.jpg" alt="" /></p>
                <a href="#" class="btn_wh"><p class="btn_text">more</p><p class="btn_bg"></p></a>
              </div>
            </div>
        </div>
    </div>
    <div class="section02 section_inner">
        <div class="section_cont">
            <h3>section02</h3>
<!--
            <div class="cont_w4">cont_w4</div>
            <div class="cont_w4">cont_w4</div>
            <div class="cont_w4">cont_w4</div>
            <div class="cont_w4">cont_w4</div>
-->
            <div class="owl-wrapper section02-owl-wrapper">
                <div class="section02-carousel owl-carousel owl-theme">
                  <div class="item"><a href="https://house.newmedu.com/lanpage/content03" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event01.jpg" alt="" /></a></div>
                  <div class="item"><a href="https://house.newmedu.com/lanpage/content04" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event02.jpg" alt="" /></a></div>
                  <div class="item"><a href="https://house.newmedu.com/lanpage/content01" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event03.jpg" alt="" /></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content22" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event04.jpg" alt="" /></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content04" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event06.jpg" alt="" /></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content08" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event07.jpg" alt="" /></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content07" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event08.jpg" alt="" /></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content05" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event09.jpg" alt="" /></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content15" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event10.jpg" alt="" /></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content09" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event11.jpg" alt="" /></a></div>
                </div>
            </div>
        </div>
    </div>
    <div class="section03 section_inner">
        <div class="section_cont">
            <div class="tab_container tab_container_sub">
            <div class="tabs">
                <ul>
                    <li class="sub_tab1 active"><a href="javascript:;" title="sub_tab1">메인페이지</a></li>
                    <li class="sub_tab2"><a href="javascript:;" title="sub_tab2">서브페이지</a></li>
                    <li class="sub_tab3"><a href="javascript:;" title="sub_tab3">마이페이지</a></li>
                    <li class="sub_tab4"><a href="javascript:;" title="sub_tab4">상품페이지</a></li>
                    <li class="sub_tab5"><a href="javascript:;" title="sub_tab5">결제페이지</a></li>
                </ul>
            </div>
            <div id="sub_tab1" class="tab_content">
                sub_tab1<br />sub_tab1<br />sub_tab1<br />
            </div>
            <div id="sub_tab2" class="tab_content">
                sub_tab2<br />sub_tab2<br />
            </div>
            <div id="sub_tab3" class="tab_content">
                sub_tab3
            </div>
            <div id="sub_tab4" class="tab_content">
                sub_tab4
            </div>
            <div id="sub_tab5" class="tab_content">
                sub_tab5
            </div>
        </div>
        </div>
    </div>
    <div class="banner_right">
        <div class="banner_wrap">
            <ul class="ul_rmenu">
                <li><a href="#">rmenu01</a></li>
                <li><a href="#">rmenu02</a></li>
                <li><a href="#">rmenu03</a></li>
                <li><a href="#">rmenu04</a></li>
            </ul>
        </div>
    </div>
</main>
<footer>footer</footer>
</body>
</html>