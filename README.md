<!-- 
 ╔══════════════════════════════════════════════════════════╗
 ║  README.md — Matheus Henrique (@matuzadev)             ║
 ║  Full Stack Engineer · Clean Code Advocate               ║
 ║                                                          ║
 ║  🎨 CUSTOMIZAÇÃO:                                        ║
 ║  • Cores: Busque por #00D97E (verde neon) e troque       ║
 ║  • Textos: Edite os blocos de texto entre as tags        ║
 ║  • Stats: Ajuste valores nos SVGs inline                 ║
 ║  • Links: Atualize URLs no footer                        ║
 ╚══════════════════════════════════════════════════════════╝
-->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════
     HEADER SVG CUSTOMIZADO
     ═══════════════════════════════════════════════════════════ -->
<svg width="100%" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#161b22;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0d1117;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00D97E;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#58A6FF;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background -->
  <rect width="900" height="280" fill="url(#headerGrad)" rx="12"/>
  
  <!-- Grid pattern sutil -->
  <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
    <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#21262d" stroke-width="0.5"/>
  </pattern>
  <rect width="900" height="280" fill="url(#grid)" opacity="0.3"/>
  
  <!-- Linha decorativa superior -->
  <rect x="50" y="30" width="200" height="3" fill="url(#accentGrad)" rx="2" filter="url(#glow)"/>
  
  <!-- Nome principal -->
  <text x="450" y="110" font-family="'SF Pro Display', 'Inter', system-ui, sans-serif" 
        font-size="52" font-weight="800" fill="#f0f6fc" text-anchor="middle" letter-spacing="-1">
    MATHEUS HENRIQUE
  </text>
  
  <!-- Subtítulo com gradiente -->
  <text x="450" y="155" font-family="'SF Mono', 'Fira Code', monospace" 
        font-size="18" fill="url(#accentGrad)" text-anchor="middle" letter-spacing="4">
    FULL STACK ENGINEER
  </text>
  
  <!-- Tagline -->
  <text x="450" y="200" font-family="'Inter', system-ui, sans-serif" 
        font-size="14" fill="#8b949e" text-anchor="middle">
    Building scalable systems · Clean Code · 1% better every day
  </text>
  
  <!-- Linha decorativa inferior -->
  <rect x="650" y="247" width="200" height="3" fill="url(#accentGrad)" rx="2" filter="url(#glow)"/>
  
  <!-- Decoradores geométricos -->
  <circle cx="60" cy="240" r="4" fill="#00D97E" opacity="0.6"/>
  <circle cx="80" cy="240" r="4" fill="#58A6FF" opacity="0.6"/>
  <circle cx="100" cy="240" r="4" fill="#8b949e" opacity="0.4"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════
     TYPING ANIMATION
     ═══════════════════════════════════════════════════════════ -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D97E&center=true&vCenter=true&width=600&lines=Full+Stack+Engineer;Clean+Code+Advocate;Problem+Solver;System+Designer;Always+Learning" alt="Typing SVG" />
</a>

<br/><br/>

<!-- ═══════════════════════════════════════════════════════════
     STACK DIAGRAM (ASCII ART ESTILIZADO)
     ═══════════════════════════════════════════════════════════ -->
<pre align="center">
┌─────────────────────────────────────────────────────────────┐
│                    🏗️  TECH ARCHITECTURE                     │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│   FRONTEND            BACKEND           INFRASTRUCTURE      │
│   ─────────           ───────           ──────────────      │
│   React/Next.js       Node.js/Django    Docker              │
│   TypeScript          Spring Boot       Linux               │
│   Modern CSS          REST/GraphQL      PostgreSQL/MongoDB  │
│                                                             │
│          ╔═══════════════════════════╗                      │
│          ║  CLEAN CODE · 1% BETTER   ║                      │
│          ╚═══════════════════════════╝                      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
</pre>

</div>

---

## ⚡ About Me

