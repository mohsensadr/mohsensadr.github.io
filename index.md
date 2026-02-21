
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohsen Sadr</title>

    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
                inlineMath: [['$', '$'], ['\\(', '\\)']],
                displayMath: [['$$', '$$'], ['\\[', '\\]']],
                processEscapes: true
            }
        });
    </script>
    <script type="text/javascript" async
            src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
    </script>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Source+Serif+4:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

    <style>
    :root {
      --color-bg: #fafafa;
      --color-surface: #ffffff;
      --color-text: #1e293b;
      --color-text-secondary: #475569;
      --color-text-muted: #94a3b8;
      --color-accent: #1e40af;
      --color-accent-light: #3b82f6;
      --color-accent-bg: #eff6ff;
      --color-border: #e2e8f0;
      --color-nav-bg: rgba(255, 255, 255, 0.85);
      --font-sans: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      --font-serif: 'Source Serif 4', Georgia, 'Times New Roman', serif;
      --max-width: 820px;
      --nav-height: 56px;
      --section-gap: 2rem;
    }

    *, *::before, *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
      -webkit-text-size-adjust: 100%;
    }

    body {
      font-family: var(--font-sans);
      font-size: 16px;
      line-height: 1.7;
      color: var(--color-text);
      background-color: var(--color-bg);
      padding-top: var(--nav-height);
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
    }

    /* ── Navigation ── */
    nav {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: var(--nav-height);
      background: var(--color-nav-bg);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--color-border);
      z-index: 1000;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 0.15rem;
      padding: 0 1rem;
      transform: translateY(0);
      transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1),
                  box-shadow 0.3s ease;
    }

    nav.scrolled {
      box-shadow: 0 1px 8px rgba(0, 0, 0, 0.06);
    }

    nav a {
      color: var(--color-text-secondary);
      text-decoration: none;
      font-size: 0.825rem;
      font-weight: 500;
      padding: 0.4rem 0.6rem;
      border-radius: 6px;
      transition: color 0.2s, background-color 0.2s;
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
      gap: 4px;
    }

    nav a:hover {
      color: var(--color-accent);
      background-color: var(--color-accent-bg);
    }

    nav a img {
      width: 18px;
      height: 18px;
      opacity: 0.7;
      transition: opacity 0.2s;
    }

    nav a:hover img {
      opacity: 1;
    }

    nav .nav-divider {
      width: 1px;
      height: 20px;
      background: var(--color-border);
      margin: 0 0.25rem;
    }

    /* ── Hero / Header ── */
    .hero {
      text-align: center;
      padding: 4rem 1.5rem 3rem;
      max-width: var(--max-width);
      margin: 0 auto;
    }

    .hero-avatar {
      width: 280px;
      height: 280px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid var(--color-border);
      margin-bottom: 1.5rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
    }

    .hero h1 {
      font-family: var(--font-serif);
      font-size: 2.25rem;
      font-weight: 600;
      color: var(--color-text);
      margin-bottom: 0.5rem;
      letter-spacing: -0.02em;
    }

    .hero .subtitle {
      font-size: 1.05rem;
      color: var(--color-text-secondary);
      font-weight: 400;
      max-width: 600px;
      margin: 0 auto;
      line-height: 1.6;
    }

    /* ── Sections ── */
    .content-wrapper {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 0 1.5rem 4rem;
    }

    section {
      background: var(--color-surface);
      border: 1px solid var(--color-border);
      border-radius: 12px;
      padding: 2rem 2.5rem;
      margin-bottom: var(--section-gap);
      box-shadow: 0 1px 3px rgba(0, 0, 0, 0.04);
      transition: box-shadow 0.3s ease;
    }

    section:hover {
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06);
    }

    h2 {
      font-family: var(--font-serif);
      font-size: 1.5rem;
      font-weight: 600;
      color: var(--color-text);
      margin-bottom: 1.25rem;
      padding-bottom: 0.75rem;
      border-bottom: 2px solid var(--color-accent);
      display: inline-block;
      letter-spacing: -0.01em;
    }

    h3 {
      font-size: 1.05rem;
      font-weight: 600;
      color: var(--color-text);
      margin-top: 1.5rem;
      margin-bottom: 0.5rem;
    }

    h3:first-of-type {
      margin-top: 0.5rem;
    }

    /* ── Project cards ── */
    .project {
      padding: 1.5rem 0;
      border-bottom: 1px solid var(--color-border);
    }

    .project:first-of-type {
      padding-top: 0.5rem;
    }

    .project:last-of-type {
      border-bottom: none;
      padding-bottom: 0;
    }

    .project h3 {
      margin-top: 0;
    }

    p {
      color: var(--color-text-secondary);
      margin-bottom: 0.75rem;
      line-height: 1.75;
    }

    a {
      color: var(--color-accent);
      text-decoration: none;
      transition: color 0.2s;
    }

    a:hover {
      color: var(--color-accent-light);
      text-decoration: underline;
    }

    /* ── About ── */
    section#about p {
      font-size: 0.975rem;
    }

    /* ── Experience / Education timeline ── */
    .timeline {
      list-style: none;
      padding: 0;
      position: relative;
    }

    .timeline::before {
      content: '';
      position: absolute;
      left: 6px;
      top: 8px;
      bottom: 8px;
      width: 2px;
      background: var(--color-border);
    }

    .timeline li {
      position: relative;
      padding-left: 2rem;
      margin-bottom: 1.5rem;
    }

    .timeline li:last-child {
      margin-bottom: 0;
    }

    .timeline li::before {
      content: '';
      position: absolute;
      left: 2px;
      top: 8px;
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: var(--color-accent);
      border: 2px solid var(--color-surface);
      box-shadow: 0 0 0 2px var(--color-accent);
    }

    .timeline .role {
      font-weight: 600;
      color: var(--color-text);
      font-size: 1rem;
    }

    .timeline .org {
      color: var(--color-text-secondary);
      font-size: 0.925rem;
    }

    .timeline .date {
      color: var(--color-text-muted);
      font-size: 0.85rem;
      font-weight: 500;
    }

    /* ── Awards ── */
    section#awards ul {
      list-style: none;
      padding: 0;
    }

    section#awards li {
      position: relative;
      padding-left: 1.5rem;
      margin-bottom: 0.85rem;
      color: var(--color-text-secondary);
      font-size: 0.95rem;
      line-height: 1.65;
    }

    section#awards li::before {
      content: '';
      position: absolute;
      left: 0;
      top: 10px;
      width: 8px;
      height: 8px;
      background: var(--color-accent);
      border-radius: 2px;
      transform: rotate(45deg);
    }

    /* ── Publications ── */
    .pub-category {
      font-size: 0.9rem;
      font-weight: 600;
      color: var(--color-accent);
      text-transform: uppercase;
      letter-spacing: 0.05em;
      margin-top: 1.5rem;
      margin-bottom: 0.75rem;
      padding-top: 0.5rem;
    }

    .pub-category:first-of-type {
      margin-top: 0.25rem;
    }

    section#publications ul {
      list-style: none;
      padding: 0;
    }

    section#publications li {
      margin-bottom: 0.85rem;
      padding: 0.75rem 1rem;
      border-radius: 8px;
      background: var(--color-bg);
      border: 1px solid transparent;
      transition: border-color 0.2s, background 0.2s;
      font-size: 0.925rem;
      line-height: 1.65;
      color: var(--color-text-secondary);
    }

    section#publications li:hover {
      border-color: var(--color-border);
      background: var(--color-accent-bg);
    }

    .pub-number {
      display: inline-block;
      min-width: 1.75rem;
      font-weight: 600;
      color: var(--color-accent);
    }

    .pub-links {
      display: inline;
    }

    .pub-links a {
      font-size: 0.825rem;
      font-weight: 500;
      padding: 0.15rem 0.45rem;
      border-radius: 4px;
      background: var(--color-accent-bg);
      color: var(--color-accent);
      text-decoration: none;
      transition: background 0.2s, color 0.2s;
    }

    .pub-links a:hover {
      background: var(--color-accent);
      color: #fff;
      text-decoration: none;
    }

    /* ── Presentations ── */
    section#presentations ul {
      list-style: none;
      padding: 0;
    }

    section#presentations li {
      padding: 0.5rem 0;
      border-bottom: 1px solid var(--color-border);
      font-size: 0.925rem;
      color: var(--color-text-secondary);
      line-height: 1.6;
    }

    section#presentations li:last-child {
      border-bottom: none;
    }

    section#presentations h3 {
      font-size: 0.95rem;
      text-transform: uppercase;
      letter-spacing: 0.04em;
      color: var(--color-accent);
      margin-top: 1.25rem;
      margin-bottom: 0.5rem;
      border: none;
    }

    section#presentations h3:first-of-type {
      margin-top: 0.25rem;
    }

    .badge {
      display: inline-block;
      font-size: 0.75rem;
      font-weight: 600;
      padding: 0.1rem 0.5rem;
      border-radius: 4px;
      text-transform: uppercase;
      letter-spacing: 0.03em;
      text-decoration: none;
      transition: background 0.2s, color 0.2s;
      cursor: pointer;
    }

    .badge:hover {
      text-decoration: none;
    }

    .badge-talk {
      background: #dbeafe;
      color: #1e40af;
    }

    .badge-talk:hover {
      background: #1e40af;
      color: #fff;
    }

    .badge-poster {
      background: #e0e7ff;
      color: #3730a3;
    }

    .badge-poster:hover {
      background: #3730a3;
      color: #fff;
    }

    /* ── Teaching ── */
    section#teaching ul {
      list-style: none;
      padding: 0;
    }

    section#teaching li {
      padding: 0.5rem 0;
      border-bottom: 1px solid var(--color-border);
      font-size: 0.925rem;
      color: var(--color-text-secondary);
      line-height: 1.6;
    }

    section#teaching li:last-child {
      border-bottom: none;
    }

    section#teaching h3 {
      font-size: 0.95rem;
      text-transform: uppercase;
      letter-spacing: 0.04em;
      color: var(--color-accent);
      margin-top: 1.25rem;
      margin-bottom: 0.5rem;
    }

    section#teaching h3:first-of-type {
      margin-top: 0.25rem;
    }

    /* ── News ── */
    .news-item {
      display: flex;
      gap: 1.25rem;
      padding: 1.25rem;
      border-radius: 8px;
      background: var(--color-bg);
      border: 1px solid transparent;
      transition: border-color 0.2s, background 0.2s;
      margin-bottom: 0.75rem;
    }

    .news-item:hover {
      border-color: var(--color-border);
      background: var(--color-accent-bg);
    }

    .news-item:last-child {
      margin-bottom: 0;
    }

    .news-date {
      flex-shrink: 0;
      width: 4.5rem;
      text-align: center;
      padding-top: 0.15rem;
    }

    .news-date .month {
      display: block;
      font-size: 0.75rem;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.05em;
      color: var(--color-accent);
    }

    .news-date .year {
      display: block;
      font-size: 0.8rem;
      color: var(--color-text-muted);
    }

    .news-content {
      flex: 1;
    }

    .news-content h3 {
      font-size: 1rem;
      font-weight: 600;
      margin: 0 0 0.35rem 0;
      line-height: 1.4;
    }

    .news-content h3 a {
      color: var(--color-text);
      text-decoration: none;
      transition: color 0.2s;
    }

    .news-content h3 a:hover {
      color: var(--color-accent);
      text-decoration: none;
    }

    .news-content p {
      font-size: 0.9rem;
      color: var(--color-text-secondary);
      margin: 0;
      line-height: 1.6;
    }

    .news-source {
      display: inline-block;
      font-size: 0.775rem;
      font-weight: 500;
      color: var(--color-text-muted);
      margin-top: 0.4rem;
    }

    .news-source a {
      color: var(--color-accent);
      text-decoration: none;
    }

    .news-source a:hover {
      text-decoration: underline;
    }

    @media (max-width: 480px) {
      .news-item {
        flex-direction: column;
        gap: 0.5rem;
      }

      .news-date {
        width: auto;
        text-align: left;
        display: flex;
        gap: 0.35rem;
      }
    }

    /* ── Review ── */
    section#referee ul {
      list-style: none;
      padding: 0;
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 0.75rem;
    }

    section#referee p {
      margin-bottom: 0.5rem;
    }

    section#referee li {
      display: inline-block;
    }

    section#referee li a {
      display: inline-block;
      font-size: 0.85rem;
      font-weight: 500;
      padding: 0.35rem 0.8rem;
      border-radius: 20px;
      border: 1px solid var(--color-border);
      color: var(--color-text-secondary);
      background: var(--color-surface);
      text-decoration: none;
      transition: all 0.2s;
    }

    section#referee li a:hover {
      border-color: var(--color-accent);
      color: var(--color-accent);
      background: var(--color-accent-bg);
      text-decoration: none;
    }

    /* ── Contact ── */
    section#contact {
      text-align: center;
      padding: 2.5rem;
    }

    section#contact h2 {
      display: block;
      text-align: center;
    }

    section#contact a {
      font-weight: 500;
    }

    /* ── Video / Media ── */
    .video-container {
      position: relative;
      width: 100%;
      padding-bottom: 56.25%;
      margin: 1rem 0;
      border-radius: 8px;
      overflow: hidden;
      background: #000;
    }

    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    .responsive-img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      margin: 1rem 0;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
    }

    .img-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.75rem;
      margin: 1rem 0;
    }

    .img-grid img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
      transition: transform 0.2s;
    }

    .img-grid img:hover {
      transform: scale(1.02);
    }

    /* ── Footer ── */
    footer {
      text-align: center;
      padding: 2rem 1.5rem;
      color: var(--color-text-muted);
      font-size: 0.85rem;
      border-top: 1px solid var(--color-border);
      max-width: var(--max-width);
      margin: 0 auto;
    }

    /* ── Responsive ── */
    @media (max-width: 768px) {
      :root {
        --nav-height: auto;
      }

      nav {
        flex-wrap: wrap;
        height: auto;
        padding: 0.5rem 0.75rem;
        gap: 0.1rem;
      }

      nav a {
        font-size: 0.75rem;
        padding: 0.3rem 0.45rem;
      }

      nav .nav-divider {
        display: none;
      }

      .hero {
        padding: 2.5rem 1rem 2rem;
      }

      .hero h1 {
        font-size: 1.75rem;
      }

      .hero-avatar {
        width: 200px;
        height: 200px;
      }

      section {
        padding: 1.5rem 1.25rem;
        border-radius: 8px;
      }

      .content-wrapper {
        padding: 0 1rem 3rem;
      }

      .img-grid {
        grid-template-columns: 1fr;
      }

      h2 {
        font-size: 1.3rem;
      }

      section#referee ul {
        gap: 0.35rem;
      }
    }

    @media (max-width: 480px) {
      nav a {
        font-size: 0.7rem;
        padding: 0.25rem 0.35rem;
      }

      .hero h1 {
        font-size: 1.5rem;
      }

      section {
        padding: 1.25rem 1rem;
      }
    }
    </style>
