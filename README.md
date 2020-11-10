<!DOCTYPE html>
<html lang="ja">

<head>
  <meta charset="utf-8" />
  <title>紹介ブログ</title>
  <meta name="viewport" content="width=device-width" ; initial-scale=1.0 />

 <!-- Bootstrap CSS -->
 <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://code.jquery.com/ui/1.10.3/themes/smoothness/jquery-ui.css" />
  <link rel="stylesheet" href="animate.min.css" />

  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="bxslider.min.css" />
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.1.0/css/all.css" integrity="sha384-lKuwvrZot6UHsBSfcMvOkWwlCMgc0TaWr+30HWe3a4ltaBwTZhyTEggF5tJv8tbt" crossorigin="anonymous">
 

  <script src="/js/jquery.js"></script>
  <script src="/js/bxslider.min.js"></script>
  <script src="https://code.jquery.com/ui/1.10.3/jquery-ui.js"
    integrity="sha256-ugED92WALymbx9ylw12aADWaCrsQysE29DyvnAv5i3w=" crossorigin="anonymous"></script>

  <script>
    $(function () {
      $("#aside").tabs();
    });

    $(document).ready(function(){
  var windowWidth = jQuery(window).width();
  if (windowWidth >= 360) {
    var numi = 5,
      numx = 5, 
      numi2 = 5,
      numx2 = 5,
      mar = 20;
  } else {
    var numi = 1,
      numx = 1, 
      numi2 = 3,
      numx2 = 3,
      mar = 0;
  }
    $('.slider').bxSlider({
    minSlides: numi,
    maxSlides: numx,
    moveSlides: 1,
    slideMargin: mar,
    auto: true,
    pager: false,
  nextText: '<i class="fa fa-angle-right" aria-hidden="true"></i>',
    prevText: '<i class="fa fa-angle-left" aria-hidden="true"></i>'
  });
});
  </script>

<script>
    $('#sample-animate-click').click(function(){
    $('#sample-animate-click').addClass('animated infinite pulse');
  });
</script>

<script>
$(function(){
  $(window).on('load scroll', function() {
     var winScroll = $(window).scrollTop();
     var winHeight = $(window).height();
     var scrollPos = winScroll + (winHeight * 0.8);

     $(".show").each(function() {
        if($(this).offset().top < scrollPos) {
           $(this).css({opacity: 1, transform: 'translate(0, 0)'});
        }
     });
  });
});
</script>

<style>
  .animated:hover {
  animation-iteration-count: infinite;
  animation-fill-mode: both;
  }
</style>


</head>

