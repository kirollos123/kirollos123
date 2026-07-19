<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GitHub Profile README · Premium</title>
    <!-- This is a preview of the README.md rendered in a browser.
         The actual README.md is pure Markdown + SVG + HTML (GitHub compatible). -->
    <style>
        /* ── Preview styles (only for this HTML preview) ── */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: #0b0d12;
            display: flex;
            justify-content: center;
            padding: 2rem 1rem;
            font-family: system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
        }
        .readme-preview {
            max-width: 1100px;
            width: 100%;
            background: transparent;
            border-radius: 32px;
            padding: 0.5rem;
        }
        /* The actual README content will be injected here */
        .readme-preview>* {
            margin-bottom: 0;
        }
        /* misc */
        .footnote {
            text-align: center;
            color: #6b7280;
            font-size: 0.8rem;
            padding: 2rem 0 0.5rem;
            border-top: 1px solid rgba(255, 255, 255, 0.06);
            margin-top: 2rem;
            letter-spacing: 0.3px;
        }
        .footnote a {
            color: #60a5fa;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <div class="readme-preview">

        <!-- ════════════════════════════════════════════════════════════════
        README.md content begins below.
        This is the EXACT content that would go into your README.md.
        GitHub renders Markdown + HTML + SVG.
        ════════════════════════════════════════════════════════════════ -->

        <!--
        ╔═══════════════════════════════════════════════════════════════╗
        ║  🚀  PREMIUM GITHUB PROFILE README  –  v3.0                ║
        ║  Designed by  @yourhandle                                    ║
        ║  Style:  Dark · Glass · Neon · Cyber · Football Manager     ║
        ╚═══════════════════════════════════════════════════════════════╝
        -->

        <!-- ──────────────────────────────────────────────────────────────
        HERO SECTION  –  Animated Wave + Typing + Glass Cards
        ────────────────────────────────────────────────────────────── -->

        <div align="center">

            <!-- ANIMATED WAVE HEADER (SVG) -->
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

    <!-- PROFILE PICTURE + GLOW RING (SVG) -->
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
        <!-- profile image placeholder -->
        <circle cx="70" cy="70" r="58" fill="#1e293b" />
        <circle cx="70" cy="70" r="58" fill="url(#ringGrad)" opacity="0.08" />
        <g clip-path="url(#profileClip)">
            <!-- abstract avatar: gradient + initials -->
            <rect x="0" y="0" width="140" height="140" fill="#0f172a" />
            <circle cx="70" cy="70" r="58" fill="url(#ringGrad)" opacity="0.15" />
            <text x="70" y="82" font-family="system-ui, sans-serif" font-size="44" font-weight="700"
            fill="white" text-anchor="middle" letter-spacing="2">JD</text>
        </g>
    </svg>
</div>

<!-- TYPING ANIMATION (SVG) -->
<svg width="100%" height="60" viewBox="0 0 600 60" style="max-width:600px; margin: 8px auto 4px;">
    <defs>
        <linearGradient id="typeGrad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%"   stop-color="#60a5fa" />
            <stop offset="50%"  stop-color="#22d3ee" />
            <stop offset="100%" stop-color="#a78bfa" />
        </linearGradient>
    </defs>
    <text x="0" y="38" font-family="system-ui, -apple-system, sans-serif" font-size="28" font-weight="600"
    fill="url(#typeGrad)" letter-spacing="0.5">
    <tspan>Senior </tspan>
    <tspan fill="#f1f5f9">Full‑Stack </tspan>
    <tspan fill="url(#typeGrad)">Engineer </tspan>
    <tspan fill="#94a3b8" font-weight="400">· </tspan>
    <tspan fill="#e2e8f0" font-weight="400">Architect</tspan>
    <!-- cursor -->
    <tspan fill="#22d3ee" font-weight="300">|</tspan>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite" />
</text>
</svg>

<!-- TAGLINE -->
<p style="color:#94a3b8; font-size:1.1rem; max-width:520px; margin: 0 auto 1.2rem; letter-spacing:0.3px; font-weight:300;">
    Crafting high‑performance systems &amp; delightful experiences
</p>

<!-- SOCIAL ICONS + VISITOR COUNTER + BUTTONS -->
<div style="display:flex; flex-wrap:wrap; justify-content:center; align-items:center; gap:1rem 1.8rem; margin:1.5rem 0 0.8rem;">

    <!-- visitor counter -->
    <div style="display:flex; align-items:center; gap:6px; background:rgba(255,255,255,0.04); backdrop-filter:blur(8px); padding:0.4rem 1.2rem; border-radius:40px; border:1px solid rgba(255,255,255,0.06);">
        <span style="color:#64748b; font-size:0.85rem;">👁️</span>
        <span style="color:#e2e8f0; font-size:0.9rem; font-weight:500;">12,847</span>
        <span style="color:#475569; font-size:0.7rem; font-weight:300;">visitors</span>
    </div>

    <!-- social icons -->
    <a href="#" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">🐙</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">🐦</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">🔗</a>
    <a href="#" style="color:#94a3b8; text-decoration:none; transition:color 0.2s; font-size:1.3rem;">💼</a>

    <!-- buttons -->
    <a href="#" style="display:inline-block; padding:0.5rem 1.6rem; border-radius:40px; background:linear-gradient(135deg,#2563eb,#7c3aed); color:white; font-weight:500; font-size:0.9rem; text-decoration:none; border:none; box-shadow:0 4px 20px rgba(37,99,235,0.25); transition:all 0.25s;">📄 Resume</a>
    <a href="#" style="display:inline-block; padding:0.5rem 1.6rem; border-radius:40px; background:rgba(255,255,255,0.06); backdrop-filter:blur(8px); color:#e2e8f0; font-weight:500; font-size:0.9rem; text-decoration:none; border:1px solid rgba(255,255,255,0.08); transition:all 0.25s;">✉️ Contact</a>
</div>

<!-- subtle divider -->
<hr style="width:80px; margin:2.2rem auto 1.8rem; border:none; height:1px; background:linear-gradient(90deg,transparent,#334155,transparent);" />

</div>

<!-- ──────────────────────────────────────────────────────────────
ABOUT ME  –  Premium Glass Card + Timeline
───────────────────────────────────────────────────────────── -->

<div style="background:rgba(255,255,255,0.02); backdrop-filter:blur(12px); border-radius:28px; padding:2rem 2.5rem; margin:2rem 0; border:1px solid rgba(255,255,255,0.05); box-shadow:0 20px 60px rgba(0,0,0,0.4);">

    <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.4rem;">
        <span style="font-size:1.8rem;">🧑‍💻</span>
        <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">About Me</h2>
        <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
    </div>

    <div style="display:grid; grid-template-columns:1fr 1fr; gap:2rem;">

        <!-- left column -->
        <div>
            <p style="color:#cbd5e1; font-size:1rem; line-height:1.7; margin-bottom:1.2rem;">
                I'm <strong style="color:#f1f5f9;">John Doe</strong>, a full‑stack engineer with <strong style="color:#60a5fa;">8+ years</strong> of experience
                architecting scalable systems at the intersection of <strong style="color:#22d3ee;">AI</strong> and
                <strong style="color:#a78bfa;">cloud infrastructure</strong>.
            </p>
            <div style="display:flex; flex-wrap:wrap; gap:0.8rem 1.8rem; margin:1.2rem 0 1rem; font-size:0.9rem; color:#94a3b8;">
                <span>🎯 <span style="color:#e2e8f0;">Currently:</span> Staff Engineer @ Vercel</span>
                <span>🧭 <span style="color:#e2e8f0;">Mission:</span> Build the future of developer tooling</span>
                <span>📌 <span style="color:#e2e8f0;">Values:</span> Craft · Simplicity · Impact</span>
            </div>
            <!-- mini timeline -->
            <div style="margin-top:1.2rem; padding-left:0.5rem;">
                <div style="display:flex; gap:1.2rem; align-items:center; margin-bottom:0.6rem;">
                    <span style="color:#475569; font-size:0.7rem; min-width:60px;">2024 →</span>
                    <span style="color:#cbd5e1; font-size:0.9rem;">Staff Engineer · Vercel</span>
                </div>
                <div style="display:flex; gap:1.2rem; align-items:center; margin-bottom:0.6rem;">
                    <span style="color:#475569; font-size:0.7rem; min-width:60px;">2021–2024</span>
                    <span style="color:#cbd5e1; font-size:0.9rem;">Senior Full‑Stack · Stripe</span>
                </div>
                <div style="display:flex; gap:1.2rem; align-items:center; margin-bottom:0.6rem;">
                    <span style="color:#475569; font-size:0.7rem; min-width:60px;">2018–2021</span>
                    <span style="color:#cbd5e1; font-size:0.9rem;">Software Engineer · Apple</span>
                </div>
                <div style="display:flex; gap:1.2rem; align-items:center;">
                    <span style="color:#475569; font-size:0.7rem; min-width:60px;">2016–2018</span>
                    <span style="color:#cbd5e1; font-size:0.9rem;">B.S. Computer Science · MIT</span>
                </div>
            </div>
        </div>

        <!-- right column: values + mission -->
        <div style="background:rgba(255,255,255,0.02); border-radius:20px; padding:1.2rem 1.6rem; border:1px solid rgba(255,255,255,0.04);">
            <div style="display:flex; gap:1.5rem; flex-wrap:wrap;">
                <div style="flex:1; min-width:120px;">
                    <div style="color:#475569; font-size:0.7rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:4px;">Mission</div>
                    <p style="color:#e2e8f0; font-size:0.95rem; line-height:1.5;">Democratize AI‑powered development for every engineer.</p>
                </div>
                <div style="flex:1; min-width:120px;">
                    <div style="color:#475569; font-size:0.7rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:4px;">Long‑term</div>
                    <p style="color:#e2e8f0; font-size:0.95rem; line-height:1.5;">Build the operating system for the next generation of software.</p>
                </div>
            </div>
            <div style="margin-top:1rem; display:flex; gap:0.6rem; flex-wrap:wrap;">
                <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(37,99,235,0.12); color:#60a5fa; font-size:0.75rem; border:1px solid rgba(37,99,235,0.1);">#systems</span>
                <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(6,182,212,0.12); color:#22d3ee; font-size:0.75rem; border:1px solid rgba(6,182,212,0.1);">#ai</span>
                <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(139,92,246,0.12); color:#a78bfa; font-size:0.75rem; border:1px solid rgba(139,92,246,0.1);">#cloud</span>
                <span style="padding:0.2rem 1rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#94a3b8; font-size:0.75rem; border:1px solid rgba(255,255,255,0.06);">#developer‑experience</span>
            </div>
        </div>
    </div>
</div>

<!-- ──────────────────────────────────────────────────────────────
TECH STACK  –  Animated Grid with Cards
───────────────────────────────────────────────────────────── -->

<div style="margin:2.8rem 0 2rem;">

    <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
        <span style="font-size:1.8rem;">⚡</span>
        <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Tech Stack</h2>
        <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
    </div>

    <!-- grid of tech cards -->
    <div style="display:grid; grid-template-columns:repeat(auto-fill, minmax(160px,1fr)); gap:1rem;">

        <!-- card template -->
        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); transition:all 0.2s; box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Languages</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">TypeScript</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Python</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Rust</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Go</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Frontend</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">React</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Next.js</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Tailwind</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Framer</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Backend</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">Node.js</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Python</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Go</span>
                <span style="color:#94a3b8; font-size:0.8rem;">GraphQL</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Databases</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">PostgreSQL</span>
                <span style="color:#94a3b8; font-size:0.8rem;">MongoDB</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Redis</span>
                <span style="color:#94a3b8; font-size:0.8rem;">DynamoDB</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Cloud</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">AWS</span>
                <span style="color:#94a3b8; font-size:0.8rem;">GCP</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Azure</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Cloudflare</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">DevOps</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">Docker</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Kubernetes</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Terraform</span>
                <span style="color:#94a3b8; font-size:0.8rem;">GitHub Actions</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">AI</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">PyTorch</span>
                <span style="color:#94a3b8; font-size:0.8rem;">TensorFlow</span>
                <span style="color:#94a3b8; font-size:0.8rem;">LangChain</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Hugging Face</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Data Eng.</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">Spark</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Kafka</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Airflow</span>
                <span style="color:#94a3b8; font-size:0.8rem;">dbt</span>
            </div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1rem 1.2rem; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 24px rgba(0,0,0,0.2);">
            <div style="color:#475569; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase; margin-bottom:6px;">Tools</div>
            <div style="display:flex; flex-wrap:wrap; gap:6px 12px;">
                <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">VS Code</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Neovim</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Git</span>
                <span style="color:#94a3b8; font-size:0.8rem;">Figma</span>
            </div>
        </div>

    </div>
