[index.html](https://github.com/user-attachments/files/35027827/index.html)
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>NuriNail — beauty studio</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Jost:wght@300;400&family=Manrope:wght@400;500;600;800&display=swap" rel="stylesheet">
<style>
:root{--ink:#241d19;--mut:#7b6e66;--bg:#fbf4ee;--ln:rgba(36,29,25,.14);--ac:#e8672a}
*{box-sizing:border-box;margin:0}html{scroll-behavior:smooth}
body{font:400 16px/1.6 Manrope,system-ui,sans-serif;color:var(--ink);background:var(--bg);-webkit-font-smoothing:antialiased}
a{color:inherit;text-decoration:none}
header{position:fixed;inset:0 0 auto;z-index:30;display:grid;grid-template-columns:1fr auto 1fr;align-items:center;padding:18px 3vw;transition:background .4s}
header.sc{background:rgba(251,244,238,.8);-webkit-backdrop-filter:blur(14px);backdrop-filter:blur(14px)}
.logo{display:flex;align-items:center;gap:10px;font-weight:800;letter-spacing:.04em;font-size:18px}.logo svg{height:26px;color:var(--ac)}
.m{display:flex;gap:2.4vw;font-size:13px}
.m a{position:relative;padding:4px 0;color:var(--mut);transition:color .3s}
.m a.on,.m a:hover{color:var(--ink)}
.m a.on::after{content:"";position:absolute;left:0;right:0;bottom:-2px;height:1px;background:currentColor}
.bk{justify-self:end;position:relative}
.pill{font:500 13px Manrope,sans-serif;padding:9px 16px;border:1px solid var(--ln);border-radius:99px;background:rgba(255,255,255,.5);cursor:pointer;color:inherit;transition:background .3s}
.pill:hover{background:#fff}
.dd{position:absolute;right:0;top:120%;min-width:220px;padding:8px;border-radius:14px;background:#fff;box-shadow:0 18px 50px rgba(40,40,80,.16);opacity:0;visibility:hidden;transform:translateY(-6px);transition:.25s}
.bk.o .dd{opacity:1;visibility:visible;transform:none}
.dd a{display:block;padding:10px 12px;border-radius:8px;font-size:14px}.dd a:hover{background:var(--bg)}
a:focus-visible,button:focus-visible{outline:2px solid var(--ac);outline-offset:3px}
.hero{height:230vh;position:relative}
.hs{position:sticky;top:0;height:100vh;overflow:hidden;display:grid;place-items:end center;background:linear-gradient(120deg,var(--a,#f6e4d6),var(--b,#fbf1ea));transform:scale(var(--s,1));border-radius:var(--r,0)}
.pt{position:relative;height:min(92vh,120vw);aspect-ratio:400/520}
.pt>div{position:absolute;inset:0}.pt svg{width:100%;height:100%;display:block}
.nx{display:none}
.hl{position:absolute;top:0;bottom:0;left:54%;width:1px;background:rgba(255,255,255,.75)}
.ov{position:absolute;inset:0;background:rgba(60,34,22,.62);opacity:var(--o,0);pointer-events:none}
.tg{position:absolute;inset:0;display:grid;align-content:center;justify-items:center;text-align:center;color:#fff;opacity:var(--o,0);pointer-events:none;padding:0 6vw}
.tg small{font:400 11px Jost,sans-serif;letter-spacing:.3em;text-transform:uppercase;margin-bottom:22px}
.tg h2{font:300 clamp(32px,6.4vw,92px)/1.06 Jost,sans-serif;letter-spacing:.06em;text-transform:uppercase}
.tg p{margin-top:22px;font-size:14px}
section{padding:14vh 8vw}
.in{max-width:1200px;margin:0 auto}
h2.t{font:500 clamp(30px,4vw,56px)/1.05 Manrope,sans-serif;letter-spacing:-.02em}
.lead{font-size:clamp(17px,1.7vw,22px);font-weight:500;line-height:1.35;margin:22px 0 14px;max-width:26ch}
.mu{color:var(--mut);font-size:14px;max-width:44ch}
.lk{display:inline-block;margin-top:26px;font-size:13px;border-bottom:1px solid currentColor;padding-bottom:2px}
.two{display:grid;grid-template-columns:1fr 1.15fr;gap:6vw;align-items:center}
.img{border-radius:6px;overflow:hidden;aspect-ratio:4/3;background:#ddd}.img svg{width:100%;height:100%;display:block}
#studio{background:linear-gradient(180deg,var(--bg),#fffaf6)}
.hd{display:flex;justify-content:space-between;align-items:end;gap:6vw;margin-bottom:6vh}
.g3{display:grid;grid-template-columns:repeat(3,1fr);gap:2.2vw 2.2vw}
.card .img{aspect-ratio:4/5}.card h3{font:600 15px Manrope,system-ui,sans-serif;margin-top:14px}.card p{font-size:13px;color:var(--mut)}
.card .img svg{transition:transform 1.2s}.card:hover .img svg{transform:scale(1.05)}
.sv{display:grid;grid-template-columns:1fr 2fr;gap:6vw}
.tabs{display:flex;gap:8px;margin-top:28px;flex-wrap:wrap}
.tabs button{font:500 12px Manrope,system-ui,sans-serif;padding:8px 14px;border:0;border-radius:99px;background:rgba(28,29,36,.07);color:var(--ink);cursor:pointer}
.tabs button.on{background:var(--ac);color:#fff}
.grp{margin-bottom:6vh}.grp h3{font:500 18px Manrope,system-ui,sans-serif;padding-bottom:12px;border-bottom:1px solid var(--ln);margin-bottom:6px}
.row{display:grid;grid-template-columns:1fr auto;gap:20px;padding:16px 0;align-items:baseline}
.row b{font-weight:600;font-size:15px}.row span{display:block;font-size:13px;color:var(--mut)}.row i{font-style:normal;font-size:12px;color:var(--mut)}.row em{font-style:normal;font-weight:600;text-align:right}
.bkc{position:relative;display:grid;grid-template-columns:1fr 1fr;align-items:end;min-height:72vh;padding:0 8vw;background:linear-gradient(180deg,#f6dccb,#fbeee4);overflow:hidden}
.bkc .tx{align-self:center;padding:10vh 0}.bkc .pf{height:72vh;justify-self:end;aspect-ratio:400/520;align-self:end}.bkc svg{width:100%;height:100%;display:block}
.info dl{margin:26px 0;border-top:1px solid var(--ln)}.info dl div{display:flex;justify-content:space-between;padding:12px 0;border-bottom:1px solid var(--ln);font-size:14px}.info dt{color:var(--mut)}
footer{padding:10vh 8vw 6vh;background:#f1e2d7}
footer .in{display:grid;grid-template-columns:1fr auto;gap:6vw;align-items:end}
.wm{font:800 clamp(44px,10vw,150px)/.85 Manrope,system-ui,sans-serif;letter-spacing:-.04em}
.fl{display:grid;gap:8px;font-size:14px;color:var(--mut)}.fl a:hover{color:var(--ink)}
.cp{margin-top:6vh;font-size:12px;color:var(--mut);max-width:1200px;margin-left:auto;margin-right:auto}
.fab{position:fixed;right:22px;bottom:22px;z-index:30;width:42px;height:42px;border-radius:50%;background:var(--ac);display:grid;place-items:center}
.fab svg{width:18px;fill:none;stroke:#fff;stroke-width:1.8}
.dot{position:fixed;left:-4px;top:-4px;width:8px;height:8px;border-radius:50%;background:var(--ink);z-index:50;pointer-events:none}
@media(hover:none){.dot{display:none}}
@media(max-width:820px){.m{display:none}header{grid-template-columns:1fr auto}.two,.sv,.bkc,footer .in{grid-template-columns:1fr}.g3{grid-template-columns:1fr 1fr}.bkc .pf{height:52vh;justify-self:center}.row{gap:12px}}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<i class="dot"></i>
<header>
  <a class="logo" href="#top"><svg viewBox="0 0 80 64" fill="none" stroke="currentColor" stroke-width="3.2" stroke-linejoin="round" stroke-linecap="round"><rect x="4" y="4" width="42" height="56" rx="21"/><rect x="34" y="4" width="42" height="56" rx="21"/><path d="M17 46V18l16 28V18M47 46V18l16 28V18"/></svg>NuriNail</a>
  <nav class="m"><a href="#top">Главная</a><a href="#services">Услуги</a><a href="#work">Работы</a><a href="#contact">Контакты</a></nav>
  <div class="bk"><button class="pill" id="bkb" aria-expanded="false">Записаться ⌄</button>
    <div class="dd"><a href="#book">Записаться онлайн</a><a href="#services">Посмотреть цены</a><a href="#contact">Адреса и часы работы</a></div></div>
</header>

<div class="hero" id="top"><div class="hs">
  <div class="pt"><div class="cur"></div><div class="nx"></div><i class="hl"></i></div>
  <div class="ov"></div>
  <div class="tg"><small>Beauty studio · два адреса</small><h2>Каждый образ —<br>новая история.</h2><p>Волосы, ногти, брови и ресницы — под вас.</p></div>
</div></div>

<section id="studio"><div class="in two">
  <div><h2 class="t">Студия</h2><p class="lead">Beauty-студия полного цикла в двух адресах.</p>
  <p class="mu">Парикмахерские услуги, маникюр и педикюр, брови и ресницы, эпиляция и перманентный макияж. Работаем каждый день с 10:00 до 22:00.</p><a class="lk" href="#work">Смотреть работы →</a></div>
  <div class="img" id="room1"></div>
</div></section>

<section id="work"><div class="in">
  <div class="hd"><h2 class="t">Избранные работы</h2><p class="mu">Цвет и форма, подобранные под черты, текстуру волос и образ жизни.</p></div>
  <div class="g3" id="wk"></div>
</div></section>

<!-- МАСТЕРА (скрыто). Вернуть: раскомментировать блок и строку $('#ar') в скрипте, добавить 'artists' в список observe, пункты <a href="#artists">Мастера</a> в меню/футере и «Выбрать мастера» в списке записи.
<section id="artists"><div class="in">
  <div class="hd"><h2 class="t">Мастера</h2><p class="mu">Каждый мастер ведёт собственную клиентуру — выберите того, чей подход вам ближе.</p></div>
  <div class="g3" id="ar"></div>
</div></section>
-->

<section id="services"><div class="in sv">
  <div><h2 class="t">Услуги и цены</h2><p class="mu" style="margin-top:18px">Итоговая стоимость зависит от длины и густоты волос и уточняется на консультации.</p><div class="tabs" id="tabs"></div></div>
  <div id="sl"></div>
</div></section>

<div class="bkc" id="book"><div class="tx"><h2 class="t">Запись<br>на приём</h2><p class="mu" style="margin-top:18px">Выберите услугу и удобное время — мы подтвердим запись в течение дня.</p><a class="pill" style="display:inline-block;margin-top:26px" href="https://yandex.ru/maps/org/nurinail_beauty_studio/67833603444/" target="_blank" rel="noopener">Записаться</a></div><div class="pf" id="pf"></div></div>

<section id="contact"><div class="in two info">
  <div class="img" id="room2" style="aspect-ratio:1"></div>
  <div><h2 class="t">Как нас найти</h2><p class="lead" style="font-size:15px;margin:18px 0 0">NuriNail beauty studio<br>Москва</p>
  <dl><div><dt>Коммунарка</dt><dd>ул. Александры Монаховой, 84, корп. 2</dd></div><div><dt>Южнобутовская</dt><dd>ул. Южнобутовская, 123</dd></div><div><dt>Ежедневно</dt><dd>10:00–22:00</dd></div></dl>
  <a class="pill" href="https://yandex.ru/maps/org/nurinail_beauty_studio/67833603444/" target="_blank" rel="noopener">Построить маршрут →</a></div>
</div></section>

<footer><div class="in"><div class="wm">NuriNail</div><nav class="fl"><a href="#studio">Студия</a><a href="#services">Услуги</a><a href="#contact">Контакты</a></nav></div>
<p class="cp">© NuriNail. Все права защищены.</p></footer>
<a class="fab" href="#book" aria-label="Записаться"><svg viewBox="0 0 24 24"><path d="M4 5h16v10H9l-5 4z"/></svg></a>

<script>
const $=s=>document.querySelector(s),$$=s=>[...document.querySelectorAll(s)],reduce=matchMedia('(prefers-reduced-motion:reduce)').matches;
/* ---------- иллюстрации (замените на фото: достаточно подставить <img> в те же контейнеры) ---------- */
const HC={A:['#cfccd6','#eceaf1'],B:['#c9c8d2','#e8e6ee'],C:['#a4492c','#cc7048']};
window.IMGS={};/* фото героя: IMGS={A:"a.jpg",B:"b.jpg",C:"c.jpg"}, кадры 400×520 */
function prof(v){if(IMGS[v])return`<img src="${IMGS[v]}" alt="" style="width:100%;height:100%;object-fit:cover">`;const[h,l]=HC[v],S=`stroke="${l}" stroke-width="2" fill="none" opacity=".75"`;
const hair={A:`<path d="M232 104C292 98 326 150 318 232 312 300 332 384 356 480H246C256 410 238 330 262 252L242 192C216 150 190 142 176 170 174 122 200 106 232 104Z" fill="${h}"/><path d="M240 120C290 130 300 220 292 300M262 130C312 170 296 300 312 410M232 118C270 140 280 200 270 280" ${S}/>`,
B:`<path d="M250 284C264 302 302 306 318 290L316 322C292 336 262 326 250 304Z" fill="#b4623d"/><path d="M232 104C298 98 328 150 322 214L318 288C300 304 262 300 250 284L254 232 242 192C216 150 190 142 176 170 174 122 200 106 232 104Z" fill="${h}"/><path d="M244 120C296 130 306 210 300 270M266 132C312 170 308 240 296 280" ${S}/>`,
C:`<circle cx="314" cy="198" r="36" fill="${h}"/><path d="M232 104C288 98 316 140 306 204L264 216 242 192C216 150 190 142 176 170 174 122 200 106 232 104Z" fill="${h}"/><path d="M290 176c20-8 40 6 36 26M284 206c22 10 44-4 42-24M244 120c36 6 52 38 46 70" ${S}/>`}[v];
return `<svg viewBox="0 0 400 520"><path d="M92 520C100 420 170 350 215 338H262C330 352 392 420 398 520Z" fill="#dfae93"/><path d="M205 240 215 345H262L255 236Z" fill="#d4a086"/><path d="M225 118C195 122 176 145 172 170L170 186 156 207 168 213 165 224 170 232 168 246C178 262 198 268 215 266L300 250V160C298 130 265 114 225 118Z" fill="#e6b9a0"/><ellipse cx="258" cy="206" rx="9" ry="14" fill="#d9a98f"/><path d="M165 224c4 2 9 2 14 0-3 5-10 6-14 0Z" fill="#b5604f"/><path d="M186 176q8-4 15 0" stroke="#6b4a3e" fill="none" stroke-width="2"/><path d="M118 520c10-60 60-110 100-140l30 140Z" fill="#f6efe9" opacity=".9"/>${hair}</svg>`}
function fp(bg,sk,hc,st,cl){const c=(x,y,r)=>`<circle cx="${x}" cy="${y}" r="${r}"/>`;let b='',f='';
if(st=='bob'){b='<path d="M56 112C52 48 148 48 144 112L148 172C122 186 78 186 52 172Z"/>';f='<path d="M66 100C86 66 124 68 136 100C110 84 90 88 66 106Z"/>'}
if(st=='curl')b=[[100,66,30],[68,82,24],[132,82,24],[58,110,22],[142,110,22],[80,50,22],[120,50,22]].map(a=>c(...a)).join('');
if(st=='shag')b='<path d="M56 120L50 92 60 62 84 46 112 44 140 58 152 90 148 134 136 152 128 116 100 96 72 116 62 152Z"/>';
if(st=='long')b='<path d="M54 112C50 48 150 48 146 112L156 232H44Z"/>';
if(st=='crop')f='<path d="M66 98C64 58 136 58 134 98C122 80 78 80 66 98Z"/><path d="M70 118C74 146 126 146 130 118C126 134 74 134 70 118Z" opacity=".55"/>';
return `<svg viewBox="0 0 200 250" preserveAspectRatio="xMidYMid slice"><rect width="200" height="250" fill="${bg}"/><g fill="${hc}">${b}</g><path d="M30 250C34 192 70 170 100 170s66 22 70 80Z" fill="${cl}"/><rect x="88" y="136" width="24" height="38" fill="${sk}"/><ellipse cx="100" cy="106" rx="33" ry="41" fill="${sk}"/><g fill="${hc}">${f}</g><circle cx="88" cy="106" r="2" fill="#4a3a35"/><circle cx="112" cy="106" r="2" fill="#4a3a35"/><path d="M92 128q8 5 16 0" stroke="#a4584c" stroke-width="2.4" fill="none" stroke-linecap="round"/></svg>`}
function room(){return '<svg viewBox="0 0 400 300" preserveAspectRatio="xMidYMid slice"><rect width="400" height="300" fill="#eceae6"/><rect y="215" width="400" height="85" fill="#d9d4cb"/><rect x="40" y="40" width="90" height="140" fill="#dfeaf0"/><path d="M40 40h90M85 40v140M40 110h90" stroke="#c9d3d8" stroke-width="2"/>'+[170,240,310].map(x=>`<path d="M${x} 190V80a24 24 0 0 1 48 0v110Z" fill="#f7f6f3" stroke="#b9ab94" stroke-width="3"/>`).join('')+'<rect x="150" y="196" width="230" height="30" fill="#d7b992"/>'+[190,262,330].map(x=>`<rect x="${x}" y="226" width="34" height="26" rx="10" fill="#f4efe7"/><rect x="${x+15}" y="252" width="4" height="22" fill="#8c8c8c"/>`).join('')+'</svg>'}
/* ---------- контент ---------- */
$('#room1').innerHTML=room();$('#room2').innerHTML=room();$('#pf').innerHTML=prof('C');
const card=(a,t,d)=>`<a class="card" href="#book"><div class="img">${a}</div><h3>${t}</h3><p>${d}</p></a>`;
$('#wk').innerHTML=[['#e8d4bd','#e9c3a5','#b8845a','bob','#f6f1ea','Медовый боб','Стрижка · тёплый русый'],['#dcdde9','#8a5a44','#3a2a24','curl','#f6f4f2','Объёмные кудри','Форма · уход за кудрями'],['#d9dbea','#efcfbd','#a79bd0','shag','#f4f4f7','Лавандовый шэг','Креативный цвет'],['#e3e5ee','#efd0bf','#e8e6ee','long','#eeeeee','Платиновое сияние','Блонд · тонирование'],['#ead9cf','#f0cbb5','#a9552f','bob','#f4efe9','Медная амброзия','Цвет · глянец'],['#d8dce6','#ecc9b6','#bdbdc6','bob','#f2f2f5','Пепельный боб','Стрижка · холодный тон']].map(a=>card(fp(...a.slice(0,5)),a[5],a[6])).join('');
/* $('#ar').innerHTML=[['#e6d7c8','#eac7ad','#2c2420','bob','#232323','Мария Эллисон','Креативный директор','Работает с формой и цветом'],['#d9d9ec','#efcdb6','#c9a678','crop','#c7c0a8','Тео Маркетти','Старший колорист','Блонд и сложные переходы'],['#dad6ee','#8a5a44','#2b211d','curl','#b9a6dc','Инес Окафор','Специалист по текстуре','Кудри и натуральные волосы']].map(a=>card(fp(...a.slice(0,5)),a[5],a[6]+' · '+a[7])).join(''); */
const SV=[['Парикмахер','Парикмахер',`Стрижка модельная, короткие|2000
Стрижка модельная, средние|2300
Стрижка модельная, длинные|2500
Стрижка модельная, очень длинные|3000
Стрижка мужская|1300
Стрижка чёлки|1000
Стрижка детская|1200
Мытьё и сушка|1500
Укладка, средние|1500
Укладка, длинные|2000
Укладка, очень длинные|2500`],['Окрашивание Davines','Окрашивание',`Окрашивание в один тон, средние|6000
Окрашивание в один тон, длинные|8000
Окрашивание в один тон, очень длинные|10000
Окрашивание корней|4000
Частичное окрашивание, средние|10000
Частичное окрашивание, длинные|12000
Частичное окрашивание, очень длинные|14000
Сложное окрашивание, средние|13000
Сложное окрашивание, длинные|16000
Сложное окрашивание, очень длинные|20000
Выход из тёмного, кислотная смывка, средние|12000
Выход из тёмного, кислотная смывка, длинные|14000
Выход из тёмного, кислотная смывка, очень длинные|16000`],['Ботокс, кератин и уходы','Уход',`Ботокс / кератин / микс составов, ниже плеч|6000
Ботокс / кератин / микс составов, до лопаток|7000
Ботокс / кератин / микс составов, до середины спины|7500
Ботокс / кератин / микс составов, до талии|8000
Ботокс / кератин / микс составов, ниже талии|8500
Ботокс / кератин / микс составов, до поясницы|9000
Ботокс / кератин / микс составов, до копчика|10000
Реконструкция «Кератиновое чудо» Davines|7500
Спа-уход Oi Davines|4000
Экспресс-уход Naturaltech Davines|3500
Скрабирование кожи головы|1000`],['Маникюр','Маникюр',`Маникюр «комплекс» с покрытием гель-лак|2900
Комбинированный / аппаратный маникюр|1400
Мужской маникюр|1800
Детский маникюр (до 12 лет)|700
Покрытие цветным лаком|500
Снятие гель-лака|500
Наращивание «всё включено» (до третьей длины)|5000
Арочное наращивание «всё включено»|6000
Коррекция наращённых ногтей|3900
Укрепление гелем|800
Парафинотерапия|500
Дизайн: френч (все ногти)|700
Дизайн: кошачий глаз, втирка (все ногти)|600`],['Педикюр','Педикюр',`Smart педикюр «комплекс»|3800
Smart педикюр без покрытия|3000
Экспресс-педикюр с покрытием (только пальчики)|2700
Smart обработка стоп|1600
Обработка пальчиков|1800
Мужской Smart педикюр|3800`],['Брови и ресницы','Брови и ресницы',`Архитектура бровей|2000
Коррекция бровей воск / пинцет|1000
Окрашивание бровей краска / хна|1100
Долговременная укладка бровей «комплекс»|3000
Ламинирование ресниц|3000
Наращивание ресниц, классика|3000
Наращивание ресниц, 2D|3300
Наращивание ресниц, 3D|3500
Наращивание ресниц, голливудский объём|4200`],['Эпиляция','Эпиляция',`Лицо (1 зона)|400
Подмышечные впадины|1000
Бикини классическое|1300
Бикини глубокое|2300
Руки полностью|1500
Голени|1500
Бедра|2000
Спина|2000`],['Перманентный макияж','Перманент',`Брови|12000
Губы|12000
Межресничка|9000
Коррекция (не более 2 месяцев)|5000
Рефреш (наша работа)|8000
Перекрытие чужой работы|2000`]];
const tb=['Все',...SV.map(g=>g[1])];let cur='Все';
function rs(){$('#tabs').innerHTML=tb.map(t=>`<button class="${t==cur?'on':''}">${t}</button>`).join('');
$('#sl').innerHTML=SV.filter(g=>cur=='Все'||g[1]==cur).map(g=>`<div class="grp"><h3>${g[0]}</h3>${g[2].split('\n').map(l=>{const[n,p]=l.split('|');return`<div class="row"><b>${n}</b><em>${(+p).toLocaleString('ru-RU')} ₽</em></div>`}).join('')}</div>`).join('');
$$('#tabs button').forEach(b=>b.onclick=()=>{cur=b.textContent;rs()})}
rs();
/* ---------- герой: смена причёсок «разрезом» ---------- */
const TN={A:['#f6e4d6','#fbf1ea'],B:['#f3d9c6','#f8e8dc'],C:['#efd3c8','#f7e6e0']},ORD=['A','B','C'],hs=$('.hs'),cu=$('.cur'),nx=$('.nx');
let vi=0,busy=0;cu.innerHTML=prof('A');hs.style.setProperty('--a',TN.A[0]);hs.style.setProperty('--b',TN.A[1]);
const lc=(a,b,t)=>{const p=h=>[1,3,5].map(i=>parseInt(h.substr(i,2),16)),A=p(a),B=p(b);return'rgb('+A.map((v,i)=>Math.round(v+(B[i]-v)*t))+')'};
function next(){if(busy||reduce)return;busy=1;const fr=ORD[vi],to=ORD[vi=(vi+1)%3];nx.innerHTML=prof(to);nx.style.display='block';const t0=performance.now();
(function f(t){const k=Math.min(1,(t-t0)/1500),e=k<.5?2*k*k:1-Math.pow(-2*k+2,2)/2,a0=-100,a1=a0+360*e,pts=['54% 58%'];
for(let i=0;i<=40;i++){const a=(a0+(a1-a0)*i/40)*Math.PI/180;pts.push((54+Math.cos(a)*200)+'% '+(58+Math.sin(a)*200)+'%')}
nx.style.clipPath='polygon('+pts.join(',')+')';hs.style.setProperty('--a',lc(TN[fr][0],TN[to][0],e));hs.style.setProperty('--b',lc(TN[fr][1],TN[to][1],e));
if(k<1)requestAnimationFrame(f);else{cu.innerHTML=prof(to);nx.style.display='none';busy=0}})(t0)}
setInterval(next,3800);
/* ---------- скролл, меню, курсор ---------- */
function sc(){const h=$('.hero').getBoundingClientRect(),p=Math.min(1,Math.max(0,-h.top/(h.height-innerHeight))),o=Math.min(1,Math.max(0,(p-.3)/.3));
hs.style.setProperty('--o',o);hs.style.setProperty('--s',1-.06*o);hs.style.setProperty('--r',28*o+'px');$('header').classList.toggle('sc',scrollY>40)}
addEventListener('scroll',sc,{passive:true});sc();
const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting)$$('.m a').forEach(a=>a.classList.toggle('on',a.getAttribute('href')=='#'+e.target.id||(e.target.id=='studio'&&a.getAttribute('href')=='#top')))}),{rootMargin:'-45% 0px -50% 0px'});
['top','studio','work','services','book','contact'].forEach(i=>io.observe($('#'+i)));
$$('.m a')[0].classList.add('on');
const bk=$('.bk');$('#bkb').onclick=e=>{e.stopPropagation();const o=bk.classList.toggle('o');e.currentTarget.setAttribute('aria-expanded',o)};
addEventListener('click',()=>{bk.classList.remove('o');$('#bkb').setAttribute('aria-expanded',false)});addEventListener('keydown',e=>{if(e.key=='Escape')bk.classList.remove('o')});
const dot=$('.dot');let mx=0,my=0,dx=0,dy=0;addEventListener('pointermove',e=>{mx=e.clientX;my=e.clientY},{passive:true});
(function m(){dx+=(mx-dx)*.18;dy+=(my-dy)*.18;dot.style.transform=`translate(${dx}px,${dy}px)`;requestAnimationFrame(m)})();
</script>
</body>
</html>
