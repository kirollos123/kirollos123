<!--
═══════════════════════════════════════════════════════════════
  PREMIUM GITHUB PROFILE README  –  v3.0
  Designed for Kirollos Nabil
  Style: Dark · Glassmorphism · Blue · Purple · Minimal
  Inspired by Apple, Stripe, Linear, Vercel
═══════════════════════════════════════════════════════════════
-->

<!-- ─── HERO SECTION ─── -->
<div align="center">

  <!-- Animated Wave Header (SVG) -->
  <svg width="100%" height="120" viewBox="0 0 1200 120" preserveAspectRatio="none" style="display:block; margin-bottom:-20px;">
    <defs>
      <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"   stop-color="#2563eb" />
        <stop offset="50%"  stop-color="#06b6d4" />
        <stop offset="100%" stop-color="#8b5cf6" />
      </linearGradient>
      <linearGradient id="waveGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"   stop-color="#8b5cf6" />
        <stop offset="50%"  stop-color="#2563eb" />
        <stop offset="100%" stop-color="#06b6d4" />
      </linearGradient>
      <filter id="glowWave" x="-10%" y="-10%" width="120%" height="130%">
        <feGaussianBlur stdDeviation="6" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
    </defs>
    <path d="M0,80 C300,20 600,120 900,40 C1050,10 1150,50 1200,30 L1200,120 L0,120 Z"
          fill="url(#waveGrad)" opacity="0.25" filter="url(#glowWave)">
      <animate attributeName="d"
               values="M0,80 C300,20 600,120 900,40 C1050,10 1150,50 1200,30 L1200,120 L0,120 Z;
                       M0,60 C300,110 600,10 900,70 C1050,100 1150,30 1200,50 L1200,120 L0,120 Z;
                       M0,80 C300,20 600,120 900,40 C1050,10 1150,50 1200,30 L1200,120 L0,120 Z"
               dur="8s" repeatCount="indefinite" />
    </path>
    <path d="M0,90 C250,30 550,110 850,50 C1020,20 1120,60 1200,40 L1200,120 L0,120 Z"
          fill="url(#waveGrad2)" opacity="0.18" filter="url(#glowWave)">
      <animate attributeName="d"
               values="M0,90 C250,30 550,110 850,50 C1020,20 1120,60 1200,40 L1200,120 L0,120 Z;
                       M0,70 C250,100 550,20 850,80 C1020,110 1120,40 1200,60 L1200,120 L0,120 Z;
                       M0,90 C250,30 550,110 850,50 C1020,20 1120,60 1200,40 L1200,120 L0,120 Z"
               dur="10s" repeatCount="indefinite" />
    </path>
  </svg>

  <!-- Profile Picture Placeholder with Animated Ring -->
  <div style="position:relative; display:inline-block; margin-top:-10px;">
    <svg width="140" height="140" viewBox="0 0 140 140">
      <defs>
        <linearGradient id="ringGrad" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%"   stop-color="#2563eb" />
          <stop offset="50%"  stop-color="#06b6d4" />
          <stop offset="100%" stop-color="#8b5cf6" />
        </linearGradient>
        <filter id="ringGlow">
          <feGaussianBlur stdDeviation="3" result="blur" />
          <feMerge>
            <feMergeNode in="blur" />
            <feMergeNode in="SourceGraphic" />
          </feMerge>
        </filter>
        <clipPath id="profileClip">
          <circle cx="70" cy="70" r="58" />
        </clipPath>
      </defs>
      <!-- outer glow ring -->
      <circle cx="70" cy="70" r="62" fill="none" stroke="url(#ringGrad)" stroke-width="3"
              filter="url(#ringGlow)" opacity="0.7">
        <animate attributeName="stroke-opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite" />
      </circle>
      <circle cx="70" cy="70" r="62" fill="none" stroke="url(#ringGrad)" stroke-width="1.5" opacity="0.3">
        <animate attributeName="r" values="62;66;62" dur="4s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="0.3;0.6;0.3" dur="4s" repeatCount="indefinite" />
      </circle>
      <!-- Profile Image Placeholder -->
      <circle cx="70" cy="70" r="58" fill="#1e293b" />
      <circle cx="70" cy="70" r="58" fill="url(#ringGrad)" opacity="0.08" />
      <g clip-path="url(#profileClip)">
        <rect x="0" y="0" width="140" height="140" fill="#0f172a" />
        <circle cx="70" cy="70" r="58" fill="url(#ringGrad)" opacity="0.15" />
        <text x="70" y="82" font-family="system-ui, sans-serif" font-size="44" font-weight="700"
              fill="white" text-anchor="middle" letter-spacing="2">KN</text>
      </g>
    </svg>
  </div>

  <!-- Typing Animation (SVG) -->
  <svg width="100%" height="60" viewBox="0 0 600 60" style="max-width:600px; margin:8px auto 4px;">
    <defs>
      <linearGradient id="typeGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"   stop-color="#60a5fa" />
        <stop offset="50%"  stop-color="#22d3ee" />
        <stop offset="100%" stop-color="#a78bfa" />
      </linearGradient>
    </defs>
    <text x="0" y="38" font-family="system-ui, -apple-system, sans-serif" font-size="28" font-weight="600"
          fill="url(#typeGrad)" letter-spacing="0.5">
      <tspan>Backend </tspan>
      <tspan fill="#f1f5f9">Developer </tspan>
      <tspan fill="url(#typeGrad)">& </tspan>
      <tspan fill="#f1f5f9">Data Engineer </tspan>
      <tspan fill="#94a3b8" font-weight="400">· </tspan>
      <tspan fill="#e2e8f0" font-weight="400">in the making</tspan>
      <tspan fill="#22d3ee" font-weight="300">|</tspan>
      <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite" />
    </text>
  </svg>

  <!-- Tagline -->
  <p style="color:#94a3b8; font-size:1.1rem; max-width:520px; margin:0 auto 1.2rem; letter-spacing:0.3px; font-weight:300;">
    Crafting scalable APIs · Designing data pipelines · Football analytics enthusiast
  </p>

  <!-- Social Icons + Visitor Counter + Buttons -->
  <div style="display:flex; flex-wrap:wrap; justify-content:center; align-items:center; gap:1rem 1.8rem; margin:1.5rem 0 0.8rem;">

    <!-- Visitor Counter -->
    <div style="display:flex; align-items:center; gap:6px; background:rgba(255,255,255,0.04); backdrop-filter:blur(8px); padding:0.4rem 1.2rem; border-radius:40px; border:1px solid rgba(255,255,255,0.06);">
      <span style="color:#64748b; font-size:0.85rem;">👁️</span>
      <span style="color:#e2e8f0; font-size:0.9rem; font-weight:500;">2,847</span>
      <span style="color:#475569; font-size:0.7rem; font-weight:300;">visitors</span>
    </div>

    <!-- Social Icons -->
    <a href="https://github.com/kirollosnabil" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">🐙</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">🐦</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">🔗</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">💼</a>

    <!-- Buttons -->
    <a href="#" style="display:inline-block; padding:0.5rem 1.6rem; border-radius:40px; background:linear-gradient(135deg,#2563eb,#7c3aed); color:white; font-weight:500; font-size:0.9rem; text-decoration:none; border:none; box-shadow:0 4px 20px rgba(37,99,235,0.25); transition:all 0.25s;">📄 Resume</a>
    <a href="mailto:kirollos@example.com" style="display:inline-block; padding:0.5rem 1.6rem; border-radius:40px; background:rgba(255,255,255,0.06); backdrop-filter:blur(8px); color:#e2e8f0; font-weight:500; font-size:0.9rem; text-decoration:none; border:1px solid rgba(255,255,255,0.08); transition:all 0.25s;">✉️ Contact</a>
  </div>

  <hr style="width:80px; margin:2.2rem auto 1.8rem; border:none; height:1px; background:linear-gradient(90deg,transparent,#334155,transparent);" />
