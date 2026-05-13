<!doctype html>

<html lang="ko">

<head>

&#x20; <meta charset="utf-8" />

&#x20; <meta name="viewport" content="width=device-width, initial-scale=1" />

&#x20; <title>김민지 | Portfolio</title>

&#x20; <meta name="description" content="김민지 포트폴리오 — AI 영상·영화 제작, 콘텐츠 기획/디자인" />



&#x20; <link rel="preconnect" href="https://fonts.googleapis.com" />

&#x20; <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />

&#x20; <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;600;700;800\&display=swap" rel="stylesheet" />



&#x20; <style>

&#x20;   :root{

&#x20;     --main:#0018FF;

&#x20;     --bg:#ffffff;

&#x20;     --text:#111111;

&#x20;     --muted:#555;

&#x20;     --gray:#f5f7fb;

&#x20;     --card:#ffffff;

&#x20;     --border:rgba(0,0,0,0.08);

&#x20;     --shadow:0 10px 40px rgba(0,0,0,0.06);

&#x20;     --radius:28px;

&#x20;     --container:1120px;

&#x20;   }



&#x20;   \*{margin:0;padding:0;box-sizing:border-box}

&#x20;   html{scroll-behavior:smooth}

&#x20;   body{

&#x20;     font-family:"Noto Sans KR", system-ui, -apple-system, Segoe UI, Roboto, sans-serif;

&#x20;     background:var(--bg);

&#x20;     color:var(--text);

&#x20;     line-height:1.7;

&#x20;     overflow-x:hidden;

&#x20;   }

&#x20;   a{color:inherit}

&#x20;   ul{list-style:none}



&#x20;   .container{

&#x20;     width:min(var(--container), 100%);

&#x20;     margin:0 auto;

&#x20;     padding:0 10%;

&#x20;   }



&#x20;   /\* Top nav \*/

&#x20;   .topbar{

&#x20;     position:fixed;

&#x20;     inset:0 0 auto 0;

&#x20;     z-index:50;

&#x20;     padding:14px 0;

&#x20;     background:rgba(255,255,255,0.65);

&#x20;     border-bottom:1px solid rgba(0,0,0,0.06);

&#x20;     backdrop-filter: blur(10px);

&#x20;   }

&#x20;   .topbar .inner{

&#x20;     width:min(var(--container), 100%);

&#x20;     margin:0 auto;

&#x20;     padding:0 10%;

&#x20;     display:flex;

&#x20;     align-items:center;

&#x20;     justify-content:space-between;

&#x20;     gap:14px;

&#x20;   }

&#x20;   .brand{

&#x20;     font-weight:800;

&#x20;     letter-spacing:-0.02em;

&#x20;   }

&#x20;   .nav{

&#x20;     display:flex;

&#x20;     gap:16px;

&#x20;     flex-wrap:wrap;

&#x20;     justify-content:flex-end;

&#x20;   }

&#x20;   .nav a{

&#x20;     text-decoration:none;

&#x20;     font-weight:600;

&#x20;     font-size:14px;

&#x20;     color:#222;

&#x20;     padding:8px 10px;

&#x20;     border-radius:999px;

&#x20;   }

&#x20;   .nav a:hover{

&#x20;     background:rgba(0,0,0,0.06);

&#x20;   }



&#x20;   /\* Sections \*/

&#x20;   section{padding:120px 0}

&#x20;   .section-title{

&#x20;     font-size:44px;

&#x20;     font-weight:900;

&#x20;     letter-spacing:-0.03em;

&#x20;     color:var(--main);

&#x20;     margin-bottom:18px;

&#x20;   }

&#x20;   .section-desc{

&#x20;     font-size:18px;

&#x20;     color:var(--muted);

&#x20;     margin-bottom:56px;

&#x20;     max-width:820px;

&#x20;   }



&#x20;   /\* Hero \*/

&#x20;   header.hero{

&#x20;     min-height:100vh;

&#x20;     display:flex;