</div>

<!-- ──────────────────────────────────────────────────────────────
GITHUB METRICS  –  Stats + Streak + Trophies
───────────────────────────────────────────────────────────── -->

<div style="margin:2.8rem 0 2rem;">

    <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
        <span style="font-size:1.8rem;">📊</span>
        <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">GitHub Metrics</h2>
        <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
    </div>

    <!-- stat cards row -->
    <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(130px,1fr)); gap:1rem; margin-bottom:1.4rem;">

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1.2rem 1rem; text-align:center; border:1px solid rgba(255,255,255,0.04);">
            <div style="font-size:2rem; font-weight:700; background:linear-gradient(135deg,#60a5fa,#22d3ee); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text;">248</div>
            <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px;">Repositories</div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1.2rem 1rem; text-align:center; border:1px solid rgba(255,255,255,0.04);">
            <div style="font-size:2rem; font-weight:700; background:linear-gradient(135deg,#22d3ee,#a78bfa); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text;">1.2k</div>
            <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px;">Stars</div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1.2rem 1rem; text-align:center; border:1px solid rgba(255,255,255,0.04);">
            <div style="font-size:2rem; font-weight:700; background:linear-gradient(135deg,#a78bfa,#60a5fa); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text;">4.6k</div>
            <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px;">Followers</div>
        </div>

        <div style="background:rgba(255,255,255,0.025); backdrop-filter:blur(6px); border-radius:18px; padding:1.2rem 1rem; text-align:center; border:1px solid rgba(255,255,255,0.04);">
            <div style="font-size:2rem; font-weight:700; background:linear-gradient(135deg,#f59e0b,#f472b6); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text;">32</div>
            <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px;">Contributions</div>
        </div>

    </div>

    <!-- contribution graph placeholder (SVG) -->
    <div style="background:rgba(255,255,255,0.015); border-radius:20px; padding:1.2rem 1rem; border:1px solid rgba(255,255,255,0.04); margin-bottom:1.4rem;">
        <svg width="100%" height="80" viewBox="0 0 800 80" style="display:block;">
            <rect x="0" y="0" width="800" height="80" rx="12" fill="rgba(255,255,255,0.02)" />
            <!-- grid of contribution squares (simplified) -->
            <g fill="#1e293b">
                <!-- generate a pattern of small squares -->
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

    <!-- trophies row (simplified) -->
    <div style="display:flex; flex-wrap:wrap; gap:0.8rem; justify-content:center;">
        <span style="padding:0.3rem 1.2rem; border-radius:40px; background:rgba(255,215,0,0.08); border:1px solid rgba(255,215,0,0.1); color:#fbbf24; font-size:0.75rem;">🏆 4x GitHub Star</span>
        <span style="padding:0.3rem 1.2rem; border-radius:40px; background:rgba(192,132,252,0.08); border:1px solid rgba(192,132,252,0.1); color:#c084fc; font-size:0.75rem;">⭐ 12x Top Contributor</span>
        <span style="padding:0.3rem 1.2rem; border-radius:40px; background:rgba(34,211,238,0.08); border:1px solid rgba(34,211,238,0.1); color:#22d3ee; font-size:0.75rem;">🔥 30‑day streak</span>
        <span style="padding:0.3rem 1.2rem; border-radius:40px; background:rgba(251,146,60,0.08); border:1px solid rgba(251,146,60,0.1); color:#fb923c; font-size:0.75rem;">📈 98th percentile</span>
    </div>

