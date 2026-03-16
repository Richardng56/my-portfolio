<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Richard Ng | Senior Internal Audit Leader</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Playfair+Display:ital,wght@0,700;1,400&display=swap" rel="stylesheet">
    
    <style>
        /* --- ALL STYLING INCLUDED HERE TO PREVENT COLLAPSE --- */
        :root {
            --navy: #050a12;
            --gold: #cda873;
            --gold-hover: #b89565;
            --white: #ffffff;
            --gray-bg: #f8f9fa;
            --text-main: #333333;
            --text-muted: #666666;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; color: var(--text-main); line-height: 1.6; background: var(--white); }

        /* Navigation */
        nav { position: absolute; width: 100%; padding: 30px 5%; display: flex; justify-content: space-between; align-items: center; z-index: 100; }
        .logo { font-family: 'Playfair Display', serif; color: var(--white); font-size: 1.5rem; text-decoration: none; font-weight: bold; letter-spacing: 2px; text-transform: uppercase; }
        .logo span { color: var(--gold); }
        .nav-links a { color: var(--white); text-decoration: none; margin-left: 30px; font-size: 0.75rem; font-weight: bold; text-transform: uppercase; letter-spacing: 2px; transition: 0.3s; }
        .nav-links a:hover { color: var(--gold); }

        /* Hero */
        .hero { 
            height: 100vh; 
            background: linear-gradient(rgba(5, 10, 18, 0.75), rgba(5, 10, 18, 0.85)), url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop');
            background-size: cover; background-position: center;
            display: flex; align-items: center; padding: 0 10%; color: var(--white);
        }
        .hero-content { max-width: 850px; }
        .tagline { color: var(--gold); text-transform: uppercase; font-weight: bold; letter-spacing: 4px; margin-bottom: 20px; display: flex; align-items: center; font-size: 0.85rem; }
        .tagline::before { content: ""; width: 40px; height: 2px; background: var(--gold); margin-right: 15px; }
        .hero h1 { font-family: 'Playfair Display', serif; font-size: clamp(2.5rem, 8vw, 5rem); line-height: 1.1; margin-bottom: 30px; text-transform: uppercase; }
        .hero h1 span { color: var(--gold); font-style: italic; font-weight: 400; }
        .hero p { font-size: 1.15rem; color: #cccccc; margin-bottom: 40px; max-width: 650px; }

        /* Buttons */
        .btn-group { display: flex; gap: 20px; flex-wrap: wrap; }
        .btn { padding: 18px 35px; text-decoration: none; font-weight: bold; text-transform: uppercase; font-size: 0.75rem; letter-spacing: 2px; transition: 0.3s; display: inline-block; border: 1px solid var(--gold); }
        .btn-gold { background: var(--gold); color: var(--white); border: none; }
        .btn-outline { color: var(--white); border-color: var(--white); }
        .btn:hover { transform: translateY(-3px); box-shadow: 0 10px 20px rgba(0,0,0,0.2); }
        .btn-gold:hover { background: var(--gold-hover); }

        /* Sections */
        section { padding: 120px 10%; }
        .section-header { text-align: center; margin-bottom: 80px; }
        .section-header h2 { font-family: 'Playfair Display', serif; font-size: 2.5rem; text-transform: uppercase; color: var(--navy); margin-bottom: 15px; }
        .title-line { width: 60px; height: 4px; background: var(--gold); margin: 0 auto; }

        /* Professional Experience (Grid based on your photos) */
        .experience-item { display: grid; grid-template-columns: 1fr 2fr; gap: 40px; padding: 40px 0; border-bottom: 1px solid #eeeeee; }
        .experience-item:last-child { border-bottom: none; }
        .exp-meta { color: var(--gold); font-weight: bold; font-size: 0.85rem; letter-spacing: 2px; }
        .exp-info h3 { font-family: 'Playfair Display', serif; font-size: 1.6rem; color: var(--navy); margin-bottom: 5px; }
        .exp-role { text-transform: uppercase; font-size: 0.75rem; font-weight: bold; color: var(--text-muted); letter-spacing: 1.5px; margin-bottom: 15px; }
        .exp-desc { color: var(--text-muted); font-size: 1rem; }

        /* Project Highlights (3-Column) */
        .highlights-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 40px; }
        .project-card { border-top: 4px solid var(--gold); padding-top: 25px; background: #ffffff; padding: 30px; border-radius: 2px; box-shadow: 0 5px 15px rgba(0,0,0,0.02); }
        .project-num { color: var(--gold); font-weight: bold; font-size: 1.1rem; margin-bottom: 10px; display: block; }
        .project-card h4 { font-family: 'Playfair Display', serif; font-size: 1.3rem; margin-bottom: 15px; text-transform: uppercase; color: var(--navy); }
        .project-card p { font-size: 0.95rem; color: var(--text-muted); }

        /* Footer */
        footer { background: var(--navy); color: var(--white); padding: 120px 10% 40px; }
        .footer-cta { text-align: center; margin-bottom: 100px; }
        .footer-cta h2 { font-family: 'Playfair Display', serif; font-size: clamp(2rem, 5vw, 4rem); margin-bottom: 40px; text-transform: uppercase; }
        .footer-cta h2 span { color: var(--gold); font-style: italic; }

        .location-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 60px; border-top: 1px solid rgba(255,255,255,0.1); padding-top: 60px; margin-bottom: 60px; }
        .loc-item h4 { color: var(--gold); text-transform: uppercase; font-size: 0.75rem; letter-spacing: 2px; margin-bottom: 15px; }
        .loc-item p { font-size: 1.8rem; font-family: 'Playfair Display', serif; font-weight: bold; }
        .loc-sub { font-size: 0.75rem; color: #888888; text-transform: uppercase; margin-top: 8px; font-weight: bold; letter-spacing: 1px; }

        .bottom-bar { display: flex; justify-content: space-between; align-items: center; font-size: 0.7rem; color: #555555; text-transform: uppercase; letter-spacing: 1.5px; border-top: 1px solid rgba(255,255,255,0.05); padding-top: 40px; flex-wrap: wrap; gap: 20px; }
        .bottom-bar a { color: var(--gold); text-decoration: none; border-bottom: 1px solid transparent; }
        .bottom-bar a:hover { border-bottom: 1px solid var(--gold); }

        /* Responsive Fixes */
        @media (max-width: 900px) {
            .experience-item, .location-grid { grid-template-columns: 1fr; gap: 20px; }
            .location-grid div { text-align: left !important; }
            nav .nav-links { display: none; }
        }
    </style>
</head>
<body>

    <nav>
        <a href="#" class="logo">RICHARD <span>NG</span>.</a>
        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#projects">Highlights</a>
            <a href="https://audit-blog.richardng.com">Audit Blog</a>
        </div>
    </nav>

    <section class="hero">
        <div class="hero-content">
            <div class="tagline">Senior Internal Audit Leader</div>
            <h1>Integrity Through <br><span>Analytical Rigor.</span></h1>
            <p>A well-rounded Internal Audit professional with extensive experience across financial, operational, taxation, and ITGC audits. Supported by an academic foundation in Civil Engineering from the UK.</p>
            <div class="btn-group">
                <a href="#experience" class="btn btn-gold">Professional Journey</a>
                <a href="mailto:leukng@gmail.com" class="btn btn-outline">Contact Richard</a>
            </div>
        </div>
    </section>

    <section id="experience">
        <div class="section-header">
            <h2>Professional Experience</h2>
            <div class="title-line"></div>
        </div>
        
        <div class="experience-item">
            <div class="exp-meta">2023 — 2024</div>
            <div class="exp-info">
                <h3>Sa Sa International Holdings Ltd.</h3>
                <div class="exp-role">Senior Internal Audit Manager</div>
                <p class="exp-desc">Directed audit functions across Hong Kong, PRC, Macau, and Malaysia. Modernized retail protocols and inventory controls for multi-regional operations, enhancing operational transparency.</p>
            </div>
        </div>

        <div class="experience-item">
            <div class="exp-meta">2021 — 2023</div>
            <div class="exp-info">
                <h3>Lee Kum Kee Group</h3>
                <div class="exp-role">Internal Audit Manager</div>
                <p class="exp-desc">Leveraged engineering background to revamp group-wide procurement and manufacturing quality assurance policies through comprehensive cross-functional risk assessment.</p>
            </div>
        </div>

        <div class="experience-item">
            <div class="exp-meta">2007 — 2012</div>
            <div class="exp-info">
                <h3>External Audit Foundations</h3>
                <div class="exp-role">Auditor / Senior Auditor | BDO & KPMG</div>
                <p class="exp-desc">Rigorous training in financial reporting standards, IPO readiness, and internal control testing (US SOX) for multinational clients across diverse industry sectors.</p>
            </div>
        </div>
    </section>

    <section id="projects" style="background-color: var(--gray-bg);">
        <div class="section-header">
            <h2>Strategic Project Highlights</h2>
            <div class="title-line"></div>
        </div>

        <div class="highlights-grid">
            <div class="project-card">
                <span class="project-num">01.</span>
                <h4>Supply Chain Resilience</h4>
                <p>Conducted factory-to-retail audits across APAC production hubs, identifying critical bottlenecks and strengthening vendor compliance protocols.</p>
            </div>
            <div class="project-card">
                <span class="project-num">02.</span>
                <h4>ITGC Implementation</h4>
                <p>Led the rollout of COBIT-aligned IT General Controls for ERP transitions, ensuring data integrity during major system migrations.</p>
            </div>
            <div class="project-card">
                <span class="project-num">03.</span>
                <h4>Bid Rigging Detection</h4>
                <p>Developed forensic analytical tools to identify pattern-based fraud in high-value procurement contracts for manufacturing entities.</p>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-cta">
            <h2>Secure Your <br><span>Financial Integrity.</span></h2>
            <a href="mailto:leukng@gmail.com" class="btn btn-gold">leukng@gmail.com</a>
        </div>

        <div class="location-grid">
            <div class="loc-item">
                <h4>Current Hub</h4>
                <p>Vancouver, Canada</p>
                <div class="loc-sub">CPA (Canada) Member</div>
            </div>
            <div class="loc-item" style="text-align: right;">
                <h4>Operational Base</h4>
                <p>Hong Kong SAR</p>
                <div class="loc-sub">Audit Specialist (APAC Region)</div>
            </div>
        </div>

        <div class="bottom-bar">
            <p>&copy; 2026 Richard Ng.</p>
            <div>
                CPA (Canada) | CPA (Australia) | CISA | BEng (Hons) &nbsp;&nbsp; | &nbsp;&nbsp; 
                <a href="https://audit-blog.richardng.com">Internal Audit Blog</a>
            </div>
        </div>
    </footer>

</body>
</html>