&#x20;     align-items:center;

&#x20;     position:relative;

&#x20;     overflow:hidden;

&#x20;     background:linear-gradient(135deg,#0018FF 0%,#0f2dff 40%,#ffffff 100%);

&#x20;     color:#fff;

&#x20;     padding-top:84px; /\* for fixed topbar \*/

&#x20;   }

&#x20;   header.hero::after{

&#x20;     content:"";

&#x20;     position:absolute;

&#x20;     width:620px;height:620px;

&#x20;     background:rgba(255,255,255,0.10);

&#x20;     border-radius:999px;

&#x20;     right:-220px;top:-160px;

&#x20;   }

&#x20;   .hero-grid{

&#x20;     display:grid;

&#x20;     grid-template-columns: 1.3fr 0.7fr;

&#x20;     gap:36px;

&#x20;     align-items:center;

&#x20;     position:relative;

&#x20;     z-index:1;

&#x20;   }

&#x20;   .hero h1{

&#x20;     font-size:72px;

&#x20;     font-weight:900;

&#x20;     line-height:1.08;

&#x20;     letter-spacing:-0.04em;

&#x20;     margin-bottom:22px;

&#x20;   }

&#x20;   .hero p{

&#x20;     font-size:20px;

&#x20;     opacity:0.95;

&#x20;     max-width:760px;

&#x20;     margin-bottom:30px;

&#x20;   }



&#x20;   .cta-row{

&#x20;     display:flex;

&#x20;     gap:12px;

&#x20;     flex-wrap:wrap;

&#x20;     align-items:center;

&#x20;     margin-top:6px;

&#x20;   }



&#x20;   .btn{

&#x20;     display:inline-flex;

&#x20;     align-items:center;

&#x20;     justify-content:center;

&#x20;     gap:10px;

&#x20;     padding:14px 20px;

&#x20;     border-radius:999px;

&#x20;     text-decoration:none;

&#x20;     font-weight:700;

&#x20;     transition:0.2s ease;

&#x20;     border:1px solid rgba(255,255,255,0.28);

&#x20;     backdrop-filter: blur(10px);

&#x20;   }

&#x20;   .btn.primary{

&#x20;     background:#fff;

&#x20;     color:var(--main);

&#x20;     border-color:#fff;

&#x20;   }

&#x20;   .btn.primary:hover{transform: translateY(-1px)}

&#x20;   .btn.ghost{

&#x20;     color:#fff;

&#x20;     background:rgba(255,255,255,0.08);

&#x20;   }

&#x20;   .btn.ghost:hover{background:rgba(255,255,255,0.14)}



&#x20;   .hero-card{

&#x20;     background:rgba(255,255,255,0.10);

&#x20;     border:1px solid rgba(255,255,255,0.22);

&#x20;     border-radius:24px;

&#x20;     padding:22px;

&#x20;     backdrop-filter: blur(12px);

&#x20;     display:flex;

&#x20;     flex-direction:column;

&#x20;     align-items:center;

&#x20;     text-align:center;

&#x20;   }

&#x20;   .hero-card .label{

&#x20;     font-weight:800;

&#x20;     opacity:0.9;

&#x20;     margin-bottom:10px;

&#x20;   }

&#x20;   .hero-card .mini{

&#x20;     opacity:0.92;

&#x20;     font-size:14px;

&#x20;     line-height:1.6;

&#x20;   }



&#x20;   /\* hero image (transparent PNG) \*/

&#x20;   .hero-photo{

&#x20;     width:180px;

&#x20;     aspect-ratio:1/1;

&#x20;     border-radius:999px; /\* 원형 \*/

&#x20;     object-fit:cover;

&#x20;     border:1px solid rgba(255,255,255,0.28);

&#x20;     box-shadow:0 10px 30px rgba(0,0,0,0.12);

&#x20;     margin-bottom:14px;

&#x20;   }



&#x20;   /\* About / Tools grid \*/