</div>

<!-- ─── ABOUT ME ─── -->
<div style="background:rgba(255,255,255,0.02); backdrop-filter:blur(12px); border-radius:28px; padding:2rem 2.5rem; margin:2rem 0; border:1px solid rgba(255,255,255,0.05); box-shadow:0 20px 60px rgba(0,0,0,0.4);">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.4rem;">
    <span style="font-size:1.8rem;">🧑‍💻</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">About Me</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <div style="display:grid; grid-template-columns:1fr 1fr; gap:2rem;">

    <!-- Left Column -->
    <div>
      <p style="color:#cbd5e1; font-size:1rem; line-height:1.7; margin-bottom:1.2rem;">
        I'm <strong style="color:#f1f5f9;">Kirollos Nabil</strong>, a final‑year Software Development student from <strong style="color:#60a5fa;">Egypt 🇪🇬</strong> with a strong passion for <strong style="color:#22d3ee;">backend engineering</strong> and <strong style="color:#a78bfa;">data engineering</strong>.
      </p>
      <p style="color:#94a3b8; font-size:0.95rem; line-height:1.7; margin-bottom:1.2rem;">
        I enjoy designing APIs, databases, and scalable backend architectures more than building user interfaces. I believe in learning by building real projects — they teach more than any tutorial.
      </p>
      <div style="display:flex; flex-wrap:wrap; gap:0.8rem 1.8rem; margin:1.2rem 0 1rem; font-size:0.9rem; color:#94a3b8;">
        <span>🎯 <span style="color:#e2e8f0;">Currently:</span> Backend Developer &amp; Student</span>
        <span>🧭 <span style="color:#e2e8f0;">Mission:</span> Build scalable data platforms for football analytics</span>
        <span>📌 <span style="color:#e2e8f0;">Values:</span> Clean Code · Continuous Learning · Impact</span>
      </div>
      <!-- Mini Timeline -->
      <div style="margin-top:1.2rem; padding-left:0.5rem;">
        <div style="display:flex; gap:1.2rem; align-items:center; margin-bottom:0.6rem;">
          <span style="color:#475569; font-size:0.7rem; min-width:60px;">2025 →</span>
          <span style="color:#cbd5e1; font-size:0.9rem;">Backend Developer (Freelance &amp; Projects)</span>
        </div>
        <div style="display:flex; gap:1.2rem; align-items:center; margin-bottom:0.6rem;">
          <span style="color:#475569; font-size:0.7rem; min-width:60px;">2023–2025</span>
          <span style="color:#cbd5e1; font-size:0.9rem;">B.Sc. Software Development (Final Year)</span>
        </div>
        <div style="display:flex; gap:1.2rem; align-items:center;">
          <span style="color:#475569; font-size:0.7rem; min-width:60px;">2022–2023</span>
          <span style="color:#cbd5e1; font-size:0.9rem;">First Steps in Python &amp; Backend</span>
        </div>
      </div>
    </div>

    <!-- Right Column: Career Goal & Mission -->
    <div style="background:rgba(255,255,255,0.02); border-radius:20px; padding:1.2rem 1.6rem; border:1px solid rgba(255,255,255,0.04);">
      <div style="display:flex; gap:1.5rem; flex-wrap:wrap;">
        <div style="flex:1; min-width:120px;">
          <div style="color:#475569; font-size:0.7rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:4px;">Career Goal</div>
          <p style="color:#e2e8f0; font-size:0.95rem; line-height:1.5;">Become a Data Engineer specialising in scalable systems and football analytics.</p>
        </div>
        <div style="flex:1; min-width:120px;">
          <div style="color:#475569; font-size:0.7rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:4px;">Long‑term Dream</div>
          <p style="color:#e2e8f0; font-size:0.95rem; line-height:1.5;">Work as a Data Engineer in the football industry, building data platforms and analytics systems for clubs and organisations.</p>
        </div>
      </div>
      <div style="margin-top:1rem; display:flex; gap:0.6rem; flex-wrap:wrap;">
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(37,99,235,0.12); color:#60a5fa; font-size:0.75rem; border:1px solid rgba(37,99,235,0.1);">#backend</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(6,182,212,0.12); color:#22d3ee; font-size:0.75rem; border:1px solid rgba(6,182,212,0.1);">#dataengineering</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(139,92,246,0.12); color:#a78bfa; font-size:0.75rem; border:1px solid rgba(139,92,246,0.1);">#footballanalytics</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#94a3b8; font-size:0.75rem; border:1px solid rgba(255,255,255,0.06);">#cloud</span>
      </div>
    </div>
  </div>
