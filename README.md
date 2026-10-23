<!DOCTYPE html>
<html lang="ug">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ahmed Bughra · @Uycoder</title>
<style>
  @page { size: A4; margin: 16mm 18mm; }
  :root {
    --azure: #0099FF;
    --azure-deep: #0077CC;
    --azure-soft: #EAF6FF;
    --ink: #0B2239;
    --muted: #5B6B7D;
    --line: #D6EBFA;
  }
  * { box-sizing: border-box; }
  html, body { background: #FFFFFF; }
  body {
    margin: 0;
    font-family: "Segoe UI", "Noto Sans", "Noto Sans Arabic", Tahoma, sans-serif;
    font-size: 11pt;
    line-height: 1.55;
    color: var(--ink);
  }
  .page { max-width: 780px; margin: 0 auto; padding: 32px 24px; }

  header {
    display: flex;
    align-items: center;
    gap: 24px;
    border-bottom: 2px solid var(--azure);
    padding-bottom: 16px;
    margin-bottom: 22px;
  }
  .photo {
    flex: 0 0 120px;
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid var(--azure);
    background: var(--azure-soft);
    overflow: hidden;
  }
  .photo svg { width: 100%; height: 100%; display: block; }
  .head-text { flex: 1; }
  .eyebrow {
    font-family: Consolas, "Courier New", monospace;
    font-size: 9pt;
    color: var(--azure-deep);
    margin: 0 0 4px;
  }
  h1 { font-size: 24pt; margin: 0 0 4px; line-height: 1.2; }
  .handle { color: var(--azure-deep); font-weight: 600; }
  .contact { font-size: 9.5pt; color: var(--muted); margin: 6px 0 0; }

  h2 {
    font-size: 10pt;
    font-family: Consolas, "Courier New", monospace;
    text-transform: uppercase;
    letter-spacing: 1.2px;
    color: var(--azure-deep);
    border-bottom: 1px solid var(--line);
    padding-bottom: 4px;
    margin: 22px 0 10px;
  }
  p { margin: 0 0 8px; }

  .job { margin-bottom: 12px; page-break-inside: avoid; }
  .job-head { display: flex; justify-content: space-between; gap: 12px; flex-wrap: wrap; }
  .job-role { font-weight: 700; font-size: 11.5pt; }
  .job-period { font-family: Consolas, monospace; font-size: 9pt; color: var(--muted); }
  .job-focus { color: var(--muted); font-size: 10pt; margin: 2px 0 0; }

  .pillars { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .pillar {
    border: 1px solid var(--line);
    border-left: 3px solid var(--azure);
    padding: 9px 11px;
    page-break-inside: avoid;
  }
  .pillar h3 { font-size: 10.5pt; margin: 0 0 3px; }
  .pillar p { margin: 0; font-size: 9.5pt; color: var(--muted); }

  table { width: 100%; border-collapse: collapse; font-size: 10pt; }
  th, td { text-align: left; padding: 7px 10px; border-bottom: 1px solid var(--line); vertical-align: top; }
  th { background: var(--azure-soft); color: var(--azure-deep); }
  td:first-child { font-weight: 600; white-space: nowrap; width: 28%; }

  footer {
    margin-top: 24px;
    padding-top: 10px;
    border-top: 1px solid var(--line);
    font-family: Consolas, monospace;
    font-size: 8.5pt;
    color: var(--muted);
    text-align: center;
  }

  @media print {
    html, body { background: #FFFFFF; }
    .page { padding: 0; max-width: none; }
    h2 { page-break-after: avoid; }
  }
</style>
</head>
<body>
<div class="page">

  <header>
    <div class="photo" aria-label="Profile illustration">
      <svg viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
        <rect width="120" height="120" fill="#EAF6FF"/>
        <!-- desk -->
        <rect x="8" y="88" width="104" height="6" rx="2" fill="#0077CC"/>
        <!-- monitor -->
        <rect x="70" y="58" width="42" height="28" rx="3" fill="#0B2239"/>
        <rect x="73" y="61" width="36" height="22" rx="1" fill="#0099FF"/>
        <rect x="88" y="86" width="6" height="4" fill="#0B2239"/>
        <!-- torso -->
        <path d="M18 120 Q22 84 46 80 L56 80 Q72 84 74 120 Z" fill="#0077CC"/>
        <!-- neck -->
        <rect x="46" y="66" width="10" height="12" fill="#F2C9A5"/>
        <!-- head -->
        <circle cx="51" cy="50" r="15" fill="#F2C9A5"/>
        <!-- hair -->
        <path d="M35 48 Q36 30 52 32 Q66 33 66 46 Q60 38 50 40 Q42 42 35 48 Z" fill="#0B2239"/>
        <!-- arm to keyboard -->
        <path d="M56 92 Q66 84 74 90" stroke="#0077CC" stroke-width="7" stroke-linecap="round" fill="none"/>
        <circle cx="46" cy="52" r="1.6" fill="#0B2239"/>
        <circle cx="56" cy="52" r="1.6" fill="#0B2239"/>
        <path d="M46 58 Q51 62 56 58" stroke="#0B2239" stroke-width="1.5" fill="none" stroke-linecap="round"/>
      </svg>
    </div>
    <div class="head-text">
      <p class="eyebrow">// career_matrix</p>
      <h1>Ahmed Bughra <span class="handle">@Uycoder</span></h1>
      <p class="contact">Agentic AI &amp; AI-Native Systems Engineer · 7.5+ years · FinTech · PropTech · Agentic AI</p>
      <p class="contact">github.com/Uycoder</p>
    </div>
  </header>

  <h2>About</h2>
  <p>I build autonomous multi-agent workflows that connect large language models to real enterprise APIs, databases, and developer toolchains.</p>
  <p>My background is in test and API architecture for mobile financial services at Vodafone. I then spent two years engineering backend services and data pipelines for a real estate API provider. That combination shapes how I approach AI systems: reliability and testability come first.</p>

  <h2>Experience</h2>
  <div class="job">
    <div class="job-head">
      <span class="job-role">Agentic AI &amp; AI-Native Systems Engineer</span>
      <span class="job-period">Present · 1+ years</span>
    </div>
    <p class="job-focus">Claude, multi-agent orchestration, vibe coding, prompt and graph engineering</p>
  </div>
  <div class="job">
    <div class="job-head">
      <span class="job-role">Freelance API &amp; Automation Engineer (Real Estate / PropTech)</span>
      <span class="job-period">Previous · 2 years</span>
    </div>
    <p class="job-focus">RESTful API services, backend microservices, data and integration pipelines</p>
  </div>
  <div class="job">
    <div class="job-head">
      <span class="job-role">Software Development Engineer in Test @ Vodafone</span>
      <span class="job-period">Foundation · 4.5 years</span>
    </div>
    <p class="job-focus">Mobile financial services (FinTech), API and UI test automation architecture</p>
  </div>

  <h2>AI Focus Areas</h2>
  <div class="pillars">
    <div class="pillar"><h3>01 · Claude &amp; MCP</h3><p>Connecting Claude models, extended thinking, and the Model Context Protocol to enterprise APIs and toolchains.</p></div>
    <div class="pillar"><h3>02 · Agentic Orchestration</h3><p>Multi-agent systems that plan, call tools, validate outputs, and recover from failures with minimal human intervention.</p></div>
    <div class="pillar"><h3>03 · Vibe Coding</h3><p>AI-assisted development that turns domain specifications into production code, held to the same testing standards as hand-written code.</p></div>
    <div class="pillar"><h3>04 · Prompt Engineering</h3><p>Deterministic system prompts with chain-of-thought structure, XML context schemas, and automated evaluation rubrics.</p></div>
    <div class="pillar"><h3>05 · Graph Engineering</h3><p>Modeling API call chains and service dependencies as knowledge graphs to support GraphRAG and system reasoning.</p></div>
  </div>

  <h2>Technical Stack</h2>
  <table>
    <thead><tr><th>Domain</th><th>Technologies</th></tr></thead>
    <tbody>
      <tr><td>AI &amp; Agents</td><td>Claude, Agentic AI, MCP, Prompt Engineering, GraphRAG</td></tr>
      <tr><td>Backend &amp; API</td><td>Java, Spring Boot, REST APIs, Hibernate, JavaScript</td></tr>
      <tr><td>Test &amp; QA</td><td>Selenium, Cucumber (BDD), Postman, Jira, jQuery</td></tr>
      <tr><td>DevOps &amp; Cloud</td><td>AWS, Docker, Jenkins, Linux, Git, Tomcat</td></tr>
      <tr><td>Data</td><td>Oracle, PostgreSQL, Knowledge Graphs</td></tr>
    </tbody>
  </table>

  <footer>Ahmed Bughra · @Uycoder</footer>
</div>
</body>
</html>
