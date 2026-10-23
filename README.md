<!DOCTYPE html>
<html lang="ug" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>uycod2026 · خۇش كەلدىڭىز</title>
<style>
  :root {
    --bg: #0D1117;
    --blue-1: #0A3D8F;
    --blue-2: #0B6FC2;
    --blue-3: #4A7DB8;
    --accent: #0099FF;
    --text: #FFFFFF;
    --muted: #8B949E;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    min-height: 100vh;
    background: var(--bg);
    color: var(--text);
    font-family: "Noto Sans Arabic", "Segoe UI", Tahoma, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 24px;
  }
  .banner {
    position: relative;
    width: 100%;
    max-width: 820px;
    padding: 56px 32px 64px;
    border-radius: 10px;
    background: linear-gradient(90deg, var(--blue-1) 0%, var(--blue-2) 60%, var(--blue-3) 100%);
    text-align: center;
    overflow: hidden;
  }
  .banner::after {
    content: "";
    position: absolute;
    left: 0; right: 0; bottom: 0;
    height: 38%;
    background: linear-gradient(180deg, transparent, rgba(11,34,57,0.55));
    clip-path: polygon(0 40%, 25% 20%, 55% 45%, 80% 25%, 100% 35%, 100% 100%, 0 100%);
    pointer-events: none;
  }
  .name {
    position: relative;
    z-index: 1;
    font-family: "Segoe UI", Tahoma, sans-serif;
    font-size: clamp(36px, 7vw, 60px);
    font-weight: 800;
    letter-spacing: 1px;
    direction: ltr;
  }
  .tagline {
    position: relative;
    z-index: 1;
    margin-top: 14px;
    font-size: clamp(15px, 2.5vw, 19px);
    font-weight: 600;
    opacity: 0.95;
  }
  .welcome {
    margin: 36px 0 0;
    font-size: clamp(22px, 4vw, 30px);
    font-weight: 700;
    color: var(--accent);
    text-align: center;
  }
  .welcome-sub {
    margin-top: 8px;
    color: var(--muted);
    font-size: 15px;
    text-align: center;
  }
</style>
</head>
<body>
  <main>
    <section class="banner">
      <h1 class="name">uycod2026</h1>
      <p class="tagline">✦ Agentic AI · Claude · Graph &amp; Prompt Engineering ✦</p>
    </section>
    <h2 class="welcome">خۇش كەلدىڭىز</h2>
    <p class="welcome-sub">ئىسمىم uycod2026 — بۇ يەرگە كەلگىنىڭىزدىن خۇرسەنمىز.</p>
  </main>
</body>
</html>