</div>

<!-- ─── TECH STACK ─── -->
<div style="margin:2.8rem 0 2rem;">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
    <span style="font-size:1.8rem;">⚡</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Tech Stack</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <!-- Grid of Tech Cards -->
  <div style="display:grid; grid-template-columns:repeat(auto-fill, minmax(160px,1fr)); gap:1rem;">

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Languages</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">Python</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Java</span>
        <span style="color:#94a3b8; font-size:0.8rem;">C++</span>
        <span style="color:#94a3b8; font-size:0.8rem;">SQL</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Backend</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">FastAPI</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Django</span>
        <span style="color:#94a3b8; font-size:0.8rem;">REST APIs</span>
        <span style="color:#94a3b8; font-size:0.8rem;">JWT</span>
        <span style="color:#94a3b8; font-size:0.8rem;">WebSockets</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Databases</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">PostgreSQL</span>
        <span style="color:#94a3b8; font-size:0.8rem;">MySQL</span>
        <span style="color:#94a3b8; font-size:0.8rem;">SQLite</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Database Design</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">DevOps</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">Docker</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Git</span>
        <span style="color:#94a3b8; font-size:0.8rem;">GitHub Actions</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Linux</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Bash</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Cloud</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">AWS (Learning)</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Cloud Fundamentals</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Deployment</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Data Engineering</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">SQL</span>
        <span style="color:#94a3b8; font-size:0.8rem;">ETL</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Data Modeling</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Airflow (Learning)</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Spark (Learning)</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Software Engineering</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">OOP</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Data Structures</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Algorithms</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Clean Code</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Design Patterns</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
      <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Tools</div>
      <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
        <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">VS Code</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Postman</span>
        <span style="color:#94a3b8; font-size:0.8rem;">GitHub</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Docker Desktop</span>
        <span style="color:#94a3b8; font-size:0.8rem;">Linux Terminal</span>
      </div>
    </div>

  </div>