&#x20;   .grid-2{

&#x20;     display:grid;

&#x20;     grid-template-columns: 1fr 1fr;

&#x20;     gap:30px;

&#x20;   }

&#x20;   .card{

&#x20;     background:var(--card);

&#x20;     border:1px solid var(--border);

&#x20;     box-shadow:var(--shadow);

&#x20;     border-radius:var(--radius);

&#x20;     padding:34px;

&#x20;   }

&#x20;   .card h3{

&#x20;     font-size:26px;

&#x20;     letter-spacing:-0.02em;

&#x20;     margin-bottom:18px;

&#x20;     color:var(--main);

&#x20;   }

&#x20;   .card li{

&#x20;     margin-bottom:12px;

&#x20;     color:#222;

&#x20;     font-size:16px;

&#x20;   }

&#x20;   .keyword-wrap{

&#x20;     display:flex;

&#x20;     flex-wrap:wrap;

&#x20;     gap:10px;

&#x20;     margin-top:8px;

&#x20;   }

&#x20;   .keyword{

&#x20;     padding:10px 14px;

&#x20;     border-radius:999px;

&#x20;     background:var(--main);

&#x20;     color:#fff;

&#x20;     font-weight:800;

&#x20;     font-size:14px;

&#x20;     letter-spacing:-0.01em;

&#x20;   }



&#x20;   /\* Career \*/

&#x20;   section.career{background:var(--gray)}

&#x20;   .timeline{

&#x20;     display:flex;

&#x20;     flex-direction:column;

&#x20;     gap:18px;

&#x20;   }

&#x20;   .timeline-item{

&#x20;     background:#fff;

&#x20;     border:1px solid var(--border);

&#x20;     border-left:6px solid var(--main);

&#x20;     border-radius:22px;

&#x20;     padding:26px 26px;

&#x20;     box-shadow:0 6px 24px rgba(0,0,0,0.04);

&#x20;   }

&#x20;   .timeline-item h3{

&#x20;     font-size:20px;

&#x20;     margin-bottom:10px;

&#x20;     color:var(--main);

&#x20;     letter-spacing:-0.02em;

&#x20;   }

&#x20;   .timeline-item p{color:#333}



&#x20;   /\* Project \*/

&#x20;   section.project{

&#x20;     background:#0a0a0a;

&#x20;     color:#fff;

&#x20;     position:relative;

&#x20;     overflow:hidden;

&#x20;   }

&#x20;   section.project::before{

&#x20;     content:"CINEPHIL";

&#x20;     position:absolute;

&#x20;     right:-60px; top:26px;

&#x20;     font-size:170px;

&#x20;     font-weight:900;

&#x20;     color:rgba(255,255,255,0.04);

&#x20;     letter-spacing:-8px;

&#x20;     pointer-events:none;

&#x20;     user-select:none;

&#x20;   }

&#x20;   section.project .section-title{color:#fff}

&#x20;   section.project .section-desc{color:#d7d7d7}

&#x20;   .quote{

&#x20;     margin-top:28px;

&#x20;     font-size:28px;

&#x20;     font-weight:900;

&#x20;     letter-spacing:-0.02em;

&#x20;     line-height:1.45;

&#x20;     color:#fff;

&#x20;     max-width:820px;

&#x20;   }

&#x20;   .project-card{

&#x20;     background:rgba(255,255,255,0.05);

&#x20;     border:1px solid rgba(255,255,255,0.10);

&#x20;     border-radius:26px;

&#x20;     padding:32px;

&#x20;     backdrop-filter: blur(12px);

&#x20;   }

&#x20;   .project-card h3{

&#x20;     font-size:24px;

&#x20;     margin-bottom:12px;

&#x20;     letter-spacing:-0.02em;

&#x20;   }

&#x20;   .project-card p{color:#d6d6d6;margin-bottom:12px}



&#x20;   /\* Footer \*/

&#x20;   footer.footer{

&#x20;     padding:70px 0;

