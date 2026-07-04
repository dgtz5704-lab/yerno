<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>🎂 ¡Feliz Cumpleaños de la Mejor Suegrita! 🎂</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;900&display=swap');
*{box-sizing:border-box;touch-action:manipulation;-webkit-tap-highlight-color:transparent;margin:0;padding:0;}
body{min-height:100vh;font-family:'Poppins',sans-serif;background:linear-gradient(-45deg,#ff9a9e,#fecfef,#a1c4fd,#c2e9fb,#ffc3a0);background-size:500% 500%;animation:gradientBG 18s ease infinite;display:flex;justify-content:center;align-items:center;color:#333;overflow-x:hidden;}
@keyframes gradientBG{0%{background-position:0% 50%;}50%{background-position:100% 50%;}100%{background-position:0% 50%;}}
.screen{position:absolute;top:0;left:0;width:100%;min-height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;padding:30px 15px;transition:opacity 0.8s ease,transform 0.8s ease;background:rgba(255,255,255,0.35);backdrop-filter:blur(12px);z-index:10;overflow-y:auto;}
.hidden{opacity:0;pointer-events:none;transform:scale(0.85) translateY(50px);z-index:-1;visibility:hidden;position:absolute;}
h1{color:#ff4785;font-size:clamp(1.8rem,7vw,3rem);font-weight:900;line-height:1.2;margin-bottom:12px;text-shadow:3px 3px 6px rgba(0,0,0,0.1);letter-spacing:-0.5px;}
h2{color:#4a4a4a;font-size:clamp(1.1rem,4.5vw,1.6rem);font-weight:600;margin-bottom:10px;}
p{font-size:clamp(0.95rem,3.8vw,1.2rem);color:#555;line-height:1.6;margin-bottom:20px;max-width:90%;}
.gift-container{position:relative;margin:25px 0;cursor:pointer;}
.gift-icon{font-size:110px;animation:pulseGift 1.2s infinite;user-select:none;filter:drop-shadow(0px 12px 15px rgba(0,0,0,0.15));transition:transform 0.3s;}
.gift-icon:hover{transform:scale(1.15);}
@keyframes pulseGift{0%{transform:scale(1) rotate(0deg);}30%{transform:scale(1.1) rotate(-5deg);}50%{transform:scale(1.05) rotate(5deg);}70%{transform:scale(1.1) rotate(-3deg);}100%{transform:scale(1) rotate(0deg);}}
.gift-glow{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);width:130px;height:130px;background:radial-gradient(circle,rgba(255,71,133,0.4) 0%,rgba(255,255,255,0) 70%);z-index:-1;animation:glowPulse 2s infinite;}
@keyframes glowPulse{0%{width:100px;height:100px;opacity:0.8;}50%{width:160px;height:160px;opacity:0;}100%{width:100px;height:100px;opacity:0;}}
.btn{padding:14px 28px;font-size:1.1rem;font-weight:700;border:none;border-radius:50px;cursor:pointer;transition:all 0.2s ease;box-shadow:0 8px 20px rgba(255,71,133,0.25);font-family:'Poppins',sans-serif;z-index:50;display:inline-flex;align-items:center;justify-content:center;gap:8px;}
.btn:active{transform:scale(0.93);box-shadow:0 4px 10px rgba(0,0,0,0.15);}
.botones-decision{display:flex;justify-content:center;align-items:center;gap:25px;width:100%;margin-top:25px;height:90px;position:relative;}
.btn-yes{background:linear-gradient(45deg,#1dd1a1,#10ac84);color:white;min-width:130px;}
.btn-no{background:linear-gradient(45deg,#ff6b6b,#ee5253);color:white;min-width:130px;transition:top 0.25s cubic-bezier(0.175,0.885,0.32,1.275),left 0.25s cubic-bezier(0.175,0.885,0.32,1.275);position:absolute;}
.grid-acciones{display:grid;grid-template-columns:1fr 1fr;gap:12px;width:100%;max-width:420px;margin:15px 0;}
.btn-action{background:rgba(255,255,255,0.85);color:#ff4785;border:2px solid #ff4785;font-size:0.95rem;padding:12px 10px;box-shadow:0 4px 10px rgba(0,0,0,0.05);border-radius:20px;margin:0;width:100%;}
.btn-action:hover{background:#ff4785;color:white;}
.celebration-box{background:rgba(255,255,255,0.88);padding:30px 18px;border-radius:35px;box-shadow:0 20px 45px rgba(0,0,0,0.15),inset 0 0 20px rgba(255,255,255,0.6);width:100%;max-width:480px;display:flex;flex-direction:column;align-items:center;margin:auto;border:1px solid rgba(255,255,255,0.5);}
.particle{position:fixed;font-size:28px;pointer-events:none;z-index:100;animation:fall linear forwards;}
@keyframes fall{0%{transform:translateY(-10vh) rotate(0deg) scale(0.8);opacity:1;}100%{transform:translateY(110vh) rotate(360deg) scale(1.4);opacity:0;}}
.music-player{background:linear-gradient(135deg,#ffeef2,#fff5f7);border-radius:20px;padding:12px 20px;width:100%;max-width:400px;display:flex;align-items:center;gap:15px;margin:15px 0;box-shadow:0 5px 15px rgba(0,0,0,0.04);border:1px solid #ffe1e6;}
.music-icon{font-size:24px;animation:bounceMusic 0.6s infinite alternate;}
@keyframes bounceMusic{0%{transform:translateY(0);}100%{transform:translateY(-5px);}}
.music-info{flex:1;text-align:left;}
.music-title{font-size:0.9rem;font-weight:700;color:#ff4785;}
.music-sub{font-size:0.75rem;color:#777;}
.music-bar{height:4px;background:#e0e0e0;border-radius:2px;width:100%;margin-top:6px;position:relative;overflow:hidden;}
.music-progress{height:100%;background:#ff4785;width:65%;animation:playProgress 20s linear infinite;}
@keyframes playProgress{0%{width:0%;}100%{width:100%;}}
.wishes-container{display:flex;justify-content:center;gap:12px;margin:15px 0;width:100%;}
.wish-bubble{width:60px;height:60px;border-radius:50%;background:white;display:flex;flex-direction:column;justify-content:center;align-items:center;font-size:1.4rem;cursor:pointer;box-shadow:0 6px 12px rgba(0,0,0,0.08);border:2px solid #a1c4fd;transition:all 0.3s;position:relative;}
.wish-bubble:hover{transform:scale(1.15);background:#fff0f3;border-color:#ff4785;}
.wish-label{font-size:0.65rem;font-weight:600;color:#666;margin-top:2px;}
#wishText{font-size:0.95rem;font-weight:700;color:#ff4785;min-height:24px;margin-top:5px;animation:fadeIn 0.5s;}
.card-slider{width:100%;background:rgba(255,255,255,0.6);border-radius:15px;padding:12px;margin:15px 0;text-align:center;box-shadow:0 4px 10px rgba(0,0,0,0.03);}
#sliderText{font-size:0.85rem;font-style:italic;color:#666;line-height:1.4;}
#cartaMensaje{display:none;background:#fff5f7;padding:22px;border-radius:20px;border:2px dashed #ff4785;margin-top:20px;font-size:0.95rem;color:#444;animation:fadeIn 0.8s forwards;text-align:left;box-shadow:0 10px 25px rgba(255,71,133,0.08);}
@keyframes fadeIn{from{opacity:0;transform:translateY(-15px);}to{opacity:1;transform:translateY(0);}}
.game-target{position:fixed;font-size:40px;cursor:pointer;z-index:200;user-select:none;animation:floatTarget 2s ease-out forwards;}
@keyframes floatTarget{0%{transform:translateY(100vh) scale(0.5);opacity:0;}15%{opacity:1;transform:translateY(80vh) scale(1.2);}90%{opacity:1;}100%{transform:translateY(-10vh) scale(0.8);opacity:0;}}
.score-board{position:absolute;top:15px;font-size:0.9rem;font-weight:700;background:rgba(255,255,255,0.8);padding:6px 15px;border-radius:20px;color:#ff4785;box-shadow:0 4px 10px rgba(0,0,0,0.05);}
</style>
</head>
<body>
<div id="pantalla1" class="screen">
<h1>¡Hola, Suegrita Linda! 👋</h1>
<h2>Hoy el calendario brilla más que nunca... ✨</h2>
<p>Porque es el cumpleaños de una mujer increíble, trabajadora y de gran corazón. He preparado una gran sorpresa para usted en este día.</p>
<div class="gift-container" onclick="irPantalla2()">
<div class="gift-glow"></div>
<div class="gift-icon">🎁</div>
</div>
<p style="font-size:0.85rem;color:#777;font-style:italic;">Toque el paquetito para deshacer el lazo...</p>
</div>
<div id="pantalla2" class="screen hidden">
<h1>¡Un pequeño control! 🕵️‍♀️</h1>
<p>Antes de abrir oficialmente su regalo, el sistema requiere validar una respuesta muy importante con total honestidad:</p>
<h2 style="color:#ff4785;font-weight:900;margin:25px 0;font-size:clamp(1.3rem,5vw,1.8rem);text-shadow:1px 1px 2px rgba(0,0,0,0.05);">¿Verdad que usted adora con todo el alma a su yerno favorito? 😇</h2>
<div class="botones-decision">
<button class="btn btn-yes" onclick="iniciarMinijuego()">¡SÍ, MUCHO! ❤️</button>
<button class="btn btn-no" id="btnNo" onmouseover="moverBotonNo(event)" ontouchstart="moverBotonNo(event)">No 🥱</button>
</div>
</div>
<div id="pantallaIntermedia" class="screen hidden" style="background:rgba(255,240,243,0.5);">
<div class="score-board">¡Atrape 3 corazones para abrir el regalo! 👉 <span id="scoreNum">0</span>/3</div>
<h1>¡Excelente respuesta! 💖</h1>
<p style="margin-top:40px;">¡Demuestre su amor atrapando los corazones flotantes que van saliendo en la pantalla!</p>
</div>
<div id="pantalla3" class="screen hidden" style="background:transparent;backdrop-filter:none;">
<div class="celebration-box">
<span style="font-size:2.5rem;animation:pulseGift 1s infinite alternate;">🎉🥳🎈</span>
<h1 style="margin-top:5px;">¡Feliz Cumpleaños!</h1>
<h2 id="pastel" style="font-size:3.2rem;margin:8px 0;filter:drop-shadow(0 5px 5px rgba(0,0,0,0.1));">🎂🕯️✨</h2>
<p style="margin-bottom:10px;font-size:0.95rem;">¡Sabía que no fallaría la prueba! Usted es la suegra más maravillosa del planeta entero. ¡Que comience el festejo!</p>
<div class="music-player">
<div class="music-icon">🎵</div>
<div class="music-info">
<div class="music-title">Las Mañanitas Festivas.mp3</div>
<div class="music-sub">Mariachi Virtual del Yerno Agradecido</div>
<div class="music-bar"><div class="music-progress"></div></div>
</div>
</div>
<h2 style="font-size:0.95rem;color:#888;font-weight:700;margin-top:5px;">🎁 Efectos mágicos de celebración:</h2>
<div class="grid-acciones">
<button class="btn btn-action" onclick="lanzarParticulas(['🌸','🌺','🌷','🌼','🌻'])">Lluvia Flores 🌸</button>
<button class="btn btn-action" onclick="lanzarParticulas(['🐻','🫂','💖','🥰','✨'])">Mil Abrazos 🐻</button>
<button class="btn btn-action" onclick="lanzarParticulas(['🎈','✨','🎊','🎉','🎨'])">Más Globos 🎈</button>
<button class="btn btn-action" onclick="lanzarParticulas(['🎆','🎇','💥','✨'])">Fuegos Artificiales 🎆</button>
<button class="btn btn-action" onclick="lanzarParticulas(['🎷','🎺','🎸','🎵','🎶'])">Mariachis 🎺</button>
<button class="btn btn-action" onclick="apagarVelitas()">Soplar Vela 💨</button>
</div>
<h2 style="font-size:0.95rem;color:#888;font-weight:700;margin-top:5px;">🔮 Pozo de los buenos deseos:</h2>
<div class="wishes-container">
<div class="wish-bubble" onclick="revelarDeseo('🍀 ¡Le deseo un año repleto de salud inquebrantable, energía y mucha vitalidad diaria!')">🩺<div class="wish-label">Salud</div></div>
<div class="wish-bubble" onclick="revelarDeseo('❤️ ¡Que su hogar siempre rebose de amor, sonrisas, abrazos y unión familiar!')">🏡<div class="wish-label">Amor</div></div>
<div class="wish-bubble" onclick="revelarDeseo('💰 ¡Que nunca falte la abundancia, el éxito y la prosperidad en todo lo que emprenda!')">✨<div class="wish-label">Suerte</div></div>
<div class="wish-bubble" onclick="revelarDeseo('✈️ ¡Este año toca descansar, pasear y disfrutar de nuevos viajes hermosos!')">🧳<div class="wish-label">Viajes</div></div>
</div>
<div id="wishText">Toque una burbuja de arriba...</div>
<div class="card-slider">
<div id="sliderText">"Una suegra como usted es un tesoro difícil de encontrar y una bendición del cielo."</div>
</div>
<button class="btn" style="background:linear-gradient(45deg,#ff4785,#ff6b6b);color:white;width:90%;margin-top:15px;font-weight:800;border-radius:25px;box-shadow:0 6px 15px rgba(255,71,133,0.3);" onclick="mostrarCarta()">💌 Leer Carta Especial Completa</button>
<div id="cartaMensaje">
<strong>Querida y Admirada Suegrita:</strong><br><br>
Hoy en su cumpleaños quiero aprovechar para darle las gracias de todo corazón. Gracias por su constante bondad, por sus sabios consejos, por su excelente sazón y, sobre todo, por abrirme las puertas de su hogar con tanto cariño desde el primer día.<br><br>
Le deseo un año maravilloso, lleno de paz mental, risas eternas y bendiciones gigantescas. Dios me la cuide siempre. ¡Disfrute al máximo su día de principio a fin porque se merece el mundo entero! ¡La queremos muchísimo! 🎉🎂❤️
</div>
</div>
</div>
<script>
let score=0;
const frases=["«Una suegra increíble merece un cumpleaños inolvidable.»","«Gracias por ser siempre un pilar tan alegre en la familia.»","«Hoy celebramos su vida y la gran alegría de tenerla cerca.»","«¡Que los cumplas muy feliz hoy y siempre!»"];
let currentFrase=0;
setInterval(()=>{currentFrase=(currentFrase+1)%frases.length;const t=document.getElementById('sliderText');if(t)t.innerText=frases[currentFrase];},4500);
function irPantalla2(){document.getElementById('pantalla1').classList.add('hidden');document.getElementById('pantalla2').classList.remove('hidden');posicionarNoInicial();}
function posicionarNoInicial(){const b=document.getElementById('btnNo');b.style.position='absolute';b.style.right='20px';b.style.top='20px';}
function moverBotonNo(e){if(e)e.preventDefault();const b=document.getElementById('btnNo');const maxX=window.innerWidth-b.clientWidth-30;const maxY=window.innerHeight-b.clientHeight-30;const randomX=Math.max(15,Math.random()*maxX);const randomY=Math.max(15,Math.random()*maxY);b.style.position='fixed';b.style.left=randomX+'px';b.style.top=randomY+'px';}
function iniciarMinijuego(){document.getElementById('pantalla2').classList.add('hidden');document.getElementById('pantallaIntermedia').classList.remove('hidden');spawnTarget();spawnTarget();}
function spawnTarget(){if(score>=3)return;const t=document.createElement('div');t.className='game-target';t.innerHTML=Math.random()>0.5?'❤️':'💖';t.style.left=Math.random()*80+10+'vw';t.style.animationDuration=Math.random()*1+1.5+'s';t.onclick=()=>{score++;document.getElementById('scoreNum').innerText=score;lanzarParticulas(['✨','🎉']);t.remove();if(score>=3){setTimeout(irPantalla3,400);}else{spawnTarget();}};document.body.appendChild(t);setTimeout(()=>{if(t.parentNode){t.remove();spawnTarget();}},2000);}
function irPantalla3(){document.getElementById('pantallaIntermedia').classList.add('hidden');document.getElementById('pantalla3').classList.remove('hidden');lanzarParticulas(['🎉','✨','🎈','🎊','🎁']);setTimeout(()=>lanzarParticulas(['🥳','💖','👏','🌈']),600);}
function lanzarParticulas(a){const c=35;for(let i=0;i<c;i++){let p=document.createElement("div");p.className="particle";p.innerHTML=a[Math.floor(Math.random()*a.length)];p.style.left=Math.random()*100+"vw";p.style.animationDuration=(Math.random()*2.2+1.8)+"s";p.style.animationDelay=(Math.random()*0.6)+"s";document.body.appendChild(p);setTimeout(()=>p.remove(),4000);}}
function apagarVelitas(){const p=document.getElementById('pastel');if(p.innerHTML.includes('🕯️')){p.innerHTML="🍰🎂✨";lanzarParticulas(['💨','🎉','👏','🥳','🧁']);}}
function revelarDeseo(txt){const d=document.getElementById('wishText');d.innerText=txt;lanzarParticulas(['⭐','✨','🔮']);}
function mostrarCarta(){const c=document.getElementById('cartaMensaje');if(c.style.display==='block'){c.style.display='none';}else{c.style.display='block';setTimeout(()=>{c.scrollIntoView({behavior:"smooth",block:"end"});},150);lanzarParticulas(['💌','💖','💝','🌸']);}}
</script>
</body>
</html>