</div>

<!-- ─── DEVELOPER DASHBOARD ─── -->
<div style="margin:2.8rem 0 2rem;">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
    <span style="font-size:1.8rem;">🧩</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Developer Dashboard</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <div style="display:grid; grid-template-columns:1fr 1fr 1fr; gap:1.2rem;">

    <!-- Widget: Developer Level -->
    <div style="background:rgba(255,255,255,0.02); border-radius:22px; padding:1.2rem 1.4rem; border:1px solid rgba(255,255,255,0.04);">
      <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:0.4rem;">
        <span style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px;">Developer Level</span>
        <span style="color:#fbbf24; font-size:1.2rem; font-weight:700;">Lv. 18</span>
      </div>
      <div style="height:6px; background:rgba(255,255,255,0.06); border-radius:6px; overflow:hidden;">
        <div style="width:62%; height:100%; background:linear-gradient(90deg,#2563eb,#a78bfa); border-radius:6px;"></div>
      </div>
      <div style="display:flex; justify-content:space-between; margin-top:6px; color:#475569; font-size:0.6rem;">
        <span>XP 4,200 / 6,800</span>
        <span>⏳ 62%</span>
      </div>
    </div>

    <!-- Widget: Current Mission -->
    <div style="background:rgba(255,255,255,0.02); border-radius:22px; padding:1.2rem 1.4rem; border:1px solid rgba(255,255,255,0.04);">
      <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:4px;">🎯 Current Mission</div>
      <div style="color:#e2e8f0; font-size:0.95rem; font-weight:500;">Build a Football Analytics Platform</div>
      <div style="display:flex; gap:0.8rem; margin-top:6px; font-size:0.7rem; color:#475569;">
        <span>⏱️ 4 weeks remaining</span>
        <span>📋 8 / 15 tasks</span>
      </div>
    </div>

    <!-- Widget: Next Goal -->
    <div style="background:rgba(255,255,255,0.02); border-radius:22px; padding:1.2rem 1.4rem; border:1px solid rgba(255,255,255,0.04);">
      <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:4px;">🏁 Next Goal</div>
      <div style="color:#e2e8f0; font-size:0.95rem; font-weight:500;">Deploy first ETL pipeline on AWS</div>
      <div style="display:flex; gap:0.8rem; margin-top:6px; font-size:0.7rem; color:#475569;">
        <span>✅ 30% done</span>
        <span>📈 learning Airflow</span>
      </div>
    </div>

  </div>
</div>

