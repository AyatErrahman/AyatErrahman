
<style>
  @import url('https://fonts.googleapis.com/css2?family=MedievalSharp&family=IM+Fell+English:ital@0;1&display=swap');

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body { background: transparent; }

  .hp-root {
    font-family: 'IM Fell English', Georgia, serif;
    color: var(--color-text-primary);
    padding: 0.5rem 0 2rem;
    max-width: 680px;
  }

  .crest-banner {
    text-align: center;
    margin-bottom: 1.5rem;
    padding: 1.5rem 1rem 1rem;
    border: 1.5px solid var(--color-border-secondary);
    border-radius: var(--border-radius-lg);
    background: var(--color-background-secondary);
    position: relative;
    overflow: hidden;
  }

  .stars-bg {
    position: absolute; inset: 0; pointer-events: none; opacity: 0.18;
  }

  .crest-banner h1 {
    font-size: 22px;
    font-weight: 500;
    letter-spacing: 0.03em;
    margin-top: 10px;
  }

  .crest-banner h3 {
    font-size: 14px;
    color: var(--color-text-secondary);
    font-style: italic;
    margin-top: 6px;
    font-weight: 400;
    letter-spacing: 0.02em;
  }

  .divider {
    display: flex; align-items: center; gap: 10px;
    margin: 1.5rem 0 1rem;
  }
  .divider-line { flex: 1; height: 0.5px; background: var(--color-border-secondary); }
  .divider-icon { color: var(--color-text-tertiary); font-size: 14px; }

  .section-title {
    font-size: 16px;
    font-weight: 500;
    margin-bottom: 1rem;
    display: flex; align-items: center; gap: 8px;
    font-family: 'IM Fell English', Georgia, serif;
    letter-spacing: 0.02em;
  }

  .about-card {
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-lg);
    padding: 1rem 1.25rem;
  }

  .about-row {
    display: flex; align-items: flex-start; gap: 10px;
    padding: 7px 0;
    border-bottom: 0.5px solid var(--color-border-tertiary);
    font-size: 14px;
    line-height: 1.5;
  }
  .about-row:last-child { border-bottom: none; }
  .about-icon { flex-shrink: 0; margin-top: 1px; }

  .connect-row {
    display: flex; gap: 12px; flex-wrap: wrap;
  }

  .connect-btn {
    display: flex; align-items: center; gap: 7px;
    padding: 8px 14px;
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-secondary);
    border-radius: var(--border-radius-md);
    font-size: 13px;
    font-family: 'IM Fell English', Georgia, serif;
    color: var(--color-text-primary);
    cursor: pointer;
    text-decoration: none;
    transition: background 0.15s;
  }
  .connect-btn:hover { background: var(--color-background-secondary); }

  .tools-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(68px, 1fr));
    gap: 10px;
  }

  .tool-chip {
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-md);
    padding: 10px 6px 8px;
    text-align: center;
    font-size: 11px;
    color: var(--color-text-secondary);
    font-family: 'IM Fell English', Georgia, serif;
  }

  .tool-chip img {
    width: 28px; height: 28px; display: block; margin: 0 auto 5px;
  }

  .stats-card {
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-lg);
    padding: 1rem 1.25rem;
    text-align: center;
  }

  .stats-card img {
    max-width: 100%;
    border-radius: 6px;
  }

  .footer-scroll {
    font-size: 13px;
    color: var(--color-text-secondary);
    font-style: italic;
    text-align: center;
    margin-top: 1.5rem;
    padding: 0.75rem 1rem;
    border-top: 0.5px solid var(--color-border-tertiary);
  }
</style>

