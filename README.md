# AulaCSS
Tarefas de DW1 CSS/Javascript
*{margin: 0; padding: 0;}

body{
	margin:0 0;
}
div.header{
	padding:1px;
	color:white;
	background-color:#90EE90;

}

h1.header{
	padding:0;
	margin:0;
}

.menu{
	list-style:none;
	border:1px solid #C0C0C0;
	float:right;
}

.menu li{
	position:relative;
	float:right;
	border:1px solid #C0C0C0;
}

.menu li a, .menu li ul a{
	background:#90EE90;
	color:#333;
	text-decoration:none;
	padding: 5px 10px;
	display:block;
}

.menu li a:hover{
	background:gray;
	color:#FFF;
}

.menu li ul{
	position:absolute;
	left:0px;
	top:30px;
	background-color:#39FF14;
	display:none;
	z-index:1;
}

.menu li:hover ul, .menu li.over ul{
	display:block;
}

.menu li ul li{
	color:#FFF;
	border:1px solid #C0C0C0;
	display:block;
	width:150px;
}

div.footer{
	padding:1cm;
	color:white;
	background-color:green;
	clear:both;
}
