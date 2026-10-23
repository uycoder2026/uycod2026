<!DOCTYPE html>
<html lang="ug">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Ahmed Bughra (@Uycoder) - Agentic AI & AI-Native Systems Engineer">
<title>Ahmed Bughra · @Uycoder</title>
<style>
  :root {
    --azure: #0099FF;
    --azure-deep: #0077CC;
    --azure-soft: #EAF6FF;
    --white: #FFFFFF;
    --ink: #0B2239;
    --muted: #5B6B7D;
    --line: #D6EBFA;
    --radius: 10px;
    --mono: "JetBrains Mono", Consolas, "Courier New", monospace;
    --sans: "Segoe UI", "Noto Sans", system-ui, -apple-system, sans-serif;
  }

  *, *::before, *::after { box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    margin: 0;
    font-family: var(--sans);
    font-size: 16px;
    line-height: 1.65;
    color: var(--ink);
    background: var(--white);
  }
  a { color: var(--azure-deep); text-decoration: none; }
  a:hover { text-decoration: underline; }
  code, .mono { font-family: var(--mono); font-size: 0.9em; }

  .container { max-width: 960px; margin: 0 auto; padding: 0 24px; }

  /* ---------- Header ---------- */
  .hero {
    border-bottom: 2px solid var(--azure);
    padding: 64px 0 40px;
  }
  .eyebrow {
    font-family: var(--mono);
    font-size: 13px;
    color: var(--azure);
    letter-spacing: 0.5px;
    margin: 0 0 8px;
  }
  .hero h1 {
    font-size: clamp(28px, 4vw, 40px);
    line-height: 1.2;
    margin: 0 0 8px;
    font-weight: 700;
  }
  .handle { color: var(--azure); }
  .lead {
    color: var(--muted);
    font-size: 17px;
    max-width: 680px;
    margin: 12px 0 0;
  }
  .badges { margin-top: 20px; display: flex; flex-wrap: wrap; gap: 8px; }
  .badge {
    font-family: var(--mono);
    font-size: 12px;
    padding: 4px 10px;
    border-radius: 999px;
    border: 1px solid var(--azure);
    color: var(--azure-deep);
    background: var(--azure-soft);
  }

  /* ---------- Sections ---------- */
  section { padding: 48px 0; border-bottom: 1px solid var(--line); }
  section:last-of-type { border-bottom: none; }
  h2 {
    font-size: 14px;
    font-family: var(--mono);
    text-transform: uppercase;
    letter-spacing: 1.5px;
    color: var(--azure);
    margin: 0 0 20px;
  }

  /* ---------- Summary ---------- */
  .summary p { margin: 0 0 14px; max-width: 760px; }

  /* ---------- Timeline ---------- */
  .timeline { list-style: none; margin: 0; padding: 0 0 0 26px; position: relative; }
  .timeline::before {
    content: "";
    position: absolute;
    left: 6px; top: 8px; bottom: 8px;
    width: 2px;
    background: var(--line);
  }
  .timeline li { position: relative; margin-bottom: 26px; }
  .timeline li::before {
    content: "";
    position: absolute;
    left: -25px; top: 7px;
    width: 12px; height: 12px;
    border-radius: 50%;
    background: var(--white);
    border: 2px solid var(--azure);
  }
  .timeline li.current::before { background: var(--azure); }
  .period { font-family: var(--mono); font-size: 12px; color: var(--muted); }
  .role { font-size: 18px; font-weight: 600; margin: 2px 0; }
  .focus { font-size: 14px; color: var(--muted); margin: 0; }

  /* ---------- Pillars ---------- */
  .pillars { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 16px; }
  .pillar {
    border: 1px solid var(--line);
    border-top: 3px solid var(--azure);
    border-radius: var(--radius);
    padding: 18px;
  }
  .pillar-id { font-family: var(--mono); font-size: 12px; color: var(--azure); }
  .pillar h3 { font-size: 16px; margin: 4px 0 8px; }
  .pillar p { margin: 0; font-size: 14px; color: var(--muted); }

  /* ---------- Arsenal table ---------- */
  .table-wrap { overflow-x: auto; border: 1px solid var(--line); border-radius: var(--radius); }
  table { width: 100%; border-collapse: collapse; font-size: 14px; }
  th, td { text-align: left; padding: 12px 16px; border-bottom: 1px solid var(--line); vertical-align: top; }
  th { background: var(--azure-soft); color: var(--azure-deep); font-weight: 600; }
  tr:last-child td { border-bottom: none; }
  td:first-child { white-space: nowrap; font-weight: 600; }

  /* ---------- GitHub stats ---------- */
  .stats { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 16px; }
  .stats img { width: 100%; height: auto; border-radius: var(--radius); border: 1px solid var(--line); }

  /* ---------- Footer ---------- */
  footer {
    padding: 28px 0 48px;
    font-family: var(--mono);
    font-size: 12px;
    color: var(--muted);
    text-align: center;
  }

  @media (prefers-reduced-motion: reduce) {
    html { scroll-behavior: auto; }
  }