&#x20;     background:var(--main);

&#x20;     color:#fff;

&#x20;     text-align:center;

&#x20;   }

&#x20;   footer.footer h2{

&#x20;     font-size:40px;

&#x20;     font-weight:900;

&#x20;     letter-spacing:-0.03em;

&#x20;     margin-bottom:12px;

&#x20;   }

&#x20;   footer.footer p{opacity:0.92}



&#x20;   /\* Accessibility: reduced motion \*/

&#x20;   @media (prefers-reduced-motion: reduce){

&#x20;     html{scroll-behavior:auto}

&#x20;     .btn{transition:none}

&#x20;     .btn.primary:hover{transform:none}

&#x20;   }



&#x20;   /\* Responsive \*/

&#x20;   @media (max-width: 960px){

&#x20;     .container, .topbar .inner{padding:0 7%}

&#x20;     .hero-grid{grid-template-columns: 1fr}

&#x20;     .hero h1{font-size:48px}

&#x20;     .hero p{font-size:18px}

&#x20;     .grid-2{grid-template-columns:1fr}

&#x20;     .section-title{font-size:34px}

&#x20;     section{padding:92px 0}

&#x20;     .quote{font-size:22px}

&#x20;     section.project::before{font-size:120px}

&#x20;     .hero-photo{width:150px}

&#x20;   }

&#x20; </style>

</head>



<body>

&#x20; <div class="topbar">

&#x20;   <div class="inner">

&#x20;     <div class="brand">김민지</div>

&#x20;     <nav class="nav" aria-label="페이지 내 이동">

&#x20;       <a href="#about">About</a>

&#x20;       <a href="#experience">Experience</a>

&#x20;       <a href="#project">Project</a>

&#x20;       <a href="#tools">Tools</a>

&#x20;     </nav>

&#x20;   </div>

&#x20; </div>



&#x20; <header class="hero" role="banner">

&#x20;   <div class="container">

&#x20;     <div class="hero-grid">

&#x20;       <div>

&#x20;         <h1>

&#x20;           끊이지 않는 호기심을<br />

&#x20;           결과물로 증명합니다.

&#x20;         </h1>



&#x20;         <p>

&#x20;           방송국, 신문사를 거쳐 현재는 AI와 실사 영화를 제작하고 있습니다.

&#x20;           다양한 분야를 경험하며 세상을 이해하고,

&#x20;           결국 사람들의 이야기를 더 깊게 연결하는 콘텐츠를 만들고 싶습니다.

&#x20;         </p>



&#x20;         <div class="cta-row">

&#x20;           <!-- 상단 이메일 버튼 -->

&#x20;           <a

&#x20;             class="btn primary"

&#x20;             href="mailto:maymay0518@naver.com?subject=%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EC%9D%98%EB%AC%B8\&body=%EC%95%88%EB%85%95%ED%95%98%EC%84%B8%EC%9A%94.%0A%0A%EA%B3%84%EC%8B%A0%20%EC%9A%94%EC%B2%AD%EC%9E%A5%EC%9D%B4%20%EC%97%86%EC%9C%BC%EB%A9%B4%20%EC%B2%AD%ED%95%98%EC%8B%A4%20%EC%95%84%EB%8B%B4%20%EB%94%B0%EA%B3%A0%20%EC%B0%BE%EC%95%84%EB%93%A4%20%EA%B2%8C%EC%20%EC%9D%98%ED%95%9C%20%EC%98%88%EC%8B%A0%EC%9D%84%20%EC%9E%91%EC%84%B1%20%ED%95%A9%EB%8B%88%EB%8B%A4.%0A%0A%EC%9B%90%ED%95%98%EB%8A%94%20%EC%82%AC%ED%95%AD%EC%9D%84%20%EC%93%B0%EC%96%B4%EC%A3%A0%EC%84%B8%EC%9A%94."

&#x20;           >

&#x20;             이메일로 연락하기

&#x20;           </a>



