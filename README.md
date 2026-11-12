```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mahesh Kumar & Hema | Engagement Invitation</title>
<meta name="theme-color" content="#f7efe6">
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:Georgia,"Times New Roman",serif;
  color:#332822;background:#f8f2ea;
  overflow-x:hidden;
}
:root{
 --wine:#7d2638;--gold:#b58b4b;--cream:#fffaf4;
 --green:#52634b;--soft:#ead6c8;
}
.page{min-height:100vh;position:relative}
.decor{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.blob{position:absolute;border-radius:50%;filter:blur(2px);opacity:.55}
.b1{width:360px;height:360px;left:-170px;top:90px;background:#efd8d2}
.b2{width:430px;height:430px;right:-220px;top:360px;background:#e7dcc6}
.b3{width:330px;height:330px;left:-180px;bottom:80px;background:#dce3d2}
.b4{width:400px;height:400px;right:-190px;bottom:-40px;background:#f0d7d1}
header,main,footer{position:relative;z-index:1}
.hero{
 min-height:100vh;display:flex;align-items:center;justify-content:center;
 padding:28px 18px;
 background:
   linear-gradient(135deg,rgba(255,250,244,.94),rgba(249,239,229,.9)),
   radial-gradient(circle at 20% 20%,#ead5cd 0 7%,transparent 8%),
   radial-gradient(circle at 80% 70%,#e3d8bf 0 8%,transparent 9%);
}
.hero-card{
 width:min(900px,100%);min-height:88vh;border:1px solid #d8c39f;
 border-radius:34px;background:rgba(255,252,247,.78);
 box-shadow:0 30px 90px rgba(78,52,35,.15);
 display:flex;align-items:center;justify-content:center;text-align:center;
 padding:55px 25px;position:relative;overflow:hidden;
 backdrop-filter:blur(10px);
}
.hero-card:before,.hero-card:after{
 content:"";position:absolute;width:170px;height:170px;border:1px solid #d8c39f;
 border-radius:50%;opacity:.55;
}
.hero-card:before{left:-95px;top:-80px}
.hero-card:after{right:-95px;bottom:-80px}
.inner{max-width:730px}
.cross{font-size:58px;color:var(--gold);margin-bottom:10px}
.eyebrow{font-size:14px;letter-spacing:4px;text-transform:uppercase;color:#80663f}
h1{font-size:clamp(43px,8vw,82px);line-height:1.05;color:var(--wine);font-style:italic;margin:18px 0}
.subtitle{font-size:clamp(18px,3vw,26px);color:#58463b}
.divider{display:flex;align-items:center;gap:15px;justify-content:center;margin:24px 0;color:var(--gold)}
.divider span{width:100px;height:1px;background:var(--gold)}
.rings{font-size:36px;color:var(--gold)}
.hero-date{font-size:19px;letter-spacing:1px}
.btn{
 display:inline-block;margin-top:30px;padding:13px 27px;border-radius:999px;
 background:var(--wine);color:white;text-decoration:none;letter-spacing:1px;
 box-shadow:0 10px 25px rgba(125,38,56,.22)
}
section{padding:85px 18px}
.container{width:min(1050px,100%);margin:auto}
.label{text-align:center;color:var(--gold);font-size:13px;letter-spacing:3px;text-transform:uppercase}
.title{text-align:center;font-size:clamp(30px,5vw,48px);color:var(--wine);margin:8px 0 35px}
.intro{
 max-width:760px;margin:auto;text-align:center;font-size:20px;line-height:1.9;
 color:#5d4a3d;
}
.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:40px}
.card{
 background:rgba(255,255,255,.82);border:1px solid #e2d1bd;border-radius:24px;
 padding:32px 22px;text-align:center;box-shadow:0 15px 45px rgba(70,45,28,.08)
}
.card .icon{font-size:31px;color:var(--gold);margin-bottom:12px}
.card h3{font-size:14px;letter-spacing:2px;text-transform:uppercase;color:var(--green);margin-bottom:10px}
.card p{font-size:17px;line-height:1.65}
.names{
 background:linear-gradient(180deg,#fffaf4,#f3e6dc);
}
.family{display:grid;grid-template-columns:1fr 1fr;gap:22px;margin-top:35px}
.family-card{padding:35px 24px;text-align:center;border:1px solid #e0cdb8;border-radius:25px;background:rgba(255,255,255,.7)}
.family-card h3{color:var(--wine);font-size:21px;margin-bottom:12px}
.family-card p{font-size:17px;line-height:1.7}
.count-wrap{text-align:center}
.countdown{display:grid;grid-template-columns:repeat(4,1fr);gap:13px;max-width:680px;margin:30px auto}
.time{background:white;border:1px solid #e2d1bd;border-radius:20px;padding:20px 8px}
.time strong{display:block;font-size:34px;color:var(--wine)}
.time small{letter-spacing:2px;text-transform:uppercase;color:#8b765e}
.venue{
 background:#3f4b3a;color:#fffaf2;text-align:center;
}
.venue .label{color:#d9b979}.venue .title{color:#fffaf2}
.venue-box{max-width:720px;margin:auto;font-size:20px;line-height:1.8}
.map{
 display:inline-block;margin-top:25px;padding:12px 24px;border:1px solid #d9b979;
 color:#fffaf2;text-decoration:none;border-radius:999px
}
footer{background:#2f2622;color:#f8eee2;text-align:center;padding:50px 20px}
footer .cross{font-size:34px}
footer p{margin-top:8px;color:#d9c9ba}
@media(max-width:720px){
 .cards,.family{grid-template-columns:1fr}
 .countdown{grid-template-columns:repeat(2,1fr)}
 .hero-card{min-height:92vh;border-radius:24px}
 section{padding:65px 16px}
}
</style>
</head>
<body>
<div class="decor">
 <div class="blob b1"></div><div class="blob b2"></div><div class="blob b3"></div><div class="blob b4"></div>
</div>

<header class="hero">
 <div class="hero-card">
  <div class="inner">
   <div class="cross">✝</div>
   <div class="eyebrow">With the Blessings of God</div>
   <h1>Mahesh Kumar <span style="color:#b58b4b">&amp;</span> Hema</h1>
   <div class="subtitle">Engagement Ceremony</div>
   <div class="divider"><span></span><div class="rings">♡</div><span></span></div>
   <div class="hero-date">Thursday • 19 November 2026 • 10:00 AM</div>
   <a class="btn" href="#details">Open Invitation</a>
  </div>
 </div>
</header>

<main>
<section id="details">
 <div class="container">
  <div class="label">A joyful beginning</div>
  <h2 class="title">The Celebration</h2>
  <p class="intro">With grateful hearts and the blessings of God, we invite you to join us for the engagement ceremony of <strong>Mahesh Kumar &amp; Hema</strong>.</p>
  <div class="cards">
   <div class="card"><div class="icon">♡</div><h3>Date</h3><p>19th November 2026<br>Thursday</p></div>
   <div class="card"><div class="icon">◷</div><h3>Time</h3><p>10:00 AM</p></div>
   <div class="card"><div class="icon">⌖</div><h3>Venue</h3><p>Near Auxilium School,<br>Chopparamannagudem / Gavaravaram,<br>Koyyalagudem Mandal, Andhra Pradesh</p></div>
  </div>
 </div>
</section>

<section class="names">
 <div class="container">
  <div class="label">Our families</div>
  <h2 class="title">Together With Our Families</h2>
  <div class="family">
   <div class="family-card">
    <h3>Mallimoggala Mahesh Kumar</h3>
    <p>S/o Mallimoggala Suvarna Raj (Srinivasa Rao)<br>&amp; Vana Dhrekshewalli (Kanakadurga)</p>
   </div>
   <div class="family-card">
    <h3>Kadavakollu Hema</h3>
    <p>D/o Kadavakollu Satyanarayana &amp; Nirmala</p>
   </div>
  </div>
 </div>
</section>

<section>
 <div class="container count-wrap">
  <div class="label">The special day is approaching</div>
  <h2 class="title">Counting the Moments</h2>
  <div class="countdown">
   <div class="time"><strong id="days">0</strong><small>Days</small></div>
   <div class="time"><strong id="hours">0</strong><small>Hours</small></div>
   <div class="time"><strong id="mins">0</strong><small>Minutes</small></div>
   <div class="time"><strong id="secs">0</strong><small>Seconds</small></div>
  </div>
 </div>
</section>

<section class="venue">
 <div class="container">
  <div class="label">Join us</div>
  <h2 class="title">We Would Love Your Presence</h2>
  <div class="venue-box">
   <p>Near Auxilium School,<br>Chopparamannagudem / Gavaravaram,<br>Koyyalagudem Mandal, Andhra Pradesh</p>
   <a class="map" target="_blank" rel="noopener"
   href="https://www.google.com/maps/search/?api=1&query=Auxilium+School+Chopparamannagudem+Gavaravaram+Koyyalagudem+Andhra+Pradesh">Open in Google Maps</a>
  </div>
 </div>
</section>
</main>

<footer>
 <div class="cross">✝</div>
 <h2>Mahesh Kumar &amp; Hema</h2>
 <p>Your presence will be a blessing to us</p>
</footer>

<script>
const target=new Date("2026-11-19T10:00:00+05:30").getTime();
function update(){
 const d=Math.max(0,target-Date.now());
 document.getElementById("days").textContent=Math.floor(d/86400000);
 document.getElementById("hours").textContent=Math.floor(d/3600000)%24;
 document.getElementById("mins").textContent=Math.floor(d/60000)%60;
 document.getElementById("secs").textContent=Math.floor(d/1000)%60;
}
update();setInterval(update,1000);
</script>
</body>
</html>
``````html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mahesh Kumar & Hema | Engagement Invitation</title>
<meta name="theme-color" content="#f7efe6">
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:Georgia,"Times New Roman",serif;
  color:#332822;background:#f8f2ea;
  overflow-x:hidden;
}
:root{
 --wine:#7d2638;--gold:#b58b4b;--cream:#fffaf4;
 --green:#52634b;--soft:#ead6c8;
}
.page{min-height:100vh;position:relative}
.decor{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.blob{position:absolute;border-radius:50%;filter:blur(2px);opacity:.55}
.b1{width:360px;height:360px;left:-170px;top:90px;background:#efd8d2}
.b2{width:430px;height:430px;right:-220px;top:360px;background:#e7dcc6}
.b3{width:330px;height:330px;left:-180px;bottom:80px;background:#dce3d2}
.b4{width:400px;height:400px;right:-190px;bottom:-40px;background:#f0d7d1}
header,main,footer{position:relative;z-index:1}
.hero{
 min-height:100vh;display:flex;align-items:center;justify-content:center;
 padding:28px 18px;
 background:
   linear-gradient(135deg,rgba(255,250,244,.94),rgba(249,239,229,.9)),
   radial-gradient(circle at 20% 20%,#ead5cd 0 7%,transparent 8%),
   radial-gradient(circle at 80% 70%,#e3d8bf 0 8%,transparent 9%);
}
.hero-card{
 width:min(900px,100%);min-height:88vh;border:1px solid #d8c39f;
 border-radius:34px;background:rgba(255,252,247,.78);
 box-shadow:0 30px 90px rgba(78,52,35,.15);
 display:flex;align-items:center;justify-content:center;text-align:center;
 padding:55px 25px;position:relative;overflow:hidden;
 backdrop-filter:blur(10px);
}
.hero-card:before,.hero-card:after{
 content:"";position:absolute;width:170px;height:170px;border:1px solid #d8c39f;
 border-radius:50%;opacity:.55;
}
.hero-card:before{left:-95px;top:-80px}
.hero-card:after{right:-95px;bottom:-80px}
.inner{max-width:730px}
.cross{font-size:58px;color:var(--gold);margin-bottom:10px}
.eyebrow{font-size:14px;letter-spacing:4px;text-transform:uppercase;color:#80663f}
h1{font-size:clamp(43px,8vw,82px);line-height:1.05;color:var(--wine);font-style:italic;margin:18px 0}
.subtitle{font-size:clamp(18px,3vw,26px);color:#58463b}
.divider{display:flex;align-items:center;gap:15px;justify-content:center;margin:24px 0;color:var(--gold)}
.divider span{width:100px;height:1px;background:var(--gold)}
.rings{font-size:36px;color:var(--gold)}
.hero-date{font-size:19px;letter-spacing:1px}
.btn{
 display:inline-block;margin-top:30px;padding:13px 27px;border-radius:999px;
 background:var(--wine);color:white;text-decoration:none;letter-spacing:1px;
 box-shadow:0 10px 25px rgba(125,38,56,.22)
}
section{padding:85px 18px}
.container{width:min(1050px,100%);margin:auto}
.label{text-align:center;color:var(--gold);font-size:13px;letter-spacing:3px;text-transform:uppercase}
.title{text-align:center;font-size:clamp(30px,5vw,48px);color:var(--wine);margin:8px 0 35px}
.intro{
 max-width:760px;margin:auto;text-align:center;font-size:20px;line-height:1.9;
 color:#5d4a3d;
}
.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:40px}
.card{
 background:rgba(255,255,255,.82);border:1px solid #e2d1bd;border-radius:24px;
 padding:32px 22px;text-align:center;box-shadow:0 15px 45px rgba(70,45,28,.08)
}
.card .icon{font-size:31px;color:var(--gold);margin-bottom:12px}
.card h3{font-size:14px;letter-spacing:2px;text-transform:uppercase;color:var(--green);margin-bottom:10px}
.card p{font-size:17px;line-height:1.65}
.names{
 background:linear-gradient(180deg,#fffaf4,#f3e6dc);
}
.family{display:grid;grid-template-columns:1fr 1fr;gap:22px;margin-top:35px}
.family-card{padding:35px 24px;text-align:center;border:1px solid #e0cdb8;border-radius:25px;background:rgba(255,255,255,.7)}
.family-card h3{color:var(--wine);font-size:21px;margin-bottom:12px}
.family-card p{font-size:17px;line-height:1.7}
.count-wrap{text-align:center}
.countdown{display:grid;grid-template-columns:repeat(4,1fr);gap:13px;max-width:680px;margin:30px auto}
.time{background:white;border:1px solid #e2d1bd;border-radius:20px;padding:20px 8px}
.time strong{display:block;font-size:34px;color:var(--wine)}
.time small{letter-spacing:2px;text-transform:uppercase;color:#8b765e}
.venue{
 background:#3f4b3a;color:#fffaf2;text-align:center;
}
.venue .label{color:#d9b979}.venue .title{color:#fffaf2}
.venue-box{max-width:720px;margin:auto;font-size:20px;line-height:1.8}
.map{
 display:inline-block;margin-top:25px;padding:12px 24px;border:1px solid #d9b979;
 color:#fffaf2;text-decoration:none;border-radius:999px
}
footer{background:#2f2622;color:#f8eee2;text-align:center;padding:50px 20px}
footer .cross{font-size:34px}
footer p{margin-top:8px;color:#d9c9ba}
@media(max-width:720px){
 .cards,.family{grid-template-columns:1fr}
 .countdown{grid-template-columns:repeat(2,1fr)}
 .hero-card{min-height:92vh;border-radius:24px}
 section{padding:65px 16px}
}
</style>
</head>
<body>
<div class="decor">
 <div class="blob b1"></div><div class="blob b2"></div><div class="blob b3"></div><div class="blob b4"></div>
</div>

<header class="hero">
 <div class="hero-card">
  <div class="inner">
   <div class="cross">✝</div>
   <div class="eyebrow">With the Blessings of God</div>
   <h1>Mahesh Kumar <span style="color:#b58b4b">&amp;</span> Hema</h1>
   <div class="subtitle">Engagement Ceremony</div>
   <div class="divider"><span></span><div class="rings">♡</div><span></span></div>
   <div class="hero-date">Thursday • 19 November 2026 • 10:00 AM</div>
   <a class="btn" href="#details">Open Invitation</a>
  </div>
 </div>
</header>

<main>
<section id="details">
 <div class="container">
  <div class="label">A joyful beginning</div>
  <h2 class="title">The Celebration</h2>
  <p class="intro">With grateful hearts and the blessings of God, we invite you to join us for the engagement ceremony of <strong>Mahesh Kumar &amp; Hema</strong>.</p>
  <div class="cards">
   <div class="card"><div class="icon">♡</div><h3>Date</h3><p>19th November 2026<br>Thursday</p></div>
   <div class="card"><div class="icon">◷</div><h3>Time</h3><p>10:00 AM</p></div>
   <div class="card"><div class="icon">⌖</div><h3>Venue</h3><p>Near Auxilium School,<br>Chopparamannagudem / Gavaravaram,<br>Koyyalagudem Mandal, Andhra Pradesh</p></div>
  </div>
 </div>
</section>

<section class="names">
 <div class="container">
  <div class="label">Our families</div>
  <h2 class="title">Together With Our Families</h2>
  <div class="family">
   <div class="family-card">
    <h3>Mallimoggala Mahesh Kumar</h3>
    <p>S/o Mallimoggala Suvarna Raj (Srinivasa Rao)<br>&amp; Vana Dhrekshewalli (Kanakadurga)</p>
   </div>
   <div class="family-card">
    <h3>Kadavakollu Hema</h3>
    <p>D/o Kadavakollu Satyanarayana &amp; Nirmala</p>
   </div>
  </div>
 </div>
</section>

<section>
 <div class="container count-wrap">
  <div class="label">The special day is approaching</div>
  <h2 class="title">Counting the Moments</h2>
  <div class="countdown">
   <div class="time"><strong id="days">0</strong><small>Days</small></div>
   <div class="time"><strong id="hours">0</strong><small>Hours</small></div>
   <div class="time"><strong id="mins">0</strong><small>Minutes</small></div>
   <div class="time"><strong id="secs">0</strong><small>Seconds</small></div>
  </div>
 </div>
</section>

<section class="venue">
 <div class="container">
  <div class="label">Join us</div>
  <h2 class="title">We Would Love Your Presence</h2>
  <div class="venue-box">
   <p>Near Auxilium School,<br>Chopparamannagudem / Gavaravaram,<br>Koyyalagudem Mandal, Andhra Pradesh</p>
   <a class="map" target="_blank" rel="noopener"
   href="https://www.google.com/maps/search/?api=1&query=Auxilium+School+Chopparamannagudem+Gavaravaram+Koyyalagudem+Andhra+Pradesh">Open in Google Maps</a>
  </div>
 </div>
</section>
</main>

<footer>
 <div class="cross">✝</div>
 <h2>Mahesh Kumar &amp; Hema</h2>
 <p>Your presence will be a blessing to us</p>
</footer>

<script>
const target=new Date("2026-11-19T10:00:00+05:30").getTime();
function update(){
 const d=Math.max(0,target-Date.now());
 document.getElementById("days").textContent=Math.floor(d/86400000);
 document.getElementById("hours").textContent=Math.floor(d/3600000)%24;
 document.getElementById("mins").textContent=Math.floor(d/60000)%60;
 document.getElementById("secs").textContent=Math.floor(d/1000)%60;
}
update();setInterval(update,1000);
</script>
</body>
</html>
```
