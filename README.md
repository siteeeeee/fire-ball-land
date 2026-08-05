<html lang="fa">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Nova Land</title>


<style>

body{

background:#800000;
color:white;
font-family:tahoma;
text-align:center;
margin:0;

}



.box{

width:85%;
max-width:900px;
margin:50px auto;
background:#1f2937;
padding:40px;
border-radius:20px;
box-shadow:0 0 30px #ff4d4d;

}



h1{

color:#ff4d4d;
font-size:60px;

}



h2{

color:#00ff88;

}



p{

font-size:22px;
line-height:40px;

}



.ip{

color:#00ff88;
font-size:30px;
margin-top:30px;

}



#status{

margin-top:25px;
font-size:25px;

}



button{

margin-top:30px;
padding:15px 40px;
font-size:22px;
background:#00bfff;
color:white;
border:none;
border-radius:12px;
cursor:pointer;

}



button:hover{

background:#008ecc;

}



/* رنک ها */

.ranks{

margin-top:60px;

}



.rank-box{

display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;

}



.rank{

background:#111827;
width:180px;
padding:20px;
border-radius:15px;

}



/* تیم مدیریت */

.staff{

margin-top:60px;

}



.staff-box{

display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;

}



.person{

background:#111827;
width:200px;
padding:20px;
border-radius:15px;

}



.footer{

margin-top:50px;
color:#aaa;

}


</style>


</head>



<body>


<div class="box">



<h1>Fire ball land</h1>


<h2>Minecraft Bedrock Server</h2>


<p>
به سرور ماینکرف بدراک فایر بال لند خوش امدید
</p>


<p>
ایونت های جذاب رنک های متنوع و محیط دوستانه
</p>



<div class="ip">

IP : 185.26.33.12
port : 19132

</div>




<div id="status">

⏳ در حال بررسی وضعیت سرور...

</div>




<button onclick="copyIP()">

"🎮کپی کردن ایپی "; 

</button>



<p id="msg"></p>




<!-- رنک ها -->


<div class="ranks">


<h2>🏆 رنک های فروش </h2>


<div class="rank-box">



<div class="rank">

<h3 style="color:#ff0000">
Phantom
</h3>

<p>
  پرواز fly
  شنل cape
  کیت kit
  250کا پول سرور
  20 عدد بیمه
</p>

</div>




<div class="rank">

<h3 style="color:#404040">
spanser
</h3>

<p>
رنک اسپانسر با قابلیت های نسبتا خوب
</p>

</div>




<div class="rank">

<h3 style="color:#00e5ff">
LEGEND
</h3>

<p>
رنک ویژه
</p>

</div>




<div class="rank">

<h3 style="color:#00ff88">
VIP
</h3>

<p>
امکانات ویژه
</p>

</div>



</div>

</div>






<!-- تیم مدیریت -->


<div class="staff">


<h2>👥 تیم مدیریت Fire ball land</h2>



<div class="staff-box">



<div class="person">

<h3 style="color:red">

👑 OWNER

</h3>

<p>
NazaninMLV
</p>

</div>




<div class="person">

<h3 style="color:orange">

🛡 co-owmer

</h3>

<p>
نداریم
</p>

</div>




<div class="person">

<h3 style="color:#00ff88">

🧰 Maneger

</h3>

<p>
نداریم
</p>

</div>




<div class="person">

<h3 style="color:#00e5ff">

⭐ dev

</h3>

<p>
zuri58
</p>

</div>



</div>


</div>






<div class="footer">

© 2026 Fire ball land

</div>




</div>






<script>



function copyIP(){

navigator.clipboard.writeText("185.26.33.12");

document.getElementById("msg").innerHTML="✅ IP کپی شد";

}





async function checkServer(){


let status=document.getElementById("status");


try{


let response =
await fetch("https://api.mcsrvstat.us/bedrock/185.26.33.12");

let data =
await response.json();



if(data.online){


status.innerHTML=
"🟢 سرور آنلاین است | بازیکن آنلاین: "
+ data.players.online;


status.style.color="#00ff88";


}

else{


status.innerHTML=
"🔴 سرور آفلاین است";

status.style.color="#ff3333";


}



}

catch{


status.innerHTML=
"🟢 سرور روشن است."; 


}


}



checkServer();



</script>



</body>

</html> 
