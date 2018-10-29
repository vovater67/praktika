<!DOCTYPE html>
<html>
<head> 
	<meta charset="utf-8">
	<title>Резюме</title>
	<link rel="stylesheet" href="mystyle.css" type="text/css"/>
</head>
<body>
<div id="header">
	<h1>Владимир Тарасенко</h1>
	<h3>Я у мамы программист</h3>
	<p>
		<a href="mailto:vovater67@yandex.ru"> vovater67@yandex.ru </a>
		<a href="https://vk.com/ter67"> Мой ВК </a>
	</p>
</div>
<div id="main">
	<p>Тут я опишу себя что и как.</p>

	<h2>Опыт работы</h2>
	<hr/>
	<h4>Профкровля</h4>
	<p>Cтажер</p>
	<ul>
		 <li>Первый пункт</li>
		 <li>Второй пункт</li>
		 <li>Третий пункт</li>
	</ul>

	<h2>Образование</h2>
	<hr/>
	<ul>
		 <li>Первый пункт</li>
		 <li>Второй пункт</li>
		 <li>Третий пункт</li>
	</ul>
	<h2>Другие увлечения</h2>
	<hr/>
	<ul>
		 <li>Первый пункт</li>
		 <li>Второй пункт</li>
		 <li>Третий пункт</li>
    </ul>
</div>
<div id="footer">
	<p>
		<a href="mailto:vovater67@yandex.ru"> vovater67@yandex.ru </a>
		<a href="https://vk.com/ter67"> Мой ВК</a>
	</p>
</div>
</body>
</html>


body {
  font-family: Georgia; 
  font-size: 16px;
  margin: 0 auto;   
  max-width: 800px; 
  line-height: 1.5;
  padding-top: 32px;
  padding-bottom: 32px;
}

p, h2, h4, ul {
	margin: 0;
	margin-bottom: 12px ;
}


h1,h2,h3 {
	margin-bottom: 12px ;
	font-weight: 400;
}

h1 {
	font-size: 36px;

}


h2 {
	font-size: 32px;
	margin-bottom: 8px ;
}


h3 {
	font-size: 20px;

}

#header, #footer{
	text-align:center;
}


#header {
	margin-bottom: 32px;
}


#footer {
	margin-top: 64px;
}


hr {
	height:1px;
	width:800px;
}
