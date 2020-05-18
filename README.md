<!doctype>
<html>
<head>
<meta charset="utf-8">
 <title>Login Page</title>
 <link rel="stylesheet" href="style.css">
 <body>
 <div class="loginbox">
 <h1>  Login Here </h1>
 
 <div class="textbox">
 <i class="fa fa-user" aria-hidden="true"></i>
 <input type= "text" placeholder="Enter your email">
 </div>
 
 <div class="textbox">
 <i class="fa fa-lock" aria-hidden="true"></i>
 
 <input type= "Password" placeholder="Enter your Password">
 </div>
 
 <input class="btn" type="button" value="Sign in" 


 </body>

</head>

</html>


@import "https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css";

body{
	

margin: 0;
padding: 0;
left-side:30px;
width: 100%;
font-family: Courier;
background:url(1.jpg) ;
background-size: cover;
 

}
.loginbox{
	width:280px;
	position: absolute;
	above: 50%;
	top: 30%;
	left: 35%;
	right: 65%;
	transform= translate(-50%,-50%);
	color: #bfbfbf;
	
	
}
.loginbox h1{
	float: left;
	font-size: 40px;
	border-bottom: 5px solid #ff884d;
	margin-bottom : 50px;
	paadding: 13px 0;
	
}
.textbox{
	width: 100%;
	overflow: hidden;
	font-size: 20px;
	padding: 8px 0;
	margin: 8px 0;
	border-bottom: 2px solid #ff884d;
	
}
.textbox input{
	border: none;
	outline: none;
	background: none;
	color: white;
	font-size: 18px;
	width:80%;
	float: right;
	margin: 0 10px;
	
}
.btn{
	width:100%;
	background: none;
	border: 2px solid #ff884d;
	color: white;
	padding: 5px;
	font-size: 18px;
	cursor: pointer;
	margin: 12px 0;
}









