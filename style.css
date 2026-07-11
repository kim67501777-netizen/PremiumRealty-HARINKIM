const header = document.querySelector("header");


window.addEventListener("scroll",()=>{

if(window.scrollY>80){

header.style.background="rgba(255,255,255,.98)";
header.style.boxShadow="0 8px 30px rgba(0,0,0,.12)";

}else{

header.style.background="rgba(255,255,255,.96)";
header.style.boxShadow="0 3px 20px rgba(0,0,0,.08)";

}

});



// 화면 등장 애니메이션

const observer = new IntersectionObserver((entries)=>{

entries.forEach(entry=>{

if(entry.isIntersecting){

entry.target.classList.add("show");

}

});

},{
threshold:.15
});



document.querySelectorAll(
"section,.card,.brand-grid div,.info-grid div"
).forEach(el=>{

el.classList.add("hidden");

observer.observe(el);

});




// 메뉴 활성화

const menus=document.querySelectorAll("nav a");


menus.forEach(menu=>{

menu.addEventListener("click",()=>{

menus.forEach(a=>a.classList.remove("active"));

menu.classList.add("active");

});

});




// 이미지 확대 효과

document.querySelectorAll(".card img").forEach(img=>{


img.addEventListener("mouseenter",()=>{

img.style.transform="scale(1.08)";

});


img.addEventListener("mouseleave",()=>{

img.style.transform="scale(1)";

});


});




// TOP 버튼

const topBtn=document.createElement("div");


topBtn.innerHTML="↑";


topBtn.style.position="fixed";
topBtn.style.right="25px";
topBtn.style.bottom="95px";
topBtn.style.width="48px";
topBtn.style.height="48px";
topBtn.style.background="#c79d57";
topBtn.style.color="#fff";
topBtn.style.display="flex";
topBtn.style.justifyContent="center";
topBtn.style.alignItems="center";
topBtn.style.borderRadius="50%";
topBtn.style.cursor="pointer";
topBtn.style.fontSize="22px";
topBtn.style.zIndex="9999";
topBtn.style.opacity="0";
topBtn.style.transition=".3s";


document.body.appendChild(topBtn);



window.addEventListener("scroll",()=>{


if(window.scrollY>400){

topBtn.style.opacity="1";

}else{

topBtn.style.opacity="0";

}


});



topBtn.onclick=()=>{

window.scrollTo({

top:0,

behavior:"smooth"

});

};




// 애니메이션 CSS 추가

const style=document.createElement("style");


style.innerHTML=`

.hidden{

opacity:0;

transform:translateY(50px);

transition:.8s;

}


.show{

opacity:1;

transform:translateY(0);

}


nav a.active{

color:#c79d57;

font-weight:700;

}


.card img{

transition:.4s;

}

`;



document.head.appendChild(style);