</style>
</head>
<body>

<header class="hero">
  <div class="container">
    <p class="eyebrow">// career_matrix</p>
    <h1>Ahmed Bughra <span class="handle">@Uycoder</span></h1>
    <p class="lead">Agentic AI &amp; AI-Native Systems Engineer. 7.5+ years across FinTech QA, PropTech API engineering, and autonomous AI systems.</p>
    <div class="badges">
      <span class="badge">Agentic AI</span>
      <span class="badge">Claude / MCP</span>
      <span class="badge">GraphRAG</span>
      <span class="badge">Spring Boot</span>
      <span class="badge">Test Automation</span>
    </div>
  </div>
</header>

<main class="container">

  <section class="summary" id="about">
    <h2>About</h2>
    <p>I build autonomous multi-agent workflows that connect large language models to real enterprise APIs, databases, and developer toolchains.</p>
    <p>My background is in test and API architecture for high-concurrency mobile financial services at Vodafone. I then spent two years engineering backend services and data pipelines for a real estate API provider. That combination shapes how I approach AI systems: reliability and testability come first.</p>
  </section>

  <section id="experience">
    <h2>Experience</h2>
    <ol class="timeline">
      <li class="current">
        <div class="period">Present · 1+ years</div>
        <div class="role">Agentic AI &amp; AI-Native Systems Engineer</div>
        <p class="focus">Claude, multi-agent orchestration, vibe coding, prompt and graph engineering</p>
      </li>
      <li>
        <div class="period">Previous · 2 years</div>
        <div class="role">Freelance API &amp; Automation Engineer (Real Estate / PropTech)</div>
        <p class="focus">RESTful API services, backend microservices, data and integration pipelines</p>
      </li>
      <li>
        <div class="period">Foundation · 4.5 years</div>
        <div class="role">Software Development Engineer in Test @ Vodafone</div>
        <p class="focus">Mobile financial services (FinTech), API and UI test automation architecture</p>
      </li>
    </ol>
  </section>

  <section id="focus">
    <h2>AI Focus Areas</h2>
    <div class="pillars">
      <article class="pillar">
        <div class="pillar-id">01</div>
        <h3>Claude &amp; MCP</h3>
        <p>Connecting Claude models, extended thinking, and the Model Context Protocol to enterprise APIs and toolchains.</p>
      </article>
      <article class="pillar">
        <div class="pillar-id">02</div>
        <h3>Agentic Orchestration</h3>
        <p>Multi-agent systems that plan, call tools, validate outputs, and recover from failures with minimal human intervention.</p>
      </article>
      <article class="pillar">
        <div class="pillar-id">03</div>
        <h3>Vibe Coding</h3>
        <p>AI-assisted development that turns domain specifications into production code, held to the same testing standards as hand-written code.</p>
      </article>
      <article class="pillar">
        <div class="pillar-id">04</div>
        <h3>Prompt Engineering</h3>
        <p>Deterministic system prompts with chain-of-thought structure, XML context schemas, and automated evaluation rubrics.</p>
      </article>
      <article class="pillar">
        <div class="pillar-id">05</div>
        <h3>Graph Engineering</h3>
        <p>Modeling API call chains and service dependencies as knowledge graphs to support GraphRAG and system reasoning.</p>
      </article>
    </div>
  </section>

  <section id="stack">
    <h2>Technical Stack</h2>
    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>Domain</th><th>Technologies</th></tr>
        </thead>
        <tbody>
          <tr><td>AI &amp; Agents</td><td>Claude, Agentic AI, MCP, Prompt Engineering, GraphRAG</td></tr>
          <tr><td>Backend &amp; API</td><td>Java, Spring Boot, REST APIs, Hibernate, JavaScript</td></tr>
          <tr><td>Test &amp; QA</td><td>Selenium, Cucumber (BDD), Postman, Jira, jQuery</td></tr>
          <tr><td>DevOps &amp; Cloud</td><td>AWS, Docker, Jenkins, Linux, Git, Tomcat</td></tr>
          <tr><td>Data</td><td>Oracle, PostgreSQL, Knowledge Graphs</td></tr>
        </tbody>
      </table>
    </div>
  </section>

  <section id="github">
    <h2>GitHub</h2>
    <div class="stats">
      <img src="https://github-readme-stats.vercel.app/api?username=Uycoder&show_icons=true&theme=default" alt="GitHub stats for Uycoder" loading="lazy">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Uycoder&layout=compact&theme=default" alt="Top languages for Uycoder" loading="lazy">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=Uycoder&theme=default" alt="GitHub streak for Uycoder" loading="lazy">
    </div>
  </section>

</main>

<footer>
  <div class="container">Ahmed Bughra · @Uycoder · built with plain HTML &amp; CSS</div>
</footer>

</body>
</html>
