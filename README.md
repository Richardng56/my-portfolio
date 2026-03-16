<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Richard Ng | Senior Internal Audit Leader</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <style>
        /* Prevent Flash of Unstyled Content */
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
        }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #050a12; }
        ::-webkit-scrollbar-thumb { background: #cda873; }
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
        window.addEventListener('load', () => document.documentElement.classList.add('loaded'));
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
                <div class="hidden md:flex space-x-8 items-center text-white">
                    <a href="#about" class="text-xs font-bold uppercase tracking-widest hover:text-gold-500 transition-colors">About</a>
                    <a href="#expertise" class="text-xs font-bold uppercase tracking-widest hover:text-gold-500 transition-colors">Expertise</a>
                    <a href="#experience" class="text-xs font-bold uppercase tracking-widest hover:text-gold-500 transition-colors">Experience</a>
                    <a href="#cases" class="text-xs font-bold uppercase tracking-widest hover:text-gold-500 transition-colors">Portfolio</a>
                    <a href="#contact" class="px-5 py-2 border border-gold-500 text-gold-500 hover:bg-gold-500 hover:text-white transition-colors text-xs font-bold uppercase tracking-widest">Contact</a>
                </div>
                <button id="mobile-menu-btn" class="md:hidden text-white">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </div>
        <div id="mobile-menu" class="hidden md:hidden bg-navy-950 px-6 py-6 space-y-4">
            <a href="#about" class="block text-white text-sm uppercase tracking-widest">About</a>
            <a href="#experience" class="block text-white text-sm uppercase tracking-widest">Experience</a>
            <a href="#contact" class="block text-gold-500 text-sm uppercase tracking-widest font-bold">Contact</a>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center py-20">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 w-full">
            <div class="fade-up-element max-w-3xl">
                <p class="text-gold-500 font-bold tracking-[0.4em] uppercase mb-6 flex items-center">
                    <span class="w-12 h-[2px] bg-gold-500 mr-4"></span> Senior Internal Audit Leader
                </p>
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif text-white font-bold leading-[1.1] mb-8 uppercase tracking-tighter">
                    Integrity <br/>Through <br/>
                    <span class="text-gold-500 italic font-normal">Analytical Rigor.</span>
                </h1>
                <div class="flex flex-col sm:flex-row gap-6">
                    <a href="#experience" class="px-10 py-5 bg-gold-500 text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-gold-600 transition-all text-center">Professional Journey</a>
                    <a href="#contact" class="px-10 py-5 bg-transparent border border-white text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-white hover:text-navy-900 transition-all text-center">Get In Touch</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-24 lg:py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
                <div class="fade-up-element order-2 lg:order-1">
                    <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-8 uppercase leading-tight">
                        Bridging <span class="text-gold-500 italic">Engineering Logic</span> with Financial Oversight
                    </h2>
                    <div class="space-y-6 text-lg text-gray-600 leading-relaxed">
                        <p>A well-rounded Internal Audit professional with extensive experience across financial, operational, taxation, ITGC, and compliance audits. Bringing a strong analytical and structured approach to complex business challenges, supported by an academic foundation in Civil Engineering.</p>
                        <p>Recognized as a fast and adaptable learner, with the ability to navigate evolving business environments and strengthen corporate governance frameworks. Proven capability to support regulatory compliance while identifying opportunities to enhance operational efficiency.</p>
                    </div>
                    <div class="grid grid-cols-2 gap-8 mt-12">
                        <div>
                            <p class="text-4xl font-serif font-bold text-navy-900">17+</p>
                            <p class="text-gold-500 text-[10px] font-bold uppercase tracking-widest mt-2">Years Experience</p>
                        </div>
                        <div>
                            <p class="text-4xl font-serif font-bold text-navy-900">150+</p>
                            <p class="text-gold-500 text-[10px] font-bold uppercase tracking-widest mt-2">Audit Review Tasks Completed</p>
                        </div>
                    </div>
                </div>
                <div class="fade-up-element order-1 lg:order-2">
                    <div class="relative max-w-md mx-auto">
                        <img src="office.png" class="w-full h-full object-cover grayscale" alt="Professional Portrait">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="expertise" class="py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element shadow-sm">
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">ITGC & Cyber</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">NIST-aligned security audits, COBIT/ISO27001 framework implementation, and IT general control testing.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element shadow-sm">
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Supply Chain</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">End-to-end operational reviews from factory SAM costs to global distribution logistics.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element shadow-sm">
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Tax & Finance</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Cross-border compliance, IPO readiness, and strategic tax reviews.</p>
                </div>
                <div class="expertise-card p-10 bg-white border-t-[6px] border-t-navy-900 fade-up-element shadow-sm">
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Forensics</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">High-stakes fraud investigation, bid rigging, and procurement kickback detection.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-24 lg:py-32 bg-navy-950 text-white">
        <div class="max-w-4xl mx-auto px-6 lg:px-12">
            <div class="text-center mb-24 fade-up-element">
                <h2 class="text-4xl md:text-5xl font-serif font-bold uppercase tracking-tight">Professional Experience</h2>
                <div class="w-20 h-1 bg-gold-500 mx-auto mt-6"></div>
            </div>
            
            <div class="space-y-16 border-l border-gold-500/20 pl-8 md:pl-12 relative">
                <div class="relative fade-up-element">
                    <div class="absolute -left-[35px] md:-left-[51px] top-1.5 w-3 h-3 bg-gold-500 rounded-full shadow-[0_0_10px_#cda873]"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">AUG 2024 - PRESENT</p>
                    <h3 class="text-2xl md:text-3xl font-serif font-bold mb-1">Strategic Sabbatical & Upskilling</h3>
                    <p class="text-gray-400 text-sm mb-4 italic">Vancouver, Canada</p>
                    <p class="text-gray-400 text-sm leading-relaxed">Dedicated to international relocation, advanced technical training (CISA, AI Prompting), and industry thought leadership.</p>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[35px] md:-left-[51px] top-1.5 w-3 h-3 bg-white/30 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">JAN 2023 - JUN 2024</p>
                    <h3 class="text-2xl md:text-3xl font-serif font-bold mb-1">Senior Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-4 italic">Sa Sa International Holdings Ltd. (SEHK: 178)</p>
                    <ul class="list-disc list-outside ml-4 space-y-2 text-gray-400 text-sm">
                        <li>Led Group IA oversight for PRC, HK, Macau, and Malaysia.</li>
                        <li>Relaunched 200+ global retail store audits post-COVID.</li>
                        <li>Established corporate Risk and Crisis Management frameworks.</li>
                    </ul>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[35px] md:-left-[51px] top-1.5 w-3 h-3 bg-white/30 rounded-full"></div>
                    <p class="text-gold-400 text-xs font-bold tracking-widest uppercase mb-2">AUG 2021 - JAN 2023</p>
                    <h3 class="text-2xl md:text-3xl font-serif font-bold mb-1">Internal Audit Manager</h3>
                    <p class="text-gold-500 text-sm mb-4 italic">Lee Kum Kee Group</p>
                    <ul class="list-disc list-outside ml-4 space-y-2 text-gray-400 text-sm">
                        <li>Reported 30+ findings covering procurement and QA.</li>
                        <li>Revamped in-house engineering policy leveraging technical background.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="cases" class="py-24 lg:py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="text-center mb-20 fade-up-element">
                <p class="text-gold-500 font-bold tracking-widest uppercase text-xs mb-4">Audit Portfolio</p>
                <h2 class="text-4xl font-serif font-bold text-navy-900 uppercase">Project Highlights</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-6"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
                <div class="fade-up-element border-b border-gray-100 pb-8 hover:bg-gray-50 p-6 transition-colors">
                    <div class="bg-gray-200 aspect-video mb-6 overflow-hidden">
                        <img src="capex.png" class="w-full h-full object-cover grayscale transform hover:scale-105 transition-transform duration-500" alt="Conflict of Interest">
                    </div>
                    <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-4">Conflict of Interest</h4>
                    <p class="text-gray-600 text-sm leading-relaxed">Investigation into a factory construction project revealing a consultant acting as a vendor for $3.3M M&E equipment without CFO authorization.</p>
                </div>
                <div class="fade-up-element border-b border-gray-100 pb-8 hover:bg-gray-50 p-6 transition-colors">
                    <div class="bg-gray-200 aspect-video mb-6 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?q=80&w=1740&auto=format&fit=crop" class="w-full h-full object-cover grayscale transform hover:scale-105 transition-transform duration-500" alt="NIST">
                    </div>
                    <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-4">NIST Framework Audit</h4>
                    <p class="text-gray-600 text-sm leading-relaxed">Executed ITGC audits identifying critical gaps in data encryption and incident response protocols.</p>
                </div>
                <div class="fade-up-element border-b border-gray-100 pb-8 hover:bg-gray-50 p-6 transition-colors">
                    <div class="bg-gray-200 aspect-video mb-6 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=1740&auto=format&fit=crop" class="w-full h-full object-cover grayscale transform hover:scale-105 transition-transform duration-500" alt="Fraud">
                    </div>
                    <h4 class="text-xl font-serif font-bold text-navy-900 uppercase mb-4">Unauthorized Funds</h4>
                    <p class="text-gray-600 text-sm leading-relaxed">Exposed an unauthorized petty cash pool for unrecorded vendor sponsorships totaling over RMB 1 Million.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white py-20 border-t border-white/10">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start mb-16">
                <div class="lg:col-span-5">
                    <a href="#" class="font-serif text-3xl font-bold tracking-wider text-white uppercase mb-6 block">
                        RICHARD <span class="text-gold-500">NG</span>.
                    </a>
                    <p class="text-gray-400 text-base max-w-sm">Bridging rigorous compliance with modern efficiency. Ready to provide strategic internal audit leadership.</p>
                </div>
                <div class="lg:col-span-4">
                    <h4 class="text-white font-bold uppercase tracking-widest text-xs mb-8">Contact</h4>
                    <div class="space-y-6 text-gray-400">
                        <div class="flex items-start gap-4">
                            <span class="text-gold-500 mt-1">📞</span>
                            <p class="text-sm leading-relaxed">+1 236-889-7868 (CA)<br>+852 6484-2159 (HK)</p>
                        </div>
                        <div class="flex items-center gap-4">
                            <span class="text-gold-500">✉️</span>
                            <a href="mailto:leukng@gmail.com" class="text-sm hover:text-white transition-colors">leukng@gmail.com</a>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-3">
                    <h4 class="text-white font-bold uppercase tracking-widest text-xs mb-8">Locations</h4>
                    <ul class="space-y-4 text-gray-400 text-sm">
                        <li>Vancouver, Canada</li>
                        <li>Hong Kong, China</li>
                    </ul>
                </div>
            </div>
            <div class="pt-8 border-t border-white/5 flex flex-col md:flex-row justify-between items-center text-[10px] text-gray-600 font-bold uppercase tracking-[0.2em]">
                <p>© 2026 RICHARD NG. ALL RIGHTS RESERVED.</p>
                <div class="flex gap-6 mt-4 md:mt-0">
                    <span>CPA (CA/AU)</span>
                    <span>CISA</span>
                    <span>CIVIL ENGINEERING (BEng)</span>
                </div>
            </div>
        </div>
    </footer>

    <script>
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

        document.getElementById('mobile-menu-btn').addEventListener('click', () => {
            document.getElementById('mobile-menu').classList.toggle('hidden');
        });

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) entry.target.classList.add('is-visible');
            });
        }, { threshold: 0.1 });
        document.querySelectorAll('.fade-up-element').forEach(el => observer.observe(el));
    </script>
</body>
</html>
