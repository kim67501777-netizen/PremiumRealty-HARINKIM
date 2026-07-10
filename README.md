<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>e편한세상 부천 어반스퀘어</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&display=swap" rel="stylesheet">

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>

<div class="logo">

e편한세상

</div>

<nav>

<a href="#brand">브랜드</a>
<a href="#location">입지</a>
<a href="#price">주변시세</a>
<a href="#contact">상담</a>

</nav>

</header>



<section class="hero">

<img src="images/garden.jpg" alt="e편한세상 부천 어반스퀘어">

<div class="overlay"></div>

<div class="hero-text">

<h3>대한민국 대표 브랜드</h3>

<h1>

e편한세상<br>

부천 어반스퀘어

</h1>

<p>

도심의 편리함과 자연의 여유를 모두 누리는<br>

새로운 프리미엄 라이프

</p>

<div class="hero-btn">

<a href="#contact" class="btn gold">

모델하우스 방문예약

</a>

<a href="tel:01067501777" class="btn black">

📞 전화상담

</a>

</div>

</div>

</section>



<section id="brand" class="section">

<div class="container">

<span>

BRAND PREMIUM

</span>

<h2>

대한민국 대표 브랜드<br>

e편한세상

</h2>

<p>

브랜드 가치와 차별화된 설계로
품격있는 라이프를 제공합니다.

</p>

<div class="card-wrap">

<div class="card">

<h3>브랜드</h3>

<p>

대한민국 대표 주거브랜드

</p>

</div>

<div class="card">

<h3>더블역세권</h3>

<p>

우수한 교통 프리미엄

</p>

</div>

<div class="card">

<h3>공원형 단지</h3>

<p>

쾌적한 녹지공간

</p>

</div>

</div>

</div>

</section>



<section id="location" class="image-section">

<div class="left">

<img src="images/location.jpg">

</div>

<div class="right">

<span>

LOCATION

</span>

<h2>

더블역세권의 가치

</h2>

<p>

생활과 교통을 모두 누리는
프리미엄 입지

</p>

</div>

</section>



<section class="image-section reverse">

<div class="left">

<img src="images/living.jpg">

</div>

<div class="right">

<span>

C2 HOUSE

</span>

<h2>

혁신 공간설계

</h2>

<p>

넓고 효율적인 공간구성과
수납특화 설계

</p>

</div>

</section>



<section class="image-section">

<div class="left">

<img src="images/smart.jpg">

</div>

<div class="right">

<span>

SMART SYSTEM

</span>

<h2>

스마트 라이프

</h2>

<p>

더 편리하고 안전한
스마트 시스템

</p>

</div>

</section>



<section id="price" class="section">

<div class="container">

<span>

MARKET PRICE

</span>

<h2>

주변 시세 비교

</h2>

<p>

분양가는 공개하지 않습니다.

</p>

<table>

<tr>

<th>주변 단지</th>

<th>최근 시세</th>

</tr>

<tr>

<td>힐스테이트 중동</td>

<td>최근 시세 기준</td>

</tr>

<tr>

<td>부천 아이파크</td>

<td>최근 시세 기준</td>

</tr>

<tr>

<td>일루미스테이트</td>

<td>최근 시세 기준</td>

</tr>

<tr>

<td>상동 스카이뷰자이</td>

<td>최근 시세 기준</td>

</tr>

</table>

</div>

</section>



<section id="contact" class="contact">

<h2>

모델하우스 방문예약

</h2>

<p>

지금 상담예약을 신청하세요.

</p>

<a href="tel:01067501777" class="reserve-btn">

📞 전화 상담하기

</a>

</section>



<div class="fixed-menu">

<a href="tel:01067501777">

📞 전화상담

</a>

<a href="#contact">

방문예약

</a>

</div>



<script src="script.js"></script>

</body>
</html>

