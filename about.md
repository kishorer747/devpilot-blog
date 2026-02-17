---
layout: default
title: About
permalink: /about/
---

<div class="post-content" markdown="0">

<!-- Hero -->
<section class="hero" style="text-align:center; padding-bottom: 1.5rem; margin-bottom: 2rem;">
  <h1 class="hero-title">About DevPilot</h1>
  <p class="hero-description" style="max-width:100%;">
    A <strong>development velocity engine</strong> — Rust CLI + Flutter command center<br/>
    that gives a solo developer the output of a <strong>100-person engineering team</strong>.
  </p>
  <div class="hero-stats" style="justify-content:center; margin-top: 1rem;">
    <span class="stat">7 Projects</span>
    <span class="stat-sep">/</span>
    <span class="stat">55+ Sprints</span>
    <span class="stat-sep">/</span>
    <span class="stat">600+ Tasks</span>
    <span class="stat-sep">/</span>
    <span class="stat">200+ Learnings</span>
    <span class="stat-sep">/</span>
    <span class="stat">1 Human</span>
  </div>
</section>

<!-- Feature pills -->
<section class="features-bar" style="margin-bottom: 2.5rem;">
  <div class="feature-pill">AI Agent Orchestra</div>
  <div class="feature-pill">Self-Learning SDLC</div>
  <div class="feature-pill">Cross-Project Intelligence</div>
  <div class="feature-pill">Content Factory</div>
  <div class="feature-pill">CoPilot Command Center</div>
  <div class="feature-pill">Offline-First</div>
</section>

<!-- 100x Vision -->
<h2 id="the-100x-vision">The 100x Vision</h2>

<p>Most tools promise 10x. DevPilot delivers <strong>100x</strong> — not by working harder, but by replacing entire departments with AI-powered agents that plan, build, test, deploy, and learn from every execution.</p>

<blockquote><p><strong>One developer. Zero meetings. Full-stack output.</strong></p></blockquote>

<pre><code class="language-mermaid">graph LR
    DEV["1 Developer"] --> DP["DevPilot"]
    DP --> PM["Product\nPlanning"]
    DP --> ENG["Engineering\n8 Agents"]
    DP --> QA["Testing &\nVerification"]
    DP --> OPS["DevOps &\nDeploy"]
    DP --> DOC["Docs &\nReports"]
    DP --> DATA["Metrics &\nLearning"]

    style DP fill:#4F46E5,color:#fff,stroke:#4F46E5
    style DEV fill:#059669,color:#fff,stroke:#059669
</code></pre>

<hr/>

<!-- What DevPilot Replaces -->
<h2 id="what-devpilot-replaces">What DevPilot Replaces</h2>

<table>
  <thead>
    <tr><th>Traditional Team (100 people)</th><th>DevPilot (1 developer)</th></tr>
  </thead>
  <tbody>
    <tr><td>Product managers write specs</td><td><code>dp ideate</code> generates structured requirements from any input</td></tr>
    <tr><td>10 engineers implement features</td><td><code>dp sprint auto</code> dispatches up to 8 parallel AI agents</td></tr>
    <tr><td>QA team writes and runs tests</td><td>Agents auto-generate tests + verification gates</td></tr>
    <tr><td>DevOps manages CI/CD pipelines</td><td><code>dp ship</code> handles build, test, deploy, verify</td></tr>
    <tr><td>Tech writers produce docs</td><td><code>dp content</code> auto-generates reports, changelogs, posts</td></tr>
    <tr><td>Data team tracks metrics</td><td>Self-learning loop captures every outcome to DB</td></tr>
    <tr><td>Project managers track progress</td><td>Orchestrator with dependency resolution + batching</td></tr>
  </tbody>
</table>

<hr/>

<!-- How It Works -->
<h2 id="how-it-works">How It Works</h2>

