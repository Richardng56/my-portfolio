<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Richard Leuk Ng | Senior Internal Audit Leader</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <style>
        /* Hidden until Tailwind is fully initialized to prevent "cracked" look on refresh */
        html { visibility: hidden; }
        html.loaded { visibility: visible; }

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
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0a1424; }
        ::-webkit-scrollbar-thumb { background: #cda873; }

        /* Fix for desktop image scaling */
        .img-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin: 0 auto;
        }
    </style>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: { 950: '#050a12', 900: '#0a1424', 800: '#11223c' },
                        gold: { 400: '#dfc095', 500: '#cda873', 600: '#b89565' }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                    }
                }
            }
        }
        window.addEventListener('load', function() {
            document.documentElement.classList.add('loaded');
        });
    </script>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&display=swap" rel="stylesheet">
</head>
<body class="font-sans text-gray-800 bg-white antialiased overflow-x-hidden">

    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 bg-transparent py-4">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="flex justify-between items-center">
                <a href="#" class="font-serif text-2xl font-bold tracking-wider text-white uppercase">
                    RICHARD <span class="text-gold-500">NG</span>.
                </a>
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#about" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">About</a>
                    <a href="#expertise" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">Expertise</a>
                    <a href="#experience" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">Experience</a>
                    <a href="#cases" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">Case Studies</a>
                    <a href="#contact" class="px-5 py-2 border border-gold-500 text-gold-500 hover:bg-gold-500 hover:text-white transition-colors text-xs font-bold uppercase tracking-widest">Contact</a>
                </div>
                <button id="mobile-menu-btn" class="md:hidden text-white focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </div>
        <div id="mobile-menu" class="hidden md:hidden bg-navy-950 px-6 py-6 space-y-4 shadow-xl">
            <a href="#about" class="block text-white text-sm uppercase tracking-widest">About</a>
            <a href="#expertise" class="block text-white text-sm uppercase tracking-widest">Expertise</a>
            <a href="#experience" class="block text-white text-sm uppercase tracking-widest">Experience</a>
            <a href="#cases" class="block text-white text-sm uppercase tracking-widest">Case Studies</a>
            <a href="#contact" class="block text-gold-500 text-sm uppercase tracking-widest font-bold">Contact</a>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center relative py-20">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 w-full z-10">
            <div class="fade-up-element max-w-3xl">
                <p class="text-gold-500 font-bold tracking-[0.4em] uppercase mb-6 flex items-center">
                    <span class="w-12 h-[2px] bg-gold-500 mr-4"></span> Senior Internal Audit Leader
                </p>
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif text-white font-bold leading-[1.1] mb-8 uppercase tracking-tighter">
                    Integrity <br/>Through <br/>
                    <span class="text-gold-500 italic font-normal">Analytical Rigor.</span>
                </h1>
                <p class="text-gray-400 text-lg md:text-xl max-w-2xl mb-12 leading-relaxed">
                    Protecting enterprise value through forensic precision, technical excellence in ITGC, and a structural approach to global governance.
                </p>
                <div class="flex flex-col sm:flex-row gap-6">
                    <a href="#experience" class="px-10 py-5 bg-gold-500 text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-gold-600 transition-all text-center">Professional Journey</a>
                    <a href="#contact" class="px-10 py-5 bg-transparent border border-white text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-white hover:text-navy-900 transition-all text-center">Get In Touch</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-24 lg:py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 lg:gap-24 items-center">
                <div class="fade-up-element order-2 lg:order-1">
                    <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-8 uppercase leading-tight">
                        Bridging <span class="text-gold-500 italic">Engineering Logic</span> with Financial Oversight
                    </h2>
                    <div class="space-y-6 text-lg text-gray-600 leading-relaxed">
                        <p>With a foundation in Civil Engineering from the UK, I approach Internal Audit as a structural challenge. My methodology ensures that governance frameworks are built to withstand the pressures of volatile global markets.</p>
                        <p>Over 17 years of experience—spanning from Big 4 public practice (KPMG/BDO) to leading audit functions for multi-billion dollar listed entities—has equipped me with the foresight to detect risks before they manifest.</p>
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
                <div class="fade-up-element order-1 lg:order-2">
                    <div class="img-container">
                        <div class="aspect-[4/5] bg-gray-100 overflow-hidden rounded-sm shadow-2xl">
                            <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?q=80&w=2071&auto=format&fit=crop" class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" alt="Professional Portrait">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="expertise" class="py-24 lg:py-32 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-4 uppercase tracking-tighter">Core Expertise</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto"></div>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
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
                    <p class="text-gray-600 text-sm leading-relaxed">Cross-border compliance, IPO readiness, and strategic tax reviews.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-3xl mb-6">🔎</div>
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Forensics</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">High-stakes fraud investigation, AML, and procurement kickback detection.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-24 lg:py-32 bg-navy-950 text-white">
        <div class="max-w-4xl mx-auto px-6 lg:px-12">
            <div class="text-center mb-24 fade-up-element">
                <h2 class="text-4xl md:text-5xl font-serif font-bold uppercase tracking-tight">Professional Journey</h2>
                <div class="w-20 h-1 bg-gold-500 mx-auto mt-6"></div>
            </div>
            <div class="space-y-16 border-l border-gold-500/20 pl-8 md:pl-12 relative">
                <div class="relative fade-up-element">
                    <div class="absolute -left-[35px] md:-left-[51px] top-1.5 w-3 h-3 bg-gold-500 rounded-full shadow-[0_0_10px_#cda873]"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2023 - 2024</p>
                    <h3 class="text-2xl md:text-3xl font-serif font-bold mb-1">Senior Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-4 italic">Sa Sa International Holdings Ltd.</p>
                    <p class="text-gray-400">Directed internal audit across HK, PRC, Macau, and Malaysia. Modernized retail audit protocols for 200+ outlets.</p>
                </div>
                <div class="relative fade-up-element">
                    <div class="absolute -left-[35px] md:-left-[51px] top-1.5 w-3 h-3 bg-white/20 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2021 - 2023</p>
                    <h3 class="text-2xl md:text-3xl font-serif font-bold mb-1">Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-4 italic">Lee Kum Kee Group</p>
                    <p class="text-gray-400">Managed cross-functional audits covering procurement and sales. Leveraged engineering background for safety policies.</p>
                </div>
                <div class="relative fade-up-element">
                    <div class="absolute -left-[35px] md:-left-[51px] top-1.5 w-3 h-3 bg-white/20 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2012 - 2021</p>
                    <h3 class="text-2xl md:text-3xl font-serif font-bold mb-1">Senior Internal Audit Officer</h3>
                    <p class="text-gold-500 text-sm mb-4 italic">Crystal International Group Ltd.</p>
                    <p class="text-gray-400">Spearheaded factory operational audits in SE Asia. Delivered $1M+ improvements in Material Utilization.</p>
                </div>
                <div class="relative fade-up-element">
                    <div class="absolute -left-[35px] md:-left-[51px] top-1.5 w-3 h-3 bg-white/10 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2007 - 2012</p>
                    <h3 class="text-2xl md:text-3xl font-serif font-bold mb-1">Senior Auditor</h3>
                    <p class="text-gold-500 text-sm mb-4 italic">BDO & KPMG</p>
                    <p class="text-gray-400">Led financial audits and US SOX compliance for multinational manufacturing and retail clients.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="cases" class="py-24 lg:py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl font-serif font-bold text-navy-900 uppercase">Strategic Case Studies</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-6"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="fade-up-element border border-gray-100 pb-8 hover:bg-gray-50 p-8 transition-all hover:shadow-lg">
                    <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-4">Conflict of Interest</h4>
                    <p class="text-gray-600 text-sm leading-relaxed">Exposed a consultant acting as a vendor for $3.3M M&E equipment without CFO authorization during a factory construction project.</p>
                </div>
                <div class="fade-up-element border border-gray-100 pb-8 hover:bg-gray-50 p-8 transition-all hover:shadow-lg">
                    <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-4">Cybersecurity (NIST)</h4>
                    <p class="text-gray-600 text-sm leading-relaxed">Identified critical flaws in Information Security Programs through intensive NIST-based reviews of enterprise protocols.</p>
                </div>
                <div class="fade-up-element border border-gray-100 pb-8 hover:bg-gray-50 p-8 transition-all hover:shadow-lg">
                    <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-4">Unauthorized Funds</h4>
                    <p class="text-gray-600 text-sm leading-relaxed">Exposed an unauthorized petty cash pool funneling RMB 1 Million via vendor sponsorships for unrecorded expenses.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white pt-24 pb-12">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="text-center mb-16">
                <h2 class="text-4xl md:text-5xl font-serif font-bold uppercase mb-8 italic tracking-tighter">Let's Secure The Future.</h2>
                <div class="flex flex-col md:flex-row justify-center items-center gap-8 text-lg">
                    <a href="mailto:leukng@gmail.com" class="text-gray-400 hover:text-gold-500 transition-colors">leukng@gmail.com</a>
                    <p class="text-gray-400">+1 236-889-7868 (CA)</p>
                    <p class="text-gray-400">+852 6484-2159 (HK)</p>
                </div>
            </div>
            <div class="border-t border-white/10 pt-12 flex flex-col md:flex-row justify-between items-center text-[10px] text-gray-500 uppercase tracking-widest font-bold">
                <p>&copy; 2026 Richard Leuk Ng. All Rights Reserved.</p>
                <p class="mt-4 md:mt-0">CPA (CA/AU/HK) | CISA | Civil Engineering</p>
            </div>
        </div>
    </footer>

    <script>
        const navbar = document.getElementById('navbar');
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('bg-navy-950', 'shadow-2xl', 'py-2');
                navbar.classList.remove('bg-transparent', 'py-4');
            } else {
                navbar.classList.remove('bg-navy-950', 'shadow-2xl', 'py-2');
                navbar.classList.add('bg-transparent', 'py-4');
            }
        });

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

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