<div align="left">

Engenheiro de software focado em construir sistemas escaláveis e código limpo. Transformo problemas complexos em soluções elegantes, sempre buscando evoluir 1% a cada dia.

```javascript
const matheus = {
  code: ["JavaScript", "TypeScript", "Python", "Java", "C#", "C++"],
  currentlyLearning: "System Design & Architecture",
  philosophy: "1% better every day",
  askMeAbout: ["Clean Code", "Design Patterns", "Algorithms", "System Design"],
  funFacts: {
    coffeesPerDay: 4,
    commitsPerWeek: "30+",
    favoriteEditor: "VS Code + Vim motions",
    musicWhileCoding: "Lo-fi Hip Hop"
  }
};
```

</div>

---

## 📊 Unique Analytics

<div align="center">

<!-- ═══════════════════════════════════════════════════════════
     GITHUB STATS + STREAK (lado a lado)
     ═══════════════════════════════════════════════════════════ -->
<img src="https://github-readme-stats.vercel.app/api?username=matuzadev&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00D97E&icon_color=58A6FF&text_color=f0f6fc&rank_icon=percentile" alt="GitHub Stats" height="195"/>
<img src="https://streak-stats.demolab.com?user=matuzadev&theme=tokyonight&hide_border=true&background=0d1117&ring=00D97E&fire=00D97E&currStreakLabel=58A6FF&sideLabels=f0f6fc&dates=8b949e" alt="Streak Stats" height="195"/>

<br/><br/>

<!-- ═══════════════════════════════════════════════════════════
     CODING TIME STATS (WakaTime Style Mock)
     ═══════════════════════════════════════════════════════════ -->
<details open>
<summary align="left"><b>⏱️ Coding Time Analytics</b></summary>
<br/>

<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <rect width="800" height="200" fill="#0d1117" rx="8"/>
  
  <!-- Título -->
  <text x="30" y="35" font-family="'Inter', sans-serif" font-size="14" font-weight="600" fill="#f0f6fc">📈 Weekly Coding Activity</text>
  
  <!-- Barras de atividade -->
  <g transform="translate(30, 55)">
    <!-- Labels -->
    <text x="0" y="15" font-family="monospace" font-size="11" fill="#8b949e">Mon</text>
    <text x="0" y="35" font-family="monospace" font-size="11" fill="#8b949e">Tue</text>
    <text x="0" y="55" font-family="monospace" font-size="11" fill="#8b949e">Wed</text>
    <text x="0" y="75" font-family="monospace" font-size="11" fill="#8b949e">Thu</text>
    <text x="0" y="95" font-family="monospace" font-size="11" fill="#8b949e">Fri</text>
    <text x="0" y="115" font-family="monospace" font-size="11" fill="#8b949e">Sat</text>
    <text x="0" y="135" font-family="monospace" font-size="11" fill="#8b949e">Sun</text>
    
    <!-- Barras -->
    <rect x="50" y="3" width="480" height="16" fill="#00D97E" rx="3" opacity="0.9"/>
    <text x="540" y="15" font-family="monospace" font-size="11" fill="#f0f6fc">8h 24m</text>
    
    <rect x="50" y="23" width="520" height="16" fill="#00D97E" rx="3" opacity="0.9"/>
    <text x="580" y="35" font-family="monospace" font-size="11" fill="#f0f6fc">9h 12m</text>
    
    <rect x="50" y="43" width="440" height="16" fill="#00D97E" rx="3" opacity="0.9"/>
    <text x="500" y="55" font-family="monospace" font-size="11" fill="#f0f6fc">7h 45m</text>
    
    <rect x="50" y="63" width="560" height="16" fill="#00D97E" rx="3" opacity="0.9"/>
    <text x="620" y="75" font-family="monospace" font-size="11" fill="#f0f6fc">9h 50m</text>
    
    <rect x="50" y="83" width="400" height="16" fill="#00D97E" rx="3" opacity="0.9"/>
    <text x="460" y="95" font-family="monospace" font-size="11" fill="#f0f6fc">7h 02m</text>
    
    <rect x="50" y="103" width="320" height="16" fill="#58A6FF" rx="3" opacity="0.7"/>
    <text x="380" y="115" font-family="monospace" font-size="11" fill="#f0f6fc">5h 38m</text>
    
    <rect x="50" y="123" width="200" height="16" fill="#58A6FF" rx="3" opacity="0.5"/>
    <text x="260" y="135" font-family="monospace" font-size="11" fill="#f0f6fc">3h 30m</text>
  </g>