</div>

<!-- ──────────────────────────────────────────────────────────────
FEATURED PROJECTS  –  Premium Cards
───────────────────────────────────────────────────────────── -->

<div style="margin:2.8rem 0 2rem;">

    <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
        <span style="font-size:1.8rem;">🚀</span>
        <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Featured Projects</h2>
        <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
    </div>

    <div style="display:grid; grid-template-columns:1fr 1fr; gap:1.4rem;">

        <!-- project card 1 -->
        <div style="background:rgba(255,255,255,0.02); backdrop-filter:blur(8px); border-radius:24px; padding:1.5rem; border:1px solid rgba(255,255,255,0.05); box-shadow:0 12px 40px rgba(0,0,0,0.3);">
            <div style="display:flex; justify-content:space-between; align-items:start; margin-bottom:0.8rem;">
                <span style="font-size:2rem;">⚡</span>
                <span style="padding:0.15rem 0.8rem; border-radius:40px; background:rgba(34,211,238,0.1); color:#22d3ee; font-size:0.6rem; letter-spacing:0.5px; border:1px solid rgba(34,211,238,0.08);">v2.4</span>
            </div>
            <h3 style="color:#f1f5f9; font-size:1.2rem; font-weight:600; margin:0 0 4px;">Vortex Core</h3>
            <p style="color:#94a3b8; font-size:0.85rem; line-height:1.5; margin-bottom:0.8rem;">High‑performance distributed task queue with AI‑powered auto‑scaling.</p>
            <div style="display:flex; flex-wrap:wrap; gap:4px 8px; margin-bottom:1rem;">
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Rust</span>
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Redis</span>
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Kubernetes</span>
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">AI</span>
            </div>
            <div style="display:flex; gap:0.8rem;">
                <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🔗 GitHub</a>
                <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🌐 Live Demo</a>
                <span style="color:#475569; font-size:0.7rem; margin-left:auto;">⚡ 1.2k stars</span>
            </div>
        </div>

        <!-- project card 2 -->
        <div style="background:rgba(255,255,255,0.02); backdrop-filter:blur(8px); border-radius:24px; padding:1.5rem; border:1px solid rgba(255,255,255,0.05); box-shadow:0 12px 40px rgba(0,0,0,0.3);">
            <div style="display:flex; justify-content:space-between; align-items:start; margin-bottom:0.8rem;">
                <span style="font-size:2rem;">🧠</span>
                <span style="padding:0.15rem 0.8rem; border-radius:40px; background:rgba(139,92,246,0.1); color:#a78bfa; font-size:0.6rem; letter-spacing:0.5px; border:1px solid rgba(139,92,246,0.08);">beta</span>
            </div>
            <h3 style="color:#f1f5f9; font-size:1.2rem; font-weight:600; margin:0 0 4px;">Neural Forge</h3>
            <p style="color:#94a3b8; font-size:0.85rem; line-height:1.5; margin-bottom:0.8rem;">Code‑generation engine powered by fine‑tuned LLMs with VSCode integration.</p>
            <div style="display:flex; flex-wrap:wrap; gap:4px 8px; margin-bottom:1rem;">
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">Python</span>
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">PyTorch</span>
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">TypeScript</span>
                <span style="padding:0.1rem 0.7rem; border-radius:40px; background:rgba(255,255,255,0.04); color:#64748b; font-size:0.65rem;">VSCode</span>
            </div>
            <div style="display:flex; gap:0.8rem;">
                <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🔗 GitHub</a>
                <a href="#" style="color:#60a5fa; font-size:0.8rem; text-decoration:none;">🌐 Live Demo</a>
                <span style="color:#475569; font-size:0.7rem; margin-left:auto;">🧪 860 stars</span>
            </div>
        </div>

    </div>