<div class="hp-root">

  <div class="crest-banner">
    <svg class="stars-bg" viewBox="0 0 600 160" xmlns="http://www.w3.org/2000/svg">
      <circle cx="40" cy="20" r="1.5" fill="currentColor"/>
      <circle cx="120" cy="50" r="1" fill="currentColor"/>
      <circle cx="200" cy="15" r="2" fill="currentColor"/>
      <circle cx="310" cy="40" r="1" fill="currentColor"/>
      <circle cx="450" cy="10" r="1.5" fill="currentColor"/>
      <circle cx="540" cy="55" r="1" fill="currentColor"/>
      <circle cx="580" cy="30" r="2" fill="currentColor"/>
      <circle cx="70" cy="80" r="1" fill="currentColor"/>
      <circle cx="160" cy="100" r="1.5" fill="currentColor"/>
      <circle cx="390" cy="80" r="1" fill="currentColor"/>
      <circle cx="490" cy="130" r="2" fill="currentColor"/>
      <circle cx="250" cy="140" r="1" fill="currentColor"/>
    </svg>

    <svg width="72" height="72" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
      <polygon points="36,4 44,26 68,26 49,40 56,62 36,49 16,62 23,40 4,26 28,26" fill="none" stroke="var(--color-border-secondary)" stroke-width="1.2"/>
      <polygon points="36,14 41,28 56,28 44,36 49,50 36,42 23,50 28,36 16,28 31,28" fill="var(--color-background-secondary)" stroke="none"/>
      <text x="36" y="41" text-anchor="middle" font-size="16" font-family="serif" fill="var(--color-text-primary)">✦</text>
    </svg>

    <h1>Ayat Errahmane Nacer</h1>
    <h3>Computer Science Student &nbsp;·&nbsp; AI/ML Learner &nbsp;·&nbsp; Web Developer &nbsp;·&nbsp; Tech Enthusiast</h3>
  </div>

  <div class="divider">
    <div class="divider-line"></div>
    <svg class="divider-icon" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M8 1l1.5 4.5H14l-3.7 2.7 1.4 4.3L8 10l-3.7 2.5 1.4-4.3L2 5.5h4.5z" stroke="currentColor" stroke-width="0.8" fill="none"/>
    </svg>
    <div class="divider-line"></div>
  </div>

  <p class="section-title">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M4 19.5v-15A2.5 2.5 0 0 1 6.5 2H19a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H6.5a1 1 0 0 1 0-5H20"/></svg>
    About Me
  </p>

  <div class="about-card">
    <div class="about-row">
      <svg class="about-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 2a10 10 0 1 0 10 10"/><path d="M12 8v4l2 2"/><path d="M19 3v4h4"/></svg>
      <span>Currently working on <strong>AI projects and full-stack web applications</strong></span>
    </div>
    <div class="about-row">
      <svg class="about-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>
      <span>Learning <strong>Machine Learning, Deep Learning, NLP</strong> and <strong>Cloud</strong></span>
    </div>
    <div class="about-row">
      <svg class="about-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="3"/><path d="M12 1v4M12 19v4M4.22 4.22l2.83 2.83M16.95 16.95l2.83 2.83M1 12h4M19 12h4M4.22 19.78l2.83-2.83M16.95 7.05l2.83-2.83"/></svg>
      <span>Exploring <strong>UI/UX, Graphic Design</strong> and <strong>3D Design</strong> on the side</span>
    </div>
    <div class="about-row">
      <svg class="about-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
      <span>Portfolio: <em>coming soon…</em></span>
    </div>
    <div class="about-row">
      <svg class="about-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
      <span>Ultimate goal: Becoming skilled enough to <strong>publish impactful research</strong></span>
    </div>
    <div class="about-row">
      <svg class="about-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
      <span>ayaterrahmane.nacer@ensia.edu.dz &nbsp;|&nbsp; ayanacer00@gmail.com</span>
    </div>
    <div class="about-row">
      <svg class="about-icon" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 8h1a4 4 0 0 1 0 8h-1"/><path d="M2 8h16v9a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V8z"/><line x1="6" y1="1" x2="6" y2="4"/><line x1="10" y1="1" x2="10" y2="4"/><line x1="14" y1="1" x2="14" y2="4"/></svg>
      <span>Fun fact: Coffee is my superpower</span>
    </div>
  </div>

  <div class="divider">
    <div class="divider-line"></div>
    <svg class="divider-icon" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M8 1l1.5 4.5H14l-3.7 2.7 1.4 4.3L8 10l-3.7 2.5 1.4-4.3L2 5.5h4.5z" stroke="currentColor" stroke-width="0.8" fill="none"/></svg>
    <div class="divider-line"></div>
  </div>

  <p class="section-title">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
    Connect with me
  </p>

  <div class="connect-row">
    <a href="https://linkedin.com" target="_blank" class="connect-btn">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
      LinkedIn
    </a>
    <a href="#" target="_blank" class="connect-btn">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
      Portfolio
    </a>
    <a href="mailto:ayanacer00@gmail.com" class="connect-btn">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
      Email
    </a>
  </div>

  <div class="divider">
    <div class="divider-line"></div>
    <svg class="divider-icon" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M8 1l1.5 4.5H14l-3.7 2.7 1.4 4.3L8 10l-3.7 2.5 1.4-4.3L2 5.5h4.5z" stroke="currentColor" stroke-width="0.8" fill="none"/></svg>
    <div class="divider-line"></div>
  </div>

  <p class="section-title">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"/></svg>
    Languages and tools
  </p>

  <div class="tools-grid">
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/python.png" alt="Python"/>Python</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/javascript.png" alt="JavaScript"/>JavaScript</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/c-programming.png" alt="C"/>C</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/html-5.png" alt="HTML5"/>HTML5</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/css3.png" alt="CSS3"/>CSS3</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/react-native.png" alt="React"/>React</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/git.png" alt="Git"/>Git</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/github.png" alt="GitHub"/>GitHub</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/oracle-logo.png" alt="Oracle"/>Oracle</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/mysql-logo.png" alt="MySQL"/>MySQL</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/linux--v1.png" alt="Linux"/>Linux</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/figma.png" alt="Figma"/>Figma</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/adobe-photoshop.png" alt="Photoshop"/>Photoshop</div>
    <div class="tool-chip"><img src="https://img.icons8.com/color/48/adobe-illustrator.png" alt="Illustrator"/>Illustrator</div>
  </div>

  <div class="divider">
    <div class="divider-line"></div>
    <svg class="divider-icon" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M8 1l1.5 4.5H14l-3.7 2.7 1.4 4.3L8 10l-3.7 2.5 1.4-4.3L2 5.5h4.5z" stroke="currentColor" stroke-width="0.8" fill="none"/></svg>
    <div class="divider-line"></div>
  </div>

  <p class="section-title">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg>
    GitHub stats
  </p>

  <div class="stats-card">
    <img src="https://github-readme-stats.vercel.app/api?username=AyatErrahman&show_icons=true&theme=tokyonight" alt="GitHub Stats"/>
  </div>

  <div class="footer-scroll">
    "Always building, always learning — the journey never ends."
  </div>

</div>
