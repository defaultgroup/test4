<!DOCTYPE HTML>
	<title>디폴트숙제-심우영</title>
	<head>
		<meta charset="UTF-8">
		<style type="text/css">
			body{
				background-color:#87CEEB;
				width: 700px; 
				margin: 0 auto;
				text-align: center;
			}
			button{
				background-color: #FFFFFF;
				border: none;
				color: blue;
				text-align: center;
				margin: 8px 16px;
			}
			#mondai{
				color:red;
				width:300;
				font-size:20pt;
			}

			#margin{
				width: 400px;
				margin: 0 auto;
			}
		</style>
		<script ="text/javascript">
			function chang(){
				alert("정답")
			}
			function nono(){
				alert("오답")
			}
		</script>
	</head>
	<body>
		<h1 id="mondai">문제 2번</h1>
		<br>
		<div id="margin">이 동물의 이름은?</div>
		<img src="http://postfiles12.naver.net/20150628_123/graindea_1435422901723zhszz_JPEG/20150618_170005.jpg?type=w2" width="740" height="555">
		<br>
		<br>
		<a href="wrong.html">
			<button onclick="nono();">1.강아지</button>
		</a>
		
		<a href="defaulthw.html">
			<button onclick="chang();">2.고양이</button>
			
		</a>
		
		<a href="wrong.html">
			<button onclick="nono();">3.캥거루</button>
		</a>
		
		<a href="wrong.html">
			<button onclick="nono();">4.다람쥐</button>
		</a>
		
		<a href="wrong.html">
			<button onclick="nono();">5.모름</button>
		</a>
	</body>
</html>
