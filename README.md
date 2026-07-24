<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--         SOFT EMERALD ✦ ANIMATED PIXEL HERO HEADER                   -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=18&duration=3200&pause=1200&color=D4AF37&center=true&vCenter=true&width=750&height=70&lines=HI%2C+I'M+RASHMIKA+%F0%9F%8C%B8;AI+%2B+FULL-STACK+DEVELOPER;WELCOME+TO+MY+WORLD" alt="Typing SVG" />

<!--
  IMPORTANT SETUP NOTE (delete once done):
  This SVG references your character art at:
    https://raw.githubusercontent.com/narlarashmika05/narlarashmika05/main/assets/profile.png
  1. Commit your uploaded image to  assets/profile.png  in this repo.
  2. If your default branch is "master" instead of "main", change that word
     in the href="" URL below (search this file for "raw.githubusercontent").
  3. The animation only looks right if the PNG background is transparent.
     If it currently has a solid white background, remove it first
     (e.g. remove.bg, Photopea "magic wand" + delete, or any bg-removal tool).
-->

<svg width="420" height="560" viewBox="0 0 420 560" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" style="image-rendering: pixelated;">
  <defs>
    <pattern id="lattice2" x="0" y="0" width="36" height="36" patternUnits="userSpaceOnUse">
      <line x1="0" y1="0" x2="36" y2="36" stroke="#D4AF3722" stroke-width="0.6"/>
      <line x1="36" y1="0" x2="0" y2="36" stroke="#D4AF3722" stroke-width="0.6"/>
    </pattern>
    <linearGradient id="softBg2" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0b1f16"/>
      <stop offset="100%" stop-color="#123024"/>
    </linearGradient>
    <radialGradient id="auraGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#F5C2C2" stop-opacity="0.55"/>
      <stop offset="60%" stop-color="#D4AF37" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#D4AF37" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <!-- background -->
  <rect width="420" height="560" fill="url(#softBg2)"/>
  <rect width="420" height="560" fill="url(#lattice2)"/>

  <!-- ambient stars, twinkling independently -->
  <rect x="30" y="40" width="5" height="5" fill="#F5C2C2" opacity="0.8">
    <animate attributeName="opacity" values="0.2;0.9;0.2" dur="2.4s" repeatCount="indefinite"/>
  </rect>
  <rect x="370" y="70" width="5" height="5" fill="#F5C2C2" opacity="0.5">
    <animate attributeName="opacity" values="0.8;0.1;0.8" dur="3.1s" repeatCount="indefinite"/>
  </rect>
  <rect x="55" y="480" width="5" height="5" fill="#D4AF37" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.9;0.2" dur="2.8s" repeatCount="indefinite"/>
  </rect>
  <rect x="360" y="490" width="5" height="5" fill="#D4AF37" opacity="0.6">
    <animate attributeName="opacity" values="0.9;0.2;0.9" dur="2.1s" repeatCount="indefinite"/>
  </rect>

  <!-- ambient power aura, pulsing continuously behind her -->
  <circle cx="210" cy="300" r="120" fill="url(#auraGlow)">
    <animate attributeName="r" values="110;135;110" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.9;0.6" dur="3s" repeatCount="indefinite"/>
  </circle>

  <!-- ring pulses, staggered -->
  <circle cx="210" cy="300" r="100" fill="none" stroke="#D4AF37" stroke-width="2" opacity="0">
    <animate attributeName="r" values="60;150" dur="3s" begin="0s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0" dur="3s" begin="0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="210" cy="300" r="100" fill="none" stroke="#F5C2C2" stroke-width="2" opacity="0">
    <animate attributeName="r" values="60;150" dur="3s" begin="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0" dur="3s" begin="1.5s" repeatCount="indefinite"/>
  </circle>

  <!-- ================= HERO GROUP (bob + windup/punch/recoil) ================= -->
  <g>
    <!-- idle bob, continuous -->
    <animateTransform attributeName="transform" type="translate" values="0 0; 0 -5; 0 0" dur="2s" repeatCount="indefinite" additive="sum"/>

    <g>
      <!-- punch windup / thrust / recoil cycle, 4s loop -->
      <animateTransform attributeName="transform" type="rotate"
        values="0 210 470; -5 210 470; 8 210 470; -2 210 470; 0 210 470; 0 210 470"
        keyTimes="0; 0.45; 0.55; 0.62; 0.72; 1"
        dur="4s" repeatCount="indefinite" additive="sum"/>
      <animateTransform attributeName="transform" type="translate"
        values="0 0; -4 0; 22 0; -6 0; 0 0; 0 0"
        keyTimes="0; 0.45; 0.55; 0.62; 0.72; 1"
        dur="4s" repeatCount="indefinite" additive="sum"/>

      <!-- your pixel character -->
      <image href="https://raw.githubusercontent.com/narlarashmika05/narlarashmika05/main/assets/profile.png"
             xlink:href="https://raw.githubusercontent.com/narlarashmika05/narlarashmika05/main/assets/profile.png"
             x="90" y="150" width="240" height="330" preserveAspectRatio="xMidYMid meet"/>
    </g>
  </g>

  <!-- ================= FIST OVERLAY (only visible during the punch) ================= -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.5;0.55;0.65;0.72;1" dur="4s" repeatCount="indefinite"/>
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="200 300; 200 300; 280 300; 300 295; 200 300; 200 300"
        keyTimes="0;0.5;0.58;0.63;0.72;1"
        dur="4s" repeatCount="indefinite"/>
      <!-- simple pixel fist: sleeve cuff + fist block -->
      <rect x="-14" y="-10" width="18" height="18" fill="#0f2e22"/>
      <rect x="2" y="-14" width="22" height="24" fill="#d99a6c"/>
      <rect x="6" y="-18" width="6" height="6" fill="#d99a6c"/>
      <rect x="14" y="-18" width="6" height="6" fill="#d99a6c"/>
    </g>
  </g>

  <!-- ================= IMPACT BURST (star + POW text + sparks) ================= -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;0;1;0;0" keyTimes="0;0.58;0.62;0.7;1" dur="4s" repeatCount="indefinite"/>
    <g transform="translate(300,290)">
      <animateTransform attributeName="transform" type="scale" values="0.4;1.3;1" keyTimes="0;0.6;1" dur="4s" repeatCount="indefinite" additive="sum"/>
      <polygon points="0,-22 6,-6 22,0 6,6 0,22 -6,6 -22,0 -6,-6" fill="#D4AF37"/>
      <text x="0" y="5" font-family="monospace" font-size="10" fill="#0b1f16" text-anchor="middle" font-weight="bold">POW</text>
    </g>

    <!-- sparks flying outward -->
    <rect x="298" y="288" width="6" height="6" fill="#F5C2C2">
      <animateMotion path="M0,0 L40,-25" dur="4s" keyTimes="0;1" begin="0s" repeatCount="indefinite"/>
    </rect>
    <rect x="298" y="288" width="6" height="6" fill="#D4AF37">
      <animateMotion path="M0,0 L45,10" dur="4s" repeatCount="indefinite"/>
    </rect>
    <rect x="298" y="288" width="6" height="6" fill="#F5C2C2">
      <animateMotion path="M0,0 L20,40" dur="4s" repeatCount="indefinite"/>
    </rect>
  </g>

  <rect x="0" y="530" width="420" height="6" fill="#D4AF37" opacity="0.18"/>
  <text x="210" y="550" font-family="monospace" font-size="10" fill="#D4AF37" text-anchor="middle" opacity="0.85">
    ✦ CODE, CRAFTED WITH CARE ✦
  </text>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                        ABOUT ME SECTION                            -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<table>
