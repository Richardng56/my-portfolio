<html lang="en" class="scroll-smooth" style="scroll-padding-top: 80px;">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Richard Ng | Senior Internal Audit Leader</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* This ensures that when you click 'About', it stops 100px before the section so the header doesn't cover the title */
        html { 
        scroll-padding-top: 100px; 
        visibility: hidden; 
        }
        html.loaded { visibility: visible; }

        /* Ensure the navbar has a solid background so text doesn't bleed through it */
        .nav-solid {
            background-color: #050a12 !important; /* Your Navy 950 color */
            box-shadow: 0 4px 20px rgba(0,0,0,0.3);
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: { navy: { 950: '#050a12', 900: '#0a1424' }, gold: { 500: '#cda873' } },
                    fontFamily: { sans: ['Inter', 'sans-serif'], serif: ['Playfair Display', 'serif'] }
                }
            }
        }
        window.addEventListener('load', () => document.documentElement.classList.add('loaded'));
    </script>
</head>
<body class="font-sans text-gray-800 bg-white antialiased">
    
    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 py-4 nav-solid">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 flex justify-between items-center">
            <a href="#" class="font-serif text-2xl font-bold text-white uppercase">
                RICHARD <span class="text-gold-500">NG</span>.
            </a>
            <div class="hidden md:flex space-x-8 items-center text-white text-xs font-bold uppercase tracking-widest">
                <a href="#about" class="hover:text-gold-500">About</a>
                <a href="#experience" class="hover:text-gold-500">Experience</a>
                <a href="#cases" class="hover:text-gold-500">Portfolio</a>
                <a href="#contact" class="px-4 py-2 border border-gold-500 text-gold-500 hover:bg-gold-500 hover:text-white transition-all">Contact</a>
            </div>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center pt-32 pb-20">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 w-full">
            </div>
    </section>

    <section id="about" class="py-24 lg:py-32 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12 grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <div class="fade-up-element">
                <h2 class="text-4xl font-serif text-navy-900 font-bold mb-8 uppercase">Bridging <span class="text-gold-500 italic">Engineering Logic</span></h2>
                <p class="text-lg text-gray-600 leading-relaxed">Combining a Civil Engineering background with over 17 years of professional audit experience to bring a unique, structured approach to corporate governance.</p>
            </div>
            <div class="fade-up-element">
                <img src="./office.png" alt="Professional Portrait" class="w-full grayscale border-2 border-gray-100" 
                     onerror="this.src='https://via.placeholder.com/400x500?text=Check+office.png+Filename'">
            </div>
        </div>
    </section>

    <section id="experience" class="py-24 bg-navy-950 text-white">
        <div class="max-w-4xl mx-auto px-6 lg:px-12">
            <h2 class="text-4xl font-serif font-bold text-center uppercase mb-12">Professional Journey</h2>
            <div class="border-l-2 border-gold-500/30 pl-8 space-y-12">
                <div>
                    <span class="text-gold-500 text-xs font-bold uppercase">2023 - 2024</span>
                    <h3 class="text-2xl font-serif font-bold">Senior Internal Audit Manager</h3>
                    <p class="text-gray-400 italic">Sa Sa International Holdings Ltd.</p>
                </div>
                </div>
        </div>
    </section>

    <section id="cases" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6 lg:px-12">
            <h2 class="text-4xl font-serif font-bold text-center uppercase mb-16">Project Highlights</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div class="fade-up-element">
                    <img src="./capex.png" alt="Conflict of Interest" class="w-full aspect-video object-cover grayscale mb-6"
                         onerror="this.src='https://via.placeholder.com/600x400?text=Check+capex.png+Filename'">
                    <h4 class="text-xl font-serif font-bold uppercase">Conflict of Interest</h4>
                    <p class="text-gray-600">Investigation into unauthorized $3.3M M&E equipment procurement.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white py-12 border-t border-white/5">
        <div class="max-w-7xl mx-auto px-6 flex justify-between items-center text-[10px] text-gray-500 font-bold uppercase tracking-widest">
            <p>© 2026 RICHARD NG</p>
            <div class="flex gap-4">
                <span>CPA (HK)</span>
                <span>CISA</span>
            </div>
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