<!-- ─── FOOTBALL ANALYTICS WIDGET ─── -->
<div style="margin:2.8rem 0 2rem;">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
    <span style="font-size:1.8rem;">⚽</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Football Analytics Focus</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <div style="display:grid; grid-template-columns:1fr 1fr; gap:1.4rem;">

    <div style="background:linear-gradient(145deg, rgba(37,99,235,0.08), rgba(139,92,246,0.05)); backdrop-filter:blur(12px); border-radius:28px; padding:1.6rem; border:1px solid rgba(255,255,255,0.06); box-shadow:0 12px 48px rgba(0,0,0,0.3);">
      <div style="display:flex; align-items:center; gap:1rem; margin-bottom:1rem;">
        <div style="width:50px; height:50px; border-radius:50%; background:linear-gradient(135deg,#2563eb,#7c3aed); display:flex; align-items:center; justify-content:center; font-size:1.4rem; font-weight:700; color:white;">⚽</div>
        <div>
          <div style="color:#f1f5f9; font-size:1rem; font-weight:600;">Match Data Model</div>
          <div style="color:#94a3b8; font-size:0.75rem; letter-spacing:0.5px;">PostgreSQL · ETL · Analytics</div>
        </div>
      </div>
      <div style="display:grid; grid-template-columns:1fr 1fr 1fr; gap:0.4rem 1rem; margin:0.8rem 0;">
        <div><span style="color:#64748b; font-size:0.65rem;">Passes</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">89%</span></div>
        <div><span style="color:#64748b; font-size:0.65rem;">Possession</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">58%</span></div>
        <div><span style="color:#64748b; font-size:0.65rem;">xG</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">1.8</span></div>
      </div>
      <div style="height:4px; background:rgba(255,255,255,0.06); border-radius:4px; overflow:hidden; margin:0.6rem 0;">
        <div style="width:72%; height:100%; background:linear-gradient(90deg,#2563eb,#22d3ee); border-radius:4px;"></div>
      </div>
      <div style="display:flex; gap:0.6rem; flex-wrap:wrap; margin-top:0.6rem;">
        <span style="padding:0.1rem 0.8rem; border-radius:40px; background:rgba(255,215,0,0.08); color:#fbbf24; font-size:0.6rem; border:1px solid rgba(255,215,0,0.06);">📊 Data Pipeline</span>
        <span style="padding:0.1rem 0.8rem; border-radius:40px; background:rgba(34,211,238,0.08); color:#22d3ee; font-size:0.6rem; border:1px solid rgba(34,211,238,0.06);">🔍 Performance</span>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.015); backdrop-filter:blur(8px); border-radius:28px; padding:1.4rem 1.6rem; border:1px solid rgba(255,255,255,0.04);">
      <div style="display:flex; justify-content:space-between; margin-bottom:1rem;">
        <span style="color:#64748b; font-size:0.65rem; letter-spacing:0.5px;">📈 CURRENT SEASON</span>
        <span style="color:#22d3ee; font-size:0.75rem; font-weight:500;">▸ in progress</span>
      </div>
      <div style="display:grid; grid-template-columns:1fr 1fr 1fr; gap:1rem; margin-bottom:1.2rem;">
        <div><span style="color:#475569; font-size:0.6rem;">Matches</span><div style="color:#e2e8f0; font-size:1.2rem; font-weight:600;">24</div></div>
        <div><span style="color:#475569; font-size:0.6rem;">Goals</span><div style="color:#22d3ee; font-size:1.2rem; font-weight:600;">42</div></div>
        <div><span style="color:#475569; font-size:0.6rem;">Assists</span><div style="color:#fbbf24; font-size:1.2rem; font-weight:600;">18</div></div>
      </div>
      <div style="display:flex; gap:0.8rem; font-size:0.75rem; color:#64748b;">
        <span>🏆 Top Scorer</span>
        <span>📊 xG: 1.6</span>
        <span>🔄 Form: W W D L W</span>
      </div>
    </div>

  </div>
</div>