&#x20;           <a class="btn ghost" href="#about">더 보기 ↓</a>

&#x20;         </div>

&#x20;       </div>



&#x20;       <aside class="hero-card" aria-label="한 줄 요약">

&#x20;         <img

&#x20;           src="minji kim.jpg"

&#x20;           alt="김민지 프로필 사진"

&#x20;           class="hero-photo"

&#x20;         />



&#x20;         <div class="label">Now</div>

&#x20;         <div class="mini">

&#x20;           AI 영상 · 영화 제작<br />

&#x20;           콘텐츠 기획 / 디자인<br />

&#x20;           마케팅 · 브랜딩 관심

&#x20;         </div>

&#x20;       </aside>

&#x20;     </div>

&#x20;   </div>

&#x20; </header>



&#x20; <main id="main-content">

&#x20;   <section id="about" aria-labelledby="about-title">

&#x20;     <div class="container">

&#x20;       <h2 id="about-title" class="section-title">ABOUT ME</h2>

&#x20;       <p class="section-desc">

&#x20;         사회학과 영화, 그리고 AI 기술을 함께 탐구하며

&#x20;         사람과 콘텐츠를 연결하는 새로운 방식을 고민하고 있습니다.

&#x20;       </p>



&#x20;       <div class="grid-2">

&#x20;         <article class="card">

&#x20;           <h3>기본 정보</h3>

&#x20;           <ul>

&#x20;             <li>한양대학교 사회학과 재학</li>

&#x20;             <li>연극영화학과 다중전공</li>

&#x20;             <li>AI 영상 · 영화 제작</li>

&#x20;             <li>콘텐츠 기획 및 디자인</li>

&#x20;             <li>마케팅/브랜딩 관심</li>

&#x20;           </ul>

&#x20;         </article>



&#x20;         <article class="card">

&#x20;           <h3>나의 키워드</h3>

&#x20;           <div class="keyword-wrap" aria-label="핵심 키워드">

&#x20;             <span class="keyword">기획</span>

&#x20;             <span class="keyword">AI 영상</span>

&#x20;             <span class="keyword">영화 제작</span>

&#x20;             <span class="keyword">콘텐츠</span>

&#x20;             <span class="keyword">디자인</span>

&#x20;             <span class="keyword">리더십</span>

&#x20;             <span class="keyword">실행력</span>

&#x20;             <span class="keyword">스토리텔링</span>

&#x20;           </div>

&#x20;         </article>

&#x20;       </div>

&#x20;     </div>

&#x20;   </section>



&#x20;   <section class="career" id="experience" aria-labelledby="experience-title">

&#x20;     <div class="container">

&#x20;       <h2 id="experience-title" class="section-title">EXPERIENCE</h2>

&#x20;       <p class="section-desc">

&#x20;         빠르게 배우고, 직접 만들고, 팀을 움직이며

&#x20;         프로젝트를 현실로 바꾸는 경험들을 쌓아왔습니다.

&#x20;       </p>



&#x20;       <div class="timeline">

&#x20;         <article class="timeline-item">

&#x20;           <h3>Leadership</h3>

&#x20;           <p>

&#x20;             HUBS 방송국 국장<br />

&#x20;             사회과학대학 언론동아리 회장<br />

&#x20;             사회학과 4학년 과대표 (2회)

&#x20;           </p>

&#x20;         </article>



&#x20;         <article class="timeline-item">

&#x20;           <h3>Media \&amp; Marketing</h3>

&#x20;           <p>

&#x20;             한국일보 문화부 인턴 기자<br />

&#x20;             MBC 문화방송 2시 뉴스 조연출<br />

&#x20;             YPO 사우디 의전 · 영어통역 · 촬영<br />

&#x20;             로레알코리아 Luxe 마케팅/기획 인턴 예정

&#x20;           </p>

&#x20;         </article>



&#x20;         <article class="timeline-item">

&#x20;           <h3>AI Film \&amp; Creative</h3>

