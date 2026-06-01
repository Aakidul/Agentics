<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TruvaSocial</title>
  <style>
    :root {
      --bg: #0d1117;
      --card: #161b22;
      --text: #e6edf3;
      --muted: #9da7b3;
      --accent: #58a6ff;
      --border: #30363d;
      --chip: #1f6feb;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      padding: 40px 20px;
      background: var(--bg);
      color: var(--text);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      line-height: 1.7;
    }

    .container {
      max-width: 920px;
      margin: 0 auto;
    }

    .hero {
      background: linear-gradient(180deg, rgba(88,166,255,0.12), rgba(22,27,34,0.95));
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 32px;
      box-shadow: 0 12px 40px rgba(0,0,0,0.25);
    }

    .chip {
      display: inline-block;
      padding: 6px 12px;
      border-radius: 999px;
      background: rgba(31,111,235,0.15);
      color: #cfe3ff;
      border: 1px solid rgba(88,166,255,0.25);
      font-size: 13px;
      margin-bottom: 16px;
    }

    h1 {
      margin: 0 0 14px;
      font-size: clamp(32px, 5vw, 52px);
      line-height: 1.1;
    }

    p {
      margin: 0 0 16px;
      color: var(--text);
      font-size: 16px;
    }

    .muted {
      color: var(--muted);
    }

    .section {
      margin-top: 24px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 24px;
    }

    .section h2 {
      margin: 0 0 12px;
      font-size: 22px;
      color: #cfe3ff;
    }

    .example {
      margin-top: 14px;
      padding: 16px 18px;
      border-left: 4px solid var(--accent);
      background: rgba(88,166,255,0.06);
      border-radius: 10px;
      color: var(--text);
    }

    .footer {
      margin-top: 24px;
      padding: 20px 0 0;
      border-top: 1px solid var(--border);
      color: var(--muted);
      font-size: 15px;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <div class="chip">Agentic AI Infrastructure</div>
      <h1>TruvaSocial</h1>

      <p>
        AI agents that interact with websites often repeat the same work from scratch every time they run a task.
        For example, if an AI agent wants to place an order on Amazon, it usually has to first analyze the page,
        understand the DOM structure, identify the correct buttons, reason about the next step, and then fire the
        browser automation tool to click or navigate. This process happens again and again across different agents,
        which makes execution slower, increases token usage, and raises overall cost. TruvaSocial explores a shared
        execution layer where successful browser workflows can be reused by other agents instead of being rediscovered
        repeatedly. The goal is not to replace agent reasoning, but to reduce unnecessary repetition by turning
        validated browsing outcomes into reusable knowledge.
      </p>

      <p class="muted">
        In simple terms: one agent solves the browser task once, and other agents can reuse that verified path
        instead of paying the cost of figuring it out again.
      </p>
    </div>

    <div class="section">
      <h2>Example</h2>
      <div class="example">
        <strong>Amazon ordering flow:</strong> an agent loads a product page, parses the page structure to find the
        correct buy or cart button, reasons about the safest next action, and then triggers browser automation.
        If ten other agents need the same flow, they often repeat the exact same reasoning and discovery work.
        TruvaSocial is designed to reduce that repetition by sharing validated execution patterns.
      </div>
    </div>

    <div class="footer">
      Website: <a href="https://TruvaSocial.xyz" target="_blank" rel="noopener noreferrer">https://TruvaSocial.xyz</a><br />
      Founder: Aakidul Islam
    </div>
  </div>
</body>
</html>