<body>

  
  <div id="header">

    <img src="image/sax.jpg" width="70" height="60" alt="" />   
    <h1><a href="#">Web_Tenorman</a></h1>
    <p>Web_Tenorman &amp;COLLECTIBLES</p>
  </div>
  
 
 
  <div id="main">
    <div class="sub-main">
      <img class="main-image" src="image/meg-WD5p2ekiqm8-unsplash.jpg" width="360" height="160" alt="main image" />
      <p>Enjoy Adrib life</p>
    </div>
   <h2 class="animated rubberBand">TENOR MANIA</h2>
    <ul>
      <a href="#">
        <li><img src="image/3.jpg" width="100" height="100" alt="" />
          <h3>OLD BOOKS</h3>
          <p>1111111111111111111111</p>
        </li>
      </a>
      <a href="#">
        <li><img src="image/10old.jpg" width="100" height="100" alt="" />
          <h3>OLD BOOKS2</h3>
          <p>2222222222222222222222</p>
        </li>
      </a>
      <a href="#">
        <li><img src="image/blue-sky-white-clouds_640x1136.jpg" width="100" height="100" alt="" />
          <h3>OLD BOOKS3</h3>
          <p>3333333333333333333333</p>
        </li>
      </a>
    </ul>
  </div>

  <div id="nav" >
    <h2>SKILL</h2>
    <ul>

      <li><a href="#">
     
        <div  class="slide-bottom show" class="fadeInUp" data-wow-delay=".3s">
          <p>HTML/CSS
            <i class="fab fa-html5"></i>
            <i class="fab fa-css3"></i>
          </p>
          </div>  
           </a></li>

      <li><a href="#"> 
        <div  class="slide-bottom show" class="fadeInUp" data-wow-delay=".3s"> 
          <p>Bootstrap
          <i class="fab fa-bootstrap"></i>
         </p>
      </div>  
      </a></li>

      <li><a href="#">
        <div  class="slide-bottom show" class="fadeInUp" data-wow-delay=".3s"> 
          <p>wordpress
          <i class="fab fa-wordpress"></i>
         </p>
      </div>  
      </a></li>


      <li><a href="#">
        <div  class="slide-bottom show" class="fadeInUp" data-wow-delay=".3s"> 
          <p>jquery
          <i class="fab fa-js-square"></i>
         </p>  
        </div>  
      </a></li>
      
      <li><a href="#">
        <div  class="slide-bottom show" class="fadeInUp" data-wow-delay=".3s"> 
          <p>Figma
          <i class="fab fa-figma"></i>
         </p>  
        </div> 
      </a></li>
     
    </ul>
  </div>

  <section class="front__slider__section">
    <div class="container container-1200">
      
        <h3><span class ="wcfontsize6 " >－ ＥＮＪＯＹ ＭＵＳＩＣ －</span></h3>
        <p class="text " >好きな練習、嫌いな練習もバランスよく進行。<br>心も身体も喜ぶ料理をご用意しています。</p>
        </div>


    <ul class="slider carousel__item--store">
          
      <li>
        <div class="carousel__item">
          <p><img src="image/fabio-alves-yFAY_s-2tS8-unsplash.jpg" alt="つるあん" width="360" height="250"></p>
          <div class="carousel__body">
            <div class="carousel__title">
              <h4>つるあん</h4>
              <p class="text">手筒花火をイメージした豊橋名物「豊橋カレーうどん」</p>
            </div>
            <div class="carousel__meta">
              <p class="carousel__days">営業時間</p>
              <p class="carousel__hour">9：00～19：00（L.O18：30）</p>
            </div>
          </div>
          <p class="carousel__foot"><a href="#">Click</a></p>
        </div>
      </li>
      <li>
        <div class="carousel__item">
          <p><img src="image/jens-thekkeveettil-dBWvUqBoOU8-unsplash (1).jpg" alt="コッぺとサンド オリーブの風" width="360" height="250"/></p>
          <div class="carousel__body">
            <div class="carousel__title">
              <h4>グループレッスン</h4>
              <p class="text">111111111111111111111111「豊橋カレーうどん」</p>
             </div>
            <div class="carousel__meta">
              <p class="carousel__days">営業時間</p>
              <p class="carousel__hour">9：00～19：00（L.O18：30）</p>
            </div>
          </div>
          <p class="carousel__foot"><a href="#">Click</a></p>
        </div>
      </li>
           
    </ul>
  </section>

 

  

  <div id="aside">
    <ul>
      <li><a href="#tabs-1">ABOUT</a></li>
      <li><a href="#tabs-2">SEARCH</a></li>
      <li><a href="#tabs-3">ACCESS</a></li>
    </ul>

    <div id="tabs-1">
      <p>hhhhhhhhhhhhhhhhhhhhhhhhhh</p>
    </div>
    <div id="tabs-2">
      <p>kkkkkkkkkkkkkkkkkkkkkkkkkk</p>
    </div>
    <div id="tabs-3">
      <p>ggggggggggggggggggggggggg</p>
         <form method="GET" action="#">
        <input type="text" name="example">
        <input type="submit" value="検索">
      </form>
    </div>
  </div>

  <div id="footer">
    <p>&copy ;Web_Tenorman</p>
  </div>




</body>

</html>
