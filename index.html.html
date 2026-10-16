<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Rutas y coberturas</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@1,800&family=Barlow:wght@400;600&display=swap">
<style>
:root{--bg:#e8eef7;--card:#fff;--tx:#101a33;--mut:#55627f;--ac:#2f55ff;--chip:#fff;--line:#cdd7e8;--on:#fff;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0e1430;--card:#18204a;--tx:#eef2ff;--mut:#9aa8d0;--ac:#7d97ff;--chip:#1c2554;--line:#2b3670;--on:#0e1430}}
:root[data-theme="dark"]{--bg:#0e1430;--card:#18204a;--tx:#eef2ff;--mut:#9aa8d0;--ac:#7d97ff;--chip:#1c2554;--line:#2b3670;--on:#0e1430}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--tx);font:16px/1.5 Barlow,system-ui,sans-serif;-webkit-tap-highlight-color:transparent}
main{max-width:520px;margin:0 auto;padding-bottom:28px}
header{padding:22px 18px 6px}
h1{font:italic 800 clamp(44px,14vw,64px)/.9 'Barlow Condensed','Arial Narrow',Impact,sans-serif;margin:0;letter-spacing:-.5px}
header p{margin:10px 0 0;color:var(--mut);max-width:34ch}
.bar{display:flex;gap:10px;align-items:center;padding:14px 18px 0}
.tabs{display:flex;flex:1;background:var(--chip);border:1px solid var(--line);border-radius:999px;padding:4px}
.tabs button{flex:1;border:0;background:none;color:var(--mut);font:600 15px Barlow,sans-serif;padding:9px 0;border-radius:999px;cursor:pointer;transition:.25s}
.tabs button.on{background:var(--ac);color:var(--on)}
#v3{border:1px solid var(--line);background:var(--chip);color:var(--tx);font:600 14px Barlow,sans-serif;padding:10px 14px;border-radius:999px;cursor:pointer}
#v3[aria-pressed=true]{border-color:var(--ac);color:var(--ac)}
.stage{perspective:760px;perspective-origin:50% 0;padding:0 14px;margin-top:6px}
.pitch{max-width:400px;margin:0 auto;transform:rotateX(34deg);transform-origin:50% 100%;transition:transform .8s cubic-bezier(.2,.8,.2,1);border-radius:12px;box-shadow:0 2px 0 #0b3d1d,0 5px 0 #0b3d1d,0 8px 0 #082f16,0 24px 30px rgba(0,0,0,.4)}
.pitch.flat{transform:none}
svg{display:block;width:100%;height:auto;border-radius:12px}
.tr{stroke-dasharray:1;stroke-dashoffset:1;animation:dr 2.6s linear infinite}
@keyframes dr{0%{stroke-dashoffset:1}80%,100%{stroke-dashoffset:0}}
.z{animation:pop .5s both}
@keyframes pop{from{opacity:0}to{opacity:1}}
.pulse{animation:pl 1.4s ease-out infinite;transform-box:fill-box;transform-origin:center}
@keyframes pl{from{transform:scale(1);opacity:.8}to{transform:scale(2.4);opacity:0}}
@media(prefers-reduced-motion:reduce){.tr{animation:none;stroke-dashoffset:0}.pulse,.z{animation:none}}
.chips{display:flex;gap:8px;overflow-x:auto;padding:16px 18px 8px;scroll-snap-type:x proximity;scrollbar-width:none}
.chips::-webkit-scrollbar{display:none}
.chip{flex:none;scroll-snap-align:center;min-width:68px;border:1px solid var(--line);background:var(--chip);color:var(--tx);border-radius:16px;padding:8px 12px;cursor:pointer;text-align:center;transition:.2s}
.chip b{display:block;font:italic 800 28px/1 'Barlow Condensed','Arial Narrow',Impact,sans-serif}
.chip span{font-size:13px;color:var(--mut)}
.chip.on{background:var(--ac);border-color:var(--ac);color:var(--on);transform:translateY(-3px)}
.chip.on span{color:var(--on)}
.cv{padding:12px 14px}
.cv b{font-size:19px}
.card{margin:8px 18px 0;background:var(--card);border:1px solid var(--line);border-radius:20px;padding:18px}
.card h2{margin:0 0 4px;font:italic 800 36px/1 'Barlow Condensed','Arial Narrow',Impact,sans-serif}
.card h2 i{color:var(--ac);margin-right:8px}
.sub{color:var(--mut);margin:0 0 10px;font-weight:600}
.card p{margin:8px 0}
.tip{border-left:4px solid #ffc400;padding-left:12px}
.ws{display:flex;flex-wrap:wrap;gap:8px;align-items:center;margin-top:12px}
.ws button{border:1px solid var(--ac);background:none;color:var(--ac);font:600 14px Barlow,sans-serif;border-radius:999px;padding:6px 12px;cursor:pointer}
.lg{display:flex;flex-wrap:wrap;gap:6px 14px;font-size:13px;color:var(--mut);margin-top:14px}
.lg i{display:inline-block;width:11px;height:11px;border-radius:50%;margin-right:5px;vertical-align:-1px}
.note{margin:14px 22px 0;font-size:13px;color:var(--mut)}
</style>
</head>
<body>
<main>
<header>
<h1>Rutas y<br>coberturas</h1>
<p>Toca una ruta o una cobertura y mírala moverse sobre el campo.</p>
</header>
<div class="bar">
<div class="tabs"><button id="tr" class="on">Rutas</button><button id="tc">Coberturas</button></div>
<button id="v3" aria-pressed="true">Vista 3D</button>
</div>
<section class="stage"><div class="pitch" id="pitch"><svg id="f" viewBox="0 0 300 360" role="img" aria-label="Campo de fútbol americano"></svg></div></section>
<div class="chips" id="chips"></div>
<article class="card" id="card"></article>
<p class="note">Árbol de rutas estándar del 1 al 9. Cada equipo puede numerarlas o llamarlas un poco distinto. Las debilidades de cada cobertura son orientativas.</p>
</main>
<script>
const R=[
['Flat','1-3 yd','M225 290V284Q238 276 288 276','Salida corta y paralela a la línea de scrimmage, hacia la banda.','La válvula de escape del QB: pase rápido y seguro. Muy útil cuando la defensa se repliega hacia atrás.'],
['Slant','3-5 yd','M225 290V280L180 244','Unos pasos rectos y un corte de 45 grados hacia dentro.','Es de timing: el QB lanza antes de que gires. Brilla contra defensa al hombre.'],
['Comeback','15 yd','M225 290V200L238 218','Subes rápido, frenas en seco y vuelves hacia la banda.','Obliga al esquina a retroceder y te deja un hueco para recibir. La pelota va lejos del safety.'],
['Curl','12-15 yd','M225 290V200L216 220','Subes, frenas y te giras hacia el QB, buscando un hueco.','Te sientas en el espacio entre defensas. Es clásica contra zona.'],
['Out','10 yd','M225 290V230H286','Subes y cortas en 90 grados hacia la banda.','Pase rápido y fuerte. Si falla, la pelota sale fuera. Ojo con el defensa que lee al QB.'],
['Dig','15 yd','M225 290V200H150','Subes y cortas en 90 grados hacia dentro, cruzando el campo.','También se llama In. Funciona mejor contra hombre y se hace pesada contra zona.'],
['Corner','12+ yd','M225 290V220L284 150','Subes, fintas hacia dentro y sales en diagonal hacia la esquina.','Gana el espacio entre safety y esquina. Es una ruta de profundidad.'],
['Post','12+ yd','M225 290V220L168 130','Subes y cortas en diagonal hacia los palos, hacia el centro.','Ruta larga hacia el centro del campo. También abre huecos para tus compañeros.'],
['Go','20+ yd','M225 290V60','Línea recta a toda velocidad por la banda, sin cortes.','La ruta de la gloria: velocidad pura y pase largo. Si el defensa no te iguala, es touchdown.']
];
const mx=[[25,262,25,290],[80,262,80,290],[205,262,205,290],[270,262,270,290]];
const C=[
{n:'Cover 0',t:'Hombre puro, sin ayuda atrás',d:'Cada defensa marca a un receptor y no hay safety libre en el fondo. Suele ir con blitz: el QB tiene muy poco tiempo, pero quien gana su duelo se queda con campo libre.',w:[9,2],m:mx,z:[],b:[[133,266],[167,266]]},
{n:'Cover 1',t:'Hombre con un safety libre',d:'Los defensas marcan al hombre y un safety se queda solo en el centro del fondo para ayudar. Es muy agresiva, pero los cruces y los bloqueos a los defensas la rompen.',w:[6,2],m:mx,z:[[150,112,64,68,'Safety libre','d']],b:[]},
{n:'Cover 2',t:'Dos mitades profundas',d:'Dos safeties se reparten el fondo en mitades y cinco defensas cubren la zona corta. Los esquinas aguantan al receptor en la banda. El centro profundo y las esquinas del campo quedan débiles.',w:[7,8],m:[],z:[[75,115,72,66,'½','d'],[225,115,72,66,'½','d'],[30,238,30,22,'flat','u'],[270,238,30,22,'flat','u'],[100,228,27,22,'hook','u'],[150,225,24,22,'hook','u'],[200,228,27,22,'hook','u']],b:[]},
{n:'Cover 3',t:'Tres tercios profundos',d:'Los dos esquinas y el safety libre cubren el fondo en tres tercios y cuatro defensas vigilan la zona corta. Es muy sólida contra el pase largo, pero cede las bandas y la media distancia.',w:[1,4],m:[],z:[[50,112,48,66,'⅓','d'],[150,112,48,66,'⅓','d'],[250,112,48,66,'⅓','d'],[40,238,30,22,'flat','u'],[260,238,30,22,'flat','u'],[105,228,34,22,'hook','u'],[195,228,34,22,'hook','u']],b:[]},
{n:'Cover 4',t:'Cuatro cuartos profundos',d:'Cuatro defensas se reparten el fondo en cuartos y tres cubren lo corto. Muy fuerte contra rutas largas, y los safeties ayudan contra la carrera. Cede espacio en la zona corta.',w:[5,6],m:[],z:[[38,112,37,66,'¼','d'],[113,112,37,66,'¼','d'],[188,112,37,66,'¼','d'],[263,112,37,66,'¼','d'],[50,238,32,22,'flat','u'],[150,228,40,22,'hook','u'],[250,238,32,22,'flat','u']],b:[]}
];
let mode='r',I={r:3,c:2},d3=true;
const $=id=>document.getElementById(id);
const dot=(x,y,g,r=7,o=1)=>`<circle cx="${x}" cy="${y}" r="${r}" fill="url(#${g})" stroke="rgba(0,0,0,.4)" stroke-width="1" opacity="${o}"/>`;
let bg='<defs><radialGradient id="gb" cx=".35" cy=".3"><stop offset="0" stop-color="#9db8ff"/><stop offset="1" stop-color="#2346d6"/></radialGradient><radialGradient id="gr" cx=".35" cy=".3"><stop offset="0" stop-color="#ffa5a5"/><stop offset="1" stop-color="#d11f2e"/></radialGradient><radialGradient id="go" cx=".35" cy=".3"><stop offset="0" stop-color="#fff3b0"/><stop offset="1" stop-color="#ffb800"/></radialGradient><marker id="ar" markerWidth="6" markerHeight="6" refX="4" refY="3" orient="auto"><path d="M0 0L6 3L0 6z" fill="#ffd23f"/></marker><marker id="ar2" markerWidth="6" markerHeight="6" refX="4" refY="3" orient="auto"><path d="M0 0L6 3L0 6z" fill="#ff5a5a"/></marker></defs>';
for(let k=0;k<13;k++)bg+=`<rect x="0" y="${-10+30*k}" width="300" height="30" fill="${k%2?'#23893f':'#1d7a37'}"/>`;
for(let i=0;i<12;i++)bg+=`<path d="M0 ${20+30*i}H300" stroke="#fff" stroke-opacity=".6" stroke-width="1.4"/>`;
bg+='<path d="M105 0V360M195 0V360" stroke="#fff" stroke-opacity=".35" stroke-width="3" stroke-dasharray="1.5 4.5"/><rect x="2" y="2" width="296" height="356" fill="none" stroke="#fff" stroke-width="2.5"/>';
for(let k=1;k<=9;k++)bg+=`<text x="8" y="${287-30*k}" font-size="9" fill="#fff" fill-opacity=".8" font-family="Barlow,sans-serif" font-weight="600">${5*k}${k==1?' yd':''}</text>`;
function off(rx){let s='';[118,134,150,166,182].forEach(x=>s+=`<rect x="${x-6}" y="284" width="12" height="12" rx="3" fill="#dbe3f2" stroke="rgba(0,0,0,.4)"/>`);
rx.forEach(([x,o])=>s+=dot(x,290,'gb',7,o));return s+dot(150,318,'gb',8)+dot(150,342,'gb',7)}
function routeSVG(p){return bg+off([[25,.5],[75,.5]])+
`<path d="${p[2]}" fill="none" stroke="#fff" stroke-opacity=".5" stroke-width="2" stroke-dasharray="3 4" marker-end="url(#ar)"/>
<path class="tr" pathLength="1" d="${p[2]}" fill="none" stroke="#ffd23f" stroke-width="4" stroke-linejoin="round"/>
<circle class="pulse" cx="225" cy="290" r="8" fill="#ffd23f"/>`+dot(225,290,'go',8)+
`<circle r="6" fill="#fff" stroke="#ffb800" stroke-width="3"><animateMotion dur="2.6s" repeatCount="indefinite" path="${p[2]}" keyPoints="0;1;1" keyTimes="0;.8;1" calcMode="linear"/></circle>`}
function covSVG(c){let s=bg,df='';
c.z.forEach(([x,y,rx,ry,l,t])=>{const col=t=='d'?'#ffb020':'#38bdf8';
s+=`<g class="z"><ellipse cx="${x}" cy="${y}" rx="${rx}" ry="${ry}" fill="${col}" fill-opacity=".24" stroke="${col}" stroke-width="2" stroke-dasharray="5 3"/><text x="${x}" y="${y-ry*.2}" text-anchor="middle" font-size="${l.length>2?10:16}" font-weight="700" fill="#fff" font-family="Barlow,sans-serif">${l}</text></g>`;
df+=dot(x,y+ry*.55,'gr',6.5)});
c.m.forEach(([a,b,x,y])=>{s+=`<path class="z" d="M${a} ${b}L${x} ${y-9}" stroke="#ff5a5a" stroke-width="2.2" stroke-dasharray="3 3"/>`;df+=dot(a,b,'gr')});
c.b.forEach(([x,y])=>{s+=`<path class="z" d="M${x} ${y}L${x<150?146:154} 306" stroke="#ff5a5a" stroke-width="2.5" marker-end="url(#ar2)"/>`;df+=dot(x,y,'gr')});
[125,145,165,185].forEach(x=>df+=dot(x,274,'gr',6));
return s+off([[25,1],[80,1],[205,1],[270,1]])+df}
function render(){
const r=mode=='r',i=I[mode],L=r?R:C;
$('tr').classList.toggle('on',r);$('tc').classList.toggle('on',!r);
$('f').innerHTML=r?routeSVG(R[i]):covSVG(C[i]);
$('chips').innerHTML=L.map((x,j)=>r?`<button class="chip${j==i?' on':''}" data-i="${j}"><b>${j+1}</b><span>${x[0]}</span></button>`:`<button class="chip cv${j==i?' on':''}" data-i="${j}"><b>${x.n}</b></button>`).join('');
const on=$('chips').querySelector('.on');if(on)on.scrollIntoView({inline:'center',block:'nearest',behavior:'smooth'});
if(r){const x=R[i];$('card').innerHTML=`<h2><i>${i+1}</i>${x[0]}</h2><p class="sub">Profundidad: ${x[1]}</p><p>${x[3]}</p><p class="tip">${x[4]}</p>`}
else{const x=C[i];$('card').innerHTML=`<h2>${x.n}</h2><p class="sub">${x.t}</p><p>${x.d}</p><div class="ws"><span>Se puede atacar con:</span>${x.w.map(n=>`<button data-r="${n}">${n} ${R[n-1][0]}</button>`).join('')}</div><div class="lg"><span><i style="background:#ffb020"></i>zona profunda</span><span><i style="background:#38bdf8"></i>zona corta</span><span><i style="background:#ff5a5a"></i>hombre o blitz</span></div>`}}
$('chips').onclick=e=>{const b=e.target.closest('.chip');if(b){I[mode]=+b.dataset.i;render()}};
$('card').onclick=e=>{const b=e.target.closest('[data-r]');if(b){mode='r';I.r=b.dataset.r-1;render();window.scrollTo({top:0,behavior:'smooth'})}};
$('tr').onclick=()=>{mode='r';render()};$('tc').onclick=()=>{mode='c';render()};
$('v3').onclick=()=>{d3=!d3;$('pitch').classList.toggle('flat',!d3);$('v3').setAttribute('aria-pressed',d3)};
render();
</script>
</body>
</html>