</div>

<!-- ──────────────────────────────────────────────────────────────
FOOTBALL THEME  –  EA FC Player Card + Manager Dashboard
───────────────────────────────────────────────────────────── -->

<div style="margin:2.8rem 0 2rem;">

    <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
        <span style="font-size:1.8rem;">⚽</span>
        <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Career Mode</h2>
        <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
    </div>

    <div style="display:grid; grid-template-columns:1fr 1.6fr; gap:1.4rem;">

        <!-- EA FC Player Card -->
        <div style="background:linear-gradient(145deg, rgba(37,99,235,0.08), rgba(139,92,246,0.05)); backdrop-filter:blur(12px); border-radius:28px; padding:1.6rem; border:1px solid rgba(255,255,255,0.06); box-shadow:0 12px 48px rgba(0,0,0,0.3);">
            <div style="display:flex; align-items:center; gap:1rem; margin-bottom:1rem;">
                <div style="width:60px; height:60px; border-radius:50%; background:linear-gradient(135deg,#2563eb,#7c3aed); display:flex; align-items:center; justify-content:center; font-size:1.6rem; font-weight:700; color:white;">JD</div>
                <div>
                    <div style="color:#f1f5f9; font-size:1.1rem; font-weight:600;">John Doe</div>
                    <div style="color:#94a3b8; font-size:0.75rem; letter-spacing:0.5px;">Staff Engineer · Vercel</div>
                </div>
                <div style="margin-left:auto; text-align:right;">
                    <div style="color:#fbbf24; font-size:1.2rem; font-weight:700;">92</div>
                    <div style="color:#475569; font-size:0.6rem; letter-spacing:0.5px;">OVERALL</div>
                </div>
            </div>
            <!-- attributes radar (simplified) -->
            <div style="display:grid; grid-template-columns:1fr 1fr 1fr; gap:0.4rem 1rem; margin:0.8rem 0;">
                <div><span style="color:#64748b; font-size:0.65rem;">Code</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">95</span></div>
                <div><span style="color:#64748b; font-size:0.65rem;">Arch</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">91</span></div>
                <div><span style="color:#64748b; font-size:0.65rem;">AI</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">88</span></div>
                <div><span style="color:#64748b; font-size:0.65rem;">Cloud</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">90</span></div>
                <div><span style="color:#64748b; font-size:0.65rem;">UX</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">82</span></div>
                <div><span style="color:#64748b; font-size:0.65rem;">Lead</span> <span style="color:#e2e8f0; font-size:0.85rem; font-weight:500;">87</span></div>
            </div>
            <div style="display:flex; gap:0.6rem; flex-wrap:wrap; margin-top:0.6rem;">
                <span style="padding:0.1rem 0.8rem; border-radius:40px; background:rgba(255,215,0,0.08); color:#fbbf24; font-size:0.6rem; border:1px solid rgba(255,215,0,0.06);">⭐ Elite</span>
                <span style="padding:0.1rem 0.8rem; border-radius:40px; background:rgba(34,211,238,0.08); color:#22d3ee; font-size:0.6rem; border:1px solid rgba(34,211,238,0.06);">🏆 MVP</span>
                <span style="padding:0.1rem 0.8rem; border-radius:40px; background:rgba(139,92,246,0.08); color:#a78bfa; font-size:0.6rem; border:1px solid rgba(139,92,246,0.06);">🎯 98% accuracy</span>
            </div>
        </div>

        <!-- Football Manager Dashboard -->
        <div style="background:rgba(255,255,255,0.015); backdrop-filter:blur(8px); border-radius:28px; padding:1.4rem 1.6rem; border:1px solid rgba(255,255,255,0.04);">
            <div style="display:flex; justify-content:space-between; margin-bottom:1rem;">
                <span style="color:#64748b; font-size:0.65rem; letter-spacing:0.5px;">📊 SEASON 2026</span>
                <span style="color:#22d3ee; font-size:0.75rem; font-weight:500;">▸ in progress</span>
            </div>
            <div style="display:grid; grid-template-columns:1fr 1fr 1fr; gap:1rem; margin-bottom:1.2rem;">
                <div><span style="color:#475569; font-size:0.6rem;">Matches</span><div style="color:#e2e8f0; font-size:1.2rem; font-weight:600;">42</div></div>
                <div><span style="color:#475569; font-size:0.6rem;">Wins</span><div style="color:#22d3ee; font-size:1.2rem; font-weight:600;">31</div></div>
                <div><span style="color:#475569; font-size:0.6rem;">Win %</span><div style="color:#fbbf24; font-size:1.2rem; font-weight:600;">73.8%</div></div>
            </div>
            <div style="height:4px; background:rgba(255,255,255,0.06); border-radius:4px; overflow:hidden; margin-bottom:0.6rem;">
                <div style="width:74%; height:100%; background:linear-gradient(90deg,#2563eb,#22d3ee); border-radius:4px;"></div>
            </div>
            <div style="display:flex; gap:1.2rem; font-size:0.75rem; color:#64748b;">
                <span>⚡ Transfer budget: <strong style="color:#e2e8f0;">$12.4M</strong></span>
                <span>📈 Form: <strong style="color:#22d3ee;">W W D W L</strong></span>
            </div>
        </div>

    </div>