<!-- ─── GITHUB METRICS ─── -->
<div style="margin:2.8rem 0 2rem;">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
    <span style="font-size:1.8rem;">📊</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">GitHub Metrics</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <!-- Replace USERNAME with your actual GitHub username -->
  <div align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=kirollosnabil&show_icons=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=60a5fa&text_color=e2e8f0&icon_color=22d3ee" alt="GitHub Stats" height="180" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kirollosnabil&layout=compact&hide_border=true&bg_color=0d1117&title_color=60a5fa&text_color=e2e8f0" alt="Top Languages" height="180" />
    <br />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=kirollosnabil&hide_border=true&background=0d1117&stroke=334155&ring=2563eb&fire=22d3ee&currStreakNum=e2e8f0&sideNums=e2e8f0&currStreakLabel=60a5fa&sideLabels=94a3b8" alt="GitHub Streak" height="180" />
  </div>

  <!-- Contribution Graph Placeholder -->
  <div style="background:rgba(255,255,255,0.015); border-radius:20px; padding:1.2rem 1rem; border:1px solid rgba(255,255,255,0.04); margin:1.4rem 0;">
    <svg width="100%" height="80" viewBox="0 0 800 80" style="display:block;">
      <rect x="0" y="0" width="800" height="80" rx="12" fill="rgba(255,255,255,0.02)" />
      <g fill="#1e293b">
        <rect x="20" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.9" />
        <rect x="32" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.3" />
        <rect x="44" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.7" />
        <rect x="56" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.4" />
        <rect x="68" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.95" />
        <rect x="80" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.2" />
        <rect x="92" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.8" />
        <rect x="104" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.6" />
        <rect x="116" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.5" />
        <rect x="128" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.3" />
        <rect x="140" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.9" />
        <rect x="152" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.7" />
        <rect x="164" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.4" />
        <rect x="176" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.6" />
        <rect x="188" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.95" />
        <rect x="200" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.2" />
        <rect x="212" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.8" />
        <rect x="224" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.7" />
        <rect x="236" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.5" />
        <rect x="248" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.9" />
        <rect x="260" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.4" />
        <rect x="272" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.6" />
        <rect x="284" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.3" />
        <rect x="296" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.95" />
        <rect x="308" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.7" />
        <rect x="320" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.2" />
        <rect x="332" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.8" />
        <rect x="344" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.5" />
        <rect x="356" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.4" />
        <rect x="368" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.9" />
        <rect x="380" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.6" />
        <rect x="392" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.3" />
        <rect x="404" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.7" />
        <rect x="416" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.5" />
        <rect x="428" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.8" />
        <rect x="440" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.9" />
        <rect x="452" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.4" />
        <rect x="464" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.2" />
        <rect x="476" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.7" />
        <rect x="488" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.95" />
        <rect x="500" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.5" />
        <rect x="512" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.6" />
        <rect x="524" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.3" />
        <rect x="536" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.8" />
        <rect x="548" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.4" />
        <rect x="560" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.9" />
        <rect x="572" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.6" />
        <rect x="584" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.2" />
        <rect x="596" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.7" />
        <rect x="608" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.5" />
        <rect x="620" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.3" />
        <rect x="632" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.9" />
        <rect x="644" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.4" />
        <rect x="656" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.8" />
        <rect x="668" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.6" />
        <rect x="680" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.3" />
        <rect x="692" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.95" />
        <rect x="704" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.5" />
        <rect x="716" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.7" />
        <rect x="728" y="20" width="8" height="8" rx="2" fill="#06b6d4" opacity="0.4" />
        <rect x="740" y="20" width="8" height="8" rx="2" fill="#1e3a5f" opacity="0.2" />
        <rect x="752" y="20" width="8" height="8" rx="2" fill="#2563eb" opacity="0.8" />
      </g>
      <text x="20" y="60" fill="#475569" font-size="8" font-family="system-ui">Jan</text>
      <text x="180" y="60" fill="#475569" font-size="8" font-family="system-ui">Mar</text>
      <text x="340" y="60" fill="#475569" font-size="8" font-family="system-ui">May</text>
      <text x="500" y="60" fill="#475569" font-size="8" font-family="system-ui">Jul</text>
      <text x="660" y="60" fill="#475569" font-size="8" font-family="system-ui">Sep</text>
    </svg>
  </div>

  <!-- Trophies -->
  <div style="display:flex; flex-wrap:wrap; gap:0.8rem; justify-content:center;">
    <span style="padding:0.3rem 1.2rem; border-radius:40px; background:rgba(255,215,0,0.08); border:1px solid rgba(255,215,0,0.1); color:#fbbf24; font-size:0.75rem;">🏆 2x Open Source Contributor</span>
    <span style="padding:0.3rem 1.2rem; border-radius:40px; background:rgba(192,132,252,0.08); border:1px solid rgba(192,132,252,0.1); color:#c084fc; font-size:0.75rem;">⭐ 5x Project Stars</span>
    <span style="padding:0.3rem 1.2rem; border-radius:40px; background:rgba(34,211,238,0.08); border:1px solid rgba(34,211,238,0.1); color:#22d3ee; font-size:0.75rem;">🔥 7‑day streak</span>
  </div>
</div>

