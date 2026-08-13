<div align="center">

  <!-- Custom Animated Header -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00FF99&center=true&vcenter=true&width=700&lines=%E2%9A%A1+NaveenKumar+B;%F0%9F%93%8A+Financial+Analyst+%2B+Data+Storyteller;%F0%9F%A7%A0+Turning+Complex+Metrics+into+Strategy;%F0%9F%8F%85+Published+NBFC+Researcher" alt="Typing SVG" />
  </a>

  <br/>

  <p align="center">
    <code><b>FINANCIAL MODELING</b></code> • 
    <code><b>BUSINESS ANALYTICS</b></code> • 
    <code><b>NBFC & CAPITAL ADEQUACY</b></code>
  </p>

  <!-- Neo-Glass Badges -->
  <a href="https://www.linkedin.com/in/naveenkumar" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:naveenbalakrishnan146@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Location-Coimbatore%2C%20IN-10B981?style=for-the-badge&logo=googlemaps&logoColor=white" />

</div>

<br/>

<!-- Neon Divider -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Naveen Kumar | Finance & Analytics</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500;700&display=swap');

:root{
    --bg:#05080d;
    --card:rgba(12,20,30,.78);
    --green:#00ff9d;
    --cyan:#00d9ff;
    --blue:#3b82f6;
    --text:#e8f0f7;
    --muted:#8493a5;
    --border:rgba(0,255,157,.16);
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    background:
        radial-gradient(circle at 10% 10%, rgba(0,255,157,.08), transparent 25%),
        radial-gradient(circle at 90% 20%, rgba(0,217,255,.08), transparent 25%),
        var(--bg);
    color:var(--text);
    font-family:Inter,sans-serif;
    overflow-x:hidden;
}

/* GRID BACKGROUND */

body::before{
    content:"";
    position:fixed;
    inset:0;
    background-image:
        linear-gradient(rgba(255,255,255,.025) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,.025) 1px, transparent 1px);
    background-size:45px 45px;
    pointer-events:none;
    z-index:-2;
}

/* FLOATING GLOW */

.glow{
    position:fixed;
    width:350px;
    height:350px;
    border-radius:50%;
    background:rgba(0,255,157,.08);
    filter:blur(80px);
    pointer-events:none;
    z-index:-1;
    animation:float 8s ease-in-out infinite;
}

.glow.one{
    top:10%;
    left:-100px;
}

.glow.two{
    right:-100px;
    bottom:10%;
    background:rgba(0,217,255,.07);
    animation-delay:2s;
}

@keyframes float{
    0%,100%{transform:translateY(0)}
    50%{transform:translateY(-50px)}
}

/* NAVBAR */

nav{
    position:fixed;
    top:0;
    width:100%;
    z-index:100;
    padding:18px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:rgba(5,8,13,.7);
    backdrop-filter:blur(18px);
    border-bottom:1px solid rgba(255,255,255,.06);
}

.logo{
    font-family:"JetBrains Mono",monospace;
    color:var(--green);
    font-weight:700;
    letter-spacing:1px;
}

.logo span{
    color:white;
}

nav ul{
    display:flex;
    list-style:none;
    gap:28px;
}

nav a{
    color:#9aaabd;
    text-decoration:none;
    font-size:14px;
    transition:.3s;
}

nav a:hover{
    color:var(--green);
}

/* HERO */

.hero{
    min-height:100vh;
    padding:150px 8% 80px;
    display:grid;
    grid-template-columns:1.15fr .85fr;
    align-items:center;
    gap:60px;
}

.terminal{
    border:1px solid var(--border);
    background:rgba(5,12,18,.8);
    border-radius:18px;
    box-shadow:0 0 60px rgba(0,255,157,.07);
    overflow:hidden;
}

.terminal-header{
    padding:12px 18px;
    background:#0c141d;
    display:flex;
    align-items:center;
    gap:7px;
    border-bottom:1px solid rgba(255,255,255,.06);
}

.dot{
    width:10px;
    height:10px;
    border-radius:50%;
}

