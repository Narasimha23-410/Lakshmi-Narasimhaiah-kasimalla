<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Kasimalla Lakshminarasimhaiah | ECE Engineer & STEM Innovator</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet"/>
<style>
:root{
  --navy:#0a1628;--navy2:#112240;--navy3:#1a3a5c;
  --teal:#87CEEB;--teal2:#5DADE2;--teal3:#3498db;
  --gold:#f4a261;--cream:#f0f7ff;--white:#ffffff;
  --text:#0a1628;--muted:#4a607a;--light:#ddeeff;
  --border:rgba(135,206,235,0.25);--r:14px;
  --sh:0 8px 30px rgba(10,22,40,0.13);
}
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{font-family:'DM Sans',sans-serif;background:var(--cream);color:var(--text);line-height:1.7;overflow-x:hidden;}

nav{position:sticky;top:0;z-index:9999;background:var(--navy);padding:0 2rem;display:flex;align-items:center;justify-content:space-between;height:64px;box-shadow:0 2px 20px rgba(0,0,0,0.4);}
.nav-logo{font-family:'Playfair Display',serif;font-size:1.15rem;font-weight:700;color:var(--teal);text-decoration:none;letter-spacing:.4px;}
.nav-links{display:flex;gap:.1rem;list-style:none;}
.nav-links a{color:rgba(255,255,255,.75);text-decoration:none;font-size:.8rem;font-weight:500;padding:6px 10px;border-radius:6px;transition:all .2s;}
.nav-links a:hover,.nav-links a.active{color:var(--teal);background:rgba(135,206,235,.15);}
.nav-toggle{display:none;background:none;border:none;cursor:pointer;flex-direction:column;gap:5px;padding:4px;}
.nav-toggle span{display:block;width:24px;height:2px;background:#fff;border-radius:2px;transition:.3s;}

#home{min-height:100vh;background:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='80' height='80'%3E%3Cpath d='M10 0h1v8h-1zM0 10h8v1H0zM20 0h1v4h-1zM40 0h1v8h-1zM30 10h8v1H30zM60 0h1v8h-1zM50 10h8v1H50zM70 4h8v1H70zM4 20h1v8h-1zM0 30h8v1H0zM4 40h1v8h-1zM0 50h8v1H0zM4 60h1v8h-1zM0 70h8v1H0zM40 20h1v8h-1zM30 30h8v1H30zM60 20h1v8h-1zM50 30h8v1H50zM20 40h1v8h-1zM10 50h8v1H10zM70 40h1v8h-1zM60 50h8v1H60z' fill='rgba(135,206,235,0.07)'/%3E%3C/svg%3E"),linear-gradient(135deg,#060e1c 0%,#0a1628 20%,#0d2040 40%,#0e2d55 60%,#0a2548 80%,#060e1c 100%);display:flex;align-items:center;position:relative;overflow:hidden;padding:5rem 2rem 4rem;}
.hero-glow{position:absolute;right:-80px;top:45%;transform:translateY(-50%);width:700px;height:700px;border-radius:50%;background:radial-gradient(circle,rgba(52,152,219,.15) 0%,transparent 70%);pointer-events:none;}
.hero-glow2{position:absolute;left:-100px;bottom:-50px;width:500px;height:500px;border-radius:50%;background:radial-gradient(circle,rgba(135,206,235,.07) 0%,transparent 65%);pointer-events:none;}
.hero-inner{max-width:1120px;margin:0 auto;width:100%;display:grid;grid-template-columns:1fr 1fr;gap:3rem;align-items:center;}
.hero-left{z-index:2;}
.hero-badge{display:inline-flex;align-items:center;gap:8px;background:rgba(135,206,235,.12);border:1px solid rgba(135,206,235,.3);border-radius:20px;padding:6px 18px;font-size:.75rem;font-weight:600;color:var(--teal);letter-spacing:1.2px;text-transform:uppercase;margin-bottom:1.5rem;}
.hero-badge::before{content:'';width:7px;height:7px;border-radius:50%;background:var(--teal);animation:blink 1.8s infinite;}
@keyframes blink{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.4;transform:scale(1.5)}}
.hero-name{font-family:'Playfair Display',serif;font-size:clamp(1.9rem,4.5vw,3.2rem);font-weight:700;line-height:1.1;color:#fff;margin-bottom:.5rem;}
.hero-name span{color:var(--teal);}
.hero-role{font-size:.98rem;color:rgba(255,255,255,.6);margin-bottom:1.25rem;}
.hero-role strong{color:var(--gold);font-weight:600;}
.hero-intro{font-size:.92rem;color:rgba(255,255,255,.5);max-width:460px;margin-bottom:2rem;line-height:1.85;}
.hero-stats{display:flex;gap:2rem;margin-bottom:2.5rem;flex-wrap:wrap;}
.stat{text-align:center;}
.stat-n{font-family:'Playfair Display',serif;font-size:1.9rem;font-weight:700;color:var(--teal);line-height:1;}
.stat-l{font-size:.67rem;color:rgba(255,255,255,.4);letter-spacing:.7px;text-transform:uppercase;margin-top:2px;max-width:120px;}
.hero-btns{display:flex;gap:1rem;flex-wrap:wrap;}
.btn{padding:11px 26px;border-radius:8px;font-size:.87rem;font-weight:600;text-decoration:none;display:inline-flex;align-items:center;gap:7px;transition:all .25s;cursor:pointer;border:none;font-family:inherit;}
.btn-t{background:var(--teal);color:var(--navy);}
.btn-t:hover{background:var(--teal2);transform:translateY(-2px);box-shadow:0 6px 20px rgba(135,206,235,.35);}
.btn-o{background:transparent;color:rgba(255,255,255,.8);border:1.5px solid rgba(255,255,255,.25);}
.btn-o:hover{border-color:var(--teal);color:var(--teal);}
.hero-right{display:flex;justify-content:center;align-items:center;position:relative;}
.photo-ring{width:300px;height:300px;border-radius:50%;border:3px solid rgba(135,206,235,.4);display:flex;align-items:center;justify-content:center;position:relative;animation:float 4s ease-in-out infinite;}
@keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-12px)}}
.photo-ring::before{content:'';position:absolute;inset:-14px;border-radius:50%;border:1px dashed rgba(135,206,235,.25);animation:rotateSlow 25s linear infinite;}
@keyframes rotateSlow{to{transform:rotate(360deg)}}
.hero-img{width:268px;height:268px;border-radius:50%;object-fit:cover;object-position:top;border:4px solid var(--navy2);}
.hero-chip{position:absolute;bottom:-8px;right:-10px;background:var(--gold);color:var(--navy);font-size:.73rem;font-weight:700;padding:7px 14px;border-radius:20px;box-shadow:0 4px 14px rgba(244,162,97,.4);white-space:nowrap;}
.hero-chip2{position:absolute;top:10px;left:-20px;background:rgba(135,206,235,.9);color:var(--navy);font-size:.7rem;font-weight:600;padding:6px 12px;border-radius:14px;white-space:nowrap;}

