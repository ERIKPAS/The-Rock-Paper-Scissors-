# CSS style sheet
@import url('https://fonts.googleapis.com/css2?family=Days+One&display=swap');

* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
 
body {
	background-color: rgb(50, 50, 50) ;
}



header {
	background: rgb(150, 0, 300); 
	padding: 15px;

}
header > h1 {
	text-align: center;
	font-family: Days one;
}

.Score {
	margin: 20px auto;
	border: 5px solid none ;
	width: 200px ;
	color: rgb(150, 0, 300);
	font-size: 50px;
	padding: 20px 50px;
	font-family: days one;
	position: relative;

}

#user-label {
	position: absolute;
	top: 15%;
	left: -50%;
}
#computer-label {
	position: absolute;
	top: 15%;
	left: 95%;
}

.result {
	margin: 50px;
	text-align: center;
	font-size: 50px;
	font-family: Days one;
	color: rgb(150, 0, 300);
}


.choices {
	margin: 150px 50px;
	text-align: center;
}
.img-rock {
	width: 300px;
	height: 300px;
}
.img-scissors {
	width: 300px;
	height: 300px;
}
.img-paper {
	width: 375px;
	height: 300px;
}

.choice {
	display: inline-block;
	border: 4px solid none;
	padding: 150px;
}
