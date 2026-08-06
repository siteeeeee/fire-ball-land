<html lang="fa" dir="rtl">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Nova Land</title>

<style>

*{
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
margin:0;
font-family:tahoma;
background:#111827;
color:white;
transition:.4s;
}


header{
background:#0f172a;
padding:20px;
position:sticky;
top:0;
z-index:100;
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
color:#38bdf8;
}


.hero{
text-align:center;
padding:100px 20px;
background:linear-gradient(135deg,#ff6666,#ff0000);
}


.hero h1{
font-size:55px;
animation:fade 2s;
}


.hero p{
font-size:22px;
}


.btn{
display:inline-block;
background:white;
color:#111;
padding:15px 35px;
border-radius:30px;
text-decoration:none;
margin-top:20px;
}


section{
padding:60px 10%;
}


.title{
text-align:center;
font-size:35px;
margin-bottom:40px;
}


.cards{
display:flex;
gap:20px;
justify-content:center;
flex-wrap:wrap;
}


.card{
background:#1f2937;
padding:30px;
width:280px;
border-radius:20px;
text-align:center;
transition:.4s;
}


.card:hover{
transform:translateY(-10px);
background:#374151;
}


.gallery{
display:flex;
gap:20px;
justify-content:center;
flex-wrap:wrap;
}


.gallery div{
width:200px;
height:150px;
background:#334155;
border-radius:15px;
display:flex;
align-items:center;
justify-content:center;
font-size:25px;
}


.contact{
text-align:center;
}


button{
padding:12px 25px;
border:none;
border-radius:20px;
cursor:pointer;
}


footer{
background:#020617;
text-align:center;
padding:25px;
}


@keyframes fade{

from{
opacity:0;
transform:translateY(-30px);
}

to{
opacity:1;
}

}


.light{
background:#f1f5f9;
color:#111;
}


.light header{
background:white;
}


.light .card{
background:white;
color:#111;
}


</style>

</head>


<body>


<header>

<nav>

<a href="#home">🏠 خانه</a>

<a href="#services">استف</a>

<a href="#about">👤 درباره ما</a>

<a href="#gallery">رنک فروشی</a>

<a href="#support">🛠 پشتیبانی</a>

<button onclick="dark()">🌙</button>

</nav>

</header>


<section class="hero" id="home">

<h1>Fire ball land</h1>

<p>
به دنیای حرفه ای فایر بال لند خوش آمدید.
</p>

<a class="btn" href="#services">
ip : 185.26.33.12
</a>

</section>


<section id="services">

<h2 class="title">
staff استف
</h2>


<div class="cards">


<div class="card">
<h2>Owner-اونر</h2>
<p>
NazaninMLV
Shadow
</p>
</div>


<div class="card">
<h2>Co-Owner-کو اونر</h2>
<p>
itz mohammad
</p>
</div>


<div class="card">
<h2>Dev-دولپر</h2>
<p>
zuri58
</p>
</div>


</div>

</section>

                        <section id="about">

<h2 class="title">
👤 درباره ما
</h2>

<p style="text-align:center;font-size:20px">

سلام پلیر گرامی ما یک سرور ماینکرفت بدراک داری با نام فایر بال لند اگر دوست  دار یتو
 سرور ما بدرخشی و گیم پلی عالی رو تجربه کنی پس برو پایین و   به روبیکا ما پیام بده و رنک بخر
 تیم پشتیبانی فایر بال لند

</p>

</section>



<section id="gallery">

<h2 class="title">
رنک های فروشی سرور
</h2>


<div class="gallery">

<div>
a
</div>


<div>
b
</div>


<div>
c
</div>


<div>
d
</div>


</div>

</section>



<section id="support" class="contact">


<h2 class="title">
🛠 پشتیبانی
</h2>


<p>
برای ارتباط با تیم پشتیبانی Fire ball land روی دکمه زیر کلیک کنید.
</p>


<a class="btn"
href="https://rubika.ir/nazaninmlv"
target="_blank">

ورود به پشتیبانی روبیکا

</a>


</section>



<footer>

© 2026 Fire ball land | تمامی حقوق محفوظ است

</footer>



<script>


function dark(){

document.body.classList.toggle("light");

}


</script>


</body>

</html>
