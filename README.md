# javamaks.github.io

<!DOCTYPE html>
<html lang="ru">
<meta charset="utf-8">
<head>
	<link rel="stylesheet" type="text/css" href="snow.css">
	<title></title>
</head>
<script src="script.js"></script>
<body>
 
 <div class="tag-inner">
<h3>Merry<br>Christmas</h3>
<p><img src="https://html5book.ru/wp-content/uploads/2017/05/bells.png"></p>
<div class="tag-line"></div>
</div>
<style>* {
   box-sizing: border-box;
}
.tag-inner {
   position: relative;
   width: 240px;
   margin: 100px auto 0;
   padding: 30px 0 0;
   background: #C0D9C4;
}
.tag-inner:before {
   content: "";
   position: absolute;
   z-index: -1;
   top: -120px;
   width: 240px;
   height: 240px;
   background: #C0D9C4;
   transform: scale(0.76, 0.4) rotate(45deg);
   border-bottom-left-radius: 30px;
   border-top-left-radius: 10px;
   border-top-right-radius: 30px;
}
.tag-inner:after {
   content: "";
   position: absolute;
   z-index: 10;
   top: -40px;
   left: calc(50% - 10px);
   width: 20px;
   height: 20px;
   border-radius: 50%;
   background: #ffffff;
   box-shadow: inset 1px 1px 3px rgba(0, 0, 0, .3), 0 0 0 7px rgba(0, 0, 0, .08);
}
.tag-inner h3 {
   margin: 0;
   font-family: 'Great Vibes', cursive;
   font-size: 36px;
   text-align: center;
   letter-spacing: 3px;
   color: #BA4732;
   text-shadow: 3px -2px 0 white;
}
.tag-inner p {
   position: relative;
   margin: 0;
   padding: 20px;
   text-align: center;
}
.tag-inner p:after {
   content: "";
   position: absolute;
   width: 100%;
   height: 10px;
   left: 0;
   bottom: -10px;
   background: radial-gradient(#C0D9C4 0%, #C0D9C4 70%, rgba(255, 255, 255, 0) 70%, rgba(255, 255, 255, 0) 100%) 0 -10px;
   background-size: 20px 20px;
   background-repeat: repeat-x;
}
.tag-line {
   height: 60px;
   background: repeating-linear-gradient(90deg, #F4EDD6, #F4EDD6 19px, #f4dc9c 19px, #f4dc9c 20px);
}</style>
</body>
</html>