/* ===========================
   e편한세상 부천 어반스퀘어
   Premium Style
=========================== */

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:'Noto Sans KR',sans-serif;
background:#0f0f10;
color:#fff;
line-height:1.7;
overflow-x:hidden;
}

a{
text-decoration:none;
}

img{
width:100%;
display:block;
}

/* ===========================
HEADER
=========================== */

header{
position:fixed;
top:0;
left:0;
width:100%;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
background:rgba(0,0,0,.45);
backdrop-filter:blur(12px);
z-index:999;
}

.logo{
font-size:28px;
font-weight:900;
color:#d4af37;
letter-spacing:2px;
}

nav{
display:flex;
gap:30px;
}

nav a{
color:#fff;
font-weight:500;
transition:.3s;
}

nav a:hover{
color:#d4af37;
}

/* ===========================
HERO
=========================== */

.hero{
height:100vh;
position:relative;
overflow:hidden;
}

.hero img{
width:100%;
height:100%;
object-fit:cover;
animation:zoom 12s ease-in-out infinite alternate;
}

.overlay{
position:absolute;
inset:0;
background:linear-gradient(rgba(0,0,0,.25),rgba(0,0,0,.7));
}

.hero-text{
position:absolute;
top:50%;
left:50%;
transform:translate(-50%,-50%);
text-align:center;
width:90%;
z-index:5;
}

.hero h3{
color:#d4af37;
font-size:20px;
letter-spacing:4px;
margin-bottom:15px;
}

.hero h1{
font-size:68px;
font-weight:900;
line-height:1.2;
margin-bottom:25px;
}

.hero p{
font-size:22px;
margin-bottom:45px;
}

.hero-btn{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
}

.btn{
padding:18px 40px;
border-radius:50px;
font-size:18px;
font-weight:700;
transition:.35s;
}

.gold{
background:#d4af37;
color:#111;
}

.gold:hover{
transform:translateY(-5px);
box-shadow:0 10px 30px rgba(212,175,55,.45);
}

.black{
background:#111;
color:#fff;
border:1px solid #d4af37;
}

.black:hover{
background:#d4af37;
color:#111;
}

/* ===========================
SECTION
=========================== */

.section{
padding:120px 8%;
}

.container{
max-width:1200px;
margin:auto;
}

.section span{
color:#d4af37;
font-weight:700;
letter-spacing:3px;
}

.section h2{
font-size:46px;
margin:20px 0;
}

.section p{
font-size:18px;
color:#ddd;
}

.card-wrap{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:30px;
margin-top:60px;
}

.card{
background:#1b1b1d;
padding:40px;
border-radius:20px;
transition:.4s;
border:1px solid rgba(255,255,255,.08);
}

.card:hover{
transform:translateY(-10px);
border-color:#d4af37;
box-shadow:0 20px 40px rgba(0,0,0,.45);
}

.card h3{
color:#d4af37;
margin-bottom:15px;
}

/* ===========================
IMAGE SECTION
=========================== */

.image-section{
display:grid;
grid-template-columns:1fr 1fr;
align-items:center;
}

.image-section .left img{
height:650px;
object-fit:cover;
}

.image-section .right{
padding:70px;
}

.image-section span{
color:#d4af37;
font-weight:700;
}

.image-section h2{
font-size:46px;
margin:25px 0;
}

.image-section p{
color:#ddd;
font-size:18px;
}

.reverse .left{
order:2;
}

.reverse .right{
order:1;
}

/* ===========================
MARKET PRICE
=========================== */

table{
width:100%;
border-collapse:collapse;
margin-top:50px;
background:#181818;
border-radius:20px;
overflow:hidden;
}

th{
background:#d4af37;
color:#111;
padding:20px;
font-size:18px;
}

td{
padding:20px;
text-align:center;
border-bottom:1px solid #2d2d2d;
color:#ddd;
}

tr:hover{
background:#222;
}

/* ===========================
CONTACT
=========================== */

.contact{
padding:120px 8%;
text-align:center;
background:#121212;
}

