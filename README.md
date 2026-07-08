<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>e편한세상 부천 어반스퀘어</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Noto Sans KR',sans-serif;
}

body{
    color:#222;
    background:#fff;
}

.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.55)),
    url('main.jpg') center/cover no-repeat;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
}

.hero h1{
    font-size:48px;
    letter-spacing:-2px;
    margin-bottom:20px;
}

.hero p{
    font-size:22px;
    margin-bottom:40px;
}

.gold{
    color:#d4af37;
}

.btn{
    display:inline-block;
    padding:18px 45px;
    border-radius:40px;
    background:#d4af37;
    color:white;
    font-size:20px;
    text-decoration:none;
    font-weight:bold;
}


section{
    padding:80px 20px;
    text-align:center;
}


.title{
    font-size:36px;
    margin-bottom:40px;
}


.cards{
    display:flex;
    gap:20px;
    justify-content:center;
    flex-wrap:wrap;
}


.card{
    width:260px;
    padding:35px 20px;
    border-radius:20px;
    box-shadow:0 10px 30px rgba(0,0,0,.1);
}

.card h3{
    margin-bottom:15px;
    color:#b08a20;
}


.gallery{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:15px;
}

.gallery img{
    width:100%;
    height:280px;
    object-fit:cover;
    border-radius:20px;
}


.reserve{
    background:#111;
    color:white;
}

.reserve h2{
    font-size:35px;
    margin-bottom:20px;
}

.phone{
    font-size:35px;
    color:#d4af37;
    font-weight:bold;
}


.fixed{
    position:fixed;
    bottom:20px;
    left:20px;
    right:20px;
    background:#d4af37;
    color:white;
    text-align:center;
    padding:15px;
    border-radius:50px;
    font-size:20px;
    font-weight:bold;
}


@media(max-width:700px){

.hero h1{
    font-size:34px;
}

.hero p{
    font-size:18px;
}

.gallery{
    grid-template-columns:1fr;
}

}

</style>

</head>


<body>


<div class="hero">

<div>

<p>새로운 주거의 기준</p>

<h1>
<span class="gold">e편한세상</span><br>
부천 어반스퀘어
</h1>

<p>
부천의 중심에서 만나는<br>
프리미엄 라이프
</p>


<a class="btn" href="tel:01067501777">
모델하우스 방문예약
</a>


</div>

</div>



<section>

<h2 class="title">
