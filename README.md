<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Richard Ng | Senior Internal Audit Leader</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&display=swap" rel="stylesheet">
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: { 950: '#050a12', 900: '#0a1424', 800: '#11223c' },
                        gold: { 400: '#dfc095', 500: '#cda873', 600: '#b89565' }
                    },
                    fontFamily: { sans: ['Inter', 'sans-serif'], serif: ['Playfair Display', 'serif'] }
                }
            }
        }
    </script>

    <style>
        .fade-up-element {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.8s cubic-bezier(0.16, 1, 0.3, 1), transform 0.8s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .fade-up-element.is-visible { opacity: 1; transform: translateY(0); }
        .hero-bg {
            background-image: linear-gradient(rgba(5, 10, 18, 0.7), rgba(5, 10, 18, 0.85)), url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop');
            background-size: cover; background-position: center;
        }
        .expertise-card { transition: all 0.4s cubic-bezier(0.16, 1, 0.3, 1); }
        .expertise-card:hover {
            transform: translateY(-10px);
            border-top-color: #cda873 !important;
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0a1424; }
        ::-webkit-scrollbar-thumb { background: #cda873; }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white antialiased">

    <nav class="absolute top-0 left-0 w-full z-50 py-8">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="flex justify-between items-center">
                <a href="#" class="font-serif text-2xl font-bold tracking-wider text-white uppercase">
                    RICHARD <span class="text-gold-500">NG</span>.
                </a>
                <div class="hidden md:flex space-x-10 items-center">
                    <a href="#about" class="text-xs font-bold text-white hover:text-gold-500 transition-colors uppercase tracking-[0.2em]">About</a>
                    <a href="#expertise" class="text-xs font-bold text-white hover:text-gold-500 transition-colors uppercase tracking-[0.2em]">Expertise</a>
                    <a href="#experience" class="text-xs font-bold text-white hover:text-gold-500 transition-colors uppercase tracking-[0.2em]">Experience</a>
                    <a href="https://audit-blog.richardng.com" class="text-xs font-bold text-gold-500 hover:text-white transition-colors uppercase tracking-[0.2em]">Internal Audit Blog</a>
                </div>
            </div>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center relative">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 w-full z-10">
            <div class="fade-up-element max-w-4xl pt-20">
                <p class="text-gold-500 font-bold tracking-[0.4em] uppercase mb-6 flex items-center">
                    <span class="w-12 h-[2px] bg-gold-500 mr-4"></span> Senior Internal Audit Leader
                </p>
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif text-white font-bold leading-tight mb-8 uppercase tracking-tighter">
                    Integrity <br/>Through <br/>
                    <span class="text-gold-500 italic font-normal">Analytical Rigor.</span>
                </h1>
                <p class="text-gray-300 text-lg max-w-3xl mb-12 leading-relaxed">
                    A well-rounded Internal Audit professional with extensive experience across financial, operational, taxation, ITGC, and compliance audits. Bringing a strong analytical and structured approach to complex business challenges, supported by an academic foundation in Civil Engineering from the UK.
                </p>
                <div class="flex flex-col sm:flex-row gap-6">
                    <a href="#experience" class="px-10 py-5 bg-gold-500 text-white text-xs font-bold uppercase tracking-widest hover:bg-gold-600 transition-all text-center shadow-lg">Professional Journey</a>
                    <a href="mailto:leukng@gmail.com" class="px-10 py-5 bg-transparent border border-white text-white text-xs font-bold uppercase tracking-widest hover:bg-white hover:text-navy-900 transition-all text-center">Contact Richard</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
                <div class="fade-up-element">
                    <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-8 uppercase leading-tight">
                        Evolving <span class="text-gold-500 italic">Governance</span> for Efficiency
                    </h2>
                    <div class="space-y-6 text-lg text-gray-600 leading-relaxed">
                        <p>Recognized as a fast and adaptable learner, with the ability to navigate evolving business environments and strengthen corporate governance frameworks.</p>
                        <p>Proven capability to support regulatory compliance while identifying opportunities to enhance operational efficiency and risk management across diverse industries.</p>
                    </div>
                    <div class="mt-12 flex flex-wrap gap-10">
                        <div>
                            <p class="text-navy-900 font-serif font-bold text-2xl uppercase">CPA (Canada)</p>
                            <p class="text-gold-500 text-[10px] font-bold uppercase tracking-widest mt-1">Professional Accreditation</p>
                        </div>
                        <div>
                            <p class="text-navy-900 font-serif font-bold text-2xl uppercase">CPA (Australia)</p>
                            <p class="text-gold-500 text-[10px] font-bold uppercase tracking-widest mt-1">Professional Accreditation</p>
                        </div>
                    </div>
                </div>
                <div class="fade-up-element relative">
                    <div class="aspect-[4/5] bg-gray-100 overflow-hidden rounded-sm shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?q=80&w=2071&auto=format&fit=crop" class="w-full h-full object-cover grayscale" alt="Richard Ng Profile">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-navy-950 text-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center gap-16">
                <div class="flex-1 fade-up-element">
                    <div class="inline-block px-4 py-1 border border-gold-500 text-gold-500 text-[10px] font-bold uppercase tracking-widest mb-6">Innovation & Automation</div>
                    <h2 class="text-4xl font-serif font-bold mb-6 uppercase tracking-tight">AI-Driven Audit Strategy</h2>
                    <p class="text-gray-400 text-lg leading-relaxed mb-8">
                        Certified in <strong>Google Prompting Essentials</strong>, I leverage Large Language Models to automate data extraction, enhance risk modeling, and streamline audit reporting. This intersection of technical auditing and AI proficiency allows for higher frequency oversight with greater precision.
                    </p>
                </div>
                <div class="flex-1 fade-up-element">
                    <div class="p-8 border border-white/10 rounded-sm bg-white/5 backdrop-blur-sm">
                        <h4 class="text-gold-500 font-bold uppercase tracking-widest text-xs mb-4 text-center">Certified Capabilities</h4>
                        <div class="space-y-4">
                            <div class="flex items-center gap-4">
                                <span class="text-gold-500">✓</span>
                                <p class="text-sm">Advanced Prompt Engineering for Audit</p>
                            </div>
                            <div class="flex items-center gap-4">
                                <span class="text-gold-500">✓</span>
                                <p class="text-sm">AI-Powered Data Visualization</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="expertise" class="py-32 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl font-serif text-navy-900 font-bold mb-4 uppercase tracking-tighter">Core Expertise</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">💻</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">ITGC & Tech</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">NIST-aligned audits, COBIT framework, and comprehensive IT control testing.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">🏗️</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Structural Logic</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Applying engineering-based analytical frameworks to complex business challenges.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">💰</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Tax & Compliance</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Strategic tax reviews, financial reporting standards, and regulatory oversight.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">⚖️</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Forensics</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Fraud investigation, bid rigging detection, and operational risk management.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl font-serif text-navy-900 font-bold mb-4 uppercase tracking-tighter">Professional Experience</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto"></div>
            </div>
            
            <div class="space-y-16">
                <div class="flex flex-col md:flex-row gap-8 fade-up-element border-b border-gray-100 pb-12">
                    <div class="md:w-1/3">
                        <p class="text-gold-500 font-bold tracking-widest text-xs uppercase">2023 - 2024</p>
                        <h3 class="text-2xl font-serif font-bold text-navy-900 mt-2 uppercase">Sa Sa International Holdings Ltd.</h3>
                        <p class="text-gray-500 text-sm font-bold uppercase tracking-widest">Senior Internal Audit Manager</p>
                    </div>
                    <div class="md:w-2/3">
                        <p class="text-gray-600 leading-relaxed">Directed audit functions across Hong Kong, PRC, Macau, and Malaysia. Modernized retail protocols and inventory controls for multi-regional operations, enhancing operational transparency.</p>
                    </div>
                </div>

                <div class="flex flex-col md:flex-row gap-8 fade-up-element border-b border-gray-100 pb-12">
                    <div class="md:w-1/3">
                        <p class="text-gold-500 font-bold tracking-widest text-xs uppercase">2021 - 2023</p>
                        <h3 class="text-2xl font-serif font-bold text-navy-900 mt-2 uppercase">Lee Kum Kee Group</h3>
                        <p class="text-gray-500 text-sm font-bold uppercase tracking-widest">Internal Audit Manager</p>
                    </div>
                    <div class="md:w-2/3">
                        <p class="text-gray-600 leading-relaxed">Leveraged engineering background to revamp group-wide procurement and manufacturing quality assurance policies through comprehensive cross-functional risk assessment.</p>
                    </div>
                </div>

                <div class="flex flex-col md:flex-row gap-8 fade-up-element">
                    <div class="md:w-1/3">
                        <p class="text-gold-500 font-bold tracking-widest text-xs uppercase">2007 - 2012</p>
                        <h3 class="text-2xl font-serif font-bold text-navy-900 mt-2 uppercase text-gold-600">External Audit Foundations</h3>
                        <p class="text-gray-500 text-sm font-bold uppercase tracking-widest">Auditor / Senior Auditor | BDO & KPMG</p>
                    </div>
                    <div class="md:w-2/3">
                        <p class="text-gray-600 leading-relaxed font-medium">Rigorous training in financial reporting standards, IPO readiness, and internal control testing (US SOX) for multinational clients across diverse industry sectors.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-32 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl font-serif text-navy-900 font-bold mb-4 uppercase tracking-tighter">Strategic Project Highlights</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12">
                <div class="fade-up-element">
                    <div class="text-gold-500 font-bold mb-2">01.</div>
                    <h4 class="text-lg font-serif font-bold text-navy-900 mb-3 uppercase">Supply Chain Resilience</h4>
                    <p class="text-sm text-gray-600 leading-relaxed">Conducted factory-to-retail audits across APACPRODUCTION hubs, identifying critical bottlenecks and strengthening vendor compliance protocols.</p>
                </div>
                <div class="fade-up-element">
                    <div class="text-gold-500 font-bold mb-2">02.</div>
                    <h4 class="text-lg font-serif font-bold text-navy-900 mb-3 uppercase">ITGC Implementation</h4>
                    <p class="text-sm text-gray-600 leading-relaxed">Led the rollout of COBIT-aligned IT General Controls for ERP transitions, ensuring data integrity during major system migrations.</p>
                </div>
                <div class="fade-up-element">
                    <div class="text-gold-500 font-bold mb-2">03.</div>
                    <h4 class="text-lg font-serif font-bold text-navy-900 mb-3 uppercase">Bid Rigging Detection</h4>
                    <p class="text-sm text-gray-600 leading-relaxed">Developed forensic analytical tools to identify pattern-based fraud in high-value procurement contracts for manufacturing entities.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white pt-32 pb-12 border-t border-white/5">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20">
                <h2 class="text-5xl md:text-7xl font-serif font-bold uppercase mb-12 tracking-tighter">Secure Your <br><span class="text-gold-500 italic">Financial Integrity.</span></h2>
                <a href="mailto:leukng@gmail.com" class="px-12 py-5 bg-gold-500 text-white text-xs font-bold uppercase tracking-[0.3em] hover:bg-gold-600 transition-all shadow-xl inline-block">le