</div>

<!-- ──────────────────────────────────────────────────────────────
CUSTOM WIDGETS  –  Developer Level · XP · Mission
───────────────────────────────────────────────────────────── -->

<div style="margin:2.8rem 0 2rem;">

    <div style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.6rem;">
        <span style="font-size:1.8rem;">🧩</span>
        <h2 style="font-size:1.6rem; font-weight:600; background:linear-gradient(135deg,#e2e8f0,#94a3b8); -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text; margin:0;">Developer Dashboard</h2>
        <span style="flex:1; height:1px; background:linear-gradient(90deg,rgba(255,255,255,0.08),transparent);"></span>
    </div>

    <div style="display:grid; grid-template-columns:1fr 1fr 1fr; gap:1.2rem;">

        <!-- widget: dev level -->
        <div style="background:rgba(255,255,255,0.02); border-radius:22px; padding:1.2rem 1.4rem; border:1px solid rgba(255,255,255,0.04);">
            <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:0.4rem;">
                <span style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px;">Developer Level</span>
                <span style="color:#fbbf24; font-size:1.2rem; font-weight:700;">Lv. 47</span>
            </div>
            <div style="height:6px; background:rgba(255,255,255,0.06); border-radius:6px; overflow:hidden;">
                <div style="width:78%; height:100%; background:linear-gradient(90deg,#2563eb,#a78bfa); border-radius:6px;"></div>
            </div>
            <div style="display:flex; justify-content:space-between; margin-top:6px; color:#475569; font-size:0.6rem;">
                <span>XP 12,840 / 16,000</span>
                <span>⏳ 78%</span>
            </div>
        </div>

        <!-- widget: current mission -->
        <div style="background:rgba(255,255,255,0.02); border-radius:22px; padding:1.2rem 1.4rem; border:1px solid rgba(255,255,255,0.04);">
            <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:4px;">🎯 Current Mission</div>
            <div style="color:#e2e8f0; font-size:0.95rem; font-weight:500;">Ship v3.0 of Vortex Core</div>
            <div style="display:flex; gap:0.8rem; margin-top:6px; font-size:0.7rem; color:#475569;">
                <span>⏱️ 3 days remaining</span>
                <span>📋 12 / 18 tasks</span>
            </div>
        </div>

        <!-- widget: next goal -->
        <div style="background:rgba(255,255,255,0.02); border-radius:22px; padding:1.2rem 1.4rem; border:1px solid rgba(255,255,255,0.04);">
            <div style="color:#64748b; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:4px;">🏁 Next Goal</div>
            <div style="color:#e2e8f0; font-size:0.95rem; font-weight:500;">10k GitHub Stars</div>
            <div style="display:flex; gap:0.8rem; margin-top:6px; font-size:0.7rem; color:#475569;">
                <span>⭐ 8,420 / 10,000</span>
                <span>📈 +340 this month</span>
            </div>
        </div>

    </div>