&#x20;           <p>

&#x20;             BIFAN AI 단편영화 「ANNA」 연출<br />

&#x20;             스웨덴 국제 영화제 노미네이트<br />

&#x20;             서울국제AI영화제 초청<br />

&#x20;             BLACK AI FEST 2개 부문 노미네이트

&#x20;           </p>

&#x20;         </article>



&#x20;         <article class="timeline-item">

&#x20;           <h3>Awards</h3>

&#x20;           <p>

&#x20;             경기북부발전 AI 콘텐츠 제작 최우수상<br />

&#x20;             KT AI P.A.N 장려상<br />

&#x20;             AI 활용 멀티모달 포스터 대회 최우수상<br />

&#x20;             로레알 브랜드스톰 국내 1위

&#x20;           </p>

&#x20;         </article>

&#x20;       </div>

&#x20;     </div>

&#x20;   </section>



&#x20;   <section class="project" id="project" aria-labelledby="project-title">

&#x20;     <div class="container">

&#x20;       <h2 id="project-title" class="section-title">내가 만들고 싶은 서비스</h2>

&#x20;       <p class="section-desc" style="color:#cfcfcf;">

&#x20;         영화를 사랑하는 사람들이 더 깊게 이야기할 수 있는 공간.

&#x20;       </p>



&#x20;       <blockquote class="quote">

&#x20;         “100명이 영화를 보면,<br />

&#x20;         100개의 다른 영화가 탄생한다.”

&#x20;       </blockquote>



&#x20;       <div class="grid-2" style="margin-top:42px;">

&#x20;         <article class="project-card">

&#x20;           <h3>씨네필</h3>

&#x20;           <p>영화를 좋아하는 사람들을 위한 커뮤니티 기반 플랫폼.</p>

&#x20;           <p>

&#x20;             단순 별점과 한 줄 리뷰가 아닌, 깊이 있는 해석과 토론,

&#x20;             그리고 개인의 감상을 기록하는 공간을 만듭니다.

&#x20;           </p>

&#x20;         </article>



&#x20;         <article class="project-card">

&#x20;           <h3>풀고 싶은 문제</h3>

&#x20;           <p>현재 영화 팬들은 블로그, SNS, 개인 메모에 흩어져 있습니다.</p>

&#x20;           <p>

&#x20;             씨네필은 영화 토론, 영화제 네트워킹, 감상 아카이빙,

&#x20;             비평 커뮤니티를 하나로 연결합니다.

&#x20;           </p>

&#x20;         </article>

&#x20;       </div>

&#x20;     </div>

&#x20;   </section>



&#x20;   <section id="tools" aria-labelledby="tools-title">

&#x20;     <div class="container">

&#x20;       <h2 id="tools-title" class="section-title">TOOLS</h2>



&#x20;       <div class="grid-2">

&#x20;         <article class="card">

&#x20;           <h3>디자인 \&amp; 편집</h3>

&#x20;           <ul>

&#x20;             <li>Figma</li>

&#x20;             <li>Premiere Pro</li>

&#x20;             <li>DaVinci Resolve</li>

&#x20;           </ul>

&#x20;         </article>



&#x20;         <article class="card">

&#x20;           <h3>AI Tools</h3>

&#x20;           <ul>

&#x20;             <li>Higgsfield</li>

&#x20;             <li>Kling</li>

&#x20;             <li>ElevenLabs</li>

&#x20;             <li>Suno</li>

&#x20;             <li>Freepik AI</li>

&#x20;           </ul>

&#x20;         </article>

&#x20;       </div>

&#x20;     </div>

&#x20;   </section>

&#x20; </main>



&#x20; <footer class="footer" role="contentinfo">

&#x20;   <div class="container">

&#x20;     <h2>Curious Enough to Build.</h2>

&#x20;     <p>세상에 대한 호기심을 콘텐츠와 기술로 연결합니다.</p>

&#x20;   </div>

&#x20; </footer>

</body>

</html>