<!-- ─── FEATURED PROJECTS ─── -->
<div style="margin:2.8rem 0 2rem;">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
    <span style="font-size:1.8rem;">🚀</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Featured Projects</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <div style="display:grid; grid-template-columns:1fr 1fr; gap:1.4rem;">

    <!-- Project 1 -->
    <div style="background:rgba(255,255,255,0.02); backdrop-filter:blur(8px); border-radius:24px; padding:1.5rem; border:1px solid rgba(255,255,255,0.05); box-shadow:0 12px 40px rgba(0,0,0,0.3);">
      <div style="display:flex; justify-content:space-between; align-items:start; margin-bottom:0.8rem;">
        <span style="font-size:2rem;">⚡</span>
        <span style="padding:0.15rem 0.8rem; border-radius:40px; background:rgba(34,211,238,0.1); color:#22d3ee; font-size:0.6rem; letter-spacing:0.5px; border:1px solid rgba(34,211,238,0.08);">Graduation Project</span>
      </div>
      <h3 style="color:#f1f5f9; font-size:1.2rem; font-weight:600; margin:0 0 4px;">Football Analytics Platform</h3>
      <p style="color:#94a3b8; font-size:0.85rem; line-height:1.5; margin-bottom:0.8rem;">A data platform to collect, process and visualise football match data using FastAPI, PostgreSQL and Docker.</p>
      <div style="display:flex; flex-wrap:wrap; gap:4px 8px; margin-bottom:1rem;">
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Python</span>
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">FastAPI</span>
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">PostgreSQL</span>
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Docker</span>
      </div>
      <div style="display:flex; gap:0.8rem;">
        <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🔗 GitHub</a>
        <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🌐 Live Demo</a>
        <span style="color:#475569; font-size:0.7rem; margin-left:auto;">📈 in progress</span>
      </div>
    </div>

    <!-- Project 2 -->
    <div style="background:rgba(255,255,255,0.02); backdrop-filter:blur(8px); border-radius:24px; padding:1.5rem; border:1px solid rgba(255,255,255,0.05); box-shadow:0 12px 40px rgba(0,0,0,0.3);">
      <div style="display:flex; justify-content:space-between; align-items:start; margin-bottom:0.8rem;">
        <span style="font-size:2rem;">📦</span>
        <span style="padding:0.15rem 0.8rem; border-radius:40px; background:rgba(139,92,246,0.1); color:#a78bfa; font-size:0.6rem; letter-spacing:0.5px; border:1px solid rgba(139,92,246,0.08);">Backend</span>
      </div>
      <h3 style="color:#f1f5f9; font-size:1.2rem; font-weight:600; margin:0 0 4px;">E‑Commerce API</h3>
      <p style="color:#94a3b8; font-size:0.85rem; line-height:1.5; margin-bottom:0.8rem;">RESTful API for an e‑commerce platform with authentication, JWT, and payment integration using Django.</p>
      <div style="display:flex; flex-wrap:wrap; gap:4px 8px; margin-bottom:1rem;">
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Django</span>
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">PostgreSQL</span>
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">JWT</span>
        <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Docker</span>
      </div>
      <div style="display:flex; gap:0.8rem;">
        <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🔗 GitHub</a>
        <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🌐 Live Demo</a>
        <span style="color:#475569; font-size:0.7rem; margin-left:auto;">✅ completed</span>
      </div>
    </div>

  </div>
</div>

<!-- ─── LEARNING ROADMAP ─── -->
<div style="margin:2.8rem 0 2rem;">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
    <span style="font-size:1.8rem;">📚</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Learning Roadmap</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <div style="display:grid; grid-template-columns:1fr 1fr; gap:1.4rem;">

    <div>
      <div style="color:#e2e8f0; font-weight:500; margin-bottom:0.8rem;">Currently Learning</div>
      <div style="display:flex; flex-direction:column; gap:0.6rem;">
        <div><span style="color:#94a3b8; font-size:0.9rem;">Backend Architecture</span><div style="height:4px; background:rgba(255,255,255,0.06); border-radius:4px; overflow:hidden; margin-top:2px;"><div style="width:60%; height:100%; background:linear-gradient(90deg,#2563eb,#22d3ee);"></div></div></div>
        <div><span style="color:#94a3b8; font-size:0.9rem;">Docker &amp; Containerisation</span><div style="height:4px; background:rgba(255,255,255,0.06); border-radius:4px; overflow:hidden; margin-top:2px;"><div style="width:70%; height:100%; background:linear-gradient(90deg,#2563eb,#22d3ee);"></div></div></div>
        <div><span style="color:#94a3b8; font-size:0.9rem;">AWS &amp; Cloud</span><div style="height:4px; background:rgba(255,255,255,0.06); border-radius:4px; overflow:hidden; margin-top:2px;"><div style="width:40%; height:100%; background:linear-gradient(90deg,#2563eb,#22d3ee);"></div></div></div>
        <div><span style="color:#94a3b8; font-size:0.9rem;">Data Engineering (Airflow, Spark)</span><div style="height:4px; background:rgba(255,255,255,0.06); border-radius:4px; overflow:hidden; margin-top:2px;"><div style="width:30%; height:100%; background:linear-gradient(90deg,#2563eb,#22d3ee);"></div></div></div>
      </div>
    </div>

    <div>
      <div style="color:#e2e8f0; font-weight:500; margin-bottom:0.8rem;">Future Skills</div>
      <div style="display:flex; flex-wrap:wrap; gap:0.4rem 0.8rem;">
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#94a3b8; font-size:0.8rem; border:1px solid rgba(255,255,255,0.06);">Kafka</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#94a3b8; font-size:0.8rem; border:1px solid rgba(255,255,255,0.06);">dbt</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#94a3b8; font-size:0.8rem; border:1px solid rgba(255,255,255,0.06);">Iceberg</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#94a3b8; font-size:0.8rem; border:1px solid rgba(255,255,255,0.06);">System Design</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#94a3b8; font-size:0.8rem; border:1px solid rgba(255,255,255,0.06);">Distributed Systems</span>
      </div>
      <div style="margin-top:1.2rem; color:#e2e8f0; font-weight:500;">Completed Skills</div>
      <div style="display:flex; flex-wrap:wrap; gap:0.4rem 0.8rem; margin-top:0.4rem;">
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(34,211,238,0.08); color:#22d3ee; font-size:0.8rem; border:1px solid rgba(34,211,238,0.06);">Python</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(34,211,238,0.08); color:#22d3ee; font-size:0.8rem; border:1px solid rgba(34,211,238,0.06);">FastAPI</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(34,211,238,0.08); color:#22d3ee; font-size:0.8rem; border:1px solid rgba(34,211,238,0.06);">PostgreSQL</span>
        <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(34,211,238,0.08); color:#22d3ee; font-size:0.8rem; border:1px solid rgba(34,211,238,0.06);">Git</span>
      </div>
    </div>

  </div>