</div>

<!-- ──────────────────────────────────────────────────────────────
PREMIUM SECTIONS  –  Quote · Achievements · Goals · Books
───────────────────────────────────────────────────────────── -->

<div style="margin:2.8rem 0 2rem;">

    <div style="display:grid; grid-template-columns:1fr 1fr; gap:1.4rem;">

        <!-- quote -->
        <div style="background:rgba(255,255,255,0.015); border-radius:22px; padding:1.6rem 1.8rem; border:1px solid rgba(255,255,255,0.04);">
            <div style="color:#475569; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:6px;">✧ QUOTE</div>
            <div style="color:#cbd5e1; font-size:1rem; font-weight:300; line-height:1.6; font-style:italic;">
                “Simplicity is the ultimate sophistication. Clarity in code reflects clarity in thought.”
            </div>
            <div style="color:#475569; font-size:0.75rem; margin-top:8px;">— John Doe</div>
        </div>

        <!-- achievements + goals -->
        <div style="background:rgba(255,255,255,0.015); border-radius:22px; padding:1.4rem 1.8rem; border:1px solid rgba(255,255,255,0.04);">
            <div style="display:flex; gap:2rem; flex-wrap:wrap;">
                <div>
                    <div style="color:#475569; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:4px;">🏅 Achievements</div>
                    <div style="color:#e2e8f0; font-size:0.85rem; line-height:1.6;">• GitHub Star 2024<br>• OSS Contributor of the Year<br>• 5x Hackathon Winner</div>
                </div>
                <div>
                    <div style="color:#475569; font-size:0.7rem; letter-spacing:0.5px; margin-bottom:4px;">📚 Reading</div>
                    <div style="color:#e2e8f0; font-size:0.85rem; line-height:1.6;">• “The Art of Systems”<br>• “AI Engineering”<br>• “Cloud Native Patterns”</div>
                </div>
            </div>
        </div>

    </div>
