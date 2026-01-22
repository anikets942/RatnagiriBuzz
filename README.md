<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>RatnagiriBuzz | Local • State • National • International News</title>
  <style>
    :root{
      --red:#c40000;
      --dark:#111;
      --blue:#0b2c5f;
      --bg:#f2f4f7;
    }
    body{margin:0;font-family:Segoe UI,Arial,sans-serif;background:var(--bg);color:#222;}
    header{background:#fff;border-bottom:3px solid var(--red);}
    .topbar{display:flex;justify-content:space-between;align-items:center;max-width:1200px;margin:auto;padding:10px 16px;}
    .logo{font-size:28px;font-weight:800;color:var(--blue);} 
    .logo span{color:var(--red);}    
    .lang button{margin-left:6px;padding:6px 10px;border:1px solid var(--red);background:#fff;color:var(--red);border-radius:4px;cursor:pointer;font-weight:600;}
    nav{background:var(--red);}    
    nav ul{margin:0;padding:0;list-style:none;display:flex;flex-wrap:wrap;max-width:1200px;margin:auto;}
    nav li a{display:block;color:#fff;padding:12px 16px;text-decoration:none;font-weight:600;}
    nav li a:hover{background:#a00000;}
    .breaking{background:#fff;max-width:1200px;margin:10px auto;padding:10px;border-left:6px solid var(--red);font-weight:700;color:var(--red);}
    .container{max-width:1200px;margin:auto;padding:16px;display:grid;grid-template-columns:2fr 1fr;gap:16px;}
    .main-news,.sidebar{background:#fff;border-radius:8px;box-shadow:0 2px 6px rgba(0,0,0,.1);padding:14px;}
    .headline{position:relative;}
    .headline img{width:100%;border-radius:8px;}
    .headline h2{position:absolute;bottom:0;margin:0;padding:12px;color:#fff;background:linear-gradient(transparent,rgba(0,0,0,.85));width:100%;border-radius:0 0 8px 8px;}
    .news-list{margin-top:12px;}
    .news-item{padding:10px 0;border-bottom:1px solid #eee;font-weight:600;}
    .news-item:last-child{border:none;}
    footer{background:var(--dark);color:#fff;text-align:center;padding:18px;margin-top:30px;}
    @media(max-width:900px){.container{grid-template-columns:1fr;}}
  </style>
</head>
<body>
<header>
  <div class="topbar">
    <div class="logo">Ratnagiri<span>Buzz</span></div>
    <div class="lang">
      <button>English</button>
      <button>मराठी</button>
    </div>
  </div>
  <nav>
    <ul>
      <li><a href="#">Top News</a></li>
      <li><a href="#">Ratnagiri</a></li>
      <li><a href="#">State</a></li>
      <li><a href="#">India</a></li>
      <li><a href="#">International</a></li>
      <li><a href="#">Politics</a></li>
      <li><a href="#">Sports</a></li>
      <li><a href="#">Entertainment</a></li>
    </ul>
  </nav>
</header>

<div class="breaking">BREAKING: Ratnagiri receives heavy rainfall alert • प्रशासन सतर्क</div>

<div class="container">
  <div class="main-news">
    <div class="headline">
      <img src="https://via.placeholder.com/800x420" alt="headline" />
      <h2>Ratnagiri district on high alert due to continuous rainfall</h2>
    </div>
    <div class="news-list">
      <div class="news-item">Road connectivity affected in rural areas</div>
      <div class="news-item">Fishermen advised not to venture into sea</div>
      <div class="news-item">Schools closed in selected talukas</div>
    </div>
  </div>
  <aside class="sidebar">
    <h3>Top Stories</h3>
    <div class="news-item">Maharashtra cabinet meeting highlights</div>
    <div class="news-item">National highway expansion update</div>
    <div class="news-item">Global markets react to US policy</div>
    <div class="news-item">India squad announced for series</div>
  </aside>
</div>

<footer>
  <p>© 2026 RatnagiriBuzz | Trusted Digital News Network</p>
</footer>


<!-- ADMIN PANEL (DEMO) -->
<div style="display:none" id="adminPanel"></div>
<script>
/* DEMO ADMIN AUTH (FRONTEND ONLY) */
const ADMIN = { user:'admin@ratnagiribuzz', pass:'Buzz@123' };
function adminLogin(u,p){
  if(u===ADMIN.user && p===ADMIN.pass){ alert('Login successful (Demo)'); }
  else{ alert('Invalid credentials'); }
}
</script>
</body>
</html>