</head>
<body>

    <nav id="navbar">
        <a href="https://www.linkedin.com/in/mohsensadr/" target="_blank" title="LinkedIn">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn">
        </a>
        <a href="https://github.com/mohsensadr" target="_blank" title="GitHub">
            <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub">
        </a>
        <a href="https://scholar.google.de/citations?user=YWJ0prAAAAAJ&hl=en&oi=ao" target="_blank" title="Google Scholar">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" alt="Google Scholar">
        </a>
        <a href="https://orcid.org/0000-0003-0241-8163" target="_blank" title="ORCID">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID">
        </a>
        <a href="CV.pdf" download title="Download CV">
            <span class="material-icons" style="font-size: 18px;">description</span> CV
        </a>
        <span class="nav-divider"></span>
        <a href="#about">About</a>
        <a href="#news">News</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#awards">Awards</a>
        <a href="#publications">Publications</a>
        <a href="#presentations">Talks</a>
        <a href="#teaching">Teaching</a>
        <a href="#referee">Review</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <img src="profile2_circle2.png" alt="Mohsen Sadr" class="hero-avatar">
        <h1>Mohsen Sadr</h1>
        <p class="subtitle">Applied Mathematician &mdash; Statistical Modeling, Monte Carlo Methods, Optimal Transport &amp; Computational Physics</p>
    </div>

    <div class="content-wrapper">

    <section id="about">
        <h2>About Me</h2>
        <p>I am an applied mathematician working at the intersection of computational physics, statistical modeling, and machine learning. My research spans Monte Carlo methods, density estimation, variance reduction, optimal transport, and particle methods, with applications in rarefied gas dynamics, plasma physics, and generative AI.</p>
        <p>Currently, I am a Founder Fellow at the Paul Scherrer Institute (PSI) and a Research Affiliate at MIT. At PSI (2023&ndash;2025), I worked on optimal transport and collaborated with <strong>Dr. Andreas Adelmann</strong> on scaling <a href="https://github.com/OPALX-project/OPALX">OPALX</a>&mdash;a particle accelerator simulation library&mdash;for exascale HPC platforms. At MIT (2021&ndash;2023), I worked with <strong>Prof. Nicolas Hadjiconstantinou</strong> on general-purpose variance-reduced Monte Carlo methods for kinetic equations. Prior to that, I was a postdoc with <strong>Prof. Laurent Villard</strong> at the Swiss Plasma Center (EPFL), contributing to <a href="https://www.epfl.ch/research/domains/swiss-plasma-center/research/theory/codes/research_theory_codes_orb5/">ORB5</a>, a gyrokinetic particle-in-cell code for confined plasma simulations. I received my PhD in Applied Mathematics from RWTH Aachen University, advised by <strong>Prof. Manuel Torrilhon</strong> and <strong>Prof. Hossein Gorji</strong>, where my <a href="https://doi.org/10.18154/RWTH-2020-07249">dissertation</a> focused on efficient Monte Carlo methods for dense gas, liquid, and phase-transition kinetics.</p>
    </section>

    <section id="news">
        <h2>News</h2>
        <div class="news-item">
            <div class="news-date">
                <span class="month">Feb</span>
                <span class="year">2026</span>
            </div>
            <div class="news-content">
                <h3><a href="https://www.psi.ch/en/news/media-releases/psi-founder-fellowship-for-ai-platform-and-solid-state-batteries" target="_blank">PSI Founder Fellowship for AI Platform and Solid-State Batteries</a></h3>
                <p>Awarded a PSI Founder Fellowship (up to 150,000 CHF) to develop an AI-based platform that accelerates and reduces the cost of physical simulations for fusion energy, aerospace, and semiconductor technologies. The fellowship includes coaching and advisory services from PSI's technology transfer team and external experts.</p>
                <div class="news-source">
                    <a href="https://www.psi.ch/en/news/media-releases/psi-founder-fellowship-for-ai-platform-and-solid-state-batteries" target="_blank">PSI Media Release</a>
                    &nbsp;&middot;&nbsp;
                    <a href="https://www.news.admin.ch/fr/newnsb/HKgkaTivg50VFiCnQbqXn" target="_blank">Swiss Federal Government</a>
                </div>
            </div>
        </div>
        <div class="news-item">
            <div class="news-date">
                <span class="month">Oct</span>
                <span class="year">2025</span>
            </div>
            <div class="news-content">
                <h3><a href="https://openreview.net/forum?id=Az3mJ4d1eT" target="_blank">Paper accepted in Transactions on Machine Learning Research (TMLR)</a></h3>
                <p>Our paper &ldquo;Data-Driven Discovery of PDEs via the Adjoint Method&rdquo; has been accepted in TMLR. We present an adjoint-based method for discovering governing PDEs from data, formulated as a PDE-constrained optimization problem with analytically derived gradients.</p>
                <div class="news-source">
                    <a href="https://openreview.net/forum?id=Az3mJ4d1eT" target="_blank">OpenReview</a>
                    &nbsp;&middot;&nbsp;
                    <a href="https://github.com/mohsensadr/DiscoverPDEAdjoint" target="_blank">Code</a>
                </div>
            </div>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>

        <div class="project">
            <h3>Non-equilibrium Multiphase Flows</h3>
            <p>In this line of research, I designed a stochastic process for modeling short and long-range interactions of monatomic particles that follows the exact kinetic equation up to desired moments with a feasible computational complexity that scales linearly with the number of particles. For details on the developed method, see [<a href="#FPmultiphase">7</a>, <a href="#LongRange">8</a>, <a href="#DFP">9</a>]. These methods have been implemented in a particle-in-cell code called <a href="https://github.com/piclas-framework/piclas">PICLas</a>. As a showcase, here a simulation of Argon's density experiencing the spinodal decomposition is presented.</p>
            <div class="video-container">
                <iframe src="spinodal_4.mp4" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>

        <div class="project">
            <h3>Excitation of Confined Plasma</h3>
            <p>Stabilizing a confined plasma in a fusion device is one of the main challenges in designing such a system. Often, it is worthwhile to study the growth/dissipation rates of modes of the system to better control the plasma. I have worked on excitation of Alfven modes in a confined plasma using a well-established particle-in-cell and gyrokinetic code called ORB5. As a showcase, electrostatic and magnetic potential fields are shown here where the mode of interest is successfully excited using a so-called antenna. For more details, see [<a href="#orb5">15</a>].</p>
            <img src="excitation_alfven_mode_confined_plasma.png" alt="Visualization of excited Alfven modes" class="responsive-img">
        </div>

        <div class="project">
            <h3>Variance Reduction Method</h3>
            <p>One of the main challenges in interpreting the solution of statistical models is noise. I have developed a general-purpose and entropy-based variance reduction method for stochastic processes where the target density is around an equilibrium/control-variate density. In this project, I devised a consistent and least-biased evolution equation for the importance weights of the Boltzmann and Fokker-Planck equation. The following figures show the snapshot estimate of number density, bulk velocity, and temperature for the Sod-Shock tube test case. We also show how the noise varies with respect to the signal for the standard Monte Carlo and the introduced variance reduction method. For details, see [<a href="#VRPIC">4</a>], [<a href="#VRDSMC">5</a>] and [<a href="#VRFP">6</a>].</p>
            <div class="img-grid">
                <img src="n_nv10_shock3.png" alt="Number density for Sod-Shock tube test case">
                <img src="U_nv10_shock3.png" alt="Bulk velocity for Sod-Shock tube test case">
                <img src="T_nv10_shock3.png" alt="Temperature for Sod-Shock tube test case">
                <img src="var_shock.png" alt="Noise variation vs signal for variance reduction">
            </div>
        </div>

        <div class="project">
            <h3>Optimal Transport Problem</h3>
            <p>Finding the optimal map/plan between marginals is one of the most attractive problems in applied mathematics with applications in data-driven modeling and Machine Learning. I am interested in devising new dynamical systems to solve this problem more efficiently than standard methods. This includes collision-based dynamics [<a href="#colOT">1</a>], orthogonal coupling dynamics [<a href="#OCD">2</a>], and moment-based methods [<a href="#WE">3</a>]. As a showcase, here I show the output of a generative model trained using the optimal map between the normal and four other marginals.</p>
            <img src="5marginals.png" alt="Visualization of optimal transport for 5 marginals" class="responsive-img">
        </div>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <ul class="timeline">
            <li>
                <div class="role">Founder Fellow</div>
                <div class="org">Paul Scherrer Institute (ETH-domain) &mdash; Scientific Computing, Theory and Data</div>
                <div class="date">February 2026 &ndash; present</div>
            </li>
            <li>
                <div class="role">Research Affiliate</div>
                <div class="org">Massachusetts Institute of Technology &mdash; Department of Mechanical Engineering</div>
                <div class="date">July 2025 &ndash; present</div>
            </li>
            <li>
                <div class="role">Scientist</div>
                <div class="org">Paul Scherrer Institute (ETH-domain) &mdash; Scientific Computing, Theory and Data</div>
                <div class="date">July 2023 &ndash; June 2025</div>
            </li>
            <li>
                <div class="role">Fellow</div>
                <div class="org">Massachusetts Institute of Technology &mdash; Department of Mechanical Engineering</div>
                <div class="date">December 2021 &ndash; June 2023</div>
            </li>
            <li>
                <div class="role">Scientific Collaborator</div>
                <div class="org">EPFL &mdash; Swiss Plasma Center</div>
                <div class="date">October 2020 &ndash; November 2021</div>
            </li>
        </ul>
    </section>

    <section id="education">
        <h2>Education</h2>
        <ul class="timeline">
            <li>
                <div class="role">PhD in Applied and Computational Mathematics</div>
                <div class="org">RWTH Aachen University, Germany</div>
                <div class="date">2020</div>
            </li>
            <li>
                <div class="role">MSc in Simulation Sciences</div>
                <div class="org">RWTH Aachen University, Germany</div>
                <div class="date">2017</div>
            </li>
            <li>
                <div class="role">BSc in Mechanical Engineering</div>
                <div class="org">KN Toosi University of Technology, Iran</div>
                <div class="date">2013</div>
            </li>
        </ul>
    </section>

    <section id="awards">
        <h2>Awards &amp; Honors</h2>
        <ul>
            <li>100k CHF for Founder Fellowship grant from Paul Scherrer Institute and QBIT Capital in 2026.</li>
            <li>1.2m Euro for a project from EUROfusion and SNSF (consortium of national fusion research institutes) in 2021 (associated).</li>
            <li>100k Euro with national Walter Benjamin scholarship offered by German Research Foundation (DFG) in 2020.</li>
            <li>4k Euro travel grant from German Academic Exchange Service (DAAD) in 2019.</li>
        </ul>
    </section>

    <section id="publications">
        <h2>Publications</h2>

        <div class="pub-category">Optimal Transport</div>
        <ul>
            <li id="colOT">
                <span class="pub-number">1.</span> Mohsen Sadr and M. Hossein Gorji. &ldquo;Collision-based dynamics for multi-marginal optimal transport&rdquo; 2024
                <span class="pub-links">[<a href="https://doi.org/10.48550/arXiv.2412.16385">Preprint</a> | <a href="https://github.com/mohsensadr/collisional_ot">Code</a>]</span>
            </li>
            <li id="OCD">
                <span class="pub-number">2.</span> Mohsen Sadr, Peyman Mohajerin Esfehani, and M. Hossein Gorji. &ldquo;Optimal transportation by orthogonal coupling dynamics&rdquo; 2024
                <span class="pub-links">[<a href="https://doi.org/10.48550/arXiv.2410.08060">Preprint</a> | <a href="https://github.com/mohsensadr/OCD">Code</a>]</span>
            </li>
            <li id="WE">
                <span class="pub-number">3.</span> Mohsen Sadr, Nicolas G. Hadjiconstantinou, and M. Hossein Gorji. &ldquo;Wasserstein-penalized Entropy closure: A use case for stochastic particle methods&rdquo; <em>Journal of Computational Physics</em>, 2024
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.jcp.2024.113066">Elsevier</a> | <a href="https://arxiv.org/abs/2306.04120">Preprint</a> | <a href="https://github.com/mohsensadr/WE">Code</a>]</span>
            </li>
        </ul>

        <div class="pub-category">Variance Reduction</div>
        <ul>
            <li id="VRPIC">
                <span class="pub-number">4.</span> Victor Windhab, Andreas Adelmann, Mohsen Sadr. &ldquo;VR-PIC: An entropic variance-reduction method for particle-in-cell solutions of the Vlasov-Poisson equation&rdquo; 2026
                <span class="pub-links">[<a href="https://doi.org/10.48550/arXiv.2602.15041">Preprint</a> | <a href="https://github.com/mohsensadr/VRPIC">Code</a>]</span>
            </li>
            <li id="VRDSMC">
                <span class="pub-number">5.</span> Mohsen Sadr, and Nicolas G. Hadjiconstantinou. &ldquo;A variance-reduced direct Monte Carlo simulation method for solving the Boltzmann equation over a wide range of rarefaction&rdquo; <em>Journal of Computational Physics</em>, 472, 111677, 2023
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.jcp.2022.111677">Elsevier</a> | <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4148310">Preprint</a>]</span>
            </li>
            <li id="VRFP">
                <span class="pub-number">6.</span> Mohsen Sadr, and Nicolas G. Hadjiconstantinou. &ldquo;Variance reduced particle solution of the Fokker-Planck equation with application to rarefied gas and plasma dynamics&rdquo; <em>Journal of Computational Physics</em>, 492, 112402, 2023
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.jcp.2023.112402">Elsevier</a> | <a href="https://dx.doi.org/10.2139/ssrn.4353547">Preprint</a>]</span>
            </li>
        </ul>

        <div class="pub-category">Modelling in Kinetic Theory</div>
        <ul>
            <li id="FPmultiphase">
                <span class="pub-number">7.</span> Mohsen Sadr, Marcel Pfeiffer, and M. Hossein Gorji. &ldquo;Fokker-Planck-Poisson kinetics: multi-phase flow beyond equilibrium&rdquo; <em>Journal of Fluid Mechanics</em>, 920, A46, 2021
                <span class="pub-links">[<a href="https://doi.org/10.1017/jfm.2021.461">Cambridge University Press</a> | <a href="https://arxiv.org/abs/2308.05580">Preprint</a>]</span>
            </li>
            <li id="LongRange">
                <span class="pub-number">8.</span> Mohsen Sadr, and M. Hossein Gorji. &ldquo;Treatment of long-range interactions arising in the Enskog&ndash;Vlasov description of dense fluids&rdquo; <em>Journal of Computational Physics</em>, 378, 129&ndash;142, 2019
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.jcp.2018.11.005">Elsevier</a> | <a href="https://arxiv.org/abs/2308.05845">Preprint</a> | <a href="https://github.com/mohsensadr/Monte-Carlo-Particle-Method">Code</a>]</span>
            </li>
            <li id="DFP">
                <span class="pub-number">9.</span> Mohsen Sadr, and M. Hossein Gorji. &ldquo;A continuous stochastic model for non-equilibrium dense gases&rdquo; <em>Journal of Physics of Fluids</em>, 29, 122007, 2017
                <span class="pub-links">[<a href="https://doi.org/10.1063/1.5004409">American Institute of Physics</a> | <a href="https://arxiv.org/abs/2308.05117">Preprint</a> | <a href="https://github.com/mohsensadr/Monte-Carlo-Particle-Method">Code</a>]</span>
            </li>
        </ul>

        <div class="pub-category">Data-Driven Modelling</div>
        <ul>
            <li>
                <span class="pub-number">10.</span> Mohsen Sadr, Tony Tohme, and Kamal Youcef-Toumi. &ldquo;Data-driven discovery of PDEs via the adjoint method&rdquo; <em>Transactions on Machine Learning Research</em>, 2025
                <span class="pub-links">[<a href="https://openreview.net/forum?id=Az3mJ4d1eT">OpenReview</a> | <a href="https://github.com/mohsensadr/DiscoverPDEAdjoint">Code</a>]</span>
            </li>
            <li>
                <span class="pub-number">11.</span> Tony Tohme, Mohsen Sadr, Kamal Youcef-Toumi, and Nicolas G. Hadjiconstantinou. &ldquo;MESSY Estimation: Maximum-Entropy based Stochastic and Symbolic densitY Estimation&rdquo; <em>Transactions on Machine Learning Research</em>, 2023
                <span class="pub-links">[<a href="https://openreview.net/forum?id=Y2ru0LuQeS">OpenReview</a> | <a href="https://github.com/mohsensadr/MESSY">Code</a>]</span>
            </li>
            <li>
                <span class="pub-number">12.</span> Mohsen Sadr, Manuel Torrilhon, and M. Hossein Gorji. &ldquo;Gaussian Process Regression for Maximum Entropy Distribution&rdquo; <em>Journal of Computational Physics</em>, 418, 109644, 2020
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.jcp.2020.109644">Elsevier</a> | <a href="https://arxiv.org/abs/2308.06149">Preprint</a>]</span>
            </li>
        </ul>

        <div class="pub-category">Approximating Collision Operator</div>
        <ul>
            <li>
                <span class="pub-number">13.</span> Fabian Mies, Mohsen Sadr, and Manuel Torrilhon. &ldquo;An efficient jump-diffusion approximation of the Boltzmann equation&rdquo; <em>Journal of Computational Physics</em>, 490, 112308, 2023
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.jcp.2023.112308">Elsevier</a> | <a href="https://arxiv.org/abs/2112.08362">Preprint</a>]</span>
            </li>
            <li>
                <span class="pub-number">14.</span> Mohsen Sadr, Qian Wang, and M. Hossein Gorji. &ldquo;Coupling kinetic and continuum using data-driven maximum entropy distribution&rdquo; <em>Journal of Computational Physics</em>, 444, 110542, 2021
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.jcp.2021.110542">Elsevier</a> | <a href="https://arxiv.org/abs/2308.05672">Preprint</a>]</span>
            </li>
        </ul>

        <div class="pub-category">Simulation of Plasma / Fluid</div>
        <ul>
            <li id="orb5">
                <span class="pub-number">15.</span> Mohsen Sadr, Alexey Mishchenko, Thomas Hayward-Schneider, Axel Koenies, Alberto Bottino, Alessandro Biancalani, Peter Donnel, Emmanuel Lanti, and Laurent Villard. &ldquo;Linear and nonlinear excitation of TAE modes by external electromagnetic perturbations using ORB5&rdquo; <em>Plasma Physics and Controlled Fusion</em>, 64, 085010, 2022
                <span class="pub-links">[<a href="https://iopscience.iop.org/article/10.1088/1361-6587/ac73eb">IOP Publishing (open access)</a>]</span>
            </li>
            <li>
                <span class="pub-number">16.</span> P Donnel, J Cazabonne, L Villard, S Brunner, S Coda, J Decker, M Murugappan, and M Sadr. &ldquo;Quasilinear treatment of wave&ndash;particle interactions in the electron cyclotron range and its implementation in a gyrokinetic code&rdquo; <em>Plasma Physics and Controlled Fusion</em>, 63, 064001, 2021
                <span class="pub-links">[<a href="https://iopscience.iop.org/article/10.1088/1361-6587/abf53f">IOP Publishing (open access)</a>]</span>
            </li>
            <li>
                <span class="pub-number">17.</span> Sima Farazi, Mohsen Sadr, Seongwon Kang, Martin Schiemann, Nikita Vorobiev, Viktor Scherer, Heinz Pitsch. &ldquo;Resolved simulations of single char particle combustion in a laminar flow field&rdquo; <em>Fuel</em>, 201, 15&ndash;28, 2017
                <span class="pub-links">[<a href="https://doi.org/10.1016/j.fuel.2016.11.011">Elsevier</a>]</span>
            </li>
        </ul>
    </section>

    <section id="presentations">
        <h2>Presentations</h2>

        <h3>Conferences</h3>
        <ul>
            <li>Particles, Flows &amp; Maps for Sampling Complex Distributions, Lausanne, Switzerland, November 2025 <a href="presentations/EPFL_Poster_2025_Collisional_OT.pdf" target="_blank" class="badge badge-poster">poster</a></li>
            <li>5th Mathematical and Scientific Machine Learning, Naples, Italy, August 2025 <a href="presentations/MSML2025_Naples_poster.pdf" target="_blank" class="badge badge-poster">poster</a></li>
            <li>30th Biennial Numerical Analysis Conference, Glasgow, UK, June 2025 <a href="presentations/30th_Biennial_Numerical_Analysis_Conference_talk.pdf" target="_blank" class="badge badge-talk">talk</a></li>
            <li>4th Mathematical and Scientific Machine Learning, Providence, USA, June 2023 <a href="presentations/MLML2023_ICERM_poster.pdf" target="_blank" class="badge badge-poster">poster</a></li>
            <li>19th European Fusion Theory Conference, virtual, October 2021 <a href="presentations/EFTC_antenna_poster.pdf" target="_blank" class="badge badge-poster">poster</a></li>
            <li>9th International Congress on Industrial and Applied Mathematics, Valencia, Spain, July 2019 <a href="presentations/ICIAM_poster.pdf" target="_blank" class="badge badge-poster">poster</a></li>
            <li>10th International Conference on Multiphase Flow, Rio de Janeiro, Brazil, May 2019 <a href="presentations/MultiphaseFlows_talk.pdf" target="_blank" class="badge badge-talk">talk</a></li>
            <li>3rd European Conference on Non-Equilibrium Gas Flows, Strasbourg, France, February 2018 <a href="presentations/NEGF_2018_talk.pdf" target="_blank" class="badge badge-talk">talk</a></li>
        </ul>

        <h3>Invited Talks</h3>
        <ul>
            <li>Swiss Plasma Center, EPFL, April 2025</li>
            <li>PSI, CSD Scientific Retreat, March 2024</li>
            <li>PSI, Machine Learning Seminar Series, April 2024</li>
            <li>MIT, Symposium of Center for Computational Science &amp; Technology, March 2023</li>
            <li>Swiss Plasma Center, EPFL, April 2020</li>
            <li>EPFL, Mathematics Institute of Computational Science and Engineering (MATHICSE), July 2019</li>
            <li>ETH Zurich, Institute of Fluid Dynamics, May 2018</li>
            <li>ETH Zurich, Institute of Fluid Dynamics, August 2017</li>
        </ul>
    </section>

    <section id="teaching">
        <h2>Teaching</h2>

        <h3>ETH Zurich</h3>
        <ul>
            <li>Introduction to Computational Physics: Monte Carlo methods (2023 and 2024) <a href="teaching_slides/ICP.pdf" target="_blank">[slides]</a></li>
            <li>Computational Statistical Physics: rarefied gas and plasma dynamics (2024) <a href="teaching_slides/CSP.pdf" target="_blank">[slides]</a></li>
        </ul>

        <h3>EPFL</h3>
        <ul>
            <li>Computational Physics 1 and 2: advection-diffusion equation, nonlinear dynamics, chaotic systems (2020 and 2021)</li>
        </ul>

        <h3>RWTH Aachen</h3>
        <ul>
            <li>Mathematical Foundations 1&ndash;5: numerical methods for PDEs, iterative solvers, Fourier transformation, linear algebra (2017 to 2019)</li>
        </ul>
    </section>

    <section id="referee">
        <h2>Review</h2>
        <p>I am an active referee of the following peer-reviewed journals and conferences:</p>
        <ul>
            <li><a href="https://www.sciencedirect.com/journal/journal-of-computational-physics">Journal of Computational Physics</a></li>
            <li><a href="https://pubs.aip.org/aip/pof">Physics of Fluids</a></li>
            <li><a href="https://www.nature.com/srep/">Nature: Scientific Reports</a></li>
            <li><a href="https://www.sciencedirect.com/journal/computer-physics-communications">Computer Physics Communications</a></li>
            <li><a href="https://www.sciencedirect.com/journal/communications-in-nonlinear-science-and-numerical-simulation">Comm. in Nonlinear Science &amp; Numerical Simulation</a></li>
            <li><a href="https://iclr.cc">ICLR</a></li>
            <li><a href="https://www.mdpi.com/journal/applsci">Applied Sciences</a></li>
            <li><a href="https://link.springer.com/journal/11012">Meccanica</a></li>
            <li><a href="https://www.sciencedirect.com/journal/advanced-powder-technology">Advanced Powder Technology</a></li>
            <li><a href="https://www.mdpi.com/journal/photonics">Photonics</a></li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach me at <a href="mailto:mohsen.sadr@icloud.com">mohsen.sadr@icloud.com</a></p>
    </section>

    </div>

    <footer>
        &copy; 2026 Mohsen Sadr. All rights reserved.
    </footer>

    <script>
    (function() {
      var lastScrollY = window.scrollY;
      var nav = document.getElementById('navbar');
      var scrollUpAccum = 0;
      var scrollUpThreshold = 80;
      var mouseThreshold = 50;
      var clickLock = false;

      function showNav() {
        if (!clickLock) {
          nav.style.transform = 'translateY(0)';
          scrollUpAccum = 0;
        }
      }

      function hideNav() {
        nav.style.transform = 'translateY(-100%)';
      }

      window.addEventListener('scroll', function() {
        var y = window.scrollY;
        if (y > 10) {
          nav.classList.add('scrolled');
        } else {
          nav.classList.remove('scrolled');
        }

        if (y === 0) {
          showNav();
          scrollUpAccum = 0;
        } else if (y > lastScrollY) {
          hideNav();
          scrollUpAccum = 0;
        } else {
          scrollUpAccum += lastScrollY - y;
          if (scrollUpAccum >= scrollUpThreshold) showNav();
        }
        lastScrollY = y;
      });

      window.addEventListener('mousemove', function(e) {
        if (e.clientY <= mouseThreshold) showNav();
      });

      nav.addEventListener('click', function(e) {
        if (e.target.tagName === 'A' && e.target.getAttribute('href') &&
            e.target.getAttribute('href').charAt(0) === '#') {
          hideNav();
          clickLock = true;
          setTimeout(function() { clickLock = false; }, 800);
        }
      });
    })();
    </script>

    <script>
    window.addEventListener('load', function() {
      if (window.location.hash) window.location.hash = '';
    });
    </script>

</body>
</html>
