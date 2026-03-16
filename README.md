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
            background-image: linear-gradient(rgba(5, 10, 18, 0.8), rgba(5, 10, 18, 0.9)), url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop');
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
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
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
                    <a href="#cases" class="text-xs font-semibold text-white hover:text-gold-500 transition-colors uppercase tracking-widest">Portfolio</a>
                    <a href="#contact" class="px-5 py-2 border border-gold-500 text-gold-500 hover:bg-gold-500 hover:text-white transition-colors text-xs font-bold uppercase tracking-widest">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center relative">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 w-full z-10 text-center">
            <div class="fade-up-element">
                <p class="text-gold-500 font-bold tracking-[0.3em] uppercase mb-6">Senior Internal Audit Leader</p>
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif text-white font-bold leading-tight mb-8 uppercase tracking-tight">
                    Precision in Governance. <br/>
                    <span class="text-gray-400 italic font-normal">Excellence in Oversight.</span>
                </h1>
                <div class="flex flex-col sm:flex-row justify-center gap-6 mt-12">
                    <a href="#expertise" class="px-10 py-4 bg-gold-500 text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-gold-600 transition-all">Explore Expertise</a>
                    <a href="#experience" class="px-10 py-4 bg-transparent border border-white text-white text-xs font-bold uppercase tracking-[0.2em] hover:bg-white hover:text-navy-900 transition-all">Professional Journey</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-32 bg-white">
        <div class="max-w-4xl mx-auto px-6 lg:px-8">
            <div class="fade-up-element text-center">
                <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-4 uppercase tracking-tighter">Professional <span class="text-gold-500 italic">Summary</span></h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-6 mb-12"></div>
                <div class="space-y-6 text-lg text-gray-600 leading-relaxed text-left">
                    <p>
                        An all-rounded Internal Audit professional with an extensive track record covering finance, operations, taxation, ITGC, and compliance audits. With an academic foundation in Civil Engineering from the UK, I bring a highly analytical, structural approach to complex corporate problem-solving.
                    </p>
                    <p>
                        As a fast and eager learner, I adapt rapidly to changing business landscapes, ensuring corporate governance frameworks not only meet regulatory demands but also drive tangible operational efficiencies across diverse sectors.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="expertise" class="py-32 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold mb-4 uppercase tracking-tighter">Core Expertise & Strategic Impact</h2>
                <p class="text-gold-500 font-bold tracking-[0.15em] uppercase text-sm">Strategic Governance | Operational Excellence | Forensic Integrity</p>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-8"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
                <div class="expertise-card p-12 border border-gray-100 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-4xl mb-6">🛡️</div>
                    <h3 class="text-2xl font-serif font-bold text-navy-900 mb-4 uppercase tracking-wide">Integrated Risk Management</h3>
                    <p class="text-gray-600 leading-relaxed">Specialized in <span class="font-semibold text-navy-950">NIST-based cybersecurity</span> and <span class="font-semibold text-navy-950">BCM</span> to ensure resilience in volatile digital landscapes.</p>
                </div>
                <div class="expertise-card p-12 border border-gray-100 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-4xl mb-6">🏭</div>
                    <h3 class="text-2xl font-serif font-bold text-navy-900 mb-4 uppercase tracking-wide">End-to-End Supply Chain Audit</h3>
                    <p class="text-gray-600 leading-relaxed">Oversight from <span class="font-semibold text-navy-950">factory floor efficiency (SAM cost)</span> to global procurement and vendor management.</p>
                </div>
                <div class="expertise-card p-12 border border-gray-100 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-4xl mb-6">⚖️</div>
                    <h3 class="text-2xl font-serif font-bold text-navy-900 mb-4 uppercase tracking-wide">Financial & Tax Governance</h3>
                    <p class="text-gray-600 leading-relaxed">Expert in <span class="font-semibold text-navy-950">cross-border compliance (HK/PRC/Macau)</span> and strategic taxation reviews (MCO & Tax Equalization).</p>
                </div>
                <div class="expertise-card p-12 border border-gray-100 bg-white border-t-[6px] border-t-navy-900 fade-up-element">
                    <div class="text-4xl mb-6">🔍</div>
                    <h3 class="text-2xl font-serif font-bold text-navy-900 mb-4 uppercase tracking-wide">Forensic Investigation</h3>
                    <p class="text-gray-600 leading-relaxed">Decisive action in <span class="font-semibold text-navy-950">fraud detection</span> and uncovering complex financial schemes such as teeming and lading.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-32 bg-navy-900 text-white">
        <div class="max-w-5xl mx-auto px-6 lg:px-8">
            <div class="mb-20 fade-up-element text-center md:text-left">
                <h2 class="text-4xl font-serif font-bold mb-4 uppercase tracking-wide">Professional Experience</h2>
                <div class="w-16 h-1.5 bg-gold-500 mx-auto md:ml-0"></div>
            </div>
            
            <div class="space-y-16 border-l border-gold-500/20 pl-10 relative">
                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-2.5 h-2.5 bg-gold-500 rounded-full shadow-[0_0_10px_#cda873]"></div>
                    <p class="text-gold-500 text-xs font-bold tracking-widest uppercase mb-2">Aug 2024 - Present</p>
                    <h3 class="text-2xl font-serif font-bold mb-1 uppercase">Strategic Upskilling</h3>
                    <p class="text-gray-400 text-sm mb-4">Vancouver, Canada</p>
                    <p class="text-gray-400 text-base leading-relaxed">Focus on advanced CISA methodologies and AI-integrated audit workflows.</p>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-2.5 h-2.5 bg-gray-500 rounded-full"></div>
                    <p class="text-gold-500 text-xs font-bold tracking-widest uppercase mb-2">Jan 2023 - Jun 2024</p>
                    <h3 class="text-2xl font-serif font-bold mb-1 uppercase">Senior Internal Audit Manager</h3>
                    <p class="text-gray-400 text-sm mb-4 italic">Sa Sa International Holdings Ltd. (SEHK: 178)</p>
                    <ul class="text-gray-400 text-base space-y-2 list-disc list-outside ml-4">
                        <li>Managed Group IA functions across Hong Kong, PRC, Macau, and Malaysia.</li>
                        <li>Implemented modernized audit protocols for 200+ retail points of sale.</li>
                    </ul>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-2.5 h-2.5 bg-gray-600 rounded-full"></div>
                    <p class="text-gold-500 text-xs font-bold tracking-widest uppercase mb-2">May 2012 - Aug 2021</p>
                    <h3 class="text-2xl font-serif font-bold mb-1 uppercase">Senior Internal Audit Officer</h3>
                    <p class="text-gray-400 text-sm mb-4 italic">Crystal International Group Ltd. (SEHK: 2232)</p>
                    <p class="text-gray-400 text-base leading-relaxed">Specialized in large-scale operational audits, factory efficiency reviews, and material utilization control.</p>
                </div>

                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-2.5 h-2.5 bg-gray-700 rounded-full"></div>
                    <p class="text-gold-500 text-xs font-bold tracking-widest uppercase mb-2">2007 - 2012</p>
                    <h3 class="text-2xl font-serif font-bold mb-1 uppercase tracking-tight">External Audit Foundations (BDO & KPMG)</h3>
                    <p class="text-gray-400 text-base leading-relaxed italic mb-2">Auditor / Senior Auditor</p>
                    <p class="text-gray-400 text-base leading-relaxed">Rigorous training in financial reporting standards, IPO readiness, and internal control testing (US SOX) for multinational clients.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="cases" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <p class="text-gold-500 font-bold tracking-widest uppercase text-sm mb-3">Audit Portfolio</p>
                <h2 class="text-4xl md:text-5xl font-serif text-navy-900 font-bold uppercase tracking-tight">Project Highlights</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-6"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
                <div class="fade-up-element group">
                    <div class="relative overflow-hidden mb-8 h-64 bg-gray-100 rounded-sm">
                        <img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=2070&auto=format&fit=crop" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="Governance Audit">
                        <div class="absolute bottom-4 left-4 bg-gold-500 px-4 py-1 text-[10px] font-black text-white uppercase tracking-widest">Governance & CAPEX</div>
                    </div>
                    <h3 class="text-2xl font-serif font-bold text-navy-900 mb-4 group-hover:text-gold-500 transition-colors uppercase">Conflict of Interest Detection</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-6">Investigated a $3.3M construction project revealing an unauthorized vendor relationship and lack of independent cost benchmarking.</p>
                </div>

                <div class="fade-up-element group">
                    <div class="relative overflow-hidden mb-8 h-64 bg-gray-100 rounded-sm">
                        <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?q=80&w=1740&auto=format&fit=crop" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="Cyber Audit">
                        <div class="absolute bottom-4 left-4 bg-gold-500 px-4 py-1 text-[10px] font-black text-white uppercase tracking-widest">IT & Cyber Security</div>
                    </div>
                    <h3 class="text-2xl font-serif font-bold text-navy-900 mb-4 group-hover:text-gold-500 transition-colors uppercase">NIST Framework Audit</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-6">Execution of comprehensive ITGC audits against NIST standards, identifying critical gaps in data encryption and incident response protocols.</p>
                </div>

                <div class="fade-up-element group">
                    <div class="relative overflow-hidden mb-8 h-64 bg-gray-100 rounded-sm">
                        <img src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=1740&auto=format&fit=crop" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="Forensic Audit">
                        <div class="absolute bottom-4 left-4 bg-gold-500 px-4 py-1 text-[10px] font-black text-white uppercase tracking-widest">Forensic & Fraud</div>
                    </div>
                    <h3 class="text-2xl font-serif font-bold text-navy-900 mb-4 group-hover:text-gold-500 transition-colors uppercase">Unauthorized Funds Exposure</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-6">Exposed an unauthorized petty cash pool used for unrecorded vendor sponsorships and operational kickbacks totaling over RMB 1 Million.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white pt-24 pb-12">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-12 mb-20 items-start">
                <div class="md:col-span-5">
                    <a href="#" class="font-serif text-3xl font-bold tracking-wider text-white uppercase block mb-8">RICHARD <span class="text-gold-500 font-black">NG</span>.</a>
                    <p class="text-gray-400 max-w-sm leading-relaxed text-sm">Bridging rigorous compliance with modern efficiency. Ready to provide strategic internal audit leadership in dynamic environments.</p>
                </div>
                
                <div class="md:col-span-4">
                    <h4 class="text-gold-500 font-black uppercase tracking-[0.2em] text-xs mb-8">Contact Information</h4>
                    <div class="space-y-6 text-sm">
                        <div class="flex items-start">
                            <span class="text-gold-500 mr-4">📞</span>
                            <span class="text-gray-400">
                                +1 236-889-7868 (Canada) <br> 
                                +852 6484-2159 (Hong Kong)
                            </span>
                        </div>
                        <div class="flex items-center">
                            <span class="text-gold-500 mr-4">✉️</span>
                            <a href="mailto:leukng@gmail.com" class="text-gray-400 hover:text-white transition-colors">leukng@gmail.com</a>
                        </div>
                        <div class="flex items-center">
                            <span class="text-gold-500 mr-4">🌐</span>
                            <a href="https://internalauditnote.blogspot.com" target="_blank" class="text-gray-400 hover:text-white transition-colors uppercase font-bold tracking-tighter">Internal Audit Blog</a>
                        </div>
                    </div>
                </div>

                <div class="md:col-span-3">
                    <h4 class="text-gold-500 font-black uppercase tracking-[0.2em] text-xs mb-8">Operational Hubs</h4>
                    <ul class="text-gray-400 text-sm space-y-4 font-bold uppercase tracking-widest">
                        <li>Vancouver, BC</li>
                        <li>Hong Kong, SAR</li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-white/10 pt-12 flex flex-col md:flex-row justify-between items-center text-[10px] text-gray-500 uppercase tracking-[0.2em] font-bold">
                <p>&copy; 2026 Richard Leuk Ng. CPA (CA/HK), CISA Exam Passed.</p>
                <div class="flex space-x-8 mt-6 md:mt-0">
                    <a href="#" class="hover:text-white transition-colors">LinkedIn</a>
                    <a href="#" class="hover:text-white transition-colors">Privacy</a>
                </div>
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
