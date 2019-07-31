# gotop
<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
  <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
</head>
<html>
  <body>
    <pre>
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    スクロール用の仮テキスト
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    ・
    </pre>
    <p id="pageTop"><a href="#"><i class="fa fa-chevron-up "></i></a></p>


<style>
  /*-- CSSの記述 --*/
  #pageTop {
    position: fixed;
    bottom: 20px;
    right: 20px;
  }
  #pageTop i {
  	padding-top: 6px 
  }
  #pageTop a {
    display: block;
    z-index: 999;
    padding: 8px;
    border-radius: 30px;
    width: 35px;
    height: 35px;
    background-color: #9FD6D2;
    color: #fff;
    font-weight: bold;
    text-decoration: none;
    text-align: center;
  }
  #pageTop a:hover {
    text-decoration: none;
    opacity: 0.7;
  }
</style>

<script>
  // Javascriptの記述
  //■page topボタン
  $(function(){
  var topBtn=$('#pageTop');
  topBtn.hide();

  //◇ボタンの表示設定
  $(window).scroll(function(){
    if($(this).scrollTop()>80){
      //---- 画面を80pxスクロールしたら、ボタンを表示する
      topBtn.fadeIn();
    }else{
      //---- 画面が80pxより上なら、ボタンを表示しない
      topBtn.fadeOut();
    } 
  });

  // ◇ボタンをクリックしたら、スクロールして上に戻る
  topBtn.click(function(){
    $('body,html').animate({
    scrollTop: 0},500);
    return false;
  });

  });
</script>

  </body>
</html>