.contact h2{
font-size:48px;
margin-bottom:20px;
}

.contact p{
font-size:20px;
color:#ccc;
margin-bottom:45px;
}

.reserve-btn{
display:inline-block;
padding:22px 55px;
background:#d4af37;
color:#111;
font-weight:700;
font-size:20px;
border-radius:60px;
transition:.35s;
}

.reserve-btn:hover{
transform:translateY(-6px);
box-shadow:0 15px 35px rgba(212,175,55,.45);
}

/* ===========================
BOTTOM FIXED
=========================== */

.fixed-menu{
position:fixed;
left:0;
bottom:0;
width:100%;
display:flex;
z-index:9999;
}

.fixed-menu a{
flex:1;
text-align:center;
padding:18px;
font-size:18px;
font-weight:700;
}

.fixed-menu a:first-child{
background:#111;
color:#fff;
}

.fixed-menu a:last-child{
background:#d4af37;
color:#111;
}

/* ===========================
FOOTER
=========================== */

footer{
background:#080808;
padding:70px 20px 110px;
text-align:center;
}

footer h3{
font-size:30px;
margin-bottom:15px;
color:#d4af37;
}

footer p{
color:#999;
margin:8px 0;
}

/* ===========================
ANIMATION
=========================== */

@keyframes zoom{

0%{
transform:scale(1);
}

100%{
transform:scale(1.12);
}

}

@keyframes fadeUp{

0%{
opacity:0;
transform:translateY(60px);
}

100%{
opacity:1;
transform:translateY(0);
}

}

.section,
.image-section,
.contact{

animation:fadeUp .9s ease both

/* ===========================
e편한세상 부천 어반스퀘어
Premium Script
=========================== */

// 부드러운 메뉴 이동
document.querySelectorAll('a[href^="#"]').forEach(link => {

    link.addEventListener("click", function(e){

        const target = document.querySelector(this.getAttribute("href"));

        if(target){

            e.preventDefault();

            target.scrollIntoView({

                behavior:"smooth"

            });

        }

    });

});



// 헤더 스크롤 효과
const header = document.querySelector("header");

window.addEventListener("scroll",()=>{

    if(window.scrollY>80){

        header.style.background="rgba(0,0,0,.88)";
        header.style.padding="15px 8%";
        header.style.boxShadow="0 10px 30px rgba(0,0,0,.4)";

    }else{

        header.style.background="rgba(0,0,0,.45)";
        header.style.padding="20px 8%";
        header.style.boxShadow="none";

    }

});



// 스크롤 등장 애니메이션
const observer = new IntersectionObserver((entries)=>{

    entries.forEach(entry=>{

        if(entry.isIntersecting){

            entry.target.classList.add("show");

        }

    });

},{
    threshold:0.15
});

document.querySelectorAll(".section,.image-section,.contact,.card")
.forEach(el=>{

    el.classList.add("hidden");

    observer.observe(el);

});



// 맨 위로 버튼
const topBtn=document.createElement("button");

topBtn.innerHTML="↑";

topBtn.className="topBtn";

document.body.appendChild(topBtn);

window.addEventListener("scroll",()=>{

    if(window.scrollY>500){

        topBtn.classList.add("active");

    }else{

        topBtn.classList.remove("active");

    }

});

topBtn.onclick=()=>{

    window.scrollTo({

        top:0,

        behavior:"smooth"

    });

};



// 현재 메뉴 활성화
const sections=document.querySelectorAll("section");

const navLinks=document.querySelectorAll("nav a");

window.addEventListener("scroll",()=>{

    let current="";

    sections.forEach(sec=>{

        const top=sec.offsetTop-120;

        const height=sec.offsetHeight;

        if(scrollY>=top){

            current=sec.getAttribute("id");

        }

    });

    navLinks.forEach(link=>{

        link.classList.remove("active");

        if(link.getAttribute("href")==="#"+current){

            link.classList.add("active");

        }

    });

});
