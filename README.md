<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Richard Leuk Ng | Senior Internal Audit Leader</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: { navy: { 950: '#050a12', 900: '#0a1424' }, gold: { 500: '#cda873' } },
                    fontFamily: { sans: ['Inter', 'sans-serif'], serif: ['Playfair Display', 'serif'] }
                }
            }
        }
    </script>
    <style>
        .fade-up { opacity: 0; transform: translateY(20px); transition: all 0.6s ease-out; }
        .is-visible { opacity: 1; transform: translateY(0); }
        .hero-bg {
            background-image: linear-gradient(rgba(5, 10, 18, 0.8), rgba(5, 10, 18, 0.9)), url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070');
            background-size: cover; background-position: center;
        }
    </style>
</head>
<body class="bg-white text-gray-800 font-sans">

    <nav class="fixed w-full z-50 bg-navy-950 py-4 px-8 flex justify-between items-center">
        <div class="text-white font-serif text-xl font-bold uppercase tracking-widest">RICHARD <span class="text-gold-500">NG</span></div>
        <div class="space-x-6 text-xs font-bold text-white uppercase tracking-widest">
            <a href="#about" class="hover:text-gold-500">About</a>
            <a href="#experience" class="hover:text-gold-500">Experience</a>
            <a href="#contact" class="hover:text-gold-500">Contact</a>
        </div>
    </nav>

    <section class="hero-bg min-h-screen flex items-center justify-center text-center px-6">
        <div class="fade-up">
            <p class="text-gold-500 font-bold tracking-[0.3em] uppercase mb-4 text-sm">Senior Internal Audit Leader</p>
            <h1 class="text-4xl md:text-7xl font-serif text-white font-bold mb-8 uppercase">Precision in Governance.</h1>
            <a href="#about" class="px-8 py-3 bg-gold-500 text-white text-xs font-bold uppercase tracking-widest hover:bg-gold-600 transition-all">View Summary</a>
        </div>
    </section>

    <section id="about" class="py-24 px-8 max-w-5xl mx-auto">
        <div class="grid md:grid-cols-2 gap-12">
            <div class="fade-up">
                <h2 class="text-3xl font-serif font-bold text-navy-900 mb-6 uppercase">Professional Summary</h2>
                <p class="text-gray-600 leading-relaxed">Accountant and Auditor with 17+ years of experience across finance, operations, and ITGC. Combining an engineering background with CPA/CISA expertise to drive operational efficiency.</p>
            </div>
            <div class="fade-up grid grid-cols-2 gap-4">
                <div class="bg-gray-50 p-6 border-t-4 border-gold-500">
                    <p class="text-xs font-bold text-gold-500 uppercase mb-1">Accounting</p>
                    <p class="font-bold text-navy-900">CPA (CA/HK)</p>
                </div>
                <div class="bg-gray-50 p-6 border-t-4 border-gold-500">
                    <p class="text-xs font-bold text-gold-500 uppercase mb-1">Systems</p>
                    <p class="font-bold text-navy-900 uppercase">CISA Requirements Met</p>
                </div>
                <div class="bg-gray-50 p-6 border-t-4 border-gold-500">
                    <p class="text-xs font-bold text-gold-500 uppercase mb-1">Modern Tech</p>
                    <p class="font-bold text-navy-900">AI & Vibe Coding</p>
                </div>
                <div class="bg-gray-50 p-6 border-t-4 border-gold-500">
                    <p class="text-xs font-bold text-gold-500 uppercase mb-1">Engineering</p>
                    <p class="font-bold text-navy-900">B.Eng (Hons)</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy-950 text-white py-16 px-8 text-center">
        <h2 class="font-serif text-2xl font-bold uppercase mb-4">Richard Leuk Ng</h2>
        <p class="text-gray-400 text-sm mb-8">leukng@gmail.com | Vancouver, BC & Hong Kong</p>
        <p class="text-[10px] text-gray-600 tracking-widest uppercase font-bold border-t border-white/10 pt-8">© 2026 Richard Leuk Ng. All Rights Reserved.</p>
    </footer>

    <script>
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => { if (entry.isIntersecting) entry.target.classList.add('is-visible'); });
        }, { threshold: 0.1 });
        document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));
    </script>
</body>
</html>
