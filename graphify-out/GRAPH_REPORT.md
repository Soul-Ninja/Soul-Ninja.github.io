# Graph Report - raw  (2026-11-13)

## Corpus Check
- Corpus is ~12,102 words - fits in a single context window. You may not need a graph.

## Summary
- 149 nodes · 265 edges · 10 communities
- Extraction: 89% EXTRACTED · 10% INFERRED · 1% AMBIGUOUS · INFERRED: 26 edges (avg confidence: 0.5)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- APIGuard Scanner Engine
- Aman Joshi Profile
- Ledgio Finance PWA
- Reference Site Visual System
- Debunkit Misinformation Detection
- FDR Shield Hackathon Project
- Killian Herzer Reference Projects
- Security Engineering Themes
- mash Shell OS Internals
- Dashboards and Motion Design

## God Nodes (most connected - your core abstractions)
1. `Aman Joshi (GitHub: Soul-Ninja)` - 41 edges
2. `APIGuard: graph-guided API authorization and BOLA scanner` - 29 edges
3. `killianherzer.com (style reference portfolio)` - 23 edges
4. `Ledgio: private, offline-first personal finance ledger` - 21 edges
5. `DEBUNK.IT: AI-assisted misinformation detection` - 18 edges
6. `AICTE FDR Shield: automated FDR monitoring platform` - 18 edges
7. `Killian Herzer (reference: fullstack developer / creative technologist, Annecy)` - 11 edges
8. `mash (Micro-Architecture Shell): POSIX-style shell` - 10 edges
9. `React` - 8 edges
10. `OWASP API Security Top 10 (2023)` - 7 edges

## Surprising Connections (you probably didn't know these)
- `Aman Joshi (GitHub: Soul-Ninja)` --conceptually_related_to--> `GitHub handle Code-Breaker-Ctrl (appears in fdr-shield and Ledgio links)`  [AMBIGUOUS]
  raw/github_Soul-Ninja_README.md → raw/github_fdr-shield_README.md
- `Transparent verdicts: stamp, confidence meter, reasoning, source receipts` --conceptually_related_to--> `Small, sharp, dependable software: works offline, says what it does, no dark patterns`  [INFERRED]
  raw/github_Debunkit_README.md → raw/github_Soul-Ninja_README.md
- `Section: COMPETENCE_ANALYSIS_REPORT positioning statement` --conceptually_related_to--> `Small, sharp, dependable software: works offline, says what it does, no dark patterns`  [INFERRED]
  raw/reference_design_notes.md → raw/github_Soul-Ninja_README.md
- `Persistent extras: live clock, LIVE FEED status, visitor counter, 3D immersive mode switch` --conceptually_related_to--> `Three.js / React Three Fiber (WebGL)`  [INFERRED]
  raw/reference_design_notes.md → raw/killianherzer_com.md
- `Aman Joshi (GitHub: Soul-Ninja)` --references--> `AICTE FDR Shield: automated FDR monitoring platform`  [INFERRED]
  raw/github_Soul-Ninja_README.md → raw/github_fdr-shield_README.md

## Communities (10 total, 0 thin omitted)

### Community 0 - "APIGuard Scanner Engine"
Cohesion: 0.13
Nodes (24): AI remediation engine (post-scan patch drafting, offline template fallback), Benchmark: 100% recall on indirect BOLA where baseline scored 0%, Resource dependency graph (DAG) with ownership rule propagation, Deterministic scanner engine with zero LLM calls, APIGuard GitHub Action (scan every pull request), apiguard-cli PyPI package and CLI, Report formats: SARIF 2.1.0, JSON, PR markdown summary, Safe by default: loopback allowlist, request budget, mutation gate, masked tokens (+16 more)

### Community 1 - "Aman Joshi Profile"
Cohesion: 0.11
Nodes (22): B.Tech CSE (AI/ML) student, Applied AI, Privacy-first product design, Now learning: graph algorithms, Now learning: LLM pipelines, Now learning: NLP, No ads, no trackers, no paywalls, free forever, Email: joshiaman2006@gmail.com (+14 more)

### Community 2 - "Ledgio Finance PWA"
Cohesion: 0.13
Nodes (19): Offline-first / local-first, Installable Progressive Web App (PWA), Postgres Row Level Security on every table, Categories and monthly spending limits, Dashboard: net worth, income, expenses, safe-to-spend, savings rate, Loans and debts tracker, Pay cycles and recurring salary, Reports: category donut chart and 6-month trend (Chart.js) (+11 more)

### Community 3 - "Reference Site Visual System"
Cohesion: 0.15
Nodes (18): Single saturated red accent with glow (cyan only for cursor tag), Thin 1px borders, bracket corners, tag chips, greyscale imagery with red overlays, Concept: portfolio as surveillance / investigation case file, Custom cursor: small square with label tag, Near-black background with film grain / noise, HUD decorations and fake terminal log lines, Loading screen: SIGNAL TRACING boot sequence with percentage counter, ACCESS GRANTED, One-page site with FR / EN language toggle (+10 more)

### Community 4 - "Debunkit Misinformation Detection"
Cohesion: 0.14
Nodes (15): Live web evidence (RAG) with fact-check source detection, Editorial-dispatch interface with light and dark themes, Searchable history ledger and telemetry, Hybrid AI pipeline: LLM reasoning + trained ML model + local NLP engine, Offline local NLP pattern engine, TF-IDF + Logistic Regression fallback (about 93% accuracy on WELFake), Transparent verdicts: stamp, confidence meter, reasoning, source receipts, Debunkit live demo: debunkit-production.up.railway.app (+7 more)

