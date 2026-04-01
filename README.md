<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: 'Courier New', monospace; }
  .profile { background: #0D1117; border-radius: 12px; padding: 2rem; color: #e6edf3; max-width: 780px; }
  .typing-banner { text-align: center; margin-bottom: 1.5rem; }
  .typing-text { color: #00d4ff; font-size: 22px; font-weight: 700; letter-spacing: 0.5px; border-right: 3px solid #00d4ff; white-space: nowrap; overflow: hidden; display: inline-block; animation: typing 3.5s steps(35) infinite alternate, blink 0.7s step-end infinite; max-width: 520px; width: 520px; }
  @keyframes typing { from { width: 0 } to { width: 520px } }
  @keyframes blink { 50% { border-color: transparent } }
  .views-badge { text-align: center; margin-bottom: 1.5rem; }
  .views-badge span { background: #161b22; border: 1px solid #30363d; color: #00d4ff; font-size: 12px; padding: 4px 12px; border-radius: 20px; }
  .divider { border: none; border-top: 1px solid #21262d; margin: 1.5rem 0; }
  .section-title { color: #00d4ff; font-size: 15px; font-weight: 700; margin-bottom: 1rem; display: flex; align-items: center; gap: 8px; }
  .badges-grid { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px; }
  .badge { display: inline-flex; align-items: center; gap: 6px; padding: 5px 10px; border-radius: 6px; font-size: 12px; font-weight: 600; letter-spacing: 0.3px; }
  .badge-python { background: #14354C; color: #4ec9f0; border: 1px solid #1e5a7a; }
  .badge-sql { background: #025E8C; color: #a5d6ff; border: 1px solid #1a7ab5; }
  .badge-fastapi { background: #005571; color: #4ecfb0; border: 1px solid #0a8068; }
  .badge-flask { background: #1a1a1a; color: #e6edf3; border: 1px solid #444; }
  .badge-sqlalchemy { background: #D71F00; color: #fff; border: 1px solid #ff3d1a; }
  .badge-rest { background: #FF6C37; color: #fff; border: 1px solid #ff8555; }
  .badge-pg { background: #316192; color: #cfe0ff; border: 1px solid #4a85c9; }
  .badge-openai { background: #412991; color: #c8b8ff; border: 1px solid #6347c7; }
  .badge-langchain { background: #1C3C3C; color: #6affe0; border: 1px solid #2a6060; }
  .badge-prompt { background: #4a1a1a; color: #ff9a9a; border: 1px solid #8b3030; }
  .badge-rag { background: #0A2540; color: #7aaef0; border: 1px solid #1a4a80; }
  .badge-git { background: #3a1a0a; color: #f97316; border: 1px solid #7a3a1a; }
  .badge-github { background: #161b22; color: #e6edf3; border: 1px solid #444; }
  .badge-vscode { background: #001d3d; color: #55aeff; border: 1px solid #1a5a9a; }
  .stats-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
  .stat-card { background: #161b22; border: 1px solid #30363d; border-radius: 8px; padding: 1rem; }
  .stat-card-title { font-size: 12px; color: #8b949e; margin-bottom: 0.5rem; }
  .stat-row { display: flex; justify-content: space-between; align-items: center; margin-bottom: 6px; }
  .stat-label { font-size: 12px; color: #8b949e; display: flex; align-items: center; gap: 6px; }
  .stat-dot { width: 10px; height: 10px; border-radius: 50%; display: inline-block; }
  .stat-bar-wrap { height: 6px; background: #21262d; border-radius: 3px; margin-top: 4px; overflow: hidden; }
  .stat-bar { height: 100%; border-radius: 3px; }
  .stat-value { font-size: 13px; font-weight: 600; }
  .contact-row { display: flex; gap: 10px; flex-wrap: wrap; }
  .contact-btn { display: inline-flex; align-items: center; gap: 7px; padding: 7px 14px; border-radius: 7px; font-size: 13px; font-weight: 600; text-decoration: none; }
  .btn-gmail { background: #b5200c; color: #fff; }
  .footer-wave { text-align: center; margin-top: 1.5rem; }
  .wave-bar { height: 5px; border-radius: 3px; background: linear-gradient(90deg, #0D1117, #00d4ff, #0D1117); opacity: 0.5; }
  .sub-label { color: #8b949e; font-size: 13px; margin-bottom: 6px; }
</style>

<div class="profile">
  <div class="typing-banner">
    <div class="typing-text">Hey, I'm Remyyyyyl 👋 AI & Automation Explorer</div>
  </div>

  <div class="views-badge">
    <span>👁 Profile Views: 0 • Remyyyyyl</span>
  </div>

  <hr class="divider">

  <div>
    <h2>🧠 About Me</h2>
    <hr class="divider">
    <p><strong>Username:</strong> Remyyyyyl</p>
    <p><strong>University:</strong> Universidad de San Buenaventura – Bogotá 🇨🇴</p>
    <p><strong>Degree:</strong> Systems Engineering</p>
    <p><strong>Focus:</strong> AI, Automation, LLMs</p>
    <p><strong>Currently:</strong> Exploring RAG, LangChain, and GPT-based applications</p>
  </div>

  <hr class="divider">

  <div class="section-title">🛠️ Tech Stack</div>

  <div class="sub-label">🐍 Languages & Core</div>
  <div class="badges-grid">
    <span class="badge badge-python">🐍 Python</span>
    <span class="badge badge-sql">🗃 SQL</span>
  </div>

  <div class="sub-label" style="margin-top:12px;">⚡ Frameworks & APIs</div>
  <div class="badges-grid">
    <span class="badge badge-fastapi">⚡ FastAPI</span>
    <span class="badge badge-flask">🧪 Flask</span>
    <span class="badge badge-sqlalchemy">🔗 SQLAlchemy</span>
    <span class="badge badge-rest">📡 REST API</span>
  </div>

  <div class="sub-label" style="margin-top:12px;">🗄️ Databases</div>
  <div class="badges-grid">
    <span class="badge badge-pg">🐘 PostgreSQL</span>
  </div>

  <div class="sub-label" style="margin-top:12px;">🤖 AI / LLM Stack</div>
  <div class="badges-grid">
    <span class="badge badge-openai">✦ OpenAI GPT</span>
    <span class="badge badge-langchain">🦜 LangChain</span>
    <span class="badge badge-prompt">💬 Prompt Engineering</span>
    <span class="badge badge-rag">🔍 RAG</span>
  </div>

  <div class="sub-label" style="margin-top:12px;">🧰 Tools</div>
  <div class="badges-grid">
    <span class="badge badge-git">Git</span>
    <span class="badge badge-github">GitHub</span>
    <span class="badge badge-vscode">VS Code</span>
  </div>

  <hr class="divider">

  <div class="section-title">📊 GitHub Stats</div>
  <div class="stats-grid">
    <div class="stat-card">
      <div class="stat-card-title">General stats</div>
      <div class="stat-row">
        <span class="stat-label">⭐ Stars</span><span class="stat-value" style="color:#ffd700">0</span>
      </div>
      <div class="stat-row">
        <span class="stat-label">📦 Commits</span><span class="stat-value" style="color:#00d4ff">0</span>
      </div>
      <div class="stat-row">
        <span class="stat-label">🔀 PRs</span><span class="stat-value" style="color:#a8ff78">0</span>
      </div>
    </div>
    <div class="stat-card">
      <div class="stat-card-title">Top languages</div>
      <div class="stat-row">
        <span class="stat-label"><span class="stat-dot" style="background:#4ec9f0"></span>Python</span>
        <span class="stat-value" style="color:#4ec9f0">–</span>
      </div>
      <div class="stat-bar-wrap"><div class="stat-bar" style="background:#4ec9f0; width: 70%"></div></div>
      <div class="stat-row" style="margin-top:8px;">
        <span class="stat-label"><span class="stat-dot" style="background:#316192"></span>SQL</span>
        <span class="stat-value" style="color:#316192">–</span>
      </div>
      <div class="stat-bar-wrap"><div class="stat-bar" style="background:#316192; width: 30%"></div></div>
    </div>
  </div>

  <hr class="divider">

  <div class="section-title">📬 Contact</div>
  <div class="contact-row"> 
    <a class="contact-btn btn-gmail" href="mailto:ocastellanos254@gmail.com">✉ Gmail</a>
  </div>

  <div class="footer-wave" style="margin-top:2rem;">
    <div class="wave-bar"></div>
  </div>
</div>