</svg>

</details>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     MOST PRODUCTIVE HOURS (Gráfico de Barras Inline)
     ═══════════════════════════════════════════════════════════ -->
<details open>
<summary align="left"><b>🕐 Most Productive Hours</b></summary>
<br/>

<svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <rect width="800" height="220" fill="#0d1117" rx="8"/>
  
  <text x="30" y="30" font-family="'Inter', sans-serif" font-size="14" font-weight="600" fill="#f0f6fc">⏰ Peak Productivity by Hour</text>
  
  <!-- Eixo X (horas) -->
  <g transform="translate(50, 180)">
    <line x1="0" y1="0" x2="700" y2="0" stroke="#21262d" stroke-width="1"/>
    
    <!-- Labels das horas -->
    <text x="0" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">6am</text>
    <text x="100" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">9am</text>
    <text x="200" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">12pm</text>
    <text x="300" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">3pm</text>
    <text x="400" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">6pm</text>
    <text x="500" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">9pm</text>
    <text x="600" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">12am</text>
    <text x="700" y="20" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">3am</text>
  </g>
  
  <!-- Barras verticais -->
  <g transform="translate(50, 180)">
    <!-- 6am - baixa -->
    <rect x="-15" y="-30" width="30" height="30" fill="#21262d" rx="3"/>
    
    <!-- 9am - alta (manhã produtiva) -->
    <rect x="85" y="-120" width="30" height="120" fill="#00D97E" rx="3" opacity="0.9"/>
    <text x="100" y="-128" font-family="monospace" font-size="10" fill="#00D97E" text-anchor="middle">PEAK</text>
    
    <!-- 12pm - média -->
    <rect x="185" y="-70" width="30" height="70" fill="#58A6FF" rx="3" opacity="0.7"/>
    
    <!-- 3pm - média-alta -->
    <rect x="285" y="-90" width="30" height="90" fill="#00D97E" rx="3" opacity="0.8"/>
    
    <!-- 6pm - baixa -->
    <rect x="385" y="-40" width="30" height="40" fill="#21262d" rx="3"/>
    
    <!-- 9pm - ALTA (noite produtiva) -->
    <rect x="485" y="-140" width="30" height="140" fill="#00D97E" rx="3" opacity="1"/>
    <text x="500" y="-148" font-family="monospace" font-size="10" fill="#00D97E" text-anchor="middle">PEAK</text>
    
    <!-- 12am - média -->
    <rect x="585" y="-60" width="30" height="60" fill="#58A6FF" rx="3" opacity="0.6"/>
    
    <!-- 3am - muito baixa -->
    <rect x="685" y="-15" width="30" height="15" fill="#21262d" rx="3"/>
  </g>
  
  <!-- Legenda -->
  <g transform="translate(580, 30)">
    <rect x="0" y="0" width="12" height="12" fill="#00D97E" rx="2"/>
    <text x="18" y="10" font-family="monospace" font-size="10" fill="#8b949e">High Focus</text>
    <rect x="0" y="18" width="12" height="12" fill="#58A6FF" rx="2" opacity="0.7"/>
    <text x="18" y="28" font-family="monospace" font-size="10" fill="#8b949e">Medium</text>
    <rect x="0" y="36" width="12" height="12"