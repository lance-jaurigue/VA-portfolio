<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Lance Jaurigue — Executive & Admin Virtual Assistant</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet" />
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --ivory: #F9F7F2;
    --cream: #EDE9DF;
    --ink: #1C1B18;
    --ink-muted: #5A5850;
    --ink-light: #8C8A82;
    --gold: #B8903A;
    --gold-light: #D4AC5A;
    --gold-pale: #F5EDD8;
    --teal: #2D6E6A;
    --teal-light: #4A9490;
    --teal-pale: #E0EFEE;
    --white: #FFFFFF;
    --shadow-sm: 0 1px 3px rgba(28,27,24,0.08);
    --shadow-md: 0 4px 16px rgba(28,27,24,0.10);
    --shadow-lg: 0 12px 40px rgba(28,27,24,0.12);
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--ivory);
    color: var(--ink);
    line-height: 1.6;
    font-size: 16px;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    background: rgba(249,247,242,0.94);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--cream);
    padding: 0 5%;
    display: flex; align-items: center; justify-content: space-between;
    height: 64px;
  }
  .nav-brand {
    font-family: 'Playfair Display', serif;
    font-size: 18px; font-weight: 600;
    letter-spacing: 0.02em;
    color: var(--ink);
    text-decoration: none;
  }
  .nav-links { display: flex; gap: 32px; list-style: none; }
  .nav-links a {
    font-size: 13px; font-weight: 500; letter-spacing: 0.06em;
    text-transform: uppercase; text-decoration: none;
    color: var(--ink-muted);
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--teal); }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 64px;
  }
  .hero-left {
    background: var(--teal);
    display: flex; flex-direction: column; justify-content: center;
    padding: 80px 6% 80px 8%;
    position: relative; overflow: hidden;
  }
  .hero-left::before {
    content: '';
    position: absolute; top: -120px; right: -80px;
    width: 400px; height: 400px;
    border-radius: 50%;
    background: rgba(255,255,255,0.04);
  }
  .hero-left::after {
    content: '';
    position: absolute; bottom: -60px; left: -60px;
    width: 260px; height: 260px;
    border-radius: 50%;
    background: rgba(255,255,255,0.03);
  }
  .hero-tag {
    display: inline-block;
    background: rgba(255,255,255,0.12);
    color: rgba(255,255,255,0.85);
    font-size: 11px; font-weight: 600; letter-spacing: 0.12em;
    text-transform: uppercase; padding: 6px 14px;
    border-radius: 20px; margin-bottom: 28px;
    border: 1px solid rgba(255,255,255,0.18);
    width: fit-content;
  }
  .hero-name {
    font-family: 'Playfair Display', serif;
    font-size: clamp(42px, 5vw, 64px);
    font-weight: 700; line-height: 1.1;
    color: #FFFFFF; margin-bottom: 24px;
  }
  .hero-name em { color: var(--gold-light); font-style: normal; }
  .hero-desc {
    font-size: 16px; font-weight: 300; line-height: 1.75;
    color: rgba(255,255,255,0.78);
    max-width: 420px; margin-bottom: 40px;
  }
  .hero-cta-group { display: flex; gap: 14px; flex-wrap: wrap; }
  .btn-primary {
    background: var(--gold);
    color: #fff; font-family: 'DM Sans', sans-serif;
    font-size: 13px; font-weight: 600; letter-spacing: 0.05em;
    text-transform: uppercase; text-decoration: none;
    padding: 14px 28px; border-radius: 4px;
    transition: background 0.2s, transform 0.15s;
    display: inline-block;
  }
  .btn-primary:hover { background: var(--gold-light); transform: translateY(-1px); }
  .btn-outline {
    border: 1.5px solid rgba(255,255,255,0.4);
    color: rgba(255,255,255,0.85); font-family: 'DM Sans', sans-serif;
    font-size: 13px; font-weight: 500; letter-spacing: 0.05em;
    text-transform: uppercase; text-decoration: none;
    padding: 14px 28px; border-radius: 4px;
    transition: border-color 0.2s, color 0.2s;
    display: inline-block;
  }
  .btn-outline:hover { border-color: #fff; color: #fff; }

  .hero-right {
    background: var(--ivory);
    display: flex; flex-direction: column; justify-content: center;
    padding: 80px 8% 80px 6%;
  }
  .hero-stats-label {
    font-size: 11px; font-weight: 600; letter-spacing: 0.12em;
    text-transform: uppercase; color: var(--ink-light);
    margin-bottom: 24px;
  }
  .stats-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 48px; }
  .stat-box {
    background: var(--white); border: 1px solid var(--cream);
    border-radius: 8px; padding: 24px 20px;
    box-shadow: var(--shadow-sm);
  }
  .stat-num {
    font-family: 'Playfair Display', serif;
    font-size: 36px; font-weight: 700;
    color: var(--teal); line-height: 1; margin-bottom: 8px;
  }
  .stat-num span { font-size: 20px; }
  .stat-label { font-size: 13px; color: var(--ink-muted); line-height: 1.4; }

  .contact-strip {
    background: var(--cream); border-radius: 8px;
    padding: 20px 24px; display: flex; flex-direction: column; gap: 10px;
  }
  .contact-item {
    display: flex; align-items: center; gap: 12px;
    font-size: 14px; color: var(--ink-muted);
  }
  .contact-icon {
    width: 32px; height: 32px; border-radius: 50%;
    background: var(--teal-pale); display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .contact-icon svg { width: 14px; height: 14px; fill: var(--teal); }
  .contact-item a { color: var(--teal); text-decoration: none; font-weight: 500; }
  .contact-item a:hover { text-decoration: underline; }

  /* SECTIONS */
  section { padding: 96px 8%; }
  .section-label {
    font-size: 11px; font-weight: 600; letter-spacing: 0.12em;
    text-transform: uppercase; color: var(--gold);
    margin-bottom: 12px;
  }
  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(28px, 3.5vw, 42px);
    font-weight: 700; line-height: 1.2;
    color: var(--ink); margin-bottom: 48px;
  }
  .section-title em { color: var(--teal); font-style: normal; }

  /* VALUE PROP */
  .value-section { background: var(--ink); }
  .value-section .section-title { color: #fff; }
  .value-section .section-label { color: var(--gold-light); }
  .value-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 28px; }
  .value-card {
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,255,255,0.10);
    border-radius: 8px; padding: 32px 28px;
    transition: background 0.2s, transform 0.2s;
  }
  .value-card:hover { background: rgba(255,255,255,0.08); transform: translateY(-3px); }
  .value-icon {
    width: 44px; height: 44px; border-radius: 8px;
    background: var(--teal); display: flex; align-items: center; justify-content: center;
    margin-bottom: 20px;
  }
  .value-icon svg { width: 20px; height: 20px; fill: #fff; }
  .value-card h3 {
    font-family: 'Playfair Display', serif;
    font-size: 18px; font-weight: 600;
    color: #fff; margin-bottom: 12px;
  }
  .value-card p { font-size: 14px; color: rgba(255,255,255,0.62); line-height: 1.7; }

  /* EXPERIENCE */
  .exp-section { background: var(--white); }
  .exp-timeline { position: relative; padding-left: 32px; }
  .exp-timeline::before {
    content: ''; position: absolute; left: 0; top: 8px; bottom: 0;
    width: 1.5px; background: var(--cream);
  }
  .exp-item { position: relative; margin-bottom: 52px; }
  .exp-item:last-child { margin-bottom: 0; }
  .exp-dot {
    position: absolute; left: -39px; top: 6px;
    width: 14px; height: 14px; border-radius: 50%;
    background: var(--teal); border: 2px solid var(--white);
    box-shadow: 0 0 0 3px var(--teal-pale);
  }
  .exp-meta {
    display: flex; align-items: flex-start; justify-content: space-between;
    flex-wrap: wrap; gap: 8px; margin-bottom: 4px;
  }
  .exp-company {
    font-family: 'Playfair Display', serif;
    font-size: 19px; font-weight: 600; color: var(--ink);
  }
  .exp-period {
    font-size: 12px; font-weight: 500; letter-spacing: 0.06em;
    background: var(--teal-pale); color: var(--teal);
    padding: 4px 12px; border-radius: 20px; white-space: nowrap;
    margin-top: 2px;
  }
  .exp-role {
    font-size: 14px; font-weight: 600; letter-spacing: 0.04em;
    text-transform: uppercase; color: var(--gold);
    margin-bottom: 4px;
  }
  .exp-location { font-size: 13px; color: var(--ink-light); margin-bottom: 16px; }
  .exp-bullets { list-style: none; display: flex; flex-direction: column; gap: 10px; }
  .exp-bullets li {
    display: flex; gap: 12px; align-items: flex-start;
    font-size: 14px; color: var(--ink-muted); line-height: 1.65;
  }
  .exp-bullets li::before {
    content: '';
    flex-shrink: 0; margin-top: 7px;
    width: 6px; height: 6px; border-radius: 50%;
    background: var(--gold);
  }
  .exp-bullets li strong { color: var(--ink); font-weight: 600; }

  /* SKILLS */
  .skills-section { background: var(--ivory); }
  .skills-layout { display: grid; grid-template-columns: 1fr 1fr; gap: 48px; align-items: start; }
  .skill-category { margin-bottom: 36px; }
  .skill-category:last-child { margin-bottom: 0; }
  .skill-cat-label {
    font-size: 11px; font-weight: 600; letter-spacing: 0.10em;
    text-transform: uppercase; color: var(--ink-light);
    margin-bottom: 14px;
  }
  .skill-tags { display: flex; flex-wrap: wrap; gap: 8px; }
  .skill-tag {
    background: var(--white); border: 1px solid var(--cream);
    border-radius: 4px; padding: 7px 14px;
    font-size: 13px; font-weight: 500; color: var(--ink-muted);
    box-shadow: var(--shadow-sm);
    transition: border-color 0.2s, color 0.2s, box-shadow 0.2s;
  }
  .skill-tag:hover { border-color: var(--teal); color: var(--teal); box-shadow: var(--shadow-md); }
  .skill-tag.highlight { background: var(--teal-pale); border-color: var(--teal-light); color: var(--teal); }

  .lang-card {
    background: var(--white); border: 1px solid var(--cream);
    border-radius: 8px; padding: 28px; box-shadow: var(--shadow-sm);
  }
  .lang-level {
    display: flex; align-items: center; justify-content: space-between;
    margin-bottom: 8px;
  }
  .lang-name { font-size: 15px; font-weight: 600; color: var(--ink); }
  .lang-badge {
    font-size: 11px; font-weight: 700; letter-spacing: 0.08em;
    background: var(--gold-pale); color: var(--gold);
    padding: 4px 12px; border-radius: 20px;
  }
  .lang-bar-bg {
    height: 5px; background: var(--cream); border-radius: 4px; margin-bottom: 20px;
  }
  .lang-bar-fill {
    height: 100%; border-radius: 4px; background: linear-gradient(90deg, var(--teal), var(--teal-light));
  }

  /* EDUCATION */
  .edu-section { background: var(--cream); }
  .edu-card {
    background: var(--white); border-radius: 12px;
    padding: 40px 44px; box-shadow: var(--shadow-md);
    display: grid; grid-template-columns: 1fr auto; gap: 24px; align-items: start;
    max-width: 860px;
  }
  .edu-school {
    font-family: 'Playfair Display', serif;
    font-size: 22px; font-weight: 700; color: var(--ink); margin-bottom: 6px;
  }
  .edu-degree {
    font-size: 15px; font-weight: 500; color: var(--teal); margin-bottom: 4px;
  }
  .edu-location { font-size: 13px; color: var(--ink-light); margin-bottom: 20px; }
  .edu-honors { display: flex; gap: 10px; flex-wrap: wrap; }
  .edu-honor {
    font-size: 12px; font-weight: 600; letter-spacing: 0.06em;
    padding: 6px 14px; border-radius: 4px;
  }
  .honor-gold { background: var(--gold-pale); color: var(--gold); }
  .honor-teal { background: var(--teal-pale); color: var(--teal); }
  .gpa-box {
    text-align: center; background: var(--teal);
    border-radius: 10px; padding: 24px 28px; flex-shrink: 0;
  }
  .gpa-num {
    font-family: 'Playfair Display', serif;
    font-size: 36px; font-weight: 700; color: #fff; line-height: 1;
  }
  .gpa-label { font-size: 11px; font-weight: 600; letter-spacing: 0.08em; color: rgba(255,255,255,0.65); margin-top: 6px; }

  /* CTA */
  .cta-section {
    background: var(--teal); text-align: center; padding: 96px 8%;
  }
  .cta-section .section-label { color: rgba(255,255,255,0.65); }
  .cta-section .section-title { color: #fff; margin-bottom: 16px; }
  .cta-subtitle { font-size: 16px; color: rgba(255,255,255,0.7); max-width: 540px; margin: 0 auto 40px; }
  .cta-actions { display: flex; gap: 16px; justify-content: center; flex-wrap: wrap; }
  .btn-white {
    background: #fff; color: var(--teal);
    font-family: 'DM Sans', sans-serif;
    font-size: 13px; font-weight: 700; letter-spacing: 0.06em;
    text-transform: uppercase; text-decoration: none;
    padding: 16px 36px; border-radius: 4px;
    transition: background 0.2s, transform 0.15s;
    display: inline-block;
  }
  .btn-white:hover { background: var(--gold-pale); transform: translateY(-1px); }

  /* FOOTER */
  footer {
    background: var(--ink); padding: 40px 8%;
    display: flex; align-items: center; justify-content: space-between;
    flex-wrap: wrap; gap: 16px;
  }
  footer .brand {
    font-family: 'Playfair Display', serif;
    font-size: 16px; color: rgba(255,255,255,0.6);
  }
  footer .brand strong { color: #fff; }
  footer .copy { font-size: 12px; color: rgba(255,255,255,0.35); }

  /* RESPONSIVE */
  @media (max-width: 860px) {
    .hero { grid-template-columns: 1fr; }
    .hero-left { padding: 60px 7%; min-height: 60vh; }
    .hero-right { padding: 48px 7%; }
    .stats-grid { grid-template-columns: repeat(2, 1fr); }
    .value-grid { grid-template-columns: 1fr; }
    .skills-layout { grid-template-columns: 1fr; }
    .edu-card { grid-template-columns: 1fr; }
    nav .nav-links { display: none; }
  }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(22px); }
    to   { opacity: 1; transform: translateY(0); }
  }
  .hero-tag  { animation: fadeUp 0.5s ease both 0.1s; }
  .hero-name { animation: fadeUp 0.5s ease both 0.2s; }
  .hero-desc { animation: fadeUp 0.5s ease both 0.3s; }
  .hero-cta-group { animation: fadeUp 0.5s ease both 0.4s; }
  .stats-grid { animation: fadeUp 0.6s ease both 0.3s; }
  .contact-strip { animation: fadeUp 0.6s ease both 0.45s; }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#" class="nav-brand">Lance Jaurigue</a>
  <ul class="nav-links">
    <li><a href="#value">Strengths</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-left">
    <span class="hero-tag">Available for Executive &amp; Admin VA Roles</span>
    <h1 class="hero-name">Lance<br/><em>Jaurigue</em></h1>
    <p class="hero-desc">
      Detail-driven virtual professional with a proven record of 95–98% client satisfaction, zero audit findings, and flawless SLA adherence. I keep executives organized, stakeholders informed, and operations running without friction.
    </p>
    <div class="hero-cta-group">
      <a href="mailto:lancejaurigue@gmail.com" class="btn-primary">Hire Me</a>
      <a href="#experience" class="btn-outline">View My Work</a>
    </div>
  </div>
  <div class="hero-right">
    <p class="hero-stats-label">By the numbers</p>
    <div class="stats-grid">
      <div class="stat-box">
        <div class="stat-num">95–98<span>%</span></div>
        <div class="stat-label">CSAT score maintained across 80–100+ daily inquiries</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">99.8<span>%</span></div>
        <div class="stat-label">On-time record completion rate at Accenture</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">23<span>+</span></div>
        <div class="stat-label">Executive reports produced for governing board decisions</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">98.1<span>%</span></div>
        <div class="stat-label">Satisfaction rating on capacity-building program (70 participants)</div>
      </div>
    </div>
    <div class="contact-strip" id="contact">
      <div class="contact-item">
        <div class="contact-icon">
          <svg viewBox="0 0 24 24"><path d="M20 4H4a2 2 0 00-2 2v12a2 2 0 002 2h16a2 2 0 002-2V6a2 2 0 00-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
        </div>
        <a href="mailto:lancejaurigue@gmail.com">lancejaurigue@gmail.com</a>
      </div>
      <div class="contact-item">
        <div class="contact-icon">
          <svg viewBox="0 0 24 24"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.3.2 2.5.6 3.6.1.3 0 .7-.2 1L6.6 10.8z"/></svg>
        </div>
        <span>+63 961 630 7967</span>
      </div>
      <div class="contact-item">
        <div class="contact-icon">
          <svg viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
        </div>
        <span>Manila, Philippines</span>
      </div>
    </div>
  </div>
</section>

<!-- VALUE PROPOSITION -->
<section class="value-section" id="value">
  <p class="section-label">Why hire me</p>
  <h2 class="section-title">What I bring to <em>your executive team</em></h2>
  <div class="value-grid">
    <div class="value-card">
      <div class="value-icon">
        <svg viewBox="0 0 24 24"><path d="M17 12h-5v5h5v-5zM16 1v2H8V1H6v2H5c-1.11 0-1.99.9-1.99 2L3 19c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2h-1V1h-2zm3 18H5V8h14v11z"/></svg>
      </div>
      <h3>Calendar & Schedule Mastery</h3>
      <p>Coordinated 12+ project evaluations and 18 legislative initiatives simultaneously — managing complex, multi-stakeholder schedules across executive and government teams with zero missed deadlines.</p>
    </div>
    <div class="value-card">
      <div class="value-icon">
        <svg viewBox="0 0 24 24"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"/></svg>
      </div>
      <h3>Executive-Grade Documentation</h3>
      <p>Produced 23 board-level decision reports and prepared meeting minutes for multi-agency stakeholders. Experienced in maintaining records at 99.8% on-time accuracy and zero audit findings.</p>
    </div>
    <div class="value-card">
      <div class="value-icon">
        <svg viewBox="0 0 24 24"><path d="M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 5 8 5C6.34 5 5 6.34 5 8s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V19h14v-2.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V19h6v-2.5c0-2.33-4.67-3.5-7-3.5z"/></svg>
      </div>
      <h3>Stakeholder Communications</h3>
      <p>Liaisoned with 20+ internal and external stakeholders weekly and coordinated across Senate, House of Representatives, and private sector clients — diplomatically and efficiently at all times.</p>
    </div>
    <div class="value-card">
      <div class="value-icon">
        <svg viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-7 3c1.93 0 3.5 1.57 3.5 3.5S13.93 13 12 13s-3.5-1.57-3.5-3.5S10.07 6 12 6zm7 13H5v-.23c0-.62.28-1.2.76-1.58C7.47 15.82 9.64 15 12 15s4.53.82 6.24 2.19c.48.38.76.97.76 1.58V19z"/></svg>
      </div>
      <h3>High-Volume Task Handling</h3>
      <p>Maintained 100% schedule adherence while managing 80–100 records daily, 3–5 concurrent live chats, and 300–500+ weekly tickets — all with measurable quality metrics consistently exceeded.</p>
    </div>
    <div class="value-card">
      <div class="value-icon">
        <svg viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm0 10.99h7c-.53 4.12-3.28 7.79-7 8.94V12H5V6.3l7-3.11v8.8z"/></svg>
      </div>
      <h3>Compliance & Data Integrity</h3>
      <p>Ensured full regulatory compliance through systematic record-keeping and SLA adherence — consistently contributing to zero audit findings across review periods at Accenture.</p>
    </div>
    <div class="value-card">
      <div class="value-icon">
        <svg viewBox="0 0 24 24"><path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zm4.24 16L12 15.45 7.77 18l1.12-4.81-3.73-3.23 4.92-.42L12 5l1.92 4.53 4.92.42-3.73 3.23L16.23 18z"/></svg>
      </div>
      <h3>Magna Cum Laude Graduate</h3>
      <p>BA Political Economy from PUP with a GPA of 1.18 and C1+ English proficiency (CEPT). Strong analytical thinking, research capability, and written communication — assets for policy-driven executive environments.</p>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section class="exp-section" id="experience">
  <p class="section-label">Career History</p>
  <h2 class="section-title">Professional <em>Experience</em></h2>
  <div class="exp-timeline">

    <div class="exp-item">
      <div class="exp-dot"></div>
      <div class="exp-meta">
        <div class="exp-company">Projection Management Limited</div>
        <span class="exp-period">Mar 2025 – Present</span>
      </div>
      <div class="exp-role">Remote Chat Support Technician</div>
      <div class="exp-location">South Wales, United Kingdom (Remote)</div>
      <ul class="exp-bullets">
        <li>Handled <strong>80–100+ daily customer inquiries</strong> while maintaining a <strong>95–98% CSAT score</strong> and 85–90% first contact resolution — exceeding all KPIs with minimal supervision.</li>
        <li>Maintained <strong>100% schedule adherence</strong> and 98–100% attendance throughout tenure; consistently delivered sub-2-minute response times.</li>
        <li>Managed 3–5 <strong>concurrent chats simultaneously</strong> and resolved 300–500+ tickets weekly without compromising quality.</li>
      </ul>
    </div>

    <div class="exp-item">
      <div class="exp-dot"></div>
      <div class="exp-meta">
        <div class="exp-company">Accenture, Inc.</div>
        <span class="exp-period">Sep 2025 – Mar 2026</span>
      </div>
      <div class="exp-role">Records &amp; Information Management Associate</div>
      <div class="exp-location">Pioneer St., Mandaluyong</div>
      <ul class="exp-bullets">
        <li>Coordinated with <strong>20+ internal and external stakeholders</strong> weekly to resolve missing or inaccurate records, improving data accuracy by up to 98%.</li>
        <li>Processed 80–100 records daily within established SLAs, maintaining a <strong>99.8% on-time completion rate</strong>.</li>
        <li>Ensured full compliance with administrative procedures — contributing to <strong>zero audit findings</strong> across all review periods.</li>
      </ul>
    </div>

    <div class="exp-item">
      <div class="exp-dot"></div>
      <div class="exp-meta">
        <div class="exp-company">DOST – National Research Council of the Philippines</div>
        <span class="exp-period">Jan 2025 – Aug 2025</span>
      </div>
      <div class="exp-role">Project Technical Assistant IV</div>
      <div class="exp-location">General Santos, Taguig</div>
      <ul class="exp-bullets">
        <li>Coordinated <strong>18 legislative initiatives</strong>, providing administrative and logistical support to the Senate and House of Representatives working alongside the Executive Director.</li>
        <li>Managed scheduling, documentation, and stakeholder communications for <strong>12 project evaluations</strong> and produced <strong>23 decision reports</strong> for the governing board.</li>
        <li>Executed a 3-month capacity-building program for <strong>70 participants</strong> — achieving a 98.1% satisfaction rating and 100% completion rate.</li>
      </ul>
    </div>

    <div class="exp-item">
      <div class="exp-dot"></div>
      <div class="exp-meta">
        <div class="exp-company">Department of Economy, Planning, and Development</div>
        <span class="exp-period">Aug – Oct 2023</span>
      </div>
      <div class="exp-role">Education &amp; Skills Development Intern</div>
      <div class="exp-location">J. Escriva, Pasig</div>
      <ul class="exp-bullets">
        <li>Conducted and presented comparative policy research on ASEAN+3 apprenticeship systems, achieving a <strong>90% evaluation rating</strong>.</li>
        <li>Prepared and finalized <strong>meeting minutes</strong> for key agenda items, enabling timely dissemination to multi-agency stakeholders.</li>
        <li>Maintained and updated regional education databases using Excel — encoding key KPI metrics and improving data organization and accessibility.</li>
      </ul>
    </div>

  </div>
</section>

<!-- SKILLS -->
<section class="skills-section" id="skills">
  <p class="section-label">Toolkit</p>
  <h2 class="section-title">Skills &amp; <em>Capabilities</em></h2>
  <div class="skills-layout">
    <div>
      <div class="skill-category">
        <p class="skill-cat-label">Scheduling &amp; Communication</p>
        <div class="skill-tags">
          <span class="skill-tag highlight">Microsoft Outlook</span>
          <span class="skill-tag highlight">Google Workspace</span>
          <span class="skill-tag highlight">Zoom</span>
          <span class="skill-tag highlight">MS Teams</span>
          <span class="skill-tag">Slack</span>
        </div>
      </div>
      <div class="skill-category">
        <p class="skill-cat-label">Project &amp; Task Management</p>
        <div class="skill-tags">
          <span class="skill-tag highlight">Trello</span>
          <span class="skill-tag highlight">Notion</span>
          <span class="skill-tag">Logistics &amp; Liaising</span>
          <span class="skill-tag">SLA Management</span>
        </div>
      </div>
      <div class="skill-category">
        <p class="skill-cat-label">Data &amp; Documentation</p>
        <div class="skill-tags">
          <span class="skill-tag highlight">Microsoft Excel</span>
          <span class="skill-tag">Records Management</span>
          <span class="skill-tag">Report Writing</span>
          <span class="skill-tag">Meeting Minutes</span>
          <span class="skill-tag">KPI Tracking</span>
        </div>
      </div>
      <div class="skill-category">
        <p class="skill-cat-label">AI &amp; Creative Tools</p>
        <div class="skill-tags">
          <span class="skill-tag">Microsoft Copilot</span>
          <span class="skill-tag">Canva</span>
          <span class="skill-tag">AI Workflow Automation</span>
        </div>
      </div>
    </div>
    <div>
      <p class="skill-cat-label" style="margin-bottom: 16px;">Language Proficiency</p>
      <div class="lang-card">
        <div class="lang-level">
          <span class="lang-name">English</span>
          <span class="lang-badge">C1+ (CEPT Score: 50)</span>
        </div>
        <div class="lang-bar-bg"><div class="lang-bar-fill" style="width: 88%;"></div></div>
        <div class="lang-level">
          <span class="lang-name">Filipino</span>
          <span class="lang-badge">Native</span>
        </div>
        <div class="lang-bar-bg"><div class="lang-bar-fill" style="width: 100%;"></div></div>
      </div>

      <div style="margin-top: 32px;">
        <p class="skill-cat-label" style="margin-bottom: 16px;">Executive Assistant Core Competencies</p>
        <div class="skill-tags" style="flex-direction: column; gap: 10px;">
          <div style="display:flex; align-items:center; gap:12px;">
            <div style="width:8px; height:8px; border-radius:50%; background:var(--gold); flex-shrink:0;"></div>
            <span style="font-size:14px; color:var(--ink-muted);">High-volume inbox &amp; calendar management</span>
          </div>
          <div style="display:flex; align-items:center; gap:12px;">
            <div style="width:8px; height:8px; border-radius:50%; background:var(--gold); flex-shrink:0;"></div>
            <span style="font-size:14px; color:var(--ink-muted);">Executive-level report preparation &amp; drafting</span>
          </div>
          <div style="display:flex; align-items:center; gap:12px;">
            <div style="width:8px; height:8px; border-radius:50%; background:var(--gold); flex-shrink:0;"></div>
            <span style="font-size:14px; color:var(--ink-muted);">Cross-functional &amp; government stakeholder liaison</span>
          </div>
          <div style="display:flex; align-items:center; gap:12px;">
            <div style="width:8px; height:8px; border-radius:50%; background:var(--gold); flex-shrink:0;"></div>
            <span style="font-size:14px; color:var(--ink-muted);">Compliance documentation &amp; audit-readiness</span>
          </div>
          <div style="display:flex; align-items:center; gap:12px;">
            <div style="width:8px; height:8px; border-radius:50%; background:var(--gold); flex-shrink:0;"></div>
            <span style="font-size:14px; color:var(--ink-muted);">Confidential data handling &amp; SLA adherence</span>
          </div>
          <div style="display:flex; align-items:center; gap:12px;">
            <div style="width:8px; height:8px; border-radius:50%; background:var(--gold); flex-shrink:0;"></div>
            <span style="font-size:14px; color:var(--ink-muted);">Remote async communication &amp; self-management</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EDUCATION -->
<section class="edu-section" id="education">
  <p class="section-label">Academic Background</p>
  <h2 class="section-title">Education &amp; <em>Credentials</em></h2>
  <div class="edu-card">
    <div>
      <div class="edu-school">Polytechnic University of the Philippines</div>
      <div class="edu-degree">Bachelor of Arts in Political Economy</div>
      <div class="edu-location">Sta. Mesa, Manila</div>
      <div class="edu-honors">
        <span class="edu-honor honor-gold">Magna Cum Laude</span>
        <span class="edu-honor honor-teal">Research 1 &amp; 2</span>
        <span class="edu-honor honor-teal">CEPT C1+ English</span>
      </div>
    </div>
    <div class="gpa-box">
      <div class="gpa-num">1.18</div>
      <div class="gpa-label">GPA (PH Scale)</div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section">
  <p class="section-label">Ready to collaborate</p>
  <h2 class="section-title">Let's keep your operations <em>flawless</em></h2>
  <p class="cta-subtitle">I'm available for executive and administrative virtual assistant roles — full-time, part-time, or project-based. Let's talk.</p>
  <div class="cta-actions">
    <a href="mailto:lancejaurigue@gmail.com" class="btn-white">Email Me Directly</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="brand"><strong>Lance Jaurigue</strong> — Executive &amp; Admin VA</div>
  <div class="copy">Manila, Philippines &nbsp;·&nbsp; lancejaurigue@gmail.com &nbsp;·&nbsp; +63 961 630 7967</div>
</footer>

</body>
</html>
