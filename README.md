<html lang="fa" dir="rtl">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Fire Ball Land | Minecraft Server</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:tahoma, Arial;
    background:#080808;
    color:white;
}


/* Header */

header{
    width:100%;
    position:fixed;
    top:0;
    right:0;
    background:rgba(0,0,0,0.85);
    padding:20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    z-index:999;
    border-bottom:2px solid #ff0000;
    backdrop-filter:blur(10px);
}


.logo{
    font-size:28px;
    color:#ff2020;
    font-weight:bold;
    text-shadow:0 0 15px red;
}


nav a{

    color:white;
    text-decoration:none;
    margin:10px;
    font-size:17px;
    transition:.3s;

}


nav a:hover{

    color:red;
    text-shadow:0 0 10px red;

}


/* Hero */

.hero{

    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    flex-direction:column;

    background:
    linear-gradient(
    rgba(0,0,0,.7),
    rgba(0,0,0,.9)
    ),
    url("https://wallpaperaccess.com/full/866877.jpg");

    background-size:cover;
    background-position:center;

}


.hero h1{

    font-size:70px;
    color:#ff2020;
    text-shadow:
    0 0 10px red,
    0 0 30px red;

    animation:fire 2s infinite alternate;

}


.hero p{

    margin-top:20px;
    font-size:22px;
    max-width:700px;
    line-height:2;

}


@keyframes fire{

from{

text-shadow:
0 0 10px red;

}

to{

text-shadow:
0 0 40px red,
0 0 70px orange;

}

}



.ip{

    margin-top:25px;
    background:#151515;
    padding:18px 35px;
    border-radius:15px;
    border:2px solid red;
    font-size:25px;
    box-shadow:0 0 20px red;

}



.btn{

    margin-top:30px;
    padding:15px 45px;
    background:red;
    color:white;
    text-decoration:none;
    border-radius:15px;
    font-size:20px;
    transition:.3s;

}


.btn:hover{

    background:#ff5555;
    transform:scale(1.1);

}


/* Sections */

section{

    padding:80px 10%;

}


.title{

    text-align:center;
    color:#ff3030;
    font-size:40px;
    margin-bottom:40px;
    text-shadow:0 0 15px red;

}


.cards{

    display:grid;
    grid-template-columns:
    repeat(auto-fit,minmax(230px,1fr));

    gap:25px;

}


.card{

    background:#151515;
    padding:30px;
    border-radius:20px;
    border:1px solid #ff2020;
    transition:.3s;

}


.card:hover{

    transform:translateY(-10px);
    box-shadow:0 0 25px red;

}


.card h3{

    color:#ff3030;
    margin-bottom:15px;

}


.card p{

    color:#ddd;
    line-height:1.8;

}

/* Server Info */

.server-box{

    background:#151515;
    padding:35px;
    border-radius:20px;
    border:2px solid red;
    text-align:center;
    box-shadow:0 0 20px rgba(255,0,0,.3);

}


.server-box h2{

    color:#ff3030;
    margin-bottom:20px;

}


.info{

    display:grid;
    grid-template-columns:
    repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
    margin-top:30px;

}


.info div{

    background:#202020;
    padding:20px;
    border-radius:15px;

}


.info span{

    display:block;
    color:#ff3030;
    font-size:25px;
    margin-bottom:10px;

}


/* Ranks */

.rank{

    text-align:center;

}


.rank h3{

    font-size:28px;

}


.owner{

    color:#ff0000;

}


.admin{

    color:#00aaff;

}


.legend{

    color:#ffd700;

}


.vip{

    color:#00ff66;

}


/* Rules */

.rules li{

    list-style:none;
    background:#171717;
    padding:18px;
    margin:12px;
    border-radius:12px;
    border-right:4px solid red;

}


/* Support */

.support{

    text-align:center;
    background:#151515;
    border-radius:20px;
    padding:40px;
    border:1px solid red;

}


/* Footer */

footer{

    background:#000;
    padding:25px;
    text-align:center;
    border-top:2px solid red;
    color:#aaa;

}


/* Mobile */

@media(max-width:700px){

.hero h1{

font-size:40px;

}


nav{

display:none;

}


}

