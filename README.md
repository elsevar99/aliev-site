<!DOCTYPE>
<html>
<head>
<TITLE>Пример</TITLE>
</head>
<body>
<style>
textarea
{
	width:500px;
	height:150px;
	border-color:#83c2ed;
}
input
{
	width:160px;
}
table
{	
	border-radius:5px;
	border-collapse:collapse;
	border-color:#2a4dab;
	display:block;
	width:700px;	
}
.header
{
	border-top:5px;
	background-color:#397cd0;
	height:40px;
}

.grad
{
 background: linear-gradient(to bottom, #83c2ed 0%, #3369c1 63%);
}
div
{
	margin-left:10px;
}
label
{
	margin-left:10px;
	font-family:Arial;
}

img
{
	margin:0;	
	margin-left:10px;
}
td
{
	width:700px;
	border:solid #2a4dab;
	border-left:1px;
	border-right:1px;
	border-bottom:1px;
}

p{
	margin-left:10px;
	margin-bottom:0;
	font-size:32;
}

button
{
	width:80px;
	height:25px;
	border-radius:4px;
	border-color:#3369c1;
	padding:5px;
	margin:1px;
}
select
{
	border-radius:3px;
}
h3{margin:0;}
.group{border: 1px solid #b1a89e; width:250px;}
.butt{
	margin-top:20px;
	margin-bottom:5px;
	border:2px solid #b1a89e;
	color:#0384b7;
	padding:0;
	width:100px;
}
.primer{
	font-size:20px;
	color:white;
	}
</style>
<table border="1px">
<tr class="header grad"><td><img name="img" src="mozila.png" height="18px"><label class="primer">Пример</label> </td></tr>
<tr ><td>  <p>Пример формы регистрации сайта</p>
<label for="login">Логин:</label>
<div><input type="text" name="name" ></div>
<label for="password"  >Пароль:</label>
<div><input type="password" value="123456"></div>
<label for="name" >URL-адрес сайта:</label>
<div> <input type="text" name="name" value="http://"></div>
<label for="name" >Название сайта:</label>
<div> <input type="text" name="name" ></div>
<label for="name" >Описание сайта:</label>
<div> <textarea></textarea></div>
<label for="name" >Тема сайта:</label>
<div>	  <select name="country">
			<option value="Тема не выбрана">Тема не выбрана</option> 
			<option value="Тема 1">Тема 1</option> 
		  </select>
</div>
<label for="name" >Баннер 88х31:</label>
<div class="group"><button>Обзор...</button><label>Файл не выбран.</label></div>
<div><button class="butt"><h3>Очистить</h3></button><button class="butt"><h3>Отправить</h3></button></div>

</td>

</tr>

</table>
</body>
</html>