section{padding:80px 2rem;}
.container{max-width:1120px;margin:0 auto;}
.sec-label{font-size:.7rem;font-weight:700;color:var(--teal);letter-spacing:2.5px;text-transform:uppercase;margin-bottom:.6rem;display:block;}
.sec-title{font-family:'Playfair Display',serif;font-size:clamp(1.8rem,4vw,2.5rem);font-weight:700;color:var(--navy);margin-bottom:.75rem;line-height:1.2;}
.sec-title span{color:var(--teal3);}
.sec-title.light{color:#fff;}
.sec-desc{font-size:.97rem;color:var(--muted);max-width:620px;line-height:1.8;margin-bottom:2.5rem;}
.sec-desc.light{color:rgba(255,255,255,.5);}

#about{background:var(--white);}
.about-grid{display:grid;grid-template-columns:300px 1fr;gap:3.5rem;align-items:start;}
.about-photos{display:flex;flex-direction:column;gap:1rem;}
.about-main-photo{width:100%;border-radius:var(--r);object-fit:cover;height:380px;box-shadow:var(--sh);}
.about-tag{background:var(--navy);color:var(--teal);font-size:.75rem;font-weight:600;padding:8px 18px;border-radius:20px;display:inline-block;margin-top:.5rem;text-align:center;width:100%;}
.about-info p{font-size:.95rem;color:var(--muted);line-height:1.9;margin-bottom:.9rem;}
.detail-grid{display:grid;grid-template-columns:1fr 1fr;gap:.75rem;margin:1.25rem 0;}
.detail-item{display:flex;align-items:flex-start;gap:10px;}
.d-icon{font-size:1.1rem;flex-shrink:0;margin-top:1px;}
.d-label{font-size:.68rem;color:var(--muted);font-weight:700;text-transform:uppercase;letter-spacing:.7px;}
.d-val{font-size:.9rem;color:var(--text);font-weight:500;}
.d-val a{color:var(--teal3);text-decoration:none;}
.soc-links{display:flex;gap:.75rem;flex-wrap:wrap;margin-top:1.25rem;}
.soc-btn{display:inline-flex;align-items:center;gap:7px;padding:9px 18px;border-radius:8px;font-size:.83rem;font-weight:500;text-decoration:none;border:1.5px solid;transition:all .2s;}
.soc-btn.li{color:#0a66c2;border-color:#0a66c2;}
.soc-btn.li:hover{background:#0a66c2;color:#fff;}
.soc-btn.ig{color:#e1306c;border-color:#e1306c;}
.soc-btn.ig:hover{background:#e1306c;color:#fff;}

.tab-nav{display:flex;gap:.5rem;flex-wrap:wrap;margin-bottom:2rem;border-bottom:2px solid rgba(255,255,255,.1);padding-bottom:.5rem;}
.tab-btn{padding:8px 20px;border-radius:8px 8px 0 0;border:none;background:none;font-family:inherit;font-size:.85rem;font-weight:600;color:rgba(255,255,255,.45);cursor:pointer;transition:all .2s;border-bottom:2px solid transparent;margin-bottom:-2px;}
.tab-btn.active{color:var(--teal);border-bottom-color:var(--teal);background:rgba(135,206,235,.06);}
.tab-btn:hover{color:var(--teal);}
.tab-panel{display:none;}
.tab-panel.active{display:block;animation:fadeIn .35s ease;}
@keyframes fadeIn{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}

#experience{background:var(--navy);}
.exp-card{background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.09);border-radius:var(--r);padding:1.5rem 1.75rem;margin-bottom:1.5rem;transition:all .3s;}
.exp-card:hover{background:rgba(255,255,255,.09);border-color:rgba(135,206,235,.25);transform:translateX(4px);}
.exp-header{display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:.5rem;margin-bottom:.5rem;}
.exp-title{font-size:1.05rem;font-weight:700;color:#fff;}
.exp-co{font-size:.88rem;color:var(--teal);font-weight:500;margin-bottom:.25rem;}
.exp-period{font-size:.73rem;font-weight:600;padding:4px 12px;border-radius:12px;background:rgba(135,206,235,.15);color:var(--teal);border:1px solid rgba(135,206,235,.2);white-space:nowrap;}
.exp-period.gold{background:rgba(244,162,97,.15);color:var(--gold);border-color:rgba(244,162,97,.25);}
.exp-period.green{background:rgba(39,174,96,.15);color:#2ecc71;border-color:rgba(39,174,96,.25);}
.exp-desc{font-size:.9rem;color:rgba(255,255,255,.55);line-height:1.8;margin-top:.5rem;}
.exp-tags{display:flex;flex-wrap:wrap;gap:6px;margin-top:.9rem;}
.exp-tag{font-size:.7rem;font-weight:500;padding:3px 10px;border-radius:10px;background:rgba(255,255,255,.07);color:rgba(255,255,255,.5);border:1px solid rgba(255,255,255,.1);}
.exp-ul{margin:1rem 0 .5rem 1.2rem;}
.exp-ul li{font-size:.85rem;color:rgba(255,255,255,.6);line-height:1.75;margin-bottom:.25rem;}
.exp-ul li strong{color:var(--teal);}

#projects{background:var(--cream);}
.proj-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(320px,1fr));gap:1.5rem;}
.proj-card{background:var(--white);border-radius:var(--r);overflow:hidden;box-shadow:var(--sh);border:1px solid rgba(0,0,0,.05);transition:all .3s;}
.proj-card:hover{transform:translateY(-7px);box-shadow:0 16px 40px rgba(10,22,40,.15);}
.proj-img-wrap{height:0;padding-top:56%;position:relative;overflow:hidden;background:var(--navy2);}
.proj-img-wrap img{position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;transition:transform .4s;}
.proj-card:hover .proj-img-wrap img{transform:scale(1.06);}
.proj-badge{position:absolute;top:10px;left:10px;z-index:2;background:var(--teal);color:var(--navy);font-size:.68rem;font-weight:700;padding:4px 10px;border-radius:10px;}
.proj-badge.gold{background:var(--gold);}
.proj-badge.purple{background:#9b59b6;color:#fff;}
.proj-badge.red{background:#e74c3c;color:#fff;}
.proj-body{padding:1.4rem;}
.proj-body h4{font-size:1rem;font-weight:700;color:var(--navy);margin-bottom:.45rem;}
.proj-body p{font-size:.87rem;color:var(--muted);line-height:1.7;}
.proj-techs{display:flex;flex-wrap:wrap;gap:5px;margin-top:.85rem;}
.proj-tech{font-size:.68rem;font-weight:600;padding:3px 9px;border-radius:10px;background:rgba(52,152,219,.12);color:var(--navy2);}
.proj-mini-gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:4px;margin-top:.75rem;}
.proj-mini-gallery img{width:100%;height:70px;object-fit:cover;border-radius:6px;cursor:pointer;}
.proj-more-card{background:var(--navy);border:2px dashed rgba(135,206,235,.35);border-radius:var(--r);padding:3rem 1.5rem;text-align:center;display:flex;flex-direction:column;justify-content:center;align-items:center;transition:all .3s;min-height:280px;}
.proj-more-card:hover{border-color:var(--teal);transform:translateY(-5px);}

#achievements{background:var(--white);}
.ach-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1.5rem;}
.ach-card{border-radius:var(--r);overflow:hidden;border:1px solid rgba(0,0,0,.06);background:var(--white);transition:all .3s;box-shadow:var(--sh);}
.ach-card:hover{transform:translateY(-5px);box-shadow:0 12px 32px rgba(10,22,40,.14);}
.ach-img{width:100%;height:200px;object-fit:cover;cursor:pointer;display:block;}
.ach-body{padding:1.2rem;}
.ach-icon{font-size:1.5rem;margin-bottom:.4rem;}
.ach-body h4{font-size:.95rem;font-weight:700;color:var(--navy);margin-bottom:.35rem;}
.ach-body p{font-size:.82rem;color:var(--muted);line-height:1.6;}
.ach-date{font-size:.7rem;color:var(--teal3);font-weight:600;margin-top:.5rem;letter-spacing:.4px;}

#certifications{background:var(--navy);}
.cert-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:1.25rem;}
.cert-card{background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.1);border-radius:var(--r);overflow:hidden;transition:all .3s;}
.cert-card:hover{background:rgba(255,255,255,.1);transform:translateY(-4px);}
.cert-img{width:100%;height:180px;object-fit:cover;object-position:top;cursor:pointer;display:block;background:rgba(255,255,255,.05);}
.cert-body{padding:1rem 1.25rem;}
.cert-body h5{font-size:.9rem;font-weight:700;color:#fff;margin-bottom:.25rem;}
.cert-body p{font-size:.78rem;color:rgba(255,255,255,.5);line-height:1.5;}
.cert-issuer{font-size:.72rem;font-weight:700;color:var(--teal);margin-top:.4rem;}

#outreach{background:var(--cream);}
.out-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1.5rem;}
.out-card{background:var(--white);border-radius:var(--r);overflow:hidden;box-shadow:var(--sh);transition:all .3s;}
.out-card:hover{transform:translateY(-5px);box-shadow:0 12px 32px rgba(10,22,40,.14);}
.out-img-grid{display:grid;grid-template-columns:1fr 1fr;gap:3px;height:190px;overflow:hidden;}
.out-img-grid img{width:100%;height:100%;object-fit:cover;cursor:pointer;}
.out-img-grid .full{grid-column:1/-1;}
.out-body{padding:1.25rem;}
.out-body h4{font-size:.97rem;font-weight:700;color:var(--navy);margin-bottom:.4rem;}
.out-body p{font-size:.85rem;color:var(--muted);line-height:1.65;}
.out-tag{display:inline-block;margin-top:.75rem;font-size:.7rem;font-weight:700;padding:4px 12px;border-radius:10px;background:rgba(135,206,235,.15);color:var(--navy2);border:1px solid rgba(135,206,235,.3);}

#gallery{background:var(--navy);}
.gallery-masonry{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:.75rem;}
.gallery-masonry img{width:100%;border-radius:10px;display:block;transition:transform .3s,box-shadow .3s;cursor:pointer;object-fit:cover;height:160px;background:rgba(255,255,255,.05);}
.gallery-masonry img:hover{transform:scale(1.05);box-shadow:0 8px 24px rgba(0,0,0,.4);}

#contact{background:var(--white);}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:3rem;align-items:start;}
.c-items{display:flex;flex-direction:column;gap:.9rem;}
.c-item{display:flex;align-items:flex-start;gap:12px;}
.c-icon{width:40px;height:40px;border-radius:10px;background:var(--navy);display:flex;align-items:center;justify-content:center;font-size:1.1rem;flex-shrink:0;}
.c-label{font-size:.68rem;color:var(--muted);font-weight:700;text-transform:uppercase;letter-spacing:.7px;}
.c-val{font-size:.9rem;color:var(--text);font-weight:500;}
.c-val a{color:var(--teal3);text-decoration:none;}
.contact-form h4{font-family:'Playfair Display',serif;font-size:1.2rem;color:var(--navy);margin-bottom:1.25rem;}
.fg{margin-bottom:1rem;}
.fg label{display:block;font-size:.78rem;font-weight:600;color:var(--muted);margin-bottom:.4rem;text-transform:uppercase;letter-spacing:.5px;}
.fg input,.fg textarea{width:100%;padding:10px 14px;border:1.5px solid var(--light);border-radius:8px;font-family:inherit;font-size:.9rem;color:var(--text);background:var(--cream);transition:border-color .2s;outline:none;}
.fg input:focus,.fg textarea:focus{border-color:var(--teal3);}
.fg textarea{height:110px;resize:vertical;}
.f-submit{width:100%;padding:12px;background:var(--navy);color:var(--teal);border:none;border-radius:8px;font-family:inherit;font-size:.95rem;font-weight:700;cursor:pointer;transition:all .2s;letter-spacing:.5px;}
.f-submit:hover{background:var(--navy3);transform:translateY(-2px);}

footer{background:var(--navy);color:rgba(255,255,255,.4);text-align:center;padding:2rem;font-size:.83rem;}
footer span{color:var(--teal);}

.reveal{opacity:0;transform:translateY(28px);transition:opacity .6s ease,transform .6s ease;}
.reveal.visible{opacity:1;transform:translateY(0);}
.reveal-left{opacity:0;transform:translateX(-30px);transition:opacity .6s ease,transform .6s ease;}
.reveal-left.visible{opacity:1;transform:translateX(0);}
.reveal-right{opacity:0;transform:translateX(30px);transition:opacity .6s ease,transform .6s ease;}
.reveal-right.visible{opacity:1;transform:translateX(0);}
.delay-1{transition-delay:.1s;}.delay-2{transition-delay:.2s;}.delay-3{transition-delay:.3s;}.delay-4{transition-delay:.4s;}.delay-5{transition-delay:.5s;}

.lb{display:none;position:fixed;inset:0;background:rgba(0,0,0,.93);z-index:99999;align-items:center;justify-content:center;}
.lb.open{display:flex;}
.lb img{max-width:90vw;max-height:88vh;border-radius:10px;box-shadow:0 0 40px rgba(0,0,0,.5);}
.lb-close{position:absolute;top:20px;right:28px;color:#fff;font-size:2.2rem;cursor:pointer;line-height:1;background:none;border:none;}

@media(max-width:960px){
  .hero-inner{grid-template-columns:1fr;text-align:center;}
  .hero-right{order:-1;}
  .hero-stats{justify-content:center;}
  .hero-btns{justify-content:center;}
  .about-grid{grid-template-columns:1fr;}
  .contact-grid{grid-template-columns:1fr;}
}
@media(max-width:680px){
  section{padding:56px 1.2rem;}
  .nav-links{display:none;flex-direction:column;position:absolute;top:64px;left:0;right:0;background:var(--navy);padding:1rem 1.5rem;gap:.5rem;border-top:1px solid rgba(255,255,255,.08);}
  .nav-links.open{display:flex;}
  .nav-toggle{display:flex;}
  .photo-ring{width:230px;height:230px;}
  .hero-img{width:200px;height:200px;}
  .gallery-masonry{grid-template-columns:repeat(auto-fill,minmax(140px,1fr));}
}
</style>
</head>
<body>

<!-- Lightbox -->
<div class="lb" id="lb" onclick="closeLB()">
  <button class="lb-close" onclick="closeLB()">&#10005;</button>
  <img alt="Image Preview" id="lb-img" src=""/>
</div>

<!-- Navigation -->
<nav>
  <a class="nav-logo" href="#home">K. Lakshminarasimhaiah</a>
  <ul class="nav-links" id="navLinks">
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#achievements">Achievements</a></li>
    <li><a href="#certifications">Certificates</a></li>
    <li><a href="#outreach">Outreach</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <button class="nav-toggle" id="navToggle">
    <span></span><span></span><span></span>
  </button>
</nav>

<!-- HERO -->
<section id="home">
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="hero-inner">
    <div class="hero-left">
      <div class="hero-badge">&#9889; Currently Employed &middot; Bengaluru</div>
      <h1 class="hero-name">Kasimalla<br/><span>Lakshminarasimhaiah</span></h1>
      <p class="hero-role">ECE Graduate &nbsp;&middot;&nbsp; <strong>STEM Engineer @ StemX Indian Innovations Pvt. Ltd.</strong></p>
      <p class="hero-intro">Electronics &amp; Communication engineer from RGMCET, Nandyal &mdash; passionate about embedded systems, IoT and making technology accessible to every child. International innovator, award-winning hackathon champion, and community STEM educator.</p>
      <div class="hero-stats">
        <div class="stat">
          <div class="stat-n">15+</div>
          <div class="stat-l">Certificates</div>
        </div>
        <div class="stat">
          <div class="stat-n">🌎</div>
          <div class="stat-l">International Competition IEEE YESIST12 Finalist</div>
        </div>
        <div class="stat">
          <div class="stat-n">200+</div>
          <div class="stat-l">Students Trained</div>
        </div>
      </div>
      <div class="hero-btns">
        <a class="btn btn-t" href="#experience">View My Journey &#8594;</a>
        <a class="btn btn-o" href="#contact">Get in Touch</a>
      </div>
    </div>
    <div class="hero-right">
      <div class="photo-ring">
        <img alt="Kasimalla Lakshminarasimhaiah - Profile" class="hero-img" loading="lazy"
          src="https://lh3.googleusercontent.com/d/1e7JPCwR0oJsz_thRCHAiIxQb4nnKNzG7"/>
      </div>
      <div class="hero-chip">&#9889; STEM Engineer</div>
      <div class="hero-chip2">🎓 ECE Graduate</div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="container">
    <div class="about-grid">
      <div class="reveal-left">
        <div class="about-photos">
          <img alt="Formal Photo at Schneider Electric Company" class="about-main-photo" loading="lazy"
            onclick="openLB(this.src)"
            src="https://lh3.googleusercontent.com/d/17JIDOk5rmJYmoNO6oh2CnyzUBS5DzvEU"/>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:.75rem;">
            <img alt="Engineering Photo" loading="lazy" onclick="openLB(this.src)"
              src="https://lh3.googleusercontent.com/d/1rL4imDyuWdLNbsh5jr2PBVNyjCVzVh72"
              style="width:100%;height:130px;object-fit:cover;border-radius:10px;box-shadow:var(--sh);cursor:pointer;"/>
            <img alt="Event Photo" loading="lazy" onclick="openLB(this.src)"
              src="https://lh3.googleusercontent.com/d/1ZyUUeq0hkb73l5YngW0OZAdpGj0bc4s6"
              style="width:100%;height:130px;object-fit:cover;border-radius:10px;box-shadow:var(--sh);cursor:pointer;"/>
          </div>
          <div class="about-tag">📍 Bengaluru, Karnataka &middot; Currently Working</div>
        </div>
      </div>
      <div class="reveal-right">
        <span class="sec-label">About Me</span>
        <h2 class="sec-title" style="margin-bottom:.75rem;">Building the Future with <span>Electronics &amp; Innovation</span></h2>
        <div class="about-info">
          <p>I am <strong>Kasimalla Lakshminarasimhaiah</strong> &mdash; an Electronics &amp; Communication Engineering graduate from Rajeev Gandhi Memorial College of Engineering and Technology (RGMCET), Nandyal, Andhra Pradesh. I am currently working as a <strong>STEM Engineer at StemX Indian Innovations Pvt. Ltd., Bengaluru</strong> (onsite, full-time), where I design and deliver hands-on STEM education programs and innovation workshops for students across India.</p>
          <p>My engineering journey spans embedded systems, IoT, VLSI design, cybersecurity and agri-tech &mdash; building real-world solutions from scratch. I represented RGMCET at the <strong>IEEE YESIST12 Grand Finale in Tunis, Tunisia</strong> (Sept 2024) and led my team to win at the <strong>Smart India Hackathon 2025</strong>. I also conduct free robotics and Arduino workshops at government schools under the Atal Innovation Mission.</p>
        </div>
        <div class="detail-grid">
          <div class="detail-item"><div class="d-icon">🎓</div><div><div class="d-label">Education</div><div class="d-val">B.Tech ECE &middot; RGMCET, Nandyal</div></div></div>
          <div class="detail-item"><div class="d-icon">🏢</div><div><div class="d-label">Current Role</div><div class="d-val">STEM Engineer &middot; StemX Pvt. Ltd., Bengaluru</div></div></div>
          <div class="detail-item"><div class="d-icon">📍</div><div><div class="d-label">Location</div><div class="d-val">Bengaluru, Karnataka, India</div></div></div>
          <div class="detail-item"><div class="d-icon">💼</div><div><div class="d-label">Past Experience</div><div class="d-val">Quality Engineer &middot; Schneider Electric, Anekal</div></div></div>
          <div class="detail-item"><div class="d-icon">🏠</div><div><div class="d-label">Home State</div><div class="d-val">Andhra Pradesh, India</div></div></div>
          <div class="detail-item"><div class="d-icon">🌐</div><div><div class="d-label">LinkedIn</div><div class="d-val"><a href="https://www.linkedin.com/in/lakshminarasimhaiah-kasimalla-432b4939b/" target="_blank">View Profile &#8599;</a></div></div></div>
        </div>
        <div class="soc-links">
          <a class="soc-btn li" href="https://www.linkedin.com/in/lakshminarasimhaiah-kasimalla-432b4939b/" target="_blank">in LinkedIn</a>
          <a class="soc-btn ig" href="https://www.instagram.com/captainkasimalla2003/" target="_blank">📷 @captainkasimalla2003</a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="container">
    <span class="sec-label" style="color:var(--gold);">Career Journey</span>
    <h2 class="sec-title light">Work <span>Experience</span></h2>
    <p class="sec-desc light">From virtual internships to international competitions and full-time industry roles &mdash; growing every step of the way.</p>

    <div class="tab-nav" id="expTabs">
      <button class="tab-btn active" data-tab="t-stemx">StemX (Current)</button>
      <button class="tab-btn" data-tab="t-schneider">Schneider Electric</button>
      <button class="tab-btn" data-tab="t-zf">ZF CVCS MNC</button>
      <button class="tab-btn" data-tab="t-training">Industrial Training</button>
    </div>

    <div class="tab-panel active" id="t-stemx">
      <div class="exp-card reveal">
        <div class="exp-header">
          <div>
            <div class="exp-title">🏫 STEM Engineer</div>
            <div class="exp-co">StemX Indian Innovations Pvt. Ltd. &middot; Bengaluru (Onsite, Full-Time)</div>
          </div>
          <div class="exp-period">2025 &ndash; Present</div>
        </div>
        <div class="exp-desc">
          StemX Indian Innovations Pvt. Ltd. is a leading STEM education company based in Bengaluru, dedicated to transforming how students across India engage with Science, Technology, Engineering, and Mathematics. As a <strong style="color:var(--teal)">STEM Engineer</strong>, I design and deliver comprehensive robotics, IoT, and electronics curriculum across schools and Atal Innovation Mission (AIM) Tinkering Labs in government and private schools.
        </div>
        <ul class="exp-ul">
          <li>Designed and delivered <strong>50+ interactive STEM workshop sessions</strong> across schools in Karnataka and Andhra Pradesh.</li>
          <li>Successfully trained and mentored over <strong>200+ students</strong> in robotics, Arduino, IoT, and electronics fundamentals.</li>
          <li>Developed innovative, curriculum-aligned project kits for middle and high school students focused on real-world problem solving.</li>
          <li>Established strong outreach programs at <strong>AIM Tinkering Labs</strong>, earning recognition for outstanding teaching methodology.</li>
          <li>Contributed to curriculum development and standardisation for STEM programs across multiple institutions.</li>
          <li>Expanded institutional outreach, building partnerships with 10+ schools and educational boards across South India.</li>
        </ul>
        <div class="exp-tags">
          <span class="exp-tag">STEM Education</span>
          <span class="exp-tag">Robotics</span>
          <span class="exp-tag">Arduino</span>
          <span class="exp-tag">IoT</span>
          <span class="exp-tag">Curriculum Design</span>
          <span class="exp-tag">AIM Tinkering Labs</span>
          <span class="exp-tag">Student Mentoring</span>
        </div>
      </div>
    </div>

    <div class="tab-panel" id="t-schneider">
      <div class="exp-card reveal">
        <div class="exp-header">
          <div>
            <div class="exp-title">🔧 Quality Engineer / Engineering Operator</div>
            <div class="exp-co">Schneider Electric &middot; Anekal, Bengaluru</div>
          </div>
          <div class="exp-period gold">Past Experience</div>
        </div>
        <div class="exp-desc">Gained invaluable hands-on experience at Schneider Electric, a world leader in energy management and industrial automation. Operated within automated assembly lines, enforced strict quality control processes, and maintained the highest standards of production quality for electrical components and switchgear manufacturing.</div>
        <div class="exp-tags">
          <span class="exp-tag">Quality Control</span>
          <span class="exp-tag">Manufacturing</span>
          <span class="exp-tag">Assembly Lines</span>
          <span class="exp-tag">Compliance</span>
          <span class="exp-tag">MNC Environment</span>
        </div>
      </div>
    </div>

    <div class="tab-panel" id="t-zf">
      <div class="exp-card reveal">
        <div class="exp-header">
          <div>
            <div class="exp-title">&#9881; Short Term Intern &mdash; Commercial Vehicle Control Systems</div>
            <div class="exp-co">ZF CVCS MNC &middot; Mahindra World City, Tamil Nadu</div>
          </div>
          <div class="exp-period green">2 Months &middot; After 3rd Year B.Tech</div>
        </div>
        <div class="exp-desc">Completed an intensive 2-month short-term internship at ZF CVCS MNC, located at Mahindra World City, Tamil Nadu, following my third year of B.Tech ECE. ZF is a globally renowned technology company specialising in driveline and chassis technology, and active and passive safety systems for commercial vehicles.</div>
        <ul class="exp-ul">
          <li>Hands-on exposure to <strong>Commercial Vehicle Control Systems (CVCS)</strong> and advanced vehicular electronics.</li>
          <li>Practical understanding of industrial manufacturing protocols, quality standards, and production workflows at a global MNC.</li>
          <li>Learned embedded control units, sensor interfacing, and automotive electronics used in commercial vehicles.</li>
          <li>Worked within a structured corporate engineering environment with cross-functional international teams.</li>
        </ul>
        <div class="exp-tags">
          <span class="exp-tag">Control Systems</span>
          <span class="exp-tag">Automotive Electronics</span>
          <span class="exp-tag">Manufacturing</span>
          <span class="exp-tag">Embedded Systems</span>
          <span class="exp-tag">Corporate MNC</span>
        </div>
      </div>
    </div>

    <div class="tab-panel" id="t-training">
      <div class="exp-card reveal">
        <div class="exp-header">
          <div>
            <div class="exp-title">💼 Industrial Trainee</div>
            <div class="exp-co">AVISHKARAN Pvt Ltd (MIVI) &middot; Thukkuguda Industrial Park, Telangana</div>
          </div>
          <div class="exp-period">6 Months &middot; Diploma Final Year</div>
        </div>
        <div class="exp-desc">Completed extensive industrial training in a leading Bluetooth audio device manufacturing company during my final year of Diploma. Gained deep expertise in consumer electronics manufacturing, PCB assembly, hardware testing, Bluetooth module integration, and QA testing protocols in a high-volume production environment.</div>
        <div class="exp-tags">
          <span class="exp-tag">Consumer Electronics</span>
          <span class="exp-tag">Hardware Assembly</span>
          <span class="exp-tag">QA Testing</span>
          <span class="exp-tag">PCB Assembly</span>
          <span class="exp-tag">Bluetooth Devices</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="container">
    <span class="sec-label">My Work</span>
    <h2 class="sec-title">Hardware <span>Projects</span></h2>
    <p class="sec-desc">A collection of physical hardware, IoT systems and embedded solutions developed throughout my academic and professional journey.</p>

    <div class="proj-grid">
      <!-- Vajra WPMS -->
      <div class="proj-card reveal">
        <div class="proj-img-wrap">
          <img alt="Vajra WPMS Prototype 1" loading="lazy" src="https://lh3.googleusercontent.com/d/1XyS_3sT5sN68k5hF_x05hL39VnS9aV-G"/>
          <div class="proj-badge">Hardware</div>
        </div>
        <div class="proj-body">
          <h4>Vajra WPMS &mdash; Wearable Posture Monitoring System</h4>
          <p>A real-time human body posture detecting and alerting wearable device. Uses flex sensors, accelerometers, and microcontrollers to detect incorrect sitting posture and alert the user. Developed a custom STM32-based second prototype with a purpose-built Bluetooth module for wireless data transmission and mobile app integration.</p>
          <div class="proj-techs">
            <span class="proj-tech">STM32</span>
            <span class="proj-tech">Flex Sensors</span>
            <span class="proj-tech">Accelerometer</span>
            <span class="proj-tech">Bluetooth</span>
            <span class="proj-tech">Embedded C</span>
          </div>
          <div class="proj-mini-gallery">
            <img alt="Second Prototype with STM32 Board" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T06c_H5BvK2-oF4-X2x6Hh6Q3cW7pM-l"/>
            <img alt="Developed Bluetooth Module" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/18Wn-ALLbotQEbl3exgpliszmK5Y-TyUm"/>
            <img alt="Vajra WPMS Prototype" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1XyS_3sT5sN68k5hF_x05hL39VnS9aV-G"/>
          </div>
        </div>
      </div>

      <!-- Smart Agriculture -->
      <div class="proj-card reveal delay-1">
        <div class="proj-img-wrap">
          <img alt="Smart Agriculture Automation Project" loading="lazy" src="https://lh3.googleusercontent.com/d/1NJklIpRgwjA4-taqHxJRMWSi7NlTb6qA"/>
          <div class="proj-badge gold">IoT &amp; App</div>
        </div>
        <div class="proj-body">
          <h4>Smart Agriculture Automation Project</h4>
          <p>An IoT-based system that monitors real-time field conditions including temperature, humidity, soil moisture, and rainfall. Transmits live data to farmers via a paired mobile application and automates irrigation based on sensor thresholds.</p>
          <div class="proj-techs">
            <span class="proj-tech">IoT</span>
            <span class="proj-tech">Sensors</span>
            <span class="proj-tech">Mobile App</span>
            <span class="proj-tech">NodeMCU</span>
            <span class="proj-tech">Cloud</span>
          </div>
        </div>
      </div>

      <!-- Classroom Automation -->
      <div class="proj-card reveal delay-2">
        <div class="proj-img-wrap">
          <img alt="Classroom Automation Diploma with Board Enhancements" loading="lazy" src="https://lh3.googleusercontent.com/d/1m-O1vZaD-FmisF6ZZc6nS-X2J74Co1kS"/>
          <div class="proj-badge">Automation</div>
        </div>
        <div class="proj-body">
          <h4>Classroom Automation through IoT</h4>
          <p>Acted as team lead to build an IoT-based classroom automation system with board enhancements, successfully deployed as a live working project on the college campus. Automates lighting, fans, and systems based on occupancy and timers, optimising energy usage.</p>
          <div class="proj-techs">
            <span class="proj-tech">IoT</span>
            <span class="proj-tech">Automation</span>
            <span class="proj-tech">PIR Sensors</span>
            <span class="proj-tech">ESP8266</span>
            <span class="proj-tech">Energy Saving</span>
          </div>
        </div>
      </div>

      <!-- Mini Quadcopter -->
      <div class="proj-card reveal delay-3">
        <div class="proj-img-wrap">
          <img alt="Mini Quadcopter Drone Build" loading="lazy" src="https://lh3.googleusercontent.com/d/1rL4imDyuWdLNbsh5jr2PBVNyjCVzVh72"/>
          <div class="proj-badge red">Robotics</div>
        </div>
        <div class="proj-body">
          <h4>Mini Quadcopter Drone</h4>
          <p>Built a functional working mini quadcopter drone model during 9th standard. Designed the frame, wired the motor controllers, configured the flight controller, and achieved stable hover flight &mdash; sparking a lifelong passion for embedded systems and robotics engineering.</p>
          <div class="proj-techs">
            <span class="proj-tech">Drones</span>
            <span class="proj-tech">Flight Controller</span>
            <span class="proj-tech">Aerodynamics</span>
            <span class="proj-tech">ESC</span>
            <span class="proj-tech">Brushless Motors</span>
          </div>
        </div>
      </div>

      <!-- IEEE YESIST12 -->
      <div class="proj-card reveal delay-4">
        <div class="proj-img-wrap">
          <img alt="IEEE YESIST12 Tunisia Grand Finale" loading="lazy" src="https://lh3.googleusercontent.com/d/1T2c_lxrRw-YR2jim6mF1h2tNDdkWt8Yi"/>
          <div class="proj-badge purple">IEEE</div>
        </div>
        <div class="proj-body">
          <h4>IEEE YESIST12 Grand Finale &mdash; Tunis, Tunisia</h4>
          <p>Represented RGMCET at the <strong>IEEE YESIST12 Grand Finale</strong> held in Tunis, Tunisia (September 2024). Presented a hardware innovation project on the international stage, competing against top engineering teams from across the globe in IEEE's prestigious student innovation challenge.</p>
          <div class="proj-techs">
            <span class="proj-tech">IEEE</span>
            <span class="proj-tech">International</span>
            <span class="proj-tech">Hardware Innovation</span>
            <span class="proj-tech">Tunisia 2024</span>
          </div>
        </div>
      </div>

      <!-- SIH 2025 -->
      <div class="proj-card reveal delay-5">
        <div class="proj-img-wrap">
          <img alt="Smart India Hackathon 2025 National Winner" loading="lazy" src="https://lh3.googleusercontent.com/d/1EBw5cZJIoFZapSc5EOvN44OQkAf2-95F"/>
          <div class="proj-badge gold">SIH Winner</div>
        </div>
        <div class="proj-body">
          <h4>Smart India Hackathon 2025 &mdash; National Winner</h4>
          <p>Led a team to victory at <strong>Smart India Hackathon 2025</strong>, India's premier national hackathon by the Government of India. The winning hardware prototype addressed a real government ministry problem statement, earning the team prize money and national recognition.</p>
          <div class="proj-techs">
            <span class="proj-tech">National Hackathon</span>
            <span class="proj-tech">Hardware Prototype</span>
            <span class="proj-tech">Team Lead</span>
            <span class="proj-tech">GoI</span>
          </div>
        </div>
      </div>

      <!-- More Projects CTA -->
      <div class="proj-more-card reveal">
        <div style="font-size:3rem;margin-bottom:1rem;">🚀</div>
        <h4 style="color:white;font-size:1.1rem;margin-bottom:.6rem;font-family:'Playfair Display',serif;">More Projects Loading...</h4>
        <p style="color:rgba(255,255,255,.55);font-size:.85rem;margin-bottom:1.5rem;line-height:1.65;max-width:300px;">I constantly build and experiment with new technologies. Daily project updates, tech builds and new learnings are posted on my LinkedIn.</p>
        <a class="btn btn-t" href="https://www.linkedin.com/in/lakshminarasimhaiah-kasimalla-432b4939b/" target="_blank">🔗 Follow on LinkedIn</a>
      </div>
    </div>
  </div>
</section>

<!-- ACHIEVEMENTS -->
<section id="achievements">
  <div class="container">
    <span class="sec-label">Awards &amp; Events</span>
    <h2 class="sec-title">Competitions &amp; <span>Achievements</span></h2>
    <p class="sec-desc">Hackathons, International Competitions, Symposiums, and Community Recognition.</p>

    <div class="ach-grid">
      <div class="ach-card reveal">
        <img alt="Smart India Hackathon Winner" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1EBw5cZJIoFZapSc5EOvN44OQkAf2-95F"/>
        <div class="ach-body">
          <div class="ach-icon">🏆</div>
          <h4>Smart India Hackathon 2025 &mdash; National Winner</h4>
          <p>Led the team to win prize money at SIH 2025, India's biggest national hackathon by Government of India. Our hardware prototype impressed the jury and earned national recognition.</p>
          <div class="ach-date">🏆 National Winner &middot; Prize Money Won</div>
        </div>
      </div>

      <div class="ach-card reveal delay-1">
        <img alt="College Award and Recognition" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1ZyUUeq0hkb73l5YngW0OZAdpGj0bc4s6"/>
        <div class="ach-body">
          <div class="ach-icon">🏅</div>
          <h4>College Award &amp; Recognition</h4>
          <p>Received recognition and award at a college-level event for outstanding academic and engineering achievement in electronics and innovation projects.</p>
          <div class="ach-date">🏅 Award Winner &middot; College Event</div>
        </div>
      </div>

      <div class="ach-card reveal delay-2">
        <img alt="College Project Exhibition Recognition" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1Lgyr2QXpxBDjOTDDNdduEJsPKmb05qNO"/>
        <div class="ach-body">
          <div class="ach-icon">🌟</div>
          <h4>College Project Exhibition Recognition</h4>
          <p>Received formal recognition and prizes for exceptional project exhibition and hardware prototype demonstration at the RGMCET technical symposium and project expo.</p>
          <div class="ach-date">🌟 Project Showcase Award</div>
        </div>
      </div>

      <div class="ach-card reveal delay-3">
        <img alt="Alumni Felicitation at Diploma College" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1aUJ7iZuH5_y-1zwc6L20Nwyqm3x8UrnS"/>
        <div class="ach-body">
          <div class="ach-icon">🎓</div>
          <h4>Alumni Felicitation &mdash; Diploma College</h4>
          <p>Invited as a distinguished guest of honour by my previous diploma college for the Alumni Function and formally felicitated by the faculty and principal for achievements post-diploma.</p>
          <div class="ach-date">🎓 Guest of Honour &middot; Alumni Function</div>
        </div>
      </div>

      <div class="ach-card reveal delay-4">
        <img alt="District Youth Fest Science Mela 1st Prize" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T2c_lxrRw-YR2jim6mF1h2tNDdkWt8Yi"/>
        <div class="ach-body">
          <div class="ach-icon">🥇</div>
          <h4>District Youth Fest Science Mela</h4>
          <p>Won the 1st Prize at the District Youth Fest Science Mela, presenting an innovative engineering project that impressed the district-level jury panel.</p>
          <div class="ach-date">🥇 1st Prize Winner</div>
        </div>
      </div>

      <div class="ach-card reveal delay-5">
        <img alt="IEEE YESIST12 International Grand Finale" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1aUJ7iZuH5_y-1zwc6L20Nwyqm3x8UrnS"/>
        <div class="ach-body">
          <div class="ach-icon">🌎</div>
          <h4>IEEE YESIST12 &mdash; International Grand Finale</h4>
          <p>Selected to represent RGMCET and competed at the IEEE YESIST12 Grand Finale in Tunis, Tunisia (September 2024) &mdash; a landmark international achievement in engineering innovation.</p>
          <div class="ach-date">🌎 International Finalist &middot; Tunis, Tunisia 2024</div>
        </div>
      </div>

      <div class="ach-card reveal">
        <img alt="Innovation Award Ceremony" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1ek-yQ1iRvRR3jLokxD0ZXj4WQqu848hN"/>
        <div class="ach-body">
          <div class="ach-icon">💡</div>
          <h4>Innovation Award Ceremony</h4>
          <p>Recognized for outstanding dedication to hardware innovation and technical excellence at an award ceremony celebrating contributions to engineering and student innovation.</p>
          <div class="ach-date">💡 Innovation Excellence Award</div>
        </div>
      </div>

      <div class="ach-card reveal delay-1">
        <img alt="Newspaper Media Recognition" class="ach-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1_7GOhD8AHd0kF3o7dkgte3d91UsRZfCU"/>
        <div class="ach-body">
          <div class="ach-icon">📰</div>
          <h4>Newspaper Media Recognition</h4>
          <p>Featured in local newspaper media for outstanding performance in the Smart India Hackathon and engineering achievements, bringing recognition to RGMCET and the region.</p>
          <div class="ach-date">📰 Media Coverage &middot; Local Newspaper</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CERTIFICATIONS -->
<section id="certifications">
  <div class="container">
    <span class="sec-label" style="color:var(--gold);">Credentials</span>
    <h2 class="sec-title light">Licenses &amp; <span>Certifications</span></h2>
    <p class="sec-desc light">Professional credentials validating expertise in Embedded Systems, IoT, VLSI, and professional development.</p>

    <div class="cert-grid">
      <div class="cert-card reveal">
        <img alt="Embedded Systems Developer Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1ecGrPUA2-ppQVI12LeCrgsGGOQRKftd_"/>
        <div class="cert-body">
          <h5>Embedded Systems Developer</h5>
          <p>Rigorous 10-week virtual internship on Microchip Embedded System architecture, microcontroller programming and hardware interfacing.</p>
          <div class="cert-issuer">🏅 Virtual Internship &middot; Microchip Technology</div>
        </div>
      </div>

      <div class="cert-card reveal delay-1">
        <img alt="NPTEL Introduction to IoT Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1oE7TqNci-BzpCmH6lUeKUkiuwBAnWwSG"/>
        <div class="cert-body">
          <h5>Introduction to Internet of Things</h5>
          <p>Achieved Elite Grade in NPTEL IoT certification. Covers sensor integration, IoT protocols, cloud connectivity and network architecture.</p>
          <div class="cert-issuer">&#11088; NPTEL &middot; Elite Grade</div>
        </div>
      </div>

      <div class="cert-card reveal delay-2">
        <img alt="Soft Skills and Personality Development Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1b1hF-qxwyXxzpQa-fjYWlgtdQTq6v74F"/>
        <div class="cert-body">
          <h5>Soft Skills &amp; Personality Development</h5>
          <p>Elite credential reflecting strong communication, leadership, professional networking and interpersonal skills for engineering careers.</p>
          <div class="cert-issuer">&#11088; NPTEL &middot; Elite Grade</div>
        </div>
      </div>

      <div class="cert-card reveal delay-3">
        <img alt="District Youth Fest Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T2c_lxrRw-YR2jim6mF1h2tNDdkWt8Yi"/>
        <div class="cert-body">
          <h5>District Youth Fest &mdash; 1st Prize Certificate</h5>
          <p>First prize certificate from the District Youth Fest Science Mela for outstanding science and engineering project presentation at district level.</p>
          <div class="cert-issuer">🥇 District Level &middot; 1st Prize</div>
        </div>
      </div>

      <div class="cert-card reveal delay-4">
        <img alt="Smart India Hackathon Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1EBw5cZJIoFZapSc5EOvN44OQkAf2-95F"/>
        <div class="cert-body">
          <h5>Smart India Hackathon 2025 &mdash; Winner Certificate</h5>
          <p>National winner certificate from Smart India Hackathon 2025, organised by the Government of India.</p>
          <div class="cert-issuer">🏆 Government of India &middot; National Winner</div>
        </div>
      </div>

      <div class="cert-card reveal delay-5">
        <img alt="IEEE YESIST12 Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1aUJ7iZuH5_y-1zwc6L20Nwyqm3x8UrnS"/>
        <div class="cert-body">
          <h5>IEEE YESIST12 Participation Certificate</h5>
          <p>Official participation and finalist certificate from IEEE YESIST12 Grand Finale, Tunis, Tunisia, September 2024.</p>
          <div class="cert-issuer">🌎 IEEE YESIST12 &middot; Tunisia 2024</div>
        </div>
      </div>

      <div class="cert-card reveal">
        <img alt="College Project Excellence Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1Lgyr2QXpxBDjOTDDNdduEJsPKmb05qNO"/>
        <div class="cert-body">
          <h5>College Project Exhibition Certificate</h5>
          <p>Certificate for excellence in project exhibition at the RGMCET technical symposium and project expo.</p>
          <div class="cert-issuer">🏅 RGMCET &middot; Technical Symposium</div>
        </div>
      </div>

      <div class="cert-card reveal delay-1">
        <img alt="Innovation Award Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1ek-yQ1iRvRR3jLokxD0ZXj4WQqu848hN"/>
        <div class="cert-body">
          <h5>Hardware Innovation Award Certificate</h5>
          <p>Awarded for outstanding dedication to hardware innovation and technical excellence at the innovation award ceremony.</p>
          <div class="cert-issuer">💡 Innovation Excellence &middot; Award Ceremony</div>
        </div>
      </div>

      <div class="cert-card reveal delay-2">
        <img alt="Industrial Training Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1rL4imDyuWdLNbsh5jr2PBVNyjCVzVh72"/>
        <div class="cert-body">
          <h5>Industrial Training Certificate &mdash; MIVI</h5>
          <p>Certificate for successful 6-month industrial training completion at AVISHKARAN Pvt. Ltd. (MIVI), Thukkuguda, Telangana.</p>
          <div class="cert-issuer">🏅 AVISHKARAN Pvt. Ltd. &middot; Industrial Training</div>
        </div>
      </div>

      <div class="cert-card reveal delay-3">
        <img alt="STEM Workshop Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1xsq1d4tOUzIXQALuWktML7TM_6v8utgz"/>
        <div class="cert-body">
          <h5>STEM Workshop Facilitation Certificate</h5>
          <p>Certified for facilitating Arduino and robotics workshops at government schools under the AIM Tinkering Lab initiative.</p>
          <div class="cert-issuer">🏅 AIM &middot; Tinkering Lab Initiative</div>
        </div>
      </div>

      <div class="cert-card reveal delay-4">
        <img alt="Community Outreach Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1MGij_jtEkdIbHwLTwNM4GVmoqvssXtSO"/>
        <div class="cert-body">
          <h5>Community Outreach Recognition</h5>
          <p>Recognition for impactful community STEM outreach and hands-on engineering education delivered to government school students.</p>
          <div class="cert-issuer">🏅 Community &middot; STEM Outreach</div>
        </div>
      </div>

      <div class="cert-card reveal delay-5">
        <img alt="ZPHS School Workshop Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T7b8vlx4erzRZIHykeuHJvUdFAwSky_r"/>
        <div class="cert-body">
          <h5>ZPHS School Workshop Certificate</h5>
          <p>Certificate for conducting successful Arduino project workshops at ZPHS Panyam school with student gift distribution event.</p>
          <div class="cert-issuer">🏅 ZPHS Panyam &middot; Workshop Event</div>
        </div>
      </div>

      <div class="cert-card reveal">
        <img alt="Classroom Automation Project Certificate" class="cert-img" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1m-O1vZaD-FmisF6ZZc6nS-X2J74Co1kS"/>
        <div class="cert-body">
          <h5>Classroom Automation Project Certificate</h5>
          <p>Recognition for successfully implementing and deploying a live IoT-based classroom automation system at the college campus.</p>
          <div class="cert-issuer">🏅 RGMCET &middot; Live Project Deployment</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- OUTREACH -->
<section id="outreach">
  <div class="container">
    <span class="sec-label">Community</span>
    <h2 class="sec-title">STEM <span>Outreach</span></h2>
    <p class="sec-desc">Empowering students through free hands-on robotics, Arduino, and electronics workshops at government schools.</p>

    <div class="out-grid">
      <div class="out-card reveal">
        <div class="out-img-grid">
          <img alt="Nandikotkuru Govt School Outreach" class="full" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1Lgyr2QXpxBDjOTDDNdduEJsPKmb05qNO"/>
        </div>
        <div class="out-body">
          <h4>Nandikotkuru Government School</h4>
          <p>Conducted extensive robotics sessions guiding young minds in building foundational STEM skills. Students were introduced to microcontrollers, sensors, and basic circuit design in a fully hands-on environment.</p>
          <div class="out-tag">🤖 Robotics Workshop</div>
        </div>
      </div>

      <div class="out-card reveal delay-1">
        <div class="out-img-grid">
          <img alt="Panyam School Outreach 1" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1xsq1d4tOUzIXQALuWktML7TM_6v8utgz"/>
          <img alt="Panyam School Outreach 2" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1MGij_jtEkdIbHwLTwNM4GVmoqvssXtSO"/>
        </div>
        <div class="out-body">
          <h4>Panyam Government School</h4>
          <p>Led hands-on Arduino and robotics training for government school students, making technology accessible for children from rural backgrounds. Students successfully built their first electronic projects.</p>
          <div class="out-tag">🖌 Arduino Training</div>
        </div>
      </div>

      <div class="out-card reveal delay-2">
        <div class="out-img-grid">
          <img alt="ZPHS Panyam Workshop" class="full" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T7b8vlx4erzRZIHykeuHJvUdFAwSky_r"/>
        </div>
        <div class="out-body">
          <h4>ZPHS School Panyam</h4>
          <p>Successfully conducted an Arduino projects workshop and distributed gifts to enthusiastic participants. The event inspired students to explore electronics and consider engineering as a career.</p>
          <div class="out-tag">🎉 Community Event</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery">
  <div class="container">
    <span class="sec-label" style="color:var(--gold);">Moments</span>
    <h2 class="sec-title light">Events &amp; <span>Gallery</span></h2>
    <p class="sec-desc light">A visual diary of my journey &mdash; international competitions, hackathons, STEM workshops, certifications, and memorable team moments.</p>

    <div class="gallery-masonry">
      <img alt="Profile Picture" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1e7JPCwR0oJsz_thRCHAiIxQb4nnKNzG7"/>
      <img alt="College Award Event" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1ZyUUeq0hkb73l5YngW0OZAdpGj0bc4s6"/>
      <img alt="Schneider Electric Formal Photo" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/17JIDOk5rmJYmoNO6oh2CnyzUBS5DzvEU"/>
      <img alt="Schneider Internship" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1rL4imDyuWdLNbsh5jr2PBVNyjCVzVh72"/>
      <img alt="Vajra WPMS Prototype" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1XyS_3sT5sN68k5hF_x05hL39VnS9aV-G"/>
      <img alt="STM32 Board Prototype" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T06c_H5BvK2-oF4-X2x6Hh6Q3cW7pM-l"/>
      <img alt="Bluetooth Module for STM32" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/18Wn-ALLbotQEbl3exgpliszmK5Y-TyUm"/>
      <img alt="Smart Agriculture Project" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1NJklIpRgwjA4-taqHxJRMWSi7NlTb6qA"/>
      <img alt="Classroom Automation" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1m-O1vZaD-FmisF6ZZc6nS-X2J74Co1kS"/>
      <img alt="Smart India Hackathon Team Prize" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1EBw5cZJIoFZapSc5EOvN44OQkAf2-95F"/>
      <img alt="District Youth Fest Science Mela" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T2c_lxrRw-YR2jim6mF1h2tNDdkWt8Yi"/>
      <img alt="Alumni Felicitation Event" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1aUJ7iZuH5_y-1zwc6L20Nwyqm3x8UrnS"/>
      <img alt="College Project Recognition" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1Lgyr2QXpxBDjOTDDNdduEJsPKmb05qNO"/>
      <img alt="Innovation Award Ceremony" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1ek-yQ1iRvRR3jLokxD0ZXj4WQqu848hN"/>
      <img alt="Newspaper Media Coverage" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1_7GOhD8AHd0kF3o7dkgte3d91UsRZfCU"/>
      <img alt="Embedded Systems Certificate" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1ecGrPUA2-ppQVI12LeCrgsGGOQRKftd_"/>
      <img alt="NPTEL IoT Elite Certificate" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1oE7TqNci-BzpCmH6lUeKUkiuwBAnWwSG"/>
      <img alt="Soft Skills NPTEL Certificate" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1b1hF-qxwyXxzpQa-fjYWlgtdQTq6v74F"/>
      <img alt="STEM Outreach Panyam 1" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1xsq1d4tOUzIXQALuWktML7TM_6v8utgz"/>
      <img alt="STEM Outreach Panyam 2" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1MGij_jtEkdIbHwLTwNM4GVmoqvssXtSO"/>
      <img alt="ZPHS Panyam Workshop" class="reveal" loading="lazy" onclick="openLB(this.src)" src="https://lh3.googleusercontent.com/d/1T7b8vlx4erzRZIHykeuHJvUdFAwSky_r"/>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="container">
    <div class="contact-grid">
      <div class="reveal-left">
        <span class="sec-label">Get in Touch</span>
        <h2 class="sec-title">Let's <span>Connect</span></h2>
        <p class="sec-desc">Open for collaborations, tech discussions, STEM education projects, and new opportunities in Electronics and Innovation.</p>
        <div class="c-items">
          <div class="c-item">
            <div class="c-icon" style="color:white;">📧</div>
            <div>
              <div class="c-label">Email</div>
              <div class="c-val"><a href="mailto:klnarasimhaiah2008@gmail.com">klnarasimhaiah2008@gmail.com</a></div>
            </div>
          </div>
          <div class="c-item">
            <div class="c-icon" style="color:white;">📞</div>
            <div>
              <div class="c-label">Phone</div>
              <div class="c-val">+91 9390904116</div>
            </div>
          </div>
          <div class="c-item">
            <div class="c-icon" style="color:white;">📍</div>
            <div>
              <div class="c-label">Address</div>
              <div class="c-val">9-19, Weavers Colony, Bandiatmakur, Nandyal, 518523, Andhra Pradesh</div>
            </div>
          </div>
          <div class="c-item">
            <div class="c-icon" style="color:white;">🌐</div>
            <div>
              <div class="c-label">LinkedIn</div>
              <div class="c-val"><a href="https://www.linkedin.com/in/lakshminarasimhaiah-kasimalla-432b4939b/" target="_blank">View LinkedIn Profile &#8599;</a></div>
            </div>
          </div>
          <div class="c-item">
            <div class="c-icon" style="color:white;">📷</div>
            <div>
              <div class="c-label">Instagram</div>
              <div class="c-val"><a href="https://www.instagram.com/captainkasimalla2003/" target="_blank">@captainkasimalla2003 &#8599;</a></div>
            </div>
          </div>
        </div>
      </div>
      <div class="reveal-right">
        <div class="contact-form">
          <h4>Send a Message</h4>
          <div class="fg">
            <label>Name</label>
            <input placeholder="Your Name" type="text"/>
          </div>
          <div class="fg">
            <label>Email</label>
            <input placeholder="Your Email" type="email"/>
          </div>
          <div class="fg">
            <label>Message</label>
            <textarea placeholder="How can I help you?"></textarea>
          </div>
          <button class="f-submit" onclick="alert('Thank you! Please email directly: klnarasimhaiah2008@gmail.com')" type="button">Send Message &#8594;</button>
        </div>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="container">
    <p>&copy; 2026 <span>Kasimalla Lakshminarasimhaiah</span>. All Rights Reserved. &middot; ECE Engineer &amp; STEM Innovator &middot; Bengaluru, India</p>
  </div>
</footer>

<script>
// Mobile nav toggle
var navToggle = document.getElementById('navToggle');
var navLinks  = document.getElementById('navLinks');
navToggle.addEventListener('click', function() {
  navLinks.classList.toggle('open');
});
document.querySelectorAll('.nav-links a').forEach(function(a) {
  a.addEventListener('click', function() { navLinks.classList.remove('open'); });
});

// Lightbox
function openLB(src) {
  document.getElementById('lb-img').src = src;
  document.getElementById('lb').classList.add('open');
}
function closeLB() {
  document.getElementById('lb').classList.remove('open');
  document.getElementById('lb-img').src = '';
}
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') closeLB();
});

// Scroll reveal
function reveal() {
  document.querySelectorAll('.reveal, .reveal-left, .reveal-right').forEach(function(el) {
    if (el.getBoundingClientRect().top < window.innerHeight - 90) {
      el.classList.add('visible');
    }
  });
}
window.addEventListener('scroll', reveal);
reveal();

// Experience tabs
document.querySelectorAll('.tab-btn').forEach(function(btn) {
  btn.addEventListener('click', function() {
    document.querySelectorAll('.tab-btn').forEach(function(b) { b.classList.remove('active'); });
    document.querySelectorAll('.tab-panel').forEach(function(p) { p.classList.remove('active'); });
    this.classList.add('active');
    var panel = document.getElementById(this.getAttribute('data-tab'));
    if (panel) panel.classList.add('active');
  });
});

// Active nav link on scroll
window.addEventListener('scroll', function() {
  var pos = window.scrollY + 80;
  document.querySelectorAll('section[id]').forEach(function(sec) {
    if (pos >= sec.offsetTop && pos < sec.offsetTop + sec.offsetHeight) {
      document.querySelectorAll('.nav-links a').forEach(function(a) {
        a.classList.remove('active');
        if (a.getAttribute('href') === '#' + sec.id) a.classList.add('active');
      });
    }
  });
});
</script>

</body>
</html>
