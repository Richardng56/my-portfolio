<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Richard Leuk Ng | Senior Internal Audit Leader</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&display=swap" rel="stylesheet">
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            950: '#050a12',
                            900: '#0a1424',
                            800: '#11223c',
                        },
                        gold: {
                            400: '#dfc095',
                            500: '#cda873',
                            600: '#b89565',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                    }
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
        .fade-up-element.is-visible {
            opacity: 1;
            transform: translateY(0);
        }
        .hero-bg {
            background-image: linear-gradient(rgba(5, 10, 18, 0.85), rgba(5, 10, 18, 0.95)), url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }
        .expertise-card {
            transition: all 0.4s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .expertise-card:hover {
            transform: translateY(-10px);
            border-top-color: #cda873 !important;
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }
        .stat-card {
            background: linear-gradient(145deg, #11223c, #0a1424);
        }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0a1424; }
        ::-webkit-scrollbar-thumb { background: #cda873; }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white antialiased">

    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 bg-transparent py-4">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="flex justify-between items-center">
                <a href="#" class="font-serif text-2xl font-bold tracking-wider text-white uppercase">
                    RICHARD <span class="text-gold-500">NG</span>.
                </a>
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#about" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">About</a>
                    <a href="#expertise" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">Expertise</a>
                    <a href="#experience" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">Experience</a>
                    <a href="#methodology" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">Methodology</a>
                    <a href="#contact" class="px-5 py-2 border border-gold-500 text-gold-500 hover:bg-gold-500 hover:text-white transition-colors text-xs font-bold uppercase tracking-widest">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center relative">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 w-full z-10">
            <div class="fade-up-element max-w-4xl">
                <p class="text-gold-500 font-bold tracking-[0.4em] uppercase mb-6 flex items-center">
                    <span class="w-12 h-[2px] bg-gold-500 mr-4"></span> Senior Internal Audit Leader
                </p>
                <h1 class="text-6xl md:text-8xl font-serif text-white font-bold leading-[1.1] mb-8 uppercase tracking-tighter">
                    Integrity <br/>Through <br/>
                    <span class="text-gold-500 italic font-normal">Analytical Rigor.</span>
                </h1>
                <p class="text-gray-400 text-xl max-w-2xl mb-12 leading-relaxed">
                    Protecting enterprise value through forensic precision, technical excellence in ITGC, and a structural approach to global governance.
                </p>
                <div class="flex flex-col sm:flex-row gap-6">
                    <a href="#expertise" class="px-10 py-5 bg-gold-500 text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-gold-600 transition-all text-center">Strategic Overview</a>
                    <a href="#contact" class="px-10 py-5 bg-transparent border border-white text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-white hover:text-navy-900 transition-all text-center">Get In Touch</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
                <div class="fade-up-element">
                    <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-8 uppercase leading-tight">
                        Bridging <span class="text-gold-500 italic">Engineering Logic</span> with Financial Oversight
                    </h2>
                    <div class="space-y-6 text-lg text-gray-600 leading-relaxed">
                        <p>
                            With a foundation in <strong>Civil Engineering</strong> from the UK, I approach Internal Audit not just as a compliance check, but as a structural challenge. My methodology is built on the belief that a corporation’s governance is only as strong as its weakest process link.
                        </p>
                        <p>
                            Over 17 years of experience—spanning from <strong>Big 4 public practice (KPMG/BDO)</strong> to leading internal audit functions for multi-billion dollar listed entities—has equipped me with the foresight to detect risks before they manifest as financial liabilities.
                        </p>
                    </div>
                    
                    <div class="grid grid-cols-2 gap-8 mt-12">
                        <div>
                            <p class="text-4xl font-serif font-bold text-navy-900">17+</p>
                            <p class="text-gold-500 text-xs font-bold uppercase tracking-widest mt-2">Years Experience</p>
                        </div>
                        <div>
                            <p class="text-4xl font-serif font-bold text-navy-900">200+</p>
                            <p class="text-gold-500 text-xs font-bold uppercase tracking-widest mt-2">Retail Hubs Audited</p>
                        </div>
                    </div>
                </div>
                <div class="relative fade-up-element">
                    <div class="aspect-[4/5] bg-gray-100 overflow-hidden rounded-sm">
                        <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?q=80&w=2071&auto=format&fit=crop" class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" alt="Professional Portfolio">
                    </div>
                    <div class="absolute -bottom-10 -left-10 bg-navy-900 p-10 hidden md:block">
                        <p class="text-white font-serif text-xl italic font-light leading-relaxed">
                            "Governance is the <br>silent engine of <br>sustainable growth."
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-32 bg-navy-900 text-white overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-24 fade-up-element">
                <h2 class="text-gold-500 text-xs font-bold tracking-[0.4em] uppercase mb-4 text-center">Strategic Pillars</h2>
                <h3 class="text-4xl md:text-6xl font-serif font-bold uppercase tracking-tighter">Leadership Philosophy</h3>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-0 border border-white/10">
                <div class="p-16 border-r border-white/10 hover:bg-navy-800 transition-colors fade-up-element">
                    <span class="text-gold-500 font-serif text-5xl mb-8 block italic">01.</span>
                    <h4 class="text-2xl font-serif font-bold mb-6 uppercase tracking-wide">Data-Centric <br>Objectivity</h4>
                    <p class="text-gray-400 leading-relaxed">Moving beyond sampling. Utilizing automated workflows to analyze 100% of data sets for anomaly detection.</p>
                </div>
                <div class="p-16 border-r border-white/10 hover:bg-navy-800 transition-colors fade-up-element">
                    <span class="text-gold-500 font-serif text-5xl mb-8 block italic">02.</span>
                    <h4 class="text-2xl font-serif font-bold mb-6 uppercase tracking-wide">Cultural <br>Integrity</h4>
                    <p class="text-gray-400 leading-relaxed">Establishing the "Tone at the Top" by embedding ethics into the operational DNA of every regional office.</p>
                </div>
                <div class="p-16 hover:bg-navy-800 transition-colors fade-up-element">
                    <span class="text-gold-500 font-serif text-5xl mb-8 block italic">03.</span>
                    <h4 class="text-2xl font-serif font-bold mb-6 uppercase tracking-wide">Adaptive <br>Resilience</h4>
                    <p class="text-gray-400 leading-relaxed">Designing controls that don't just block risk, but allow the business to pivot safely in volatile markets.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="expertise" class="py-32 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-4 uppercase tracking-tighter">Core Expertise</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">💻</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">ITGC & Cyber</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">NIST-aligned security audits, COBIT framework implementation, and IT general control testing.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">📦</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Supply Chain</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">End-to-end operational reviews from factory SAM costs to global distribution logistics.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">💰</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Tax & Finance</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Cross-border compliance, IPO readiness, and strategic tax equalization reviews.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">🔎</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Forensics</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">High-stakes fraud investigation, anti-money laundering (AML), and kickback detection.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="methodology" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
                <div class="order-2 lg:order-1 fade-up-element">
                    <img src="https://images.unsplash.com/photo-1454165833767-027ffea9e772?q=80&w=2070&auto=format&fit=crop" class="rounded-sm shadow-2xl" alt="Methodology">
                </div>
                <div class="order-1 lg:order-2 fade-up-element">
                    <h2 class="text-4xl font-serif font-bold text-navy-900 mb-8 uppercase">The Audit <span class="text-gold-500 italic">Lifecycle</span></h2>
                    <div class="space-y-12">
                        <div class="flex">
                            <div class="mr-6 flex flex-col items-center">
                                <div class="w-10 h-10 rounded-full border-2 border-gold-500 flex items-center justify-center text-gold-500 font-bold">1</div>
                                <div class="w-[2px] h-full bg-gray-100 mt-2"></div>
                            </div>
                            <div>
                                <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-2 tracking-wide">Discovery & Risk Mapping</h4>
                                <p class="text-gray-600">Deep-dive into process documentation to identify inherent risks and control gaps before field-work begins.</p>
                            </div>
                        </div>
                        <div class="flex">
                            <div class="mr-6 flex flex-col items-center">
                                <div class="w-10 h-10 rounded-full border-2 border-gold-500 flex items-center justify-center text-gold-500 font-bold">2</div>
                                <div class="w-[2px] h-full bg-gray-100 mt-2"></div>
                            </div>
                            <div>
                                <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-2 tracking-wide">Execution & Forensic Testing</h4>
                                <p class="text-gray-600">Rigorous walkthroughs and substantive testing using automated data analytics to ensure accuracy.</p>
                            </div>
                        </div>
                        <div class="flex">
                            <div class="mr-6 flex flex-col items-center">
                                <div class="w-10 h-10 rounded-full border-2 border-gold-500 flex items-center justify-center text-gold-500 font-bold">3</div>
                            </div>
                            <div>
                                <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-2 tracking-wide">Strategic Reporting</h4>
                                <p class="text-gold-500 font-bold text-sm uppercase mb-2">Value-Add Focus</p>
                                <p class="text-gray-600">Presenting findings to the Audit Committee with actionable remediation plans that enhance operational flow.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-32 bg-navy-950 text-white">
        <div class="max-w-5xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-24 fade-up-element">
                <h2 class="text-4xl md:text-5xl font-serif font-bold uppercase tracking-tight">Professional Journey</h2>
                <div class="w-20 h-1 bg-gold-500 mx-auto mt-6"></div>
            </div>
            
            <div class="space-y-16 border-l border-gold-500/20 pl-10 relative">
                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-3 h-3 bg-gold-500 rounded-full shadow-[0_0_15px_#cda873]"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2023 - 2024</p>
                    <h3 class="text-3xl font-serif font-bold mb-1">Senior Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-6 italic tracking-wide">Sa Sa International Holdings Ltd.</p>
                    <p class="text-gray-400 max-w-3xl leading-relaxed">Directed the internal audit function for the Group's operations across HK, PRC, Macau, and Malaysia. Modernized retail audit protocols for 200+ outlets and led the transition to digital-first control environments.</p>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-3 h-3 bg-white/20 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">AUG 2021 - JAN 2023</p>
                    <h3 class="text-3xl font-serif font-bold mb-1">Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-6 italic tracking-wide">Lee Kum Kee Group</p>
                    <p class="text-gray-400 max-w-3xl leading-relaxed">Reported 30+ findings covering procurement, sales, and QA. Revamped in-house engineering policy leveraging civil engineering background to enhance group-wide safety and operational compliance.</p>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-3 h-3 bg-white/20 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2012 - 2021</p>
                    <h3 class="text-3xl font-serif font-bold mb-1">Senior Internal Audit Officer</h3>
                    <p class="text-gold-500 text-sm mb-6 italic tracking-wide">Crystal International Group Ltd.</p>
                    <p class="text-gray-400 max-w-3xl leading-relaxed">Specialized in manufacturing audits and supply chain integrity. Conducted intensive reviews of factory efficiency (SAM) and inventory utilization across multiple international production hubs.</p>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-3 h-3 bg-white/10 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2007 - 2012</p>
                    <h3 class="text-3xl font-serif font-bold mb-1">External Audit (BDO & KPMG)</h3>
                    <p class="text-gold-500 text-sm mb-6 italic tracking-wide">Senior Auditor</p>
                    <p class="text-gray-400 max-w-3xl leading-relaxed">Foundation in US SOX compliance, IPO readiness, and financial statement audits for multinational clients in manufacturing and retail sectors.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-white border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12 text-center">
                <div class="fade-up-element">
                    <div class="text-navy-900 font-serif font-bold text-xl uppercase mb-2">CPA (CA/AU)</div>
                    <p class="text-gray-500 text-xs font-bold uppercase tracking-widest">CPA Ontario, Canada</p>
                </div>
                <div class="fade-up-element">
                    <div class="text-navy-900 font-serif font-bold text-xl uppercase mb-2">CPA (HK)</div>
                    <p class="text-gray-500 text-xs font-bold uppercase tracking-widest">HKICPA, Hong Kong</p>
                </div>
                <div class="fade-up-element">
                    <div class="text-navy-900 font-serif font-bold text-xl uppercase mb-2">CISA</div>
                    <p class="text-gray-500 text-xs font-bold uppercase tracking-widest">ISACA (Exam Passed)</p>
                </div>
                <div class="fade-up-element">
                    <div class="text-navy-900 font-serif font-bold text-xl uppercase mb-2">BEng (Hons)</div>
                    <p class="text-gray-500 text-xs font-bold uppercase tracking-widest">Civil Engineering, UK</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white pt-32 pb-12">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-16 mb-24">
                <div class="md:col-span-6">
                    <h2 class="text-4xl md:text-6xl font-serif font-bold uppercase mb-12 tracking-tighter">Let's Secure <br><span class="text-gold-500 italic">The Future.</span></h2>
                    <p class="text-gray-400 text-lg max-w-md leading-relaxed mb-12">Currently based in Vancouver and open to strategic leadership opportunities in Internal Audit, Governance, and Risk Management.</p>
                    <div class="flex space-x-6">
                        <a href="mailto:leukng@gmail.com" class="px-8 py-4 bg-gold-500 text-white text-xs font-bold uppercase tracking-widest hover:bg-gold-600 transition-all">Send an Email</a>
                        <a href="https://internalauditnote.blogspot.com" target="_blank" class="px-8 py-4 border border-white/20 text-white text-xs font-bold uppercase tracking-widest hover:bg-white hover:text-navy-900 transition-all">Visit Blog</a>
                    </div>
                </div>
                
                <div class="md:col-span-6 grid grid-cols-1 sm:grid-cols-2 gap-12">
                    <div>
                        <h4 class="text-gold-500 font-bold uppercase tracking-[0.2em] text-xs mb-8">Direct Contact</h4>
                        <div class="space-y-4 text-gray-400 text-sm">
                            <p>+1 236-889-7868 (Canada)</p>
                            <p>+852 6484-2159 (Hong Kong)</p>
                            <p>leukng@gmail.com</p>
                        </div>
                    </div>
                    <div>
                        <h4 class="text-gold-500 font-bold uppercase tracking-[0.2em] text-xs mb-8">Operational Hubs</h4>
                        <div class="space-y-4 text-gray-400 text-sm font-bold uppercase tracking-widest">
                            <p>Vancouver, BC</p>
                            <p>Hong Kong SAR</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-white/10 pt-12 flex flex-col md:flex-row justify-between items-center text-[10px] text-gray-500 uppercase tracking-[0.2em] font-bold">
                <p>&copy; 2026 Richard Leuk Ng. All Rights Reserved.</p>
                <p class="mt-4 md:mt-0 tracking-[0.1em]">CPA (CA/AU/HK) | CISA | Civil Engineering</p>
            </div>
        </div>
    </footer>

    <script>
        // Navbar scroll effect
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('bg-navy-950', 'shadow-2xl', 'py-2');
                navbar.classList.remove('bg-transparent', 'py-4');
            } else {
                navbar.classList.remove('bg-navy-950', 'shadow-2xl', 'py-2');
                navbar.classList.add('bg-transparent', 'py-4');
            }
        });

        // Intersection Observer for scroll animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('is-visible');
                }
            });
        }, { threshold: 0.1 });
        document.querySelectorAll('.fade-up-element').forEach(el => observer.observe(el));
    </script>
</body>
</html>
