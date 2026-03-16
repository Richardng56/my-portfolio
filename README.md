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
            background-image: linear-gradient(rgba(5, 10, 18, 0.85), rgba(5, 10, 18, 0.95)), url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop');
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
                    <a href="#contact" class="px-6 py-2.5 border border-gold-500 text-gold-500 hover:bg-gold-500 hover:text-white transition-all text-xs font-bold uppercase tracking-[0.2em]">Contact</a>
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
                <p class="text-gray-400 text-xl max-w-2xl mb-12 leading-relaxed">
                    Protecting enterprise value through forensic precision, technical excellence in ITGC, and a structural approach to global governance.
                </p>
                <div class="flex flex-col sm:flex-row gap-6">
                    <a href="#experience" class="px-10 py-5 bg-gold-500 text-white text-xs font-bold uppercase tracking-widest hover:bg-gold-600 transition-all text-center">Professional Journey</a>
                    <a href="#contact" class="px-10 py-5 bg-transparent border border-white text-white text-xs font-bold uppercase tracking-widest hover:bg-white hover:text-navy-900 transition-all text-center">Get In Touch</a>
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
                        <p>With a foundation in <strong>Civil Engineering</strong>, I approach Internal Audit not just as a compliance checkbox, but as a structural challenge. Governance is only as strong as its weakest process link.</p>
                        <p>Over 17 years of experience—spanning from Big 4 public practice to leading internal audit for multi-billion dollar listed entities—has equipped me with the foresight to detect risks early and drive operational efficiency.</p>
                    </div>
                </div>
                <div class="fade-up-element relative">
                    <div class="aspect-[4/5] bg-gray-100 overflow-hidden rounded-sm shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?q=80&w=2071&auto=format&fit=crop" class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" alt="Richard Ng">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-gray-50 border-y border-gray-100">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 text-center">
                <div class="fade-up-element">
                    <div class="text-navy-900 font-serif font-bold text-2xl uppercase mb-2">CPA (CA/AU)</div>
                    <p class="text-gray-500 text-xs font-bold uppercase tracking-[0.2em]">CPA Ontario & Australia</p>
                </div>
                <div class="fade-up-element">
                    <div class="text-navy-900 font-serif font-bold text-2xl uppercase mb-2">CISA</div>
                    <p class="text-gray-500 text-xs font-bold uppercase tracking-[0.2em]">ISACA (Exam Passed)</p>
                </div>
                <div class="fade-up-element">
                    <div class="text-navy-900 font-serif font-bold text-2xl uppercase mb-2">BEng (Hons)</div>
                    <p class="text-gray-500 text-xs font-bold uppercase tracking-[0.2em]">Civil Engineering, UK</p>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-32 bg-navy-950 text-white">
        <div class="max-w-5xl mx-auto px-6 lg:px-8">
            <h2 class="text-4xl font-serif font-bold uppercase tracking-tight text-center mb-24">Professional Journey</h2>
            <div class="space-y-20 border-l border-gold-500/20 pl-10 relative">
                <div class="relative fade-up-element">
                    <div class="absolute -left-[46px] top-1.5 w-3 h-3 bg-gold-500 rounded-full ring-4 ring-navy-950"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2023 - 2024</p>
                    <h3 class="text-3xl font-serif font-bold mb-1">Senior Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-6 italic font-medium">Sa Sa International Holdings Ltd.</p>
                    <p class="text-gray-400 leading-relaxed text-lg">Directed audit functions for HK, PRC, Macau, and Malaysia. Modernized retail protocols and inventory controls for 200+ outlets.</p>
                </div>
                <div class="relative fade-up-element">
                    <div class="absolute -left-[46px] top-1.5 w-3 h-3 bg-white/20 rounded-full ring-4 ring-navy-950"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2021 - 2023</p>
                    <h3 class="text-3xl font-serif font-bold mb-1">Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-6 italic font-medium">Lee Kum Kee Group</p>
                    <p class="text-gray-400 leading-relaxed text-lg">Leveraged engineering background to revamp group-wide procurement and manufacturing QA policies.</p>
                </div>
                <div class="relative fade-up-element">
                    <div class="absolute -left-[46px] top-1.5 w-3 h-3 bg-white/20 rounded-full ring-4 ring-navy-950"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">2007 - 2012</p>
                    <h3 class="text-3xl font-serif font-bold mb-1">Early Career: BDO & KPMG</h3>
                    <p class="text-gold-500 text-sm mb-6 italic font-medium">Big 4 & Mid-Tier Public Practice</p>
                    <p class="text-gray-400 leading-relaxed text-lg">Foundational rigorous training in external audit, US SOX control testing, and IPO project management.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white pt-32 pb-12 border-t border-white/5">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 text-center">
            <h2 class="text-5xl md:text-7xl font-serif font-bold uppercase mb-12 tracking-tighter">Let's Secure <br><span class="text-gold-500 italic">The Future.</span></h2>
            <div class="mb-16">
                <a href="mailto:leukng@gmail.com" class="px-12 py-5 bg-gold-500 text-white text-xs font-bold uppercase tracking-[0.3em] hover:bg-gold-600 transition-all shadow-xl">Contact via Email</a>
            </div>
            <div class="pt-12 flex flex-col md:flex-row justify-between items-center text-[10px] text-gray-500 uppercase tracking-widest font-bold">
                <p>&copy; 2026 Richard Ng.</p>
                <p class="mt-4 md:mt-0">CPA (CA/AU) | CISA | Civil Engineering</p>
            </div>
        </div>
    </footer>

    <script>
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) { entry.target.classList.add('is-visible'); }
            });
        }, { threshold: 0.1 });
        document.querySelectorAll('.fade-up-element').forEach(el => observer.observe(el));
    </script>
</body>
</html>