</div>

<!-- ─── EXPERIENCE TIMELINE ─── -->
<div style="margin:2.8rem 0 2rem;">

  <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
    <span style="font-size:1.8rem;">⏳</span>
    <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Experience &amp; Education</h2>
    <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
  </div>

  <div style="display:grid; grid-template-columns:1fr 1fr; gap:1.4rem;">

    <div style="background:rgba(255,255,255,0.015); border-radius:22px; padding:1.4rem; border:1px solid rgba(255,255,255,0.04);">
      <div style="color:#475569; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:1rem;">🎓 EDUCATION</div>
      <div style="margin-bottom:1.2rem;">
        <div style="color:#e2e8f0; font-weight:500;">B.Sc. in Software Development</div>
        <div style="color:#94a3b8; font-size:0.85rem;">2023 – 2025 (Final Year)</div>
        <div style="color:#64748b; font-size:0.8rem;">Egypt</div>
      </div>
      <div>
        <div style="color:#e2e8f0; font-weight:500;">Relevant Coursework</div>
        <div style="color:#94a3b8; font-size:0.85rem;">Data Structures, Algorithms, Databases, Software Engineering, Cloud Computing</div>
      </div>
    </div>

    <div style="background:rgba(255,255,255,0.015); border-radius:22px; padding:1.4rem; border:1px solid rgba(255,255,255,0.04);">
      <div style="color:#475569; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:1rem;">💼 EXPERIENCE</div>
      <div style="margin-bottom:1.2rem;">
        <div style="color:#e2e8f0; font-weight:500;">Backend Developer (Freelance)</div>
        <div style="color:#94a3b8; font-size:0.85rem;">2024 – Present</div>
        <div style="color:#64748b; font-size:0.8rem;">Building APIs and backend systems for various clients.</div>
      </div>
      <div>
        <div style="color:#e2e8f0; font-weight:500;">Open Source Contributions</div>
        <div style="color:#94a3b8; font-size:0.85rem;">Contributor to several OSS projects (Python, FastAPI).</div>
      </div>
    </div>

  </div>
</div>

<!-- ─── CONTACT & FOOTER ─── -->
<div align="center" style="margin-top:2.8rem; padding-top:1.8rem; border-top:1px solid rgba(255,255,255,0.04);">

  <div style="display:flex; gap:1.5rem; justify-content:center; flex-wrap:wrap; margin-bottom:1.2rem;">
    <a href="https://github.com/kirollosnabil" style="color:#94a3b8; text-decoration:none; font-size:0.9rem;">🐙 GitHub</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; font-size:0.9rem;">🔗 LinkedIn</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; font-size:0.9rem;">🐦 Twitter</a>
    <a href="mailto:kirollos@example.com" style="color:#94a3b8; text-decoration:none; font-size:0.9rem;">✉️ Email</a>
  </div>

  <div style="display:flex; justify-content:center; gap:1.2rem; flex-wrap:wrap; font-size:0.75rem; color:#475569; margin-bottom:0.8rem;">
    <span>✦  Backend  ✦</span>
    <span>✦  Data Engineering  ✦</span>
    <span>✦  Football Analytics  ✦</span>
    <span>✦  Open Source  ✦</span>
  </div>

  <div style="color:#334155; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase;">
    Designed with ❤️ · Kirollos Nabil · 2025
  </div>
</div>
