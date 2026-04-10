<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device, initial-scale=1.0">
<title>Навигационное меню</title>
<style>

.header {
position: fixed; top: 0; left:0; right:0; background-color: #866348; color:white; display: flex; align-items: center; justify-content:center; padding:10px;
 
.menu{
display:flex;
justify-content:center;
background-color:#866348;
color:white;
padding:10px;
}

.menu a{
text-decoration:none;
margin:0 20px;
font-size:18px;
color:white;
}

.menu a:hover{
text-decoration:underline;
}
</style>
</head>
<body>
<header class="header">
<div class="menu">
<a href="#home">Главная</a>
<a href="#advantages">Преимущества</a>
<a href="#catalog">Каталог</a>
<a href="#contacts">Контакты</a>
</div>
</header>
</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport">
<title>Художественная галерея</title>
<style>

*{
box-sizing:border-box;
margin:0;
padding:0;
}

body {
font-family:'Arial',sans-serif;
background-color:#E7DED9;
color:#230D04;
line-height:1.5;
}

header {
background-color:#866348;
color:#230D04;
padding:10px;
text-align:left;
}

nav{
background-color:#866348;
overflow:hidden
}

nav ul {
list-style-type:none;
margin:0;
padding:0;
display:flex;
justify-content:center;
}

nav li {
margin:0 30px;
}

nav a {
color:#230D04;
text-decoration:none;
padding:1px 1px;
display:inline-block;
}

main {
max-width:700px;
margin:10px auto;
padding:10px;
background-color:#fff;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

h1 {
text-align:center;
margin-bottom:30px;
}

gallery-img {
width:100%;
height:auto;
border-radius:8px;
margin-bottom:20px;
}

.about-text {
background-color:#866348;
padding:15px;
border-left:4px solid #ddd;
margin-bottom:20px;
font-size:16px;
line-height:1.6;
}


нижний колонтитул { 
цвет фона: #866348;
цвет: #fff;
выравнивание по тексту: по центру;
отступ: 10 пикселей;
очистить: оба;
}
</style>
</head>
<основная часть>


<главная>

<img src="https://i.pinimg.com/736x/02/9d/0e/029d0ee7303a1a380df6ace3bec319f6.jpg" width="680" height="400">
<section id="home">
<h1>О галерее</h1>

<div class="decorative-element"></div>
<div class="about text">
Арт-галерея представляет собой уникальное пространство, объединяющее искусство, вдохновение и культурное наследие. Здесь посетители могут погрузиться в мир творчества, насладиться живописью, скульптурой, декоративным искусством. <br><br>
Мы гордимся тем, что наша площадка является местом притяжения ценителей прекрасного, профессионалов и любителей искусства, позволяя каждому почувствовать себя частью большого творческого сообщества.
</section>
</div>
</main>

</body>
</html>


<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport">
<title>Преимущества галереи</title>
<style>

body {
font-family:'Arial',sans-serif;
background-color:#E7DED9;
color:#230D04;
margin:0;
padding:0;
}

.top-decor {
background-color:#E7DED9;
padding:20px;
background-repeat:repeat-x;
background-position:top left;
}


h1{
text-align:center;
margin-top:20px;
font-weight:bold;
font-size:24px;
}

.content {
максимальная ширина: 800 пикселей;
поле: 0 автоматически;
отступ: 20 пикселей;
цвет фона: #ffffff; 
тень от рамки: 0 0 10 пикселей rgba (0,0,0,0.1);

}

.преимущество-карта { 
цвет фона: #866348;
отступ: 20 пикселей;
нижнее поле: 20 пикселей;
радиус границы: 45 пикселей;
вставка-тень: вставка 0 0 10px rgba(0,0,0,0.1);
}

strong { 
шрифт-вес: жирный;
}
</style>
</head>
<body>

<главная>

<img src="https://i.pinimg.com/1200x/68/ef/d8/68efd80afe2f1fc51cb684e84e00449f.jpg" width="680" height="75">
<section id="advantages">
<h1>Преимущества</h1>

<div class="content">

<div class="преимущество-карта">
<strong>Погружение в творчество:</strong>Возможность увидеть произведения искусства вблизи, прочувствовать их эмоциональную глубину и оценить мастерство исполнения.
</div>

<класс div="преимущество-карта">
<strong>Расширение горизонтов:</strong>Ознакомление с различными стилями, направлениями и техниками современного искусства.
</div>
<div class="advantage-card">
<strong>Специальное взаимодействие:</strong> общение с единомышленниками, обмен мнениями и впечатлениями, расширение круга знакомств среди поклонников искусства. 
</section>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Каталог живописи</title>
</head>
<body>

<main>

<img src="https://i.pinimg.com/1200x/68/ef/d8/68efd80afe2f1fc51cb684e84e00449f.jpg" width="620" height="75">


<nav>
<ul>
<li><a href="#catalog">Каталог</a></li>
<ul>
</nav>

<section id="catalog">
<h1>Живопись</h1>

<div class="gallery">

<div class="card">
<img src="https://i.pinimg.com/736x/b1/43/af/b143afc9e694dcbf40a102a7735139cd.jpg" width="620" height="500" style="border: 15px solid #3D271E; padding: 0px;">
</div>

<класс div="карточка">
<img src="https://i.pinimg.com/1200x/c8/95/25/c895255266330ed315a6f064752ec31f.jpg" width="620" height="500" style="border: 15px solid #3D271E; padding: 0px;">
</div>

<класс div="карточка">
<img src="https://i.pinimg.com/736x/d0/2d/6a/d02d6a63c193e19be845a742243c4560.jpg" width="620" height="500" style="border: 15px solid #3D271E; padding: 0px;">
</div>

<класс div="карточка">
<img src="https://i.pinimg.com/736x/e7/13/c9/e713c9b3387f2fb1d48f1c073b6bd4f2.jpg" width="620" height="500" style="border: 15px solid #3D271E; padding: 0px;">
</div>
</div>
</section>

<section id="catalog">
<h1>Скульптура</h1>

<style>
.image-container {
border: 15px solid #3D271E;
border-radius: 40px 40px 0 0;
overflow: hidden;
отображение: встроенный блок;
}
.изображение-контейнер img {
отображение: блок;
ширина: 620 пикселей;
высота: 500 пикселей;
}
</style>

<div class="изображение-контейнер">
<img src="https://i.pinimg.com/736x/10/33/7b/10337bc3bd7425eae6bb948913c7e45a.jpg" width="620" height="500">
</div>
<style>
.image-container {
border: 15px solid #3D271E; 
border-radius: 40px 40px 0 0;
overflow: hidden;
display: inline-block;
}
.image-container img {
display: block;
width: 620px;
height: 500px;
}
</style>

<div class="изображение-контейнер">
<img src="https://i.pinimg.com/736x/1a/b3/62/1ab36212108eaca314bcaefa151af95a.jpg" width="620" height="500">
</div>

<стиль>
.image-container {
border: 15px solid #3D271E;
border-radius: 40px 40px 0 0; 
overflow: hidden; 
display: inline-block; 
}
.image-container img {
display: block; 
width: 620px; 
height: 500px;
}
</style>

<div class="image-container">
<img src="https://i.pinimg.com/1200x/73/71/7d/73717d4114bdb2e83693401b76f7889f.jpg" width="620" height="500">
</div>

<style>
.image-container {
border: 15px solid #3D271E; /* Толщина и цвет рамки */
border-radius: 40px 40px 0 0; /* Скругление только сверху (л-в, п-в, п-н, л-н) */
overflow: hidden; /* Обрезает углы картинки по рамке */
display: inline-block; /* Подгоняет размер контейнера под картинку */
}
.изображение-контейнер img {
display: block; /* Убирает отступ снизу */
width: 590px; /* Задайте нужный размер */
размер: 500 пикселей;
}
</style>

<div class="изображение-контейнер">
<img src="https://i.pinimg.com/1200x/0d/a7/2e/0da72ed0047018aa61a296fb82939eb7.jpg" alt="Картинка">
</div>

<идентификатор раздела="каталог">
<h1>Декоративное искусство</h1>

<style>
.image-container {
border: 15px solid #3D271E;
радиус границы: 0 0 40px 40px;
переполнение: скрыто; 
отображение: встроенный блок;
}
.изображение-контейнер img {
отображение: блок; 
ширина: 590px; 
высота: 500px;
}
</style>

<div class="изображение-контейнер">
<img src="https://i.pinimg.com/1200x/2d/d2/75/2dd27595d2c4e9dfc0db7d7f96078f35.jpg" alt="Картинка">
</div>

<style>
.image-container {
border: 15px solid #3D271E;
border-radius: 0 0 40px 40px;
overflow: hidden;
display: inline-block;
}
.image-container img {
display: block;
width: 590px;
height: 500px;
}
</style>

<div class="image-container">
<img src="https://i.pinimg.com/736x/15/a3/25/15a3252ef27bab631bf2dc07262231d9.jpg"> 
</div>

<style>
.image-container {
border: 15px solid #3D271E;
border-radius: 0 0 40px 40px;
overflow: hidden;
display: inline-block;
}
.image-container img {
display: block;
width: 590px;
height: 500px;
}
</style>

<div class="image-container"> 
<img src="https://i.pinimg.com/736x/85/2c/93/852c93f109baf38a5c0e2b1c5945ef18.jpg"> 
</div> 

<style>
.image-container {
border: 15px solid #3D271E;
border-radius: 0 0 40px 40px;
overflow: hidden;
display: inline-block;
}
.image-container img {
display: block;
width: 590px;
height: 500px;
}
</style>
</head>
<body>

<div class="изображение-контейнер">
<img src="https://i.pinimg.com/736x/2e/b8/d6/2eb8d6e97850023aaaf93707f0de87ae.jpg">
</div>

<main>

<img src="https://i.pinimg.com/1200x/68/ef/d8/68efd80afe2f1fc51cb684e84e00449f.jpg" width="600" height="75">
</style>
</head>
<body>
<div class="контейнер">
<идентификатор раздела="контакты">
<h1>Контакты</h1>

<div style="отображать: сгибать; выравнивать-элементы: по центру; интервал: 15 пикселей;">
 <img src="https://i.pinimg.com/1200x/41/5e/cd/415ecdc69d2494dc67adacf417e261d3.jpg" style="width: 50px;">
 <p>+7(987)-654-32-10</p>
</div>

<div style="display: flex; align-items: center; gap: 15px;">
 <img src="https://i.pinimg.com/736x/5d/9b/95/5d9b9559c8e34b724443d59ebf880759.jpg" style="width: 50px;">
 <p>Art_gallery@gmail.com</p>
</div>

<p>Мы в соц сетях:</p>
<div style="отображать: сгибать; выравнивать-элементы: по центру; интервал: 15 пикселей;">
<img src="https://i.pinimg.com/1200x/51/09/ed/5109ed18340f7826fa95a90f76d91b73.jpg" style="width: 50px;">
<img src="https://i.pinimg.com/1200x/19/0e/49/190e49361834c3fc479d81516b3d32d2.jpg" style="width: 50px;">
<img src="https://www.rmwilliams.com/on/demandware.static/-/Library-Sites-rmw-shared-library/default/dwd3222f5a/Icons/RMW_icon_FB.png " style="ширина: 50 пикселей;">
</div>

<p>94-квартал, 30</p>
<p>Режим работы: ежедневно с 10:00 до 19:00</p>
<!DOCTYPE html>
<html>
 <head>
 <meta charset="utf-8">
 <title>Выравнивание фотографии</title>
 <style>
 .rightpic {
 float: right; /* Выравнивание по правому краю */
 margin: 0 0 5px 5px; /* Отступы вокруг фотографии */
 }
</section>
 </style>
 </head>
 <body>
 <p><img src="file:///C:/Users/miron/OneDrive/Desktop/лого.png" width="65" height="40" class="rightpic">
</div>
</body>
</html