</div>

<!-- ──────────────────────────────────────────────────────────────
FOOTER / TERMINAL
───────────────────────────────────────────────────────────── -->

<div align="center" style="margin-top:2.8rem; padding-top:1.8rem; border-top:1px solid rgba(255,255,255,0.04);">

    <!-- terminal-style widget -->
    <div style="background:#0a0c12; border-radius:18px; padding:1.2rem 1.8rem; max-width:600px; margin:0 auto; text-align:left; font-family: 'JetBrains Mono', monospace; border:1px solid rgba(255,255,255,0.04); box-shadow:0 8px 32px rgba(0,0,0,0.4);">
        <div style="display:flex; gap:6px; margin-bottom:8px;">
            <span style="width:10px; height:10px; border-radius:50%; background:#ef4444;"></span>
            <span style="width:10px; height:10px; border-radius:50%; background:#f59e0b;"></span>
            <span style="width:10px; height:10px; border-radius:50%; background:#22c55e;"></span>
            <span style="color:#475569; font-size:0.6rem; margin-left:12px;">~ / developer</span>
        </div>
        <div style="color:#22d3ee; font-size:0.8rem; line-height:1.8;">
            <span style="color:#a78bfa;">➜</span> <span style="color:#60a5fa;">~</span> <span style="color:#e2e8f0;">whoami</span><br>
            <span style="color:#94a3b8;">» Senior Full‑Stack Engineer · Architect · AI Enthusiast</span><br>
            <span style="color:#a78bfa;">➜</span> <span style="color:#60a5fa;">~</span> <span style="color:#e2e8f0;">cat /etc/motd</span><br>
            <span style="color:#94a3b8;">» “Build things that matter. Ship with pride.”</span>
        </div>
    </div>

    <div style="margin-top:1.8rem; display:flex; justify-content:center; gap:1.2rem; flex-wrap:wrap; font-size:0.75rem; color:#475569;">
        <span>✦  Open Source  ✦</span>
        <span>✦  12 projects  ✦</span>
        <span>✦  MIT / Apache  ✦</span>
        <span>✦  #devlife  ✦</span>
    </div>

    <div style="margin-top:1.2rem; color:#334155; font-size:0.6rem; letter-spacing:1px; text-transform:uppercase;">
        Designed with ❤️ · GitHub Profile v3.0
    </div>

</div>

<!--
╔═══════════════════════════════════════════════════════════════╗
║  END OF README.md CONTENT                                    ║
╚═══════════════════════════════════════════════════════════════╝
-->

<!-- ─── preview footer ─── -->
<div class="footnote">
    ⚡ This is a <strong>live preview</strong> of the README.md.<br>
    The actual Markdown file is 100% <strong>GitHub‑compatible</strong> (SVG + HTML + Markdown).<br>
    <a href="#">View raw</a> · <a href="#">Copy to clipboard</a> · <a href="#">Customize</a>
</div>

</div>
<!-- end .readme-preview -->

</body>
</html>