<tr>
<td width="50%" valign="top">

### 🌸 `whoami`

```
┌──────────────────────────────────────┐
│  > Name    : Rashmika Narla          │
│  > Role    : AI & Full-Stack Dev     │
│  > Base    : Hyderabad, India        │
│  > Focus   : AI / ML + Full Stack    │
└──────────────────────────────────────┘
```

</td>
<td width="50%" valign="top">

### 🍃 `what_i_build`

```python
class Dev:
    name  = "Rashmika Narla"
    focus = "AI/ML + Full Stack"

    def daily_routine(self):
        return [
            "☕ Coffee",
            "🧠 Train models",
            "💻 Build full-stack",
            "🐛 Debug",
            "🚀 Ship"
        ]
```

</td>
</tr>
</table>

<!-- ================= FUN "POWER LEVEL" HUD BAR ================= -->
<div align="center">

<svg width="500" height="60" viewBox="0 0 500 60" xmlns="http://www.w3.org/2000/svg">
  <rect width="500" height="60" fill="#0b1f16"/>
  <text x="10" y="20" font-family="monospace" font-size="11" fill="#D4AF37">POWER LEVEL</text>
  <rect x="10" y="30" width="480" height="14" fill="#123024" stroke="#D4AF37" stroke-width="1"/>
  <rect x="12" y="32" width="0" height="10" fill="#F5C2C2">
    <animate attributeName="width" from="0" to="410" dur="2s" begin="0.3s" fill="freeze"/>
  </rect>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                       TECH STACK (Soft Pixel Style)                -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

