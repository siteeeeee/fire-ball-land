
<html lang="fa" dir="rtl">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Fire Ball  Land</title>

<style>

*{
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
margin:0;
font-family:tahoma;
background:#0b0000;
color:white;
}


header{
background:#180000;
padding:20px;
position:sticky;
top:0;
z-index:10;
border-bottom:2px solid #ff0000;
}


nav{
display:flex;
justify-content:center;
gap:25px;
flex-wrap:wrap;
}


nav a{
color:white;
text-decoration:none;
font-size:18px;
}


nav a:hover{
color:#ff3333;
}



.hero{

text-align:center;
padding:100px 20px;
background:
linear-gradient(
135deg,
#ff0000,
#550000
);

}


.hero h1{

font-size:55px;
text-shadow:0 0 20px red;

}


.hero p{

font-size:24px;

}



.btn{

display:inline-block;
background:#ff0000;
color:white;
padding:15px 35px;
border-radius:30px;
text-decoration:none;
margin:15px;

}


.btn:hover{

background:#990000;

}



section{

padding:60px 10%;

}



.title{

text-align:center;
font-size:35px;
color:#ff3333;

}



.cards{

display:flex;
gap:20px;
justify-content:center;
flex-wrap:wrap;

}



.card{

background:#210000;
border:1px solid red;
width:280px;
padding:30px;
border-radius:20px;
text-align:center;
transition:.4s;

}



.card:hover{

transform:translateY(-10px);
box-shadow:0 0 20px red;

}



.ip{

background:#150000;
padding:25px;
border-radius:20px;
text-align:center;
font-size:25px;
border:2px solid red;

}



.rules li{

margin:15px;
font-size:18px;

}



footer{

background:#050000;
padding:25px;
text-align:center;

}



.fire{

animation:fire 1s infinite alternate;

}



@keyframes fire{

from{
text-shadow:0 0 10px red;
}

to{
text-shadow:0 0 30px orange;
}

}


</style>

</head>



<body>


<header>

<nav>

<a href="#home">🏠 خانه</a>

<a href="#about">🔥 درباره سرور</a>

<a href="#features">⭐ امکانات</a>

<a href="#rules">📜 قوانین</a>

<a href="#support">🛠 پشتیبانی</a>

</nav>

</header>




<section class="hero" id="home">


<h1 class="fire">
🔥 Fire Ball Land 🔥
</h1>


<p>
به سرور حرفه‌ای فایر بال لند خوش آمدید
</p>


<a class="btn" onclick="copyIP()">
کپی IP سرور
</a>


<div class="ip">
185.26.33.12
</div>


</section>





<section id="about">

<h2 class="title">
🔥 درباره سرور
</h2>


<p style="text-align:center;font-size:20px">

سلام، به سرور فایربال لند خوش امدید.

سرور فایربال لند یک سرور خفن جالب و پر هیجان است، شما میتوانید در این سرور رولپلیی خفن را تجربه و بازی کنید.

شما برای ورود باید ایپی سرور را کپی کرده و در بخش اد سرور ماینکرافت توی servers بزارید

اگر دوست دارید از همه پلیر ها یک قدم جلو تر باشید میتوانید با خریدن رنک این کار رو انجام بدید

</p>


</section>





<section id="features">


<h2 class="title">
⭐ امکانات سرور
</h2>


<div class="cards">


<div class="card">

<h2>⚔️ گیم پلی</h2>

<p>
تجربه‌ای هیجان‌انگیز برای بازیکنان
</p>

</div>



<div class="card">

<h2>🏆 رنک‌ها</h2>

<p>
سیستم رنک حرفه‌ای
</p>

</div>




<div class="card">

<h2>🛡 امنیت</h2>

<p>
محیط امن و مدیریت قوی
دارای لاگین سرور دارای تیم استف کامل و با مدریت عالی
</p>

</div>


</div>

</section>





<section id="rules">


<h2 class="title">
📜 قوانین
</h2>


<ul class="rules">

<li>❌ استفاده از چیت ممنوع</li>

<li>❌ توهین ممنوع</li>

<li>✅ احترام به بازیکنان الزامی است</li>

<li>✅ همکاری با تیم مدیریت</li>


</ul>


</section>





<section id="support">


<h2 class="title">
🛠 پشتیبانی
</h2>


<p style="text-align:center">

برای پشتیبانی با مدیریت سرور ارتباط بگیرید.

</p>


<a class="btn"
href="https://rubika.ir/joinc/FEJDCJHH0QJTHNRNIEWSUFWASQXQGYJS"
target="_blank">

ورود به پشتیبانی روبیکا

</a>
</center>


</section>





<footer>

🔥 Fire Ball Land © 2026

</footer>




<script>

function copyIP(){

navigator.clipboard.writeText("185.26.33.12");

alert("IP سرور کپی شد!");

}

</script>


</body>

</html>