<pre><code class="language-mermaid">graph TB
    INPUT["Any Input\nidea / voice / screenshot / doc"] --> IDEATE["dp ideate"]
    IDEATE --> PLAN["dp plan\nSprint + Dependency Graph"]
    PLAN --> ORCH["dp sprint auto\nOrchestrator"]

    ORCH --> A1["Agent 1\nFeature"]
    ORCH --> A2["Agent 2\nFeature"]
    ORCH --> A3["Agent 3\nTests"]
    ORCH --> A4["Agent 4\nDocs"]

    A1 --> VERIFY["dp verify\nVerification Gate"]
    A2 --> VERIFY
    A3 --> VERIFY
    A4 --> VERIFY

    VERIFY --> LEARN["dp learn\nExtract Patterns"]
    LEARN --> KB[("Knowledge Base\n200+ Learnings")]
    KB -.->|Enriches next sprint| ORCH

    style ORCH fill:#4F46E5,color:#fff
    style KB fill:#059669,color:#fff
    style VERIFY fill:#D97706,color:#fff
</code></pre>

<p>The <strong>self-learning loop</strong> is the key differentiator: every success and failure feeds back into the knowledge base, making each subsequent sprint faster and more accurate.</p>

<hr/>

<!-- Core Capabilities -->
<h2 id="core-capabilities">Core Capabilities</h2>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1.25rem; margin: 1.5rem 0;">

  <div style="border: 1px solid #e5e7eb; border-radius: 8px; padding: 1.25rem; background: #f8f9fb;">
    <h3 style="margin: 0 0 0.5rem 0; font-size: 1.1rem;">AI Agent Orchestra</h3>
    <p style="margin: 0; font-size: 0.92rem; color: #555;">Up to 8 parallel agents with role specialization, stuck detection, checkpoint recovery, and permission batching. The orchestrator handles dependency resolution, topological sorting, and verification gates.</p>
  </div>

  <div style="border: 1px solid #e5e7eb; border-radius: 8px; padding: 1.25rem; background: #f8f9fb;">
    <h3 style="margin: 0 0 0.5rem 0; font-size: 1.1rem;">Self-Improving SDLC</h3>
    <p style="margin: 0; font-size: 0.92rem; color: #555;">Every task execution records verification results. The system injects relevant learnings into agent context before each new task. Accuracy trends are tracked per agent, per phase.</p>
  </div>

  <div style="border: 1px solid #e5e7eb; border-radius: 8px; padding: 1.25rem; background: #f8f9fb;">
    <h3 style="margin: 0 0 0.5rem 0; font-size: 1.1rem;">Cross-Project Intelligence</h3>
    <p style="margin: 0; font-size: 0.92rem; color: #555;">Learnings from any project feed all projects. A bug fix discovered in one codebase automatically enriches the knowledge base for every managed project.</p>
  </div>

  <div style="border: 1px solid #e5e7eb; border-radius: 8px; padding: 1.25rem; background: #f8f9fb;">
    <h3 style="margin: 0 0 0.5rem 0; font-size: 1.1rem;">Content Factory</h3>
    <p style="margin: 0; font-size: 0.92rem; color: #555;">Sprint reports, release notes, blog posts, architecture docs — all generated from project data with mermaid diagrams, metrics tables, and polished PDF output.</p>
  </div>

  <div style="border: 1px solid #e5e7eb; border-radius: 8px; padding: 1.25rem; background: #f8f9fb;">
    <h3 style="margin: 0 0 0.5rem 0; font-size: 1.1rem;">CoPilot Command Center</h3>
    <p style="margin: 0; font-size: 0.92rem; color: #555;">A Flutter desktop + mobile app that serves as the CEO dashboard. Sprint tracking, agent monitoring, workflow management, knowledge browsing — all in one pane.</p>
  </div>

  <div style="border: 1px solid #e5e7eb; border-radius: 8px; padding: 1.25rem; background: #f8f9fb;">
    <h3 style="margin: 0 0 0.5rem 0; font-size: 1.1rem;">Vendor-Agnostic AI</h3>
    <p style="margin: 0; font-size: 0.92rem; color: #555;">Pluggable AI provider architecture. Claude, GPT, Ollama, or any LLM. Switch providers without changing a single line of application code.</p>
  </div>

</div>

<hr/>

<!-- Tech Stack -->
<h2 id="tech-stack">Tech Stack</h2>

