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
                        navy: { 950: '#050a12', 900: '#0a1424', 800: '#11223c' },
                        gold: { 500: '#cda873', 600: '#b89565' }
                    },
                    fontFamily: { sans: ['Inter', 'sans-serif'], serif: ['Playfair Display', 'serif'] }
                }
            }
        }
    </script>

    <style>
        .fade-up-element { opacity: 0; transform: translateY(30px); transition: opacity 0.8s ease-out, transform 0.8s ease-out; }
        .fade-up-element.is-visible { opacity: 1; transform: translateY(0); }
        .hero-bg {
            background-image: linear-gradient(rgba(5, 10, 18, 0.8), rgba(5, 10, 18, 0.9)), url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070&auto=format&fit=crop');
            background-size: cover; background-position: center; background-attachment: fixed;
        }
        .expertise-card:hover { transform: translateY(-10px); border-top-color: #cda873 !important; }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white antialiased">

    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 bg-navy-950 py-4">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 flex justify-between items-center">
            <a href="#" class="font-serif text-2xl font-bold tracking-wider text-white uppercase">RICHARD <span class="text-gold-500">NG</span>.</a>
            <div class="hidden md:flex space-x-8 text-xs font-semibold text-white uppercase tracking-widest">
                <a href="#about" class="hover:text-gold-500">About</a>
                <a href="#expertise" class="hover:text-gold-500">Expertise</a>
                <a href="#experience" class="hover:text-gold-500">Experience</a>
                <a href="#cases" class="hover:text-gold-500">Portfolio</a>
                <a href="#contact" class="px-5 py-2 border border-gold-500 text-gold-500 hover:bg-gold-500 hover:text-white transition-all">Contact</a>
            </div>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center relative">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 w-full z-10 text-center">
            <div class="fade-up-element">
                <p class="text-gold-500 font-bold tracking-[0.3em] uppercase mb-6">Senior Internal Audit Leader</p>
                <h1 class="text-5xl md:text-7xl font-serif text-white font-bold leading-tight mb-8 uppercase">Precision in Governance.</h1>
                <div class="flex flex-col sm:flex-row justify-center gap-6 mt-12">
                    <a href="#expertise" class="px-10 py-4 bg-gold-500 text-white text-xs font-bold uppercase tracking-widest hover:bg-gold-600">Explore Expertise</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-32 bg-white">
        <div class="max-w-6xl mx-auto px-6 lg:px-8">
            <div class="fade-up-element text-center mb-16">
                <h2 class="text-4xl font-serif text-navy-900 font-bold mb-4 uppercase">Professional <span class="text-gold-500 italic">Summary</span></h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-6"></div>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-start">
                <div class="fade-up-element text-lg text-gray-600 leading-relaxed text-left space-y-6">
                    <p>An all-rounded Internal Audit professional with an extensive track record covering finance, operations, taxation, ITGC, and compliance audits. With an academic foundation in Civil Engineering from the UK, I bring a highly analytical, structural approach to corporate problem-solving.</p>
                    <p>As a fast learner, I adapt rapidly to changing business landscapes, ensuring corporate governance frameworks drive tangible operational efficiencies.</p>
                </div>
                <div class="fade-up-element grid grid-cols-1 sm:grid-cols-2 gap-8 bg-gray-50 p-10 border border-gray-100 shadow-sm text-left">
                    <div><p class="text-gold-500 font-black text-xs uppercase mb-2">Accounting</p><p class="text-navy-900 font-serif font-bold text-xl">CPA (CA/HK)</p></div>
                    <div><p class="text-gold-500 font-black text-xs uppercase mb-2">Systems Audit</p><p class="text-navy-900 font-serif font-bold text-lg uppercase">CISA Requirements Met</p></div>
                    <div><p class="text-gold-500 font-black text-xs uppercase mb-2">Modern Tech</p><p class="text-navy-900 font-serif font-bold text-xl uppercase">AI & Vibe Coding</p></div>
                    <div><p class="text-gold-500 font-black text-xs uppercase mb-2">Engineering</p><p class="text-navy-900 font-serif font-bold text-xl">B.Eng (Hons)</p></div>
                </div>
            </div>
        </div>
    </section>

    <section id="expertise" class="py-32 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl font-serif text-navy-900 font-bold mb-4 uppercase">Strategic Expertise</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-8"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-10 text-left">
                <div class="p-10 border border-gray-100 bg-white border-t-[6px] border-t-navy-900 fade-up-element expertise-card shadow-sm transition-all">
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Risk Management</h3>
                    <p class="text-gray-600">NIST-based cybersecurity and BCM implementation to ensure resilience in volatile digital landscapes.</p>
                </div>
                <div class="p-10 border border-gray-100 bg-white border-t-[6px] border-t-navy-900 fade-up-element expertise-card shadow-sm transition-all">
                    <h3 class="text-xl font-serif font-bold text-navy-900 mb-4 uppercase">Supply Chain Audit</h3>
                    <p class="text-gray-600">End-to-end oversight from factory floor efficiency (SAM cost) to global procurement and vendor management.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-32 bg-navy-900 text-white">
        <div class="max-w-5xl mx-auto px-6 lg:px-8 text-left">
            <h2 class="text-4xl font-serif font-bold mb-16 uppercase tracking-wide">Professional Journey</h2>
            <div class="space-y-16 border-l border-gold-500/20 pl-10 relative">
                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-2.5 h-2.5 bg-gold-500 rounded-full"></div>
                    <p class="text-gold-500 text-xs font-bold uppercase mb-2">2023 - 2024</p>
                    <h3 class="text-2xl font-serif font-bold uppercase">Senior IA Manager | Sa Sa International</h3>
                    <p class="text-gray-400 mt-2">Managed Group IA functions across Hong Kong, PRC, Macau, and Malaysia for 200+ retail points.</p>
                </div>
                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-2.5 h-2.5 bg-gray-500 rounded-full"></div>
                    <p class="text-gold-500 text-xs font-bold uppercase mb-2">2012 - 2021</p>
                    <h3 class="text-2xl font-serif font-bold uppercase">Senior IA Officer | Crystal International</h3>
                    <p class="text-gray-400 mt-2">Specialized in large-scale operational audits, factory efficiency, and material utilization control.</p>
                </div>
                <div class="relative fade-up-element">
                    <div class="absolute -left-[45px] top-1.5 w-2.5 h-2.5 bg-gray-500 rounded-full"></div>
                    <p class="text-gold-500 text-xs font-bold uppercase mb-2">2007 - 2012</p>
                    <h3 class="text-2xl font-serif font-bold uppercase tracking-tight">External Audit | BDO & KPMG</h3>
                    <p class="text-gray-400 mt-2">Rigorous training in financial reporting standards, IPO readiness, and internal control testing (US SOX).</p>
                </div>
            </div>
        </div>
    </section>

    <section id="cases" class="py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center mb-20 fade-up-element">
                <h2 class="text-4xl font-serif text-navy-900 font-bold uppercase tracking-tight">Project Highlights</h2>
                <div class="w-20 h-1.5 bg-gold-500 mx-auto mt-6"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 text-left">
                <div class="fade-up-element group">
                    <div class="h-64 bg-gray-100 mb-6 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=2070&auto=format&fit=crop" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <h3 class="text-xl font-serif font-bold uppercase mb-2">Conflict of Interest</h3>
                    <p class="text-gray-600 text-sm">Investigated a $3.3M construction project revealing unauthorized vendor relationships.</p>
                </div>
                <div class="fade-up-element group">
                    <div class="h-64 bg-gray-100 mb-6 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?q=80&w=1740&auto=format&fit=crop" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <h3 class="text-xl font-serif font-bold uppercase mb-2">NIST Cyber Audit</h3>
                    <p class="text-gray-600 text-sm">Identified gaps in data encryption and incident response protocols against NIST standards.</p>
                </div>
                <div class="fade-up-element group">
                    <div class="h-64 bg-gray-100 mb-6 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=1740&auto=format&fit=crop" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <h3 class="text-xl font-serif font-bold uppercase mb-2">Fraud Exposure</h3>
                    <p class="text-gray-600 text-sm">Exposed an unauthorized petty cash pool used for unrecorded operational kickbacks.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white pt-24 pb-12">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 text-left">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 border-b border-white/10 pb-12">
                <div>
                    <h2 class="font-serif text-3xl font-bold uppercase mb-4">RICHARD <span class="text-gold-500">NG</span>.</h2>
                    <p class="text-gray-400 text-sm">leukng@gmail.com | Vancouver & Hong Kong</p>
                </div>
            </div>
            <p class="text-[10px] text-gray-500 uppercase font-bold mt-12">© 2026 Richard Leuk Ng. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => { if (entry.isIntersecting) entry.target.classList.add('is-visible'); });
        }, { threshold: 0.1 });
        document.querySelectorAll('.fade-up-element').forEach(el => observer.observe(el));
    </script>
</body>
</html>
