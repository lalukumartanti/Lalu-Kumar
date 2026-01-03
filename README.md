<html lang="en">
<head>
<meta charset="UTF-8">
<title>Lalu Kumar Tanti | Official Page</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>
:root{--text:#fff;}

body{
  margin:0;
  font-family:'Poppins',sans-serif;
  text-align:center;
  color:var(--text);
  background:linear-gradient(270deg,#667eea,#764ba2,#f7797d,#6a82fb);
  background-size:800% 800%;
  animation:bg 20s ease infinite;
}

@keyframes bg{
  0%{background-position:0% 50%}
  50%{background-position:100% 50%}
  100%{background-position:0% 50%}
}

header{
  padding:40px 20px 60px;
}

/* ✅ PERFECT PROFILE PHOTO (FIXED) */
.profile-wrapper{
  width:150px;
  height:150px;
  margin:0 auto;
  border-radius:50%;
  border:5px solid #fff;
  background:url("profile.jpg") center 20% / cover no-repeat;
  box-shadow:0 0 30px rgba(255,255,255,.85);
}

h1{
  margin:12px 0 4px;
  font-size:32px;
}

.address{
  font-size:14px;
  font-weight:600;
  background:linear-gradient(45deg,#ff512f,#dd2476,#24c6dc);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
}

.badge{
  display:inline-block;
  margin-top:6px;
  padding:6px 16px;
  border-radius:20px;
  background:rgba(255,255,255,.25);
  font-size:13px;
}

.card{
  max-width:480px;
  margin:-40px auto 30px;
  padding:30px;
  background:rgba(255,255,255,.15);
  backdrop-filter:blur(12px);
  border-radius:30px;
  box-shadow:0 25px 60px rgba(0,0,0,.35);
}

.btn{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:10px;
  padding:15px;
  margin:12px 0;
  border-radius:18px;
  font-weight:600;
  text-decoration:none;
  color:#fff;
  transition:.3s;
}

.btn:hover{transform:translateY(-3px)}

.call{background:#0a66c2}
.whatsapp{background:#25D366}
.email{background:#f39c12}
.instagram{background:linear-gradient(45deg,#f58529,#dd2a7b,#8134af)}
.facebook{background:#1877f2}
.twitter{background:#000}
.youtube{background:#ff0000}
.linkedin{background:#0a66c2}
.telegram{background:#0088cc}
.github{background:#24292e}
.snapchat{background:#fffc00;color:#000}
.spotify{background:#1db954}
.threads{background:linear-gradient(45deg,#ff0080,#7928ca)}
.maps{background:#ff6f61}
.phonepe{background:#5f259f}
.gpay{background:#4285F4}

.services{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:12px;
}

.service{
  padding:12px;
  border-radius:14px;
  background:rgba(255,255,255,.2);
  font-weight:600;
}

footer{
  padding:20px;
  font-size:14px;
  opacity:.85;
}

.floating{
  position:fixed;
  pointer-events:none;
  font-weight:700;
  animation:float 2s linear;
}

@keyframes float{
  to{transform:translateY(-50px);opacity:0}
}
</style>
</head>

<body>

<header>
  <!-- ✅ FIXED PROFILE PHOTO -->
  <div class="profile-wrapper" aria-label="Lalu Kumar Tanti profile photo"></div>

  <h1>Lalu Kumar Tanti</h1>
  <div class="address">Jaipur, Banka, Bihar, India</div>
  <div class="badge">Official • Verified</div>
  <div id="timeDate"></div>
</header>

<div class="card">

<a class="btn call" href="tel:+919771617808" onclick="floatName()">
<i class="fa-solid fa-phone"></i> Call
</a>

<a class="btn whatsapp" href="https://wa.me/919771617808" onclick="floatName()">
<i class="fa-brands fa-whatsapp"></i> WhatsApp
</a>

<a class="btn email" href="mailto:lalukumartanti75@gmail.com" onclick="floatName()">
<i class="fa-solid fa-envelope"></i> Email
</a>

<a class="btn instagram" href="https://www.instagram.com/lalu_kumar_tanti">
<i class="fa-brands fa-instagram"></i> Instagram
</a>

<a class="btn facebook" href="https://www.facebook.com/lalukumartantii">
<i class="fa-brands fa-facebook"></i> Facebook
</a>

<a class="btn twitter" href="https://x.com/LaluKumarTanti">
<i class="fa-brands fa-x-twitter"></i> X
</a>

<a class="btn youtube" href="https://www.youtube.com/@Lalu_Kumar_Tanti">
<i class="fa-brands fa-youtube"></i> YouTube
</a>

<a class="btn linkedin" href="https://in.linkedin.com/in/lalu-kumar-tanti-540185351">
<i class="fa-brands fa-linkedin"></i> LinkedIn
</a>

<a class="btn telegram" href="https://t.me/Lalu_kumar_tanti_0">
<i class="fa-brands fa-telegram"></i> Telegram
</a>

<a class="btn github" href="https://github.com/lalukumartanti">
<i class="fa-brands fa-github"></i> GitHub
</a>

<a class="btn snapchat" href="https://www.snapchat.com/add/lalu_kumar77">
<i class="fa-brands fa-snapchat"></i> Snapchat
</a>

<a class="btn spotify" href="https://open.spotify.com/user/31c4utsldd2omujkcxyjbrwgvnou">
<i class="fa-brands fa-spotify"></i> Spotify
</a>

<a class="btn threads" href="https://www.threads.com/@lalu_kumar_tanti">
<i class="fa-brands fa-threads"></i> Threads
</a>

<a class="btn maps" href="https://maps.app.goo.gl/BeG2PYziNmuQ85L7A">
<i class="fa-solid fa-location-dot"></i> Google Maps
</a>

<a class="btn maps" href="https://maps.app.goo.gl/DvQjApJQStwhEsmTA">
<i class="fa-solid fa-location-dot"></i> Business Map
</a>

<a class="btn phonepe" href="upi://pay?pa=9771617808-2@ybl&pn=Lalu%20Kumar%20Tanti&cu=INR&am=1">
<i class="fa-solid fa-wallet"></i> PhonePe ₹1
</a>

<a class="btn gpay" href="upi://pay?pa=9771617808-2@axl&pn=Lalu%20Kumar%20Tanti&cu=INR&am=1">
<i class="fa-brands fa-google-pay"></i> Google Pay ₹1
</a>

<h3>Services</h3>
<div class="services">
  <div class="service">Business Promotion</div>
  <div class="service">Digital Branding</div>
  <div class="service">Social Media Growth</div>
  <div class="service">Online Support</div>
</div>

</div>

<footer>© 2026 Lalu Kumar Tanti | All Rights Reserved</footer>

<script>
function floatName(){
 const f=document.createElement("div");
 f.className="floating";
 f.style.left=Math.random()*window.innerWidth+"px";
 f.style.top=Math.random()*window.innerHeight+"px";
 f.style.color=`hsl(${Math.random()*360},90%,60%)`;
 f.innerText="Lalu Kumar Tanti 😄";
 document.body.appendChild(f);
 setTimeout(()=>f.remove(),2000);
}

setInterval(()=>{
 const d=new Date();
 document.getElementById("timeDate").innerText =
 d.toLocaleTimeString()+" | "+d.toDateString();
},1000);
</script>

</body>
</html>