</style>

</head>


<body>


<header>

<div class="logo">
🔥 Fire Ball Land
</div>


<nav>

<a href="#home">خانه</a>
<a href="#features">امکانات</a>
<a href="#ranks">رنک‌ها</a>
<a href="#rules">قوانین</a>
<a href="#support">پشتیبانی</a>

</nav>


</header>

<main>


<section class="hero" id="home">

<h1>
🔥 Fire Ball Land 🔥
</h1>


<p>
به سرور حرفه‌ای ماینکرفت ما خوش آمدید.
<br>
تجربه‌ای جذاب، امکانات زیاد و جامعه‌ای دوستانه منتظر شماست.
</p>


<div class="ip">

📡 IP :
<br>
185.26.33.12

</div>


<a class="btn" href="https://rubika.ir/fireball_land">
    ورود به چنل روبیکا سرور
</a>


</section>



<section id="features">


<h2 class="title">
⭐ امکانات سرور
</h2>


<div class="cards">


<div class="card">

<h3>
🎮 Rolplay
</h3>

<p>
حالت بقا با تجربه‌ای جذاب و چالش‌های مختلف.
</p>

</div>



<div class="card">

<h3>
💰Money
</h3>

<p>
سیستم اقتصادی، خرید و فروش و کسب درآمد داخل بازی.
</p>

</div>



<div class="card">

<h3>
👑 Rank
</h3>

<p>
رنک‌های ویژه با امکانات متفاوت برای بازیکنان.
</p>

</div>



<div class="card">

<h3>
🛒 Shop
</h3>

<p>
فروشگاه حرفه‌ای برای خرید آیتم‌ها.
</p>

</div>


 <div class="card">

<h3>
Administration
</h3>

<p>
سیستم مدریت حرفه ای
</p>

</div>


<div class="card">

<h3>
🎉 Events
</h3>

<p>
رویدادهای جذاب و مسابقات هفتگی.
</p>

</div>

<div class="card">

<h3>
Rank shop
</h3>

<p>
رنک های فروشی متنوع و با قیمت اقتصادی, برای خرید رنک به چنل سرور مراجعه کنید.
</p>

</div>

</div>


</section>

 <section>


<h2 class="title">
📡 اطلاعات سرور
</h2>


<div class="server-box">


<h2>
Fire Ball Land Server
</h2>


<div class="info">


<div>

<span>
🌐
</span>

IP

<br>

185.26.33.12

</div>


<div>

<span>
🟢
</span>

آنلاین است.

<br>

Online

</div>


</div>


</div>


</section>




<section id="ranks">


<h2 class="title">
👑 رنک‌های سرور
</h2>


<div class="cards">


<div class="card rank">

<h3 class="owner">
OWNER
</h3>

<p>
NazaninMLV
<br>
Shadow
</p>

</div>



<div class="card rank">

<h3 class="admin">
Co-Owner
</h3>

<p>
itz mohamad
</p>

</div>



<div class="card rank">

<h3 class="legend">
Dev
</h3>

<p>
Zuru58
</p>

</div>


</div>


</section>





<section id="rules">


<h2 class="title">
📜 قوانین سرور
</h2>


<ul class="rules">


<li>
❌ استفاده از چیت ممنوع است.
</li>


<li>
🤝 به بازیکنان و اعضای تیم احترام بگذارید.
</li>


<li>
🚫 اسپم و تبلیغات بدون اجازه ممنوع است.
</li>


<li>
⚖️ قوانین سرور را رعایت کنید.
</li>


</ul>


</section>





<section id="support">


<h2 class="title">
💬 پشتیبانی
</h2>


<div class="support">


<p>
برای ارتباط با پشتیبانی سرور وارد روبیکا شوید:
</p>


<br>


<a class="btn" href="https://rubika.ir/joinc/FEJDCJHH0QJTHNRNIEWSUFWASQXQGYJS">

پشتیبانی روبیکا

</a>


</div>


</section>




</main>




<footer>

© 2026 Fire Ball Land

<br>

Mr-Mamad dev

</footer>



</body>

</html>
