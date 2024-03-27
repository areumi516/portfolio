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
.tab_content_wrap {height: 500px; margin-top: -7px; padding-top: 10px; text-align: center; border: 1px solid #aaa; overflow: auto;}
.tab_container_sub {border-top: 3px solid #5d5d5d;}
.tabs ul {display: inline-block; width: 100%; margin-top: -2px;}
.tabs li {float: left; width: 20%; text-align: center; border: 1px solid #aaa; border-top-color: #5d5d5d; background: #f8f8f8;}
.tabs li:nth-child(1) {border-right: none;}
.tabs li a {display: block; width: 100%; font-size: 14px; line-height: 2.8; color: #333;}
.tabs li.active {border-bottom-color: #fff; background: #fff;}
.tabs li.active a {font-weight: bold;}
.owl-nav, .owl-dots {display: block; text-align: center;} 
.owl-nav .owl-prev, .owl-nav .owl-next{ display:inline-block; } 
.owl-dots .owl-dot {display: inline-block;} 
.owl-controls .owl-page span.owl-numbers {display: block; width: auto; height: auto; font-size: 20px;}    
header, footer {min-width: 1100px;}
footer {text-align: center;}
footer .section_inner {padding: 50px 0;}
footer p, footer span {font-size: 12px; color: #606060;}
footer span {margin-left: 10px; padding-left: 10px; border-left: 1px solid #aaa;}
header {position: relative;}
.header_top {height: 50px;}
.header_top h1 {display: inline-block; width: 40px; height: 40px; margin: 7px 10px; font-weight: bold; text-align: center;background: #202020; color: #fff; border-radius: 100%;}
.header_menu {position: absolute; top: 50px; left: 0; display: inline-block; width: 100%; height: 55px; border-top: 1px solid #bbb; border-bottom: 2px solid #114de3; background: #202020; z-index: 9;}
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
.section01 {background: #f2f2f2;}
.section01 .cont_wrap + .cont_wrap {margin-top: 2%;}
.section02 {}
.section03 {background: #f0f0f0;}
.section03 .cont_w3 {width: 30%; margin-left: 4%;}
.section03 .cont_w3:first-child {margin-left: 0;}
.section03 .cont_wrap + .cont_wrap {margin-top: 4%;}
.section02-owl-wrapper {position: relative;}
.section02-owl-wrapper .owl-item {height: 188px; overflow: hidden;}
.section02-owl-wrapper .owl-dots {text-align: center;}
.section02-owl-wrapper .owl-theme .owl-dots .owl-dot span {display: block; width: 8px; height: 8px; margin: 0 0 0 5px; background: #b8b8b8; -webkit-backface-visibility: visible; transition: opacity .2s ease; border-radius: 100%;}
.section02-owl-wrapper .owl-theme .owl-dots .owl-dot.active span, .owl-theme .owl-dots .owl-dot:hover span {background: #114de3;}
.mobile_wrap {height: 400px; overflow-y: auto; border: 1px solid #202020; border-radius: 4px;}
.mobile_wrap::-webkit-scrollbar {width:5px;}
.mobile_wrap::-webkit-scrollbar-thumb {background: #114de3;}
.mobile_wrap::-webkit-scrollbar-track {background: #5d5d5d;}
.section04 {border-top: 1px solid #ccc;}
.btn_wh {position: relative; display: inline-block; width: 100%; height: 40px; line-height: 36px; text-align: center; background: #fff; border: 1px solid #ccc; border-radius: 2px;}
.btn_wh > p {position: absolute; top: 0; left: 0; width: 100%; height: 100%; color: #202020;}
.btn_wh:hover p.btn_text {color: #ccc; z-index: 1;}
.btn_wh:hover p.btn_bg {animation: roll_img 1s; animation-fill-mode: both; width: 0; background: #202020;}
 @keyframes roll_img{0%{width: 0}100%,to{width: 100%}}
.banner_right {position: absolute; right: 20px; top: 85px; width: 130px; margin-top: 400px; z-index: 9;}
.banner_right_fixed {position: fixed; margin-top: 0;}    
.banner_wrap { border: 1px solid #ccc; background: #fff; border-radius: 10px; opacity: 0.7;}
.ul_rmenu > li {border-top: 1px dotted #ccc;}
.ul_rmenu > li:first-child {border-top: none;}
.ul_rmenu > li > a {display: inline-block; width: 100%; line-height: 2; text-align: center; color: #333;}
.ul_rmenu > li > a:hover {opacity: 1;}
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
        items: 5,
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
      if($(document).scrollTop() > $('.section01').offset().top + 300) {
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
        <h1>R</h1>
    </div>
    <div class="header_menu">
        <div class="section_cont">
            <ul class="ul_mainmenu">
                <li><a href="#section01">Main page</a></li>
                <li><a href="#section02">Event page</a></li>
                <li><a href="#section03">Mobile page</a></li>
                <li><a href="#section04">Page Screenshot</a></li>
            </ul>
        </div>
    </div>
</header>
<main>
    <!-- <div class="main_container">
        <div class="owl-wrapper main-owl-wrapper">
            <div class="main-carousel owl-carousel owl-theme">
              <div class="item">01</div>
              <div class="item">02</div>
            </div>
        </div>
    </div> -->
    <div id="section01" class="section01 section_inner">
        <div class="section_cont">
            <h3>메인페이지</h3>
            <div class="cont_wrap">
              <div class="cont_w4">
                <p><img src="https://user-images.githubusercontent.com/107483293/177173070-1f763c83-db1d-4aa4-a5e0-a12786abc58e.jpg" alt="" ></p>
                <a href="https://house.newmedu.com/" target="_blank" class="btn_wh"><p class="btn_text">house.newmedu.com &gt;</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
                <p><img src="https://user-images.githubusercontent.com/107483293/177173138-3ee790cc-8282-4724-a912-7e83d7d5513e.jpg" alt="" ></p>
                <a href="https://newmedu.com/" target="_blank" class="btn_wh"><p class="btn_text">newmedu.com &gt;</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
                <p><img src="https://github.com/areumi516/portfolio/assets/107483293/4fb7f617-0303-49f6-a0c8-7b72e5ec6696" alt="" ></p>
                <a href="http://www.gosischool.or.kr/" target="_blank" class="btn_wh"><p class="btn_text">gosischool.com &gt;</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">d
                <p><img src="https://user-images.githubusercontent.com/107483293/177173138-3ee790cc-8282-4724-a912-7e83d7d5513e.jpg" alt="" ></p>
                <a href="http://www.newm.co.kr/new2/main/index.php" target="_blank" class="btn_wh"><p class="btn_text">newm.co.kr &gt;</p><p class="btn_bg"></p></a>
              </div>
            </div>
            <div class="cont_wrap">
              <div class="cont_w4">
                <p><img src="https://github.com/areumi516/portfolio/assets/107483293/1008c418-ea05-4d0f-9a7a-4443086f9b08" alt="" ></p>
                <a href="https://www.mdca.co.kr/lec/home/cyberlec/" target="_blank" class="btn_wh"><p class="btn_text">mdca.co.kr &gt;</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
                <p><img src="https://github.com/areumi516/portfolio/assets/107483293/63bf1350-6455-4b76-bc3d-3966d32ad5e2" alt="" ></p>
                <a href="https://www.helphouse.biz/" target="_blank" class="btn_wh"><p class="btn_text">helphouse.biz &gt;</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
                <p><img src="https://github.com/areumi516/portfolio/assets/107483293/2614a3cb-a5e0-438d-91c8-4253c0ec6e6e" alt="" ></p>
                <a href="javascript:;" class="btn_wh"><p class="btn_text">gosischool_new &gt;</p><p class="btn_bg"></p></a>
              </div>
              <div class="cont_w4">
              </div>
            </div>
        </div>
    </div>
    <div id="section02" class="section02 section_inner">
        <div class="">
            <h3>이벤트페이지</h3>
            <div class="owl-wrapper section02-owl-wrapper">
                <div class="section02-carousel owl-carousel owl-theme">
                  <div class="item"><a href="https://house.newmedu.com/lanpage/content03" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event01.jpg" alt="" ></a></div>
                  <div class="item"><a href="https://house.newmedu.com/lanpage/content04" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event02.jpg" alt="" ></a></div>
                  <div class="item"><a href="https://house.newmedu.com/lanpage/content01" target="_blank"><img src="https://newmedu.com/common/img/edu/section02_event03.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content22" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan14.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content04" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan04.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content08" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan08.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content07" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan07.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content05" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan05.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content15" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan15.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content09" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan09.jpg" alt="" ></a></div>
                  <div class="item"><a href="http://www.gosischool.or.kr/lec/home/cyberlec/new_lanpage.php?q=content33" target="_blank"><img src="https://www.gosischool.or.kr/img/new_page/main_new/thumb_lan33.jpg" alt="" ></a></div>
                </div>
            </div>
        </div>
    </div>
    <div id="section03" class="section03 section_inner">
        <div class="section_cont">
            <h3>모바일페이지</h3>
            <div class="cont_wrap">
              <div class="cont_w3">
                  <div class="mobile_wrap">
                    <a href="https://house.newmedu.com/" target="_blank" ><p><img src="https://user-images.githubusercontent.com/107483293/177176652-346a9dff-fd31-4a8a-8e0c-f66d22535c8e.jpg" alt="" ></p></a>
                  </div>
                </div>
              <div class="cont_w3">
                <div class="mobile_wrap">
                  <a href="https://newmedu.com/" target="_blank" ><p><img src="https://user-images.githubusercontent.com/107483293/177176782-9b466233-3d64-4a38-a00c-2decc3febb1c.jpg" alt="" ></p></a>
                </div>
              </div>
              <div class="cont_w3">
                <div class="mobile_wrap">
                  <a href="http://www.newm.co.kr/new_mobile/main/" target="_blank" ><p><img src="https://github.com/areumi516/portfolio/assets/107483293/197355bb-9047-4b02-b9a6-696f407ebc52" alt="" ></p></a>
                </div>
              </div>
            </div>
            <div class="cont_wrap">
              <div class="cont_w3">
                  <div class="mobile_wrap">
                    <a href="https://m.gosischool.or.kr/" target="_blank" ><p><img src="https://github.com/areumi516/portfolio/assets/107483293/a8e22315-c158-4439-a816-36288193a9d2" alt="" ></p></a>
                  </div>
                </div>
              <div class="cont_w3">
                <div class="mobile_wrap">
                  <a href="https://www.mdca.co.kr/lec/home/cyberlec/" target="_blank" ><p><img src="https://github.com/areumi516/portfolio/assets/107483293/f7b83984-c75c-40e1-b4cb-6c499d991140" alt="" ></p></a>
                </div>
              </div>
              <div class="cont_w3">
                <div class="mobile_wrap">
                  <a href="https://www.helphouse.biz/" target="_blank" ><p><img src="https://github.com/areumi516/portfolio/assets/107483293/197355bb-9047-4b02-b9a6-696f407ebc52" alt="" ></p></a>
                </div>
              </div>
            </div>
        </div>
    </div>
    <div id="section04" class="section04 section_inner">
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
                <div class="tab_content_wrap">
                  <img src="https://user-images.githubusercontent.com/107483293/177346746-7dd8aa3e-14f6-44f3-9617-7c83ecf010a7.jpg" alt="">
                </div>
            </div>
            <div id="sub_tab2" class="tab_content">
                <div class="tab_content_wrap">
                  <!-- <img src="https://user-images.githubusercontent.com/107483293/177182697-39ff317b-3ae5-4907-93e5-2ec6ab6aeeff.jpg" alt=""> -->
                  <img src="https://user-images.githubusercontent.com/107483293/177184420-90fe2ed7-3e74-46c3-bdf0-e5af464a7f63.jpg" alt="">
                </div>
            </div>
            <div id="sub_tab3" class="tab_content">
                <div class="tab_content_wrap">
                  <img src="https://user-images.githubusercontent.com/107483293/177185203-7aab5c5d-2b67-4044-aa99-ed345a65e4f9.jpg" alt="" >
                </div>
            </div>
            <div id="sub_tab4" class="tab_content">
                <div class="tab_content_wrap">
                  <div class="cont_wrap">
                      <div class="cont_w2"><img src="https://user-images.githubusercontent.com/107483293/177181900-a1c69db6-ada8-48dc-84f4-cdd70bc7cf71.jpg" alt=""></div>
                      <div class="cont_w2"><img src="https://user-images.githubusercontent.com/107483293/177181937-4fca0cb6-2347-49de-9417-2751b15032e9.jpg" alt=""></div>
                  </div>
                </div>
            </div>
            <div id="sub_tab5" class="tab_content">
                <div class="tab_content_wrap">
                  <div class="cont_wrap">
                      <div class="cont_w2"><img src="https://user-images.githubusercontent.com/107483293/177184971-5ce7efad-c05a-4480-bc53-f4a4212b5a17.jpg" alt=""></div>
                      <div class="cont_w2"><img src="https://user-images.githubusercontent.com/107483293/177185024-73fb5e94-7688-4dff-85be-7da2a655f3e6.jpg" alt=""></div>
                  </div>
                </div>
            </div>
        </div>
        </div>
    </div>
    <div class="banner_right">
        <div class="banner_wrap">
            <ul class="ul_rmenu">
                <li><a href="https://house.newmedu.com/" target="_blank">houseedu</a></li>
                <li><a href="https://elec.newmedu.com/" target="_blank">elecedu</a></li>
                <li><a href="https://newmedu.com/" target="_blank">newmedu</a></li>
                <li><a href="http://www.gosischool.or.kr/" target="_blank">gosischool</a></li>
                <li><a href="http://www.newm.co.kr/new2/main/index.php" target="_blank">newm</a></li>
                <li><a href="hhttps://www.helphouse.biz/" target="_blank">helphouse</a></li>
                <li><a href="https://www.mdca.co.kr/lec/home/cyberlec/" target="_blank">mdca</a></li>
            </ul>
        </div>
    </div>
</main>
<footer>
  <div class="section_cont section_inner">
    <p>Lee Ahreum<span>areumi516@gmail.com</span></p>
  </div>
</footer>
</body>
</html>
