# sunny
nothing is impossible 
<html>
	<head>
		<meta charset="UTF-8">
		<title>选择器</title>
		<style>
			/*4.通配符选择器*/
			*{
				background-color: powderblue;
			}
			/*通过标签选择的body来选择也可以达到这样的效果
			 * body{
				background-color: peachpuff;
			}*/
			/*1.类选择器*/
			/*	1.1<标签名 class="类名"></标签名>*/
			/*	1.2 通过 .类名{
			 * 			属性名1:属性值1;
			 * 			属性名2：属性值2;
			 * 			....
			 * }*/
			.span1{
				color: green;
			}
			.span2{
				color: gold;
			}
			/*2.ID选择器*/
			/*	2.1<标签名 id="ID名"></标签名>*/
			/*	1.2 通过 #ID名{
			 * 			属性名1:属性值1;
			 * 			属性名2：属性值2;
			 * 			....
			 * }*/
			#astyle{
				font-size: 30px;
			}
			/*3.标签选择器*/
			h2{
				font-size: 50px;
			}

		</style>
	</head>
	<body>
		<h2 class="span2">我是一个标题</h2>
		<span class="span1">我是一个段落</span>
		<span class="span2">我是第二个段落</span>
		<a href="#" id="astyle">更多</a>
	</body>
</html>