### ✦ `tech_stack --list`

<img src="https://skillicons.dev/icons?i=java,python,js,react,spring,flask,html,css,mysql,mongodb,git,github&theme=dark&perline=12" />

**AI / ML:** TensorFlow · Scikit-learn · PyTorch · HuggingFace Transformers · Ollama · NLP
**Core CS:** DSA · OOP · DBMS · Operating Systems · Computer Networks

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                        GITHUB STATS                                -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

### 📊 `github --stats`

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=narlarashmika05&show_icons=true&theme=radical&hide_border=true&bg_color=0b1f16&title_color=D4AF37&icon_color=F5C2C2&text_color=FFFFFF&ring_color=D4AF37" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=narlarashmika05&theme=radical&hide_border=true&background=0b1f16&ring=D4AF37&fire=F5C2C2&currStreakLabel=D4AF37&sideLabels=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=888888" />
</p>

<p align="center">
  <img width="45%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=narlarashmika05&layout=compact&theme=radical&hide_border=true&bg_color=0b1f16&title_color=D4AF37&text_color=FFFFFF" />
</p>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                     ACTIVITY GRAPH                                 -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

### 💫 `contribution --graph`

<img src="https://github-readme-activity-graph.vercel.app/graph?username=narlarashmika05&bg_color=0b1f16&color=D4AF37&line=F5C2C2&point=FFFFFF&area=true&area_color=D4AF3722&hide_border=true" width="100%"/>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                         FEATURED PROJECTS                          -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

### 💎 `featured --projects`

<table>
<tr>
<td width="33%" valign="top">

**🧠 TalentVantage**
AI Resume Screening & Candidate Matching Platform
`Python` `Streamlit` `HuggingFace` `PyTorch` `Ollama`
BERT embeddings + cosine similarity for semantic candidate–job matching, with an LLM assistant for summaries & interview questions.

</td>
<td width="33%" valign="top">

**🌾 Crop Fertilizer & Disease Predictor**
Agricultural ML application
`Python` `Flask` `TensorFlow` `Scikit-learn` `MongoDB`
Classification-based crop & fertilizer recommendation with disease prediction.

</td>
<td width="33%" valign="top">

**⚔️ SkillSync**
Technical Interview Prep & Assessment Platform
`Java` `Spring Boot` `React.js` `JWT` `MySQL`
Full-stack platform with secure auth, DSA progress tracking, and mock assessments.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                     TROPHIES / ACHIEVEMENTS                        -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

### 🏆 `achievements --trophies`

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=narlarashmika05&theme=radical&no-frame=true&no-bg=true&margin-w=4&column=7" />
</p>

- 🌸 Participant, PwC Women Leadership Development Program — 2025
- 🍃 CSI Member — 2025
- 🤝 NGO Volunteer — fundraising & awareness campaigns, Hyderabad
- 📜 Red Hat Certified — *Programming in Java EE*
- 📜 Full-Stack Web Development Certification
- 📜 Juniper Networks — Networking Virtual Internship

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                        SNAKE ANIMATION                             -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

### ✨ `watch the garden grow`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/narlarashmika05/narlarashmika05/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/narlarashmika05/narlarashmika05/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/narlarashmika05/narlarashmika05/output/github-contribution-grid-snake-dark.svg" />
</picture>

> ⚠️ *This animation requires a one-time GitHub Actions setup — see the note below.*

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                     CONNECT / SOCIAL                               -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

### 🌸 `./connect --with-me`

<p align="center">
  <a href="https://github.com/narlarashmika05">
    <img src="https://img.shields.io/badge/GitHub-narlarashmika05-D4AF37?style=for-the-badge&logo=github&logoColor=white&labelColor=0b1f16"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/narla-rashmika26">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-D4AF37?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b1f16"/>
  </a>
  &nbsp;
  <a href="mailto:narlarashmika05@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D4AF37?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0b1f16"/>
  </a>
</p>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                     PIXEL FOOTER                                   -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="40" viewBox="0 0 800 40" xmlns="http://www.w3.org/2000/svg">
  <rect width="800" height="40" fill="#0b1f16"/>
  <text x="400" y="26" font-family="monospace" font-size="11" fill="#D4AF37" text-anchor="middle" opacity="0.85">
    ✦ thanks for stopping by ✦
  </text>
</svg>

![Profile Views](https://komarev.com/ghpvc/?username=narlarashmika05&color=D4AF37&style=for-the-badge&label=VISITORS)

</div>