### Community 5 - "FDR Shield Hackathon Project"
Cohesion: 0.18
Nodes (14): GitHub handle Code-Breaker-Ctrl (appears in fdr-shield and Ledgio links), Smart India Hackathon 2026 (Problem Statement 26265, Smart Automation), Bhashini multilingual suite (7 Indian languages), Executive portfolio intelligence dashboard and CSV reports, Tri-channel escalation engine: Email (Nodemailer), SMS (MSG91), WhatsApp (Twilio), nightly node-cron, Human-in-the-loop verification queue with immutable audit trail, Multimodal Vision AI document verification (IDP / OCR), FDR Shield demo video on YouTube (+6 more)

### Community 6 - "Killian Herzer Reference Projects"
Cohesion: 0.27
Nodes (13): Killian Herzer (reference: fullstack developer / creative technologist, Annecy), Celia: narrative 3D experience (Gobelins), Ciao: bar showcase site (Genesii), H.A.N.D.S.: hand-gesture controlled interactive experience, J. Pancras: photographer portfolio redesign (Genesii), Voeux 2026: 3D van assembly experience (Genesii), GSAP, JavaScript (+5 more)

### Community 7 - "Security Engineering Themes"
Cohesion: 0.22
Nodes (9): CSRF protection, Misinformation detection for headlines, URLs and articles, SSRF blocking, XSS sanitisation, Security-first hardening: rate limiting, hashed passwords, Security engineering, Now learning: OS internals, Takeaway: one strong narrative concept carried through every label (+1 more)

### Community 8 - "mash Shell OS Internals"
Cohesion: 0.43
Nodes (8): Process Control Block (PCB) management, Raw kernel system calls, Memory replacement with execvp, Process creation with fork, I/O redirection via file descriptors (dup2), SIGINT interrupt handling, Process synchronization and zombie prevention with wait, mash (Micro-Architecture Shell): POSIX-style shell

### Community 9 - "Dashboards and Motion Design"
Cohesion: 0.38
Nodes (7): APIGuard dashboard: interactive DAG, live SSE audit replay, differential inspector, Paper & Grace design: light pixel-art theme with animated banner, Scroll effect: banner title shrinks into toolbar logo, APIGuard live demo: soul-ninja.github.io/APIGuard, Respects prefers-reduced-motion, Motion: scroll-driven reveals, smooth scrolling, per-section text fades, React Flow (@xyflow/react) with Dagre layout

## Ambiguous Edges - Review These
- `Aman Joshi (GitHub: Soul-Ninja)` → `GitHub handle Code-Breaker-Ctrl (appears in fdr-shield and Ledgio links)`  [AMBIGUOUS]
  raw/github_fdr-shield_README.md · relation: conceptually_related_to
- `Respects prefers-reduced-motion` → `Motion: scroll-driven reveals, smooth scrolling, per-section text fades`  [AMBIGUOUS]
  raw/reference_design_notes.md · relation: conceptually_related_to

## Knowledge Gaps
- **43 isolated node(s):** `GitHub profile stats: 13 repositories, 22 stars, 14 followers`, `GitHub: github.com/Soul-Ninja`, `LinkedIn: linkedin.com/in/aman-joshi-ai`, `X (Twitter): x.com/S0UL_N1NJA`, `LeetCode: leetcode.com/u/CodeBreakr` (+38 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 43 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Aman Joshi (GitHub: Soul-Ninja)` connect `Aman Joshi Profile` to `APIGuard Scanner Engine`, `Ledgio Finance PWA`, `Reference Site Visual System`, `Debunkit Misinformation Detection`, `FDR Shield Hackathon Project`, `Killian Herzer Reference Projects`, `Security Engineering Themes`, `mash Shell OS Internals`?**
  _High betweenness centrality (0.591) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Aman Joshi (GitHub: Soul-Ninja)` (e.g. with `AICTE FDR Shield: automated FDR monitoring platform` and `Team FLUXDCE (Team ID 199409)`) actually correct?**
  _`Aman Joshi (GitHub: Soul-Ninja)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `GitHub profile stats: 13 repositories, 22 stars, 14 followers`, `GitHub: github.com/Soul-Ninja`, `LinkedIn: linkedin.com/in/aman-joshi-ai` to the rest of the system?**
  _43 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `APIGuard Scanner Engine` be split into smaller, more focused modules?**
  _Cohesion score 0.13043478260869565 - nodes in this community are weakly interconnected._
- **Why does `APIGuard: graph-guided API authorization and BOLA scanner` connect `APIGuard Scanner Engine` to `Aman Joshi Profile`, `Reference Site Visual System`, `Debunkit Misinformation Detection`, `FDR Shield Hackathon Project`, `Killian Herzer Reference Projects`, `Security Engineering Themes`, `Dashboards and Motion Design`?**
  _High betweenness centrality (0.249) - this node is a cross-community bridge._

### Low-confidence Hints
_AMBIGUOUS edges — the extractor was unsure. Verify before acting on these._

- **What is the exact relationship between `Aman Joshi (GitHub: Soul-Ninja)` and `GitHub handle Code-Breaker-Ctrl (appears in fdr-shield and Ledgio links)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Respects prefers-reduced-motion` and `Motion: scroll-driven reveals, smooth scrolling, per-section text fades`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._