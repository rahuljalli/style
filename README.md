# style
css for naughty america
*{
	margin: 0;
	padding: 0;
	font-family: Century Gothic;
}
header{
	background-image:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)),url(../den.jpg);
	height:100vh;
	background-size: cover;
	background-position :center;
}
ul{
	float:right;
	
	list-style-type:none;
	margin-top:25px;

}

ul li{
	display: inline-block;
}

ul li a{
	text-decoration: none;
	color: #fff;
	padding:5px 20px;
	border: 1px solid transparent;
	transition: 0.6s ease;
}

ul li a:hover{
	background-color: #fff;
	color: #000;

}
ul li.active a{
	background-color: #fff;
	color: #000;

}
.logo img{
	float:left;
	width:150px;
	height: auto;
}

.main{
	max-width:1200px;
	margin:auto;
}
.title{
	position: absolute;
	top:50%;
	left: 50%;
	transform: translate(-50%,-50%);

}

.title h1{
	color: #ff0000;
	font-size: 70px;


}

.button{
	position: absolute;
	top:62%;
	left: 50%;
	transform: translate(-50%,-50%);

}

.btn{
	border: 1px solid #fff;
	padding: 10px 30px ;
	color:#fff;
	text-decoration: none;
	transition: 0.6s ease;


}

.btn :hover{
	background-color: #fff;
	color: #000;

}
