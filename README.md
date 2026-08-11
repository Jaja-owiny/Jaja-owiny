<!-- ████████████████████████████████████████████████████████████ -->
<!--                  INITIALIZING SYSTEM...                     -->
<!-- ████████████████████████████████████████████████████████████ -->

<div align="center">

<!-- MATRIX RAIN HEADER — pure SVG, no external service needed -->
<svg width="100%" viewBox="0 0 680 220" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Matrix rain header — Jason Ocholla</title>
  <desc>Animated matrix rain with falling green digits over a black background</desc>

  <rect width="680" height="220" fill="#000"/>

  <style>
    .col text { font-family: 'Courier New', monospace; font-size: 13px; fill: #00FF41; }
    .col text.dim { fill: #003300; }
    .col text.mid { fill: #00AA22; }
    .col text.bright { fill: #CCFFCC; }

    @keyframes fall1  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall2  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall3  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall4  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall5  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall6  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall7  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall8  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall9  { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall10 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall11 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall12 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall13 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall14 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall15 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall16 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall17 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall18 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall19 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall20 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall21 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall22 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall23 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall24 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall25 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall26 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall27 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall28 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall29 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall30 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall31 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall32 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall33 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }
    @keyframes fall34 { 0%{transform:translateY(-220px)} 100%{transform:translateY(220px)} }

    .c1  { animation: fall1  1.8s linear -0.2s infinite; }
    .c2  { animation: fall2  2.1s linear -0.7s infinite; }
    .c3  { animation: fall3  1.6s linear -1.1s infinite; }
    .c4  { animation: fall4  2.4s linear -0.4s infinite; }
    .c5  { animation: fall5  1.9s linear -1.5s infinite; }
    .c6  { animation: fall6  2.2s linear -0.9s infinite; }
    .c7  { animation: fall7  1.7s linear -0.3s infinite; }
    .c8  { animation: fall8  2.0s linear -1.8s infinite; }
    .c9  { animation: fall9  1.5s linear -0.6s infinite; }
    .c10 { animation: fall10 2.3s linear -1.2s infinite; }
    .c11 { animation: fall11 1.8s linear -0.5s infinite; }
    .c12 { animation: fall12 2.0s linear -1.7s infinite; }
    .c13 { animation: fall13 1.6s linear -0.1s infinite; }
    .c14 { animation: fall14 2.5s linear -0.8s infinite; }
    .c15 { animation: fall15 1.9s linear -1.4s infinite; }
    .c16 { animation: fall16 2.1s linear -0.3s infinite; }
    .c17 { animation: fall17 1.7s linear -1.9s infinite; }
    .c18 { animation: fall18 2.3s linear -0.6s infinite; }
    .c19 { animation: fall19 1.5s linear -1.0s infinite; }
    .c20 { animation: fall20 2.0s linear -0.2s infinite; }
    .c21 { animation: fall21 1.8s linear -1.3s infinite; }
    .c22 { animation: fall22 2.2s linear -0.7s infinite; }
    .c23 { animation: fall23 1.6s linear -1.6s infinite; }
    .c24 { animation: fall24 2.4s linear -0.4s infinite; }
    .c25 { animation: fall25 1.9s linear -1.1s infinite; }
    .c26 { animation: fall26 2.1s linear -0.8s infinite; }
    .c27 { animation: fall27 1.7s linear -0.2s infinite; }
    .c28 { animation: fall28 2.3s linear -1.5s infinite; }
    .c29 { animation: fall29 1.5s linear -0.9s infinite; }
    .c30 { animation: fall30 2.0s linear -1.3s infinite; }
    .c31 { animation: fall31 1.8s linear -0.5s infinite; }
    .c32 { animation: fall32 2.2s linear -1.8s infinite; }
    .c33 { animation: fall33 1.6s linear -0.3s infinite; }
    .c34 { animation: fall34 2.4s linear -1.0s infinite; }
  </style>

  <defs>
    <clipPath id="rain-clip"><rect width="680" height="220"/></clipPath>
    <radialGradient id="vignette" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#000" stop-opacity="0.0"/>
      <stop offset="100%" stop-color="#000" stop-opacity="0.7"/>
    </radialGradient>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#003300" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#000" stop-opacity="0.0"/>
    </radialGradient>
  </defs>

  <g clip-path="url(#rain-clip)" class="col">
    <g class="c1"><text x="10" y="16" class="bright">1</text><text x="10" y="30" class="mid">0</text><text x="10" y="44">7</text><text x="10" y="58" class="mid">3</text><text x="10" y="72">1</text><text x="10" y="86" class="dim">0</text><text x="10" y="100" class="dim">8</text><text x="10" y="114" class="dim">2</text></g>
    <g class="c2"><text x="30" y="16" class="mid">9</text><text x="30" y="30" class="bright">4</text><text x="30" y="44">0</text><text x="30" y="58">6</text><text x="30" y="72" class="dim">1</text><text x="30" y="86" class="dim">5</text><text x="30" y="100" class="dim">9</text></g>
    <g class="c3"><text x="50" y="16">2</text><text x="50" y="30" class="mid">7</text><text x="50" y="44" class="bright">1</text><text x="50" y="58" class="mid">8</text><text x="50" y="72">3</text><text x="50" y="86" class="dim">0</text><text x="50" y="100" class="dim">6</text><text x="50" y="114" class="dim">4</text></g>
    <g class="c4"><text x="70" y="16" class="dim">5</text><text x="70" y="30">0</text><text x="70" y="44" class="mid">9</text><text x="70" y="58" class="bright">2</text><text x="70" y="72" class="mid">7</text><text x="70" y="86">4</text><text x="70" y="100" class="dim">1</text></g>
    <g class="c5"><text x="90" y="16" class="mid">8</text><text x="90" y="30" class="bright">3</text><text x="90" y="44" class="mid">6</text><text x="90" y="58">1</text><text x="90" y="72" class="dim">9</text><text x="90" y="86" class="dim">5</text><text x="90" y="100" class="dim">2</text></g>
    <g class="c6"><text x="110" y="16">4</text><text x="110" y="30" class="mid">1</text><text x="110" y="44" class="bright">0</text><text x="110" y="58" class="mid">8</text><text x="110" y="72">3</text><text x="110" y="86" class="dim">7</text><text x="110" y="100" class="dim">6</text></g>
    <g class="c7"><text x="130" y="16" class="dim">6</text><text x="130" y="30">2</text><text x="130" y="44" class="mid">5</text><text x="130" y="58" class="bright">9</text><text x="130" y="72" class="mid">0</text><text x="130" y="86">4</text><text x="130" y="100" class="dim">1</text></g>
    <g class="c8"><text x="150" y="16" class="mid">7</text><text x="150" y="30" class="bright">4</text><text x="150" y="44">2</text><text x="150" y="58" class="mid">6</text><text x="150" y="72">8</text><text x="150" y="86" class="dim">3</text><text x="150" y="100" class="dim">0</text></g>
    <g class="c9"><text x="170" y="16">1</text><text x="170" y="30" class="mid">9</text><text x="170" y="44" class="bright">3</text><text x="170" y="58">7</text><text x="170" y="72" class="mid">5</text><text x="170" y="86" class="dim">2</text><text x="170" y="100" class="dim">8</text></g>
    <g class="c10"><text x="190" y="16" class="dim">0</text><text x="190" y="30">6</text><text x="190" y="44" class="mid">1</text><text x="190" y="58" class="bright">4</text><text x="190" y="72" class="mid">9</text><text x="190" y="86">2</text><text x="190" y="100" class="dim">7</text></g>
    <g class="c11"><text x="210" y="16" class="mid">5</text><text x="210" y="30" class="bright">8</text><text x="210" y="44" class="mid">0</text><text x="210" y="58">3</text><text x="210" y="72" class="dim">6</text><text x="210" y="86" class="dim">1</text></g>
    <g class="c12"><text x="230" y="16">9</text><text x="230" y="30" class="mid">2</text><text x="230" y="44" class="bright">7</text><text x="230" y="58" class="mid">5</text><text x="230" y="72">1</text><text x="230" y="86" class="dim">4</text><text x="230" y="100" class="dim">8</text></g>
    <g class="c13"><text x="250" y="16" class="dim">3</text><text x="250" y="30">0</text><text x="250" y="44" class="mid">6</text><text x="250" y="58" class="bright">2</text><text x="250" y="72" class="mid">9</text><text x="250" y="86">7</text><text x="250" y="100" class="dim">4</text></g>
    <g class="c14"><text x="270" y="16" class="mid">8</text><text x="270" y="30" class="bright">5</text><text x="270" y="44">3</text><text x="270" y="58" class="mid">0</text><text x="270" y="72">6</text><text x="270" y="86" class="dim">2</text></g>
    <g class="c15"><text x="290" y="16">1</text><text x="290" y="30" class="mid">7</text><text x="290" y="44" class="bright">4</text><text x="290" y="58" class="mid">8</text><text x="290" y="72">0</text><text x="290" y="86" class="dim">5</text><text x="290" y="100" class="dim">3</text></g>
    <g class="c16"><text x="310" y="16" class="dim">6</text><text x="310" y="30">9</text><text x="310" y="44" class="mid">2</text><text x="310" y="58" class="bright">1</text><text x="310" y="72" class="mid">7</text><text x="310" y="86">3</text><text x="310" y="100" class="dim">5</text></g>
    <g class="c17"><text x="330" y="16" class="mid">4</text><text x="330" y="30" class="bright">0</text><text x="330" y="44" class="mid">8</text><text x="330" y="58">6</text><text x="330" y="72" class="dim">2</text><text x="330" y="86" class="dim">9</text></g>
    <g class="c18"><text x="350" y="16">7</text><text x="350" y="30" class="mid">3</text><text x="350" y="44" class="bright">5</text><text x="350" y="58" class="mid">1</text><text x="350" y="72">4</text><text x="350" y="86" class="dim">8</text><text x="350" y="100" class="dim">0</text></g>
    <g class="c19"><text x="370" y="16" class="dim">2</text><text x="370" y="30">6</text><text x="370" y="44" class="mid">9</text><text x="370" y="58" class="bright">3</text><text x="370" y="72" class="mid">7</text><text x="370" y="86">5</text><text x="370" y="100" class="dim">1</text></g>
    <g class="c20"><text x="390" y="16" class="mid">0</text><text x="390" y="30" class="bright">8</text><text x="390" y="44">4</text><text x="390" y="58" class="mid">2</text><text x="390" y="72">6</text><text x="390" y="86" class="dim">9</text></g>
    <g class="c21"><text x="410" y="16">5</text><text x="410" y="30" class="mid">1</text><text x="410" y="44" class="bright">7</text><text x="410" y="58" class="mid">0</text><text x="410" y="72">3</text><text x="410" y="86" class="dim">8</text><text x="410" y="100" class="dim">4</text></g>
    <g class="c22"><text x="430" y="16" class="dim">9</text><text x="430" y="30">2</text><text x="430" y="44" class="mid">6</text><text x="430" y="58" class="bright">5</text><text x="430" y="72" class="mid">1</text><text x="430" y="86">7</text><text x="430" y="100" class="dim">3</text></g>
    <g class="c23"><text x="450" y="16" class="mid">4</text><text x="450" y="30" class="bright">9</text><text x="450" y="44" class="mid">2</text><text x="450" y="58">8</text><text x="450" y="72" class="dim">5</text><text x="450" y="86" class="dim">0</text></g>
    <g class="c24"><text x="470" y="16">6</text><text x="470" y="30" class="mid">3</text><text x="470" y="44" class="bright">1</text><text x="470" y="58" class="mid">4</text><text x="470" y="72">9</text><text x="470" y="86" class="dim">7</text><text x="470" y="100" class="dim">2</text></g>
    <g class="c25"><text x="490" y="16" class="dim">8</text><text x="490" y="30">5</text><text x="490" y="44" class="mid">0</text><text x="490" y="58" class="bright">3</text><text x="490" y="72" class="mid">6</text><text x="490" y="86">1</text><text x="490" y="100" class="dim">4</text></g>
    <g class="c26"><text x="510" y="16" class="mid">2</text><text x="510" y="30" class="bright">7</text><text x="510" y="44">5</text><text x="510" y="58" class="mid">9</text><text x="510" y="72">0</text><text x="510" y="86" class="dim">3</text></g>
    <g class="c27"><text x="530" y="16">8</text><text x="530" y="30" class="mid">4</text><text x="530" y="44" class="bright">6</text><text x="530" y="58" class="mid">2</text><text x="530" y="72">7</text><text x="530" y="86" class="dim">5</text><text x="530" y="100" class="dim">9</text></g>
    <g class="c28"><text x="550" y="16" class="dim">1</text><text x="550" y="30">3</text><text x="550" y="44" class="mid">8</text><text x="550" y="58" class="bright">0</text><text x="550" y="72" class="mid">4</text><text x="550" y="86">6</text><text x="550" y="100" class="dim">2</text></g>
    <g class="c29"><text x="570" y="16" class="mid">9</text><text x="570" y="30" class="bright">1</text><text x="570" y="44" class="mid">5</text><text x="570" y="58">3</text><text x="570" y="72" class="dim">7</text><text x="570" y="86" class="dim">0</text></g>
    <g class="c30"><text x="590" y="16">4</text><text x="590" y="30" class="mid">2</text><text x="590" y="44" class="bright">8</text><text x="590" y="58" class="mid">6</text><text x="590" y="72">1</text><text x="590" y="86" class="dim">9</text><text x="590" y="100" class="dim">5</text></g>
    <g class="c31"><text x="610" y="16" class="dim">7</text><text x="610" y="30">0</text><text x="610" y="44" class="mid">3</text><text x="610" y="58" class="bright">9</text><text x="610" y="72" class="mid">2</text><text x="610" y="86">8</text><text x="610" y="100" class="dim">4</text></g>
    <g class="c32"><text x="630" y="16" class="mid">5</text><text x="630" y="30" class="bright">6</text><text x="630" y="44">1</text><text x="630" y="58" class="mid">4</text><text x="630" y="72">7</text><text x="630" y="86" class="dim">0</text></g>
    <g class="c33"><text x="650" y="16">3</text><text x="650" y="30" class="mid">8</text><text x="650" y="44" class="bright">2</text><text x="650" y="58" class="mid">5</text><text x="650" y="72">9</text><text x="650" y="86" class="dim">1</text><text x="650" y="100" class="dim">6</text></g>
    <g class="c34"><text x="668" y="16" class="dim">0</text><text x="668" y="30">7</text><text x="668" y="44" class="mid">4</text><text x="668" y="58" class="bright">3</text><text x="668" y="72" class="mid">8</text><text x="668" y="86">2</text><text x="668" y="100" class="dim">5</text></g>
  </g>

  <rect width="680" height="220" fill="url(#vignette)" opacity="0.55"/>
  <rect width="680" height="220" fill="url(#glow)"/>

  <text x="340" y="105" text-anchor="middle" font-family="'Courier New', monospace" font-size="44" font-weight="700" fill="#00FF41" letter-spacing="6">JASON OCHOLLA</text>
  <text x="340" y="135" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#00CC33" letter-spacing="3">FULL-STACK DEVELOPER · AI ENGINEER · VIBE CODER</text>
  <text x="340" y="162" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#007700" letter-spacing="2">root@matrix:~# ./initialize.sh ▮</text>
</svg>

<!-- PROFILE VIEWS + FOLLOWERS - LIVE -->
<p>
  <img src="https://komarev.com/ghpvc/?username=Jaja-owiny&label=INTRUSIONS+DETECTED&color=00FF41&style=for-the-badge&labelColor=000000" />
  <img src="https://img.shields.io/github/followers/Jaja-owiny?label=OPERATIVES&style=for-the-badge&color=00FF41&labelColor=000000&logo=github" />
</p>

<!-- TERMINAL TYPING ANIMATION -->
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=800&color=00FF41&background=000000&center=true&vCenter=true&width=750&lines=%5BROOT%40LOCALHOST%5D%23+whoami;%3E+Jason+Ocholla+%7C+Full-Stack+Developer;%3E+AI+Engineer+%7C+Vibe+Coder+%7C+Prompt+Architect;%5BROOT%40LOCALHOST%5D%23+cat+%2Fetc%2Fskills;%3E+Python+%7C+React+%7C+Flask+%7C+Django;%3E+AI+Agents+%7C+LLM+Orchestration+%7C+Data+Science;%5BROOT%40LOCALHOST%5D%23+./deploy_portfolio.sh;%3E+STATUS%3A+LIVE+%E2%9C%93+TARGET+ACQUIRED" width="750" />

</div>

<br/>

<!-- DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## `>> SYS_INFO —— ABOUT THE OPERATOR`

```bash
┌──[root@matrix]─[~]
└──╼ cat /etc/operator.conf

  ALIAS       : Jason Ocholla
  HANDLE      : @Jaja-owiny
  CLASS       : Full-Stack Web Developer | AI Engineer
  BASE        : Nairobi, Kenya 🌍
  UNIVERSITY  : JKUAT — BBIT (Business Information Technology)
  CLEARANCE   : ALX Africa — Data Science (Python + ML)
  PORTFOLIO   : https://jaja-owiny.github.io/Portfolio/
  STATUS      : [ ONLINE ] ██████████ 100%
  OBJECTIVE   : Crafting immersive digital experiences & intelligent systems
  
  >> Systems armed. Awaiting instructions...
```

<div align="center">
  <a href="https://jaja-owiny.github.io/Portfolio/">
    <img src="https://img.shields.io/badge/⚡_PORTFOLIO-BREACH_NOW-00FF41?style=for-the-badge&logo=google-chrome&logoColor=00FF41&labelColor=000000" />
  </a>
  <a href="mailto:your@email.com">
    <img src="https://img.shields.io/badge/📡_COMMS-ESTABLISH_LINK-00FF41?style=for-the-badge&logo=gmail&logoColor=00FF41&labelColor=000000" />
  </a>
  <a href="https://linkedin.com/in/your-linkedin">
    <img src="https://img.shields.io/badge/🔗_LINKEDIN-ACCESS_NODE-00FF41?style=for-the-badge&logo=linkedin&logoColor=00FF41&labelColor=000000" />
  </a>
  <a href="https://github.com/Jaja-owiny">
    <img src="https://img.shields.io/badge/⚙_GITHUB-REPOSITORY_HUB-00FF41?style=for-the-badge&logo=github&logoColor=00FF41&labelColor=000000" />
  </a>
</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## `>> SKILL_TREE —— LOADED MODULES`

```
[SCANNING OPERATOR CAPABILITIES...]  ██████████████████████  COMPLETE
```

### 🖥️ `// FRONTEND`
<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap&theme=dark" />
</p>

### ⚙️ `// BACKEND`
<p align="left">
  <img src="https://skillicons.dev/icons?i=python,flask,django&theme=dark" />
</p>

### 🗄️ `// DATABASES`
<p align="left">
  <img src="https://skillicons.dev/icons?i=mysql,sqlite&theme=dark" />
</p>

### 🛠️ `// TOOLS & ENV`
<p align="left">
  <img src="https://skillicons.dev/icons?i=vscode,git,github,postman,linux&theme=dark" />
</p>

### 🤖 `// AI / NEXT-GEN — UNLOCKED MODULES`

<p align="left">
  <img src="https://img.shields.io/badge/AI_PROMPT_ENGINEERING-MASTERED-00FF41?style=for-the-badge&logo=openai&logoColor=00FF41&labelColor=0D0D0D" />
  <img src="https://img.shields.io/badge/VIBECODING-ACTIVATED-00FF41?style=for-the-badge&logo=lightning&logoColor=00FF41&labelColor=0D0D0D" />
  <img src="https://img.shields.io/badge/AI_AGENTS-DEPLOYED-00FF41?style=for-the-badge&logo=probot&logoColor=00FF41&labelColor=0D0D0D" />
  <img src="https://img.shields.io/badge/LLM_ORCHESTRATION-ONLINE-00FF41?style=for-the-badge&logo=anthropic&logoColor=00FF41&labelColor=0D0D0D" />
  <img src="https://img.shields.io/badge/DATA_SCIENCE-ALX_CERTIFIED-00FF41?style=for-the-badge&logo=python&logoColor=00FF41&labelColor=0D0D0D" />
</p>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## `>> INTEL_BOARD —— LIVE GITHUB STATISTICS`

```
[QUERYING GITHUB API...]  ████████████████████  BREACH SUCCESSFUL
```

<div align="center">

<!-- STREAK STATS — LIVE -->
<a href="https://github.com/Jaja-owiny">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Jaja-owiny&theme=matrix&hide_border=true&background=000000&ring=00FF41&fire=00CC33&currStreakLabel=00FF41&sideLabels=00CC33&currStreakNum=00FF41&sideNums=00FF41&dates=33FF66" width="49%" />
</a>

<!-- OVERALL STATS — LIVE -->
<a href="https://github.com/Jaja-owiny">
  <img src="https://github-readme-stats.vercel.app/api?username=Jaja-owiny&show_icons=true&theme=matrix&hide_border=true&bg_color=000000&title_color=00FF41&icon_color=00FF41&text_color=00CC33&border_color=00FF41" width="49%" />
</a>

<br/>

<!-- TOP LANGUAGES — LIVE -->
<a href="https://github.com/Jaja-owiny">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jaja-owiny&layout=compact&theme=matrix&hide_border=true&bg_color=000000&title_color=00FF41&text_color=00CC33&langs_count=8" width="49%" />
</a>

<!-- TROPHIES — LIVE -->
<a href="https://github.com/Jaja-owiny">
  <img src="https://github-profile-trophy.vercel.app/?username=Jaja-owiny&theme=matrix&no-frame=true&no-bg=true&margin-w=8&margin-h=8&column=4" width="49%" />
</a>

</div>

<br/>

<!-- ACTIVITY GRAPH — LIVE -->
<a href="https://github.com/Jaja-owiny">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Jaja-owiny&theme=matrix&bg_color=000000&color=00FF41&line=00CC33&point=00FF41&area=true&area_color=003300&hide_border=true" width="100%" />
</a>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## `>> CONTRIBUTION_GRID —— SNAKE PROTOCOL`

```
[DEPLOYING SNAKE PROCESS...]  CONSUMING COMMIT HISTORY...
```

> ⚠️ **Setup Required:** Run the GitHub Action below to activate the snake. Once done, the live animation will render automatically.

<div align="center">

<!-- SNAKE — requires GitHub Action setup (see bottom of file) -->
<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Jaja-owiny/Jaja-owiny/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Jaja-owiny/Jaja-owiny/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/Jaja-owiny/Jaja-owiny/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## `>> CLASSIFIED_PROJECTS —— ACTIVE DEPLOYMENTS`

```
[DECRYPTING PROJECT MANIFESTS...]  ██████████████  ACCESS GRANTED
```

<details>
<summary><code>[01] ── 🌐 REACT PORTFOLIO — [ LIVE ]</code></summary>
<br/>

```
TARGET     : Personal Portfolio
STACK      : React • GSAP Animations • Styled Components
STATUS     : ██████████ DEPLOYED
MISSION    : Showcase projects with cinematic transitions & immersive UI
URL        : https://jaja-owiny.github.io/Portfolio/
```

<p>
  <img src="https://img.shields.io/badge/React-000?style=for-the-badge&logo=react&logoColor=00FF41" />
  <img src="https://img.shields.io/badge/GSAP-000?style=for-the-badge&logo=greensock&logoColor=00FF41" />
  <img src="https://img.shields.io/badge/GitHub_Pages-000?style=for-the-badge&logo=github&logoColor=00FF41" />
</p>
</details>

<details>
<summary><code>[02] ── 🔥 DJANGO + MySQL FULLSTACK — [ OPERATIONAL ]</code></summary>
<br/>

```
TARGET     : Full-Stack Web Application
STACK      : Django • MySQL • REST API • Auth System
STATUS     : ██████████ OPERATIONAL
MISSION    : Production-grade backend with admin panel and API endpoints
```

<p>
  <img src="https://img.shields.io/badge/Django-000?style=for-the-badge&logo=django&logoColor=00FF41" />
  <img src="https://img.shields.io/badge/MySQL-000?style=for-the-badge&logo=mysql&logoColor=00FF41" />
  <img src="https://img.shields.io/badge/REST_API-000?style=for-the-badge&logo=fastapi&logoColor=00FF41" />
</p>
</details>

<details>
<summary><code>[03] ── ⚡ JAVASCRIPT UI LIBRARY — [ ACTIVE ]</code></summary>
<br/>

```
TARGET     : Reusable Component Library
STACK      : Vanilla JS • CSS Animations • Modular Architecture
STATUS     : ██████████ ACTIVE
MISSION    : Lightweight, composable UI primitives for rapid deployment
```

<p>
  <img src="https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript&logoColor=00FF41" />
  <img src="https://img.shields.io/badge/CSS3-000?style=for-the-badge&logo=css3&logoColor=00FF41" />
</p>
</details>

<details>
<summary><code>[04] ── 🤖 AI AGENT SYSTEMS — [ IN DEVELOPMENT ]</code></summary>
<br/>

```
TARGET     : Autonomous AI Pipelines
STACK      : Python • LangChain / OpenAI • Flask • Prompt Engineering
STATUS     : ████████░░ BUILDING
MISSION    : Deploy intelligent agents that reason, plan and execute tasks
```

<p>
  <img src="https://img.shields.io/badge/Python-000?style=for-the-badge&logo=python&logoColor=00FF41" />
  <img src="https://img.shields.io/badge/AI_Agents-000?style=for-the-badge&logo=openai&logoColor=00FF41" />
  <img src="https://img.shields.io/badge/Flask-000?style=for-the-badge&logo=flask&logoColor=00FF41" />
</p>
</details>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## `>> COMMS_RELAY —— ESTABLISH CONNECTION`

```
[OPENING SECURE CHANNEL...]  END-TO-END ENCRYPTED  ██  CONNECTED
```

<div align="center">

<a href="https://jaja-owiny.github.io/Portfolio/">
  <img src="https://img.shields.io/badge/🌐_PORTFOLIO-jaja--owiny.github.io-00FF41?style=for-the-badge&labelColor=000000" />
</a>
<a href="mailto:your@email.com">
  <img src="https://img.shields.io/badge/📧_EMAIL-SECURE_CHANNEL-00FF41?style=for-the-badge&logo=protonmail&logoColor=00FF41&labelColor=000000" />
</a>
<a href="https://linkedin.com/in/your-linkedin">
  <img src="https://img.shields.io/badge/💼_LINKEDIN-PROFESSIONAL_NODE-00FF41?style=for-the-badge&logo=linkedin&logoColor=00FF41&labelColor=000000" />
</a>

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

<details>
<summary><code>[⚙] SETUP: SNAKE GITHUB ACTION — click to expand</code></summary>
<br/>

To activate the snake contribution graph, create this file in your profile repo:

**`.github/workflows/snake.yml`**

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: Jaja-owiny
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark&color_snake=00FF41&color_dots=#003300,#005500,#007700,#009900,#00CC33

      - uses: peaceiris/actions-gh-pages@v4
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_branch: output
          publish_dir: dist
          force_orphan: true
```

Then: **Settings → Actions → General → Allow all actions** ✓

</details>

<!-- FOOTER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:000000,50:003300,100:000000&height=120&section=footer&text=root%40matrix%3A%20session%20terminated&fontSize=18&fontColor=00FF41&animation=twinkling&stroke=00FF41&strokeWidth=1" width="100%" />
</div>

<!-- EOF -->