<table>
  <thead>
    <tr><th>Component</th><th>Technology</th><th>Purpose</th></tr>
  </thead>
  <tbody>
    <tr><td><strong>Core Engine</strong></td><td>Rust</td><td>Speed, safety, zero-cost abstractions</td></tr>
    <tr><td><strong>CLI</strong></td><td>Rust (clap)</td><td>42+ commands, orchestrator, NLP interface</td></tr>
    <tr><td><strong>Gateway</strong></td><td>Rust (Axum)</td><td>JSON-RPC over WebSocket, real-time events</td></tr>
    <tr><td><strong>Command Center</strong></td><td>Flutter</td><td>Desktop + mobile, cross-platform</td></tr>
    <tr><td><strong>Database</strong></td><td>PostgreSQL</td><td>Source of truth for everything</td></tr>
    <tr><td><strong>AI Provider</strong></td><td>Pluggable</td><td>Claude, GPT, Ollama — any LLM</td></tr>
  </tbody>
</table>

<hr/>

<!-- Philosophy -->
<h2 id="philosophy">Philosophy</h2>

<div style="display: grid; grid-template-columns: auto 1fr; gap: 0.6rem 1.25rem; margin: 1.5rem 0; align-items: center;">
  <div style="font-size: 1.5rem; width: 40px; text-align: center;">1.</div>
  <div><strong>100x, not 10x</strong> — Replace departments, not just tasks</div>
  <div style="font-size: 1.5rem; width: 40px; text-align: center;">2.</div>
  <div><strong>DB-first</strong> — PostgreSQL is the source of truth. Files are exports</div>
  <div style="font-size: 1.5rem; width: 40px; text-align: center;">3.</div>
  <div><strong>Self-improving</strong> — Every execution makes the next one better</div>
  <div style="font-size: 1.5rem; width: 40px; text-align: center;">4.</div>
  <div><strong>Ship &gt; Perfect</strong> — Working MVP beats polished vaporware</div>
  <div style="font-size: 1.5rem; width: 40px; text-align: center;">5.</div>
  <div><strong>Offline-first</strong> — Local tools before cloud. AI is the last resort</div>
</div>

<hr/>

<!-- By the Numbers -->
<h2 id="by-the-numbers">By the Numbers</h2>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin: 1.5rem 0;">
  <div style="text-align: center; padding: 1.25rem; border: 1px solid #e5e7eb; border-radius: 8px; background: #f8f9fb;">
    <div style="font-size: 2rem; font-weight: 800; color: #4169E1;">7</div>
    <div style="font-size: 0.85rem; color: #6b7280; font-weight: 500;">Projects Managed</div>
  </div>
  <div style="text-align: center; padding: 1.25rem; border: 1px solid #e5e7eb; border-radius: 8px; background: #f8f9fb;">
    <div style="font-size: 2rem; font-weight: 800; color: #4169E1;">55+</div>
    <div style="font-size: 0.85rem; color: #6b7280; font-weight: 500;">Sprints Completed</div>
  </div>
  <div style="text-align: center; padding: 1.25rem; border: 1px solid #e5e7eb; border-radius: 8px; background: #f8f9fb;">
    <div style="font-size: 2rem; font-weight: 800; color: #4169E1;">600+</div>
    <div style="font-size: 0.85rem; color: #6b7280; font-weight: 500;">Tasks Tracked</div>
  </div>
  <div style="text-align: center; padding: 1.25rem; border: 1px solid #e5e7eb; border-radius: 8px; background: #f8f9fb;">
    <div style="font-size: 2rem; font-weight: 800; color: #4169E1;">200+</div>
    <div style="font-size: 0.85rem; color: #6b7280; font-weight: 500;">Cross-Project Learnings</div>
  </div>
  <div style="text-align: center; padding: 1.25rem; border: 1px solid #e5e7eb; border-radius: 8px; background: #f8f9fb;">
    <div style="font-size: 2rem; font-weight: 800; color: #4169E1;">8</div>
    <div style="font-size: 0.85rem; color: #6b7280; font-weight: 500;">Parallel Agents</div>
  </div>
  <div style="text-align: center; padding: 1.25rem; border: 1px solid #059669; border-radius: 8px; background: linear-gradient(135deg, #059669, #10b981); color: #fff;">
    <div style="font-size: 2rem; font-weight: 800;">1</div>
    <div style="font-size: 0.85rem; font-weight: 500; opacity: 0.9;">Human Operator</div>
  </div>
</div>

<hr/>

<p style="text-align: center; padding: 2rem 0 1rem; color: #6b7280; font-style: italic;">
  Built with Rust. Powered by AI. Driven by one developer doing the work of 100.
</p>

</div>