.red{background:#ff5f56}
.yellow{background:#ffbd2e}
.green{background:#27c93f}

.terminal-title{
    margin-left:10px;
    font:12px "JetBrains Mono";
    color:#64748b;
}

.terminal-body{
    padding:30px;
    font-family:"JetBrains Mono",monospace;
    line-height:2;
}

.prompt{
    color:var(--green);
}

.command{
    color:#fff;
}

.output{
    color:#8191a5;
}

.hero h1{
    font-size:clamp(42px,6vw,78px);
    line-height:1;
    margin:25px 0;
    letter-spacing:-3px;
}

.hero h1 span{
    color:var(--green);
    text-shadow:0 0 30px rgba(0,255,157,.35);
}

.subtitle{
    color:var(--muted);
    font-size:18px;
    line-height:1.8;
    max-width:650px;
}

.typing{
    color:var(--cyan);
    font-family:"JetBrains Mono";
}

.cursor{
    animation:blink .7s infinite;
}

@keyframes blink{
    50%{opacity:0}
}

.buttons{
    display:flex;
    gap:15px;
    margin-top:35px;
}

.btn{
    padding:13px 22px;
    border-radius:8px;
    text-decoration:none;
    font-weight:600;
    transition:.3s;
}

.primary{
    background:var(--green);
    color:#00140d;
}

.primary:hover{
    transform:translateY(-4px);
    box-shadow:0 10px 30px rgba(0,255,157,.25);
}

.secondary{
    border:1px solid #263746;
    color:white;
}

.secondary:hover{
    border-color:var(--green);
    color:var(--green);
}

/* PROFILE CARD */

.profile-card{
    padding:35px;
    border:1px solid var(--border);
    background:var(--card);
    border-radius:24px;
    backdrop-filter:blur(15px);
    text-align:center;
    position:relative;
    overflow:hidden;
}

.profile-card::before{
    content:"";
    position:absolute;
    width:180px;
    height:180px;
    background:var(--green);
    filter:blur(100px);
    opacity:.12;
    top:-80px;
    right:-50px;
}

.avatar{
    width:120px;
    height:120px;
    margin:auto;
    border-radius:50%;
    border:2px solid var(--green);
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:42px;
    font-weight:800;
    color:var(--green);
    box-shadow:0 0 40px rgba(0,255,157,.2);
}

.profile-card h2{
    margin:20px 0 8px;
}

.role{
    color:var(--green);
    font-family:"JetBrains Mono";
    font-size:13px;
}

.status{
    margin:25px auto;
    padding:10px;
    background:rgba(0,255,157,.05);
    border:1px solid rgba(0,255,157,.12);
    border-radius:8px;
    color:#a9b8c8;
    font-size:13px;
}

.online{
    color:var(--green);
}

/* SECTIONS */

section{
    padding:100px 8%;
}

.section-title{
    font-size:38px;
    margin-bottom:12px;
}

.section-title span{
    color:var(--green);
}

.section-subtitle{
    color:var(--muted);
    margin-bottom:45px;
}

/* STATS */

.stats{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:18px;
}

.stat{
    padding:30px;
    background:var(--card);
    border:1px solid rgba(255,255,255,.06);
    border-radius:16px;
    transition:.3s;
}

.stat:hover{
    transform:translateY(-8px);
    border-color:var(--green);
}

.stat-number{
    font-size:38px;
    font-weight:800;
    color:var(--green);
}

.stat p{
    color:var(--muted);
    margin-top:8px;
}

/* SKILLS */

.skills{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:25px;
}

.skill-box{
    padding:25px;
    background:var(--card);
    border:1px solid rgba(255,255,255,.06);
    border-radius:15px;
}

.skill-name{
    display:flex;
    justify-content:space-between;
    margin-bottom:10px;
    font-size:14px;
}

.skill-name span{
    color:var(--green);
}

.progress{
    height:7px;
    background:#16212c;
    border-radius:10px;
    overflow:hidden;
}

.progress-bar{
    height:100%;
    width:0;
    border-radius:10px;
    background:linear-gradient(90deg,var(--green),var(--cyan));
    box-shadow:0 0 15px rgba(0,255,157,.3);
    transition:width 1.5s ease;
}

/* PROJECTS */

.projects{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:25px;
}

.project{
    padding:30px;
    background:linear-gradient(145deg,#0b141d,#081018);
    border:1px solid rgba(255,255,255,.07);
    border-radius:18px;
    transition:.4s;
    position:relative;
    overflow:hidden;
}

.project:hover{
    transform:translateY(-10px);
    border-color:rgba(0,255,157,.4);
    box-shadow:0 20px 50px rgba(0,0,0,.3);
}

.project-number{
    color:var(--green);
    font-family:"JetBrains Mono";
    font-size:13px;
}

.project h3{
    font-size:23px;
    margin:15px 0;
}

.project p{
    color:var(--muted);
    line-height:1.7;
}

.tags{
    display:flex;
    flex-wrap:wrap;
    gap:8px;
    margin-top:20px;
}

.tag{
    padding:6px 10px;
    border-radius:6px;
    background:rgba(0,255,157,.07);
    color:#7fffc6;
    font:11px "JetBrains Mono";
}

/* TIMELINE */

.timeline{
    max-width:850px;
    border-left:1px solid rgba(0,255,157,.25);
    padding-left:35px;
}

.timeline-item{
    position:relative;
    margin-bottom:45px;
}

.timeline-item::before{
    content:"";
    position:absolute;
    width:12px;
    height:12px;
    background:var(--green);
    border-radius:50%;
    left:-41px;
    top:5px;
    box-shadow:0 0 15px var(--green);
}

.timeline-date{
    color:var(--green);
    font:12px "JetBrains Mono";
}

.timeline h3{
    margin:10px 0;
}

.timeline p{
    color:var(--muted);
    line-height:1.7;
}

/* QUOTE */

.quote{
    text-align:center;
    max-width:800px;
    margin:auto;
}

.quote-text{
    font-size:30px;
    line-height:1.5;
    font-weight:600;
}

.quote-text span{
    color:var(--green);
}

.quote-author{
    margin-top:20px;
    color:var(--muted);
}

/* FOOTER */

footer{
    padding:50px 8%;
    border-top:1px solid rgba(255,255,255,.06);
    text-align:center;
    color:#657487;
}

footer strong{
    color:var(--green);
}

/* REVEAL */

.reveal{
    opacity:0;
    transform:translateY(35px);
    transition:opacity .8s,transform .8s;
}

.reveal.show{
    opacity:1;
    transform:translateY(0);
}

/* MOBILE */

@media(max-width:850px){

    nav ul{
        display:none;
    }

    .hero{
        grid-template-columns:1fr;
        padding-top:130px;
    }

    .stats{
        grid-template-columns:1fr 1fr;
    }

    .skills,
    .projects{
        grid-template-columns:1fr;
    }

    .hero h1{
        font-size:48px;
    }
}

@media(max-width:500px){

    section{
        padding:70px 6%;
    }

    .stats{
        grid-template-columns:1fr;
    }

    .terminal-body{
        padding:20px;
        font-size:12px;
    }

    .buttons{
        flex-direction:column;
    }
}
</style>
</head>

<body>

<div class="glow one"></div>
<div class="glow two"></div>

<!-- NAVIGATION -->

<nav>
    <div class="logo">NAVEEN<span>.FINANCE</span></div>

    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#experience">Experience</a></li>
    </ul>
</nav>

<!-- HERO -->

<header class="hero">

    <div>

        <div class="terminal">

            <div class="terminal-header">
                <div class="dot red"></div>
                <div class="dot yellow"></div>
                <div class="dot green"></div>
                <div class="terminal-title">
                    naveen@finance-terminal
                </div>
            </div>

            <div class="terminal-body">

                <div>
                    <span class="prompt">naveen@finance:~$</span>
                    <span class="command"> whoami</span>
                </div>

                <div class="output">
                    Finance Analyst | Data Enthusiast
                </div>

                <br>

                <div>
                    <span class="prompt">naveen@finance:~$</span>
                    <span class="command"> current_focus</span>
                </div>

                <div class="output">
                    Python + Pandas + Power BI
                </div>

                <br>

                <div>
                    <span class="prompt">naveen@finance:~$</span>
                    <span class="command"> status</span>
                </div>

                <div class="output">
                    <span class="online">● ONLINE</span>
                    Building smarter finance workflows...
                </div>

            </div>

        </div>

        <h1>
            Hi, I'm <span>Naveen.</span>
        </h1>

        <p class="subtitle">
            I turn financial data into
            <span class="typing" id="typing"></span>
            <span class="cursor">|</span>
        </p>

        <div class="buttons">
            <a href="#projects" class="btn primary">Explore My Work →</a>
            <a href="mailto:naveenbalakrishnan146@gmail.com"
               class="btn secondary">
               Let's Connect
            </a>
        </div>

    </div>

    <!-- PROFILE -->

    <div class="profile-card reveal">

        <div class="avatar">NK</div>

        <h2>Naveen Kumar</h2>

        <div class="role">
            JUNIOR ANALYST
        </div>

        <div class="status">
            <span class="online">●</span>
            Currently working at
            <strong>Zold UDP Group</strong>
        </div>

        <p style="color:#8493a5;line-height:1.7;">
            Finance & Business Analytics professional
            focused on reconciliation, reporting,
            NBFC research and automation.
        </p>

    </div>

</header>


<!-- ABOUT -->

<section id="about" class="reveal">

    <h2 class="section-title">
        Finance <span>×</span> Analytics
    </h2>

    <p class="section-subtitle">
        Where accounting meets data, automation and decision-making.
    </p>

    <div class="stats">

        <div class="stat">
            <div class="stat-number counter" data-target="7.9">0</div>
            <p>MBA CGPA</p>
        </div>

        <div class="stat">
            <div class="stat-number counter" data-target="2025">0</div>
            <p>Research Published</p>
        </div>

        <div class="stat">
            <div class="stat-number counter" data-target="5">0</div>
            <p>NBFCs Researched</p>
        </div>

        <div class="stat">
            <div class="stat-number counter" data-target="8">0</div>
            <p>Core Tools</p>
        </div>

    </div>

</section>


<!-- SKILLS -->

<section id="skills" class="reveal">

    <h2 class="section-title">
        Technical <span>Stack</span>
    </h2>

    <p class="section-subtitle">
        Tools I use to transform raw financial data into insights.
    </p>

    <div class="skills">

        <div class="skill-box">

            <div class="skill-name">
                <b>Excel</b>
                <span>90%</span>
            </div>

            <div class="progress">
                <div class="progress-bar" data-width="90%"></div>
            </div>

        </div>

        <div class="skill-box">

            <div class="skill-name">
                <b>Power BI</b>
                <span>85%</span>
            </div>

            <div class="progress">
                <div class="progress-bar" data-width="85%"></div>
            </div>

        </div>

        <div class="skill-box">

            <div class="skill-name">
                <b>Python / Pandas</b>
                <span>78%</span>
            </div>

            <div class="progress">
                <div class="progress-bar" data-width="78%"></div>
            </div>

        </div>

        <div class="skill-box">

            <div class="skill-name">
                <b>Financial Analysis</b>
                <span>88%</span>
            </div>

            <div class="progress">
                <div class="progress-bar" data-width="88%"></div>
            </div>

        </div>

        <div class="skill-box">

            <div class="skill-name">
                <b>SAP FICO</b>
                <span>75%</span>
            </div>

            <div class="progress">
                <div class="progress-bar" data-width="75%"></div>
            </div>

        </div>

        <div class="skill-box">

            <div class="skill-name">
                <b>SQL / MySQL</b>
                <span>72%</span>
            </div>

            <div class="progress">
                <div class="progress-bar" data-width="72%"></div>
            </div>

        </div>

    </div>

</section>


<!-- PROJECTS -->

<section id="projects" class="reveal">

    <h2 class="section-title">
        Selected <span>Projects</span>
    </h2>

    <p class="section-subtitle">
        Finance problems translated into analytical solutions.
    </p>

    <div class="projects">

        <div class="project">

            <div class="project-number">01 / FINANCE AUTOMATION</div>

            <h3>ReconX</h3>

            <p>
                Automated financial reconciliation workflow using
                Python and Pandas to reduce repetitive spreadsheet
                operations and identify mismatches efficiently.
            </p>

            <div class="tags">
                <span class="tag">PYTHON</span>
                <span class="tag">PANDAS</span>
                <span class="tag">EXCEL</span>
                <span class="tag">AUTOMATION</span>
            </div>

        </div>


        <div class="project">

            <div class="project-number">02 / FINANCIAL ANALYTICS</div>

            <h3>NBFC Lens</h3>

            <p>
                Financial analysis of India's leading NBFCs focusing
                on capital adequacy, profitability, liquidity and
                growth trends.
            </p>

            <div class="tags">
                <span class="tag">NBFC</span>
                <span class="tag">RATIOS</span>
                <span class="tag">RESEARCH</span>
                <span class="tag">EXCEL</span>
            </div>

        </div>


        <div class="project">

            <div class="project-number">03 / BUSINESS INTELLIGENCE</div>

            <h3>FinPulse</h3>

            <p>
                Executive-level Power BI dashboard designed to turn
                financial records into clear management insights,
                KPIs and trends.
            </p>

            <div class="tags">
                <span class="tag">POWER BI</span>
                <span class="tag">DAX</span>
                <span class="tag">KPI</span>
                <span class="tag">DASHBOARD</span>
            </div>

        </div>


        <div class="project">

            <div class="project-number">04 / SOCIAL ECONOMICS</div>

            <h3>Pollachi Handloom Study</h3>

            <p>
                Research into demand, marketing, credit access and
                economic challenges affecting handloom weavers in
                Pollachi Taluk.
            </p>

            <div class="tags">
                <span class="tag">RESEARCH</span>
                <span class="tag">SURVEY</span>
                <span class="tag">ANALYTICS</span>
            </div>

        </div>

    </div>

</section>


<!-- EXPERIENCE -->

<section id="experience" class="reveal">

    <h2 class="section-title">
        Career <span>Timeline</span>
    </h2>

    <p class="section-subtitle">
        From accounting fundamentals to financial analytics.
    </p>

    <div class="timeline">

        <div class="timeline-item">

            <div class="timeline-date">
                AUG 2025 — PRESENT
            </div>

            <h3>Junior Analyst · Zold UDP Group</h3>

            <p>
                Financial records, reconciliations, AP/AR,
                reporting workflows and management support.
            </p>

        </div>


        <div class="timeline-item">

            <div class="timeline-date">
                MBA · FINANCE & BUSINESS ANALYTICS
            </div>

            <h3>MBA — 7.9 CGPA</h3>

            <p>
                Developed expertise in finance, analytics,
                financial modelling, research and business intelligence.
            </p>

        </div>


        <div class="timeline-item">

            <div class="timeline-date">
                2025 · RESEARCH
            </div>

            <h3>Published NBFC Research</h3>

            <p>
                Published research on capital adequacy of India's
                leading NBFCs in EPRA IJEBM.
            </p>

        </div>

    </div>

</section>


<!-- QUOTE -->

<section class="reveal">

    <div class="quote">

        <div class="quote-text">
            "Nothing will work unless
            <span>you do.</span>"
        </div>

        <div class="quote-author">
            — Maya Angelou
        </div>

    </div>

</section>


<!-- FOOTER -->

<footer>

    <p>
        <strong>NAVEEN.FINANCE</strong>
    </p>

    <p style="margin-top:10px;">
        Finance · Analytics · Automation · Research
    </p>

    <p style="margin-top:20px;">
        © 2026 Naveen Kumar
    </p>

</footer>


<script>

/* TYPING EFFECT */

const words = [
    "actionable insights.",
    "automated workflows.",
    "executive dashboards.",
    "better decisions."
];

let wordIndex = 0;
let charIndex = 0;
let deleting = false;

const typing = document.getElementById("typing");

function typeEffect(){

    const word = words[wordIndex];

    if(!deleting){

        typing.textContent = word.substring(0,charIndex++);

        if(charIndex > word.length){

            deleting = true;

            setTimeout(typeEffect,1400);

            return;
        }

    }else{

        typing.textContent = word.substring(0,charIndex--);

        if(charIndex === 0){

            deleting = false;

            wordIndex++;

            if(wordIndex >= words.length){
                wordIndex = 0;
            }

        }
    }

    setTimeout(typeEffect, deleting ? 45 : 80);
}

typeEffect();


/* SCROLL REVEAL */

const reveals = document.querySelectorAll(".reveal");

const observer = new IntersectionObserver(
    entries => {

        entries.forEach(entry => {

            if(entry.isIntersecting){

                entry.target.classList.add("show");

            }

        });

    },
    {
        threshold:.15
    }
);

reveals.forEach(el => observer.observe(el));


/* SKILL BAR ANIMATION */

const skillBars = document.querySelectorAll(".progress-bar");

const skillObserver = new IntersectionObserver(
    entries => {

        entries.forEach(entry => {

            if(entry.isIntersecting){

                entry.target.style.width =
                    entry.target.dataset.width;

            }

        });

    },
    {
        threshold:.5
    }
);

skillBars.forEach(bar => skillObserver.observe(bar));


/* NUMBER COUNTERS */

const counters = document.querySelectorAll(".counter");

const counterObserver = new IntersectionObserver(
    entries => {

        entries.forEach(entry => {

            if(!entry.isIntersecting) return;

            const counter = entry.target;
            const target = parseFloat(counter.dataset.target);

            let current = 0;

            const increment = target / 60;

            function update(){

                current += increment;

                if(current < target){

                    counter.textContent =
                        target % 1 !== 0
                        ? current.toFixed(1)
                        : Math.floor(current);

                    requestAnimationFrame(update);

                }else{

                    counter.textContent =
                        target % 1 !== 0
                        ? target.toFixed(1)
                        : target;

                }

            }

            update();

            counterObserver.unobserve(counter);

        });

    }
);

counters.forEach(counter =>
    counterObserver.observe(counter)
);

</script>

</body>
</html>
