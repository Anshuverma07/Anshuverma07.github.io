<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anshu Verma | Sr. Android Developer</title>
    <!-- Tailwind CSS for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for professional icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        html { scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; }

        .hero-pattern {
            background-color: #0f172a;
            background-image: radial-gradient(at 0% 0%, rgba(59, 130, 246, 0.15) 0, transparent 50%), 
                              radial-gradient(at 100% 0%, rgba(29, 78, 216, 0.1) 0, transparent 50%);
        }

        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px -5px rgba(59, 130, 246, 0.3);
        }

        /* Fixed the animation glitch */
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fade { animation: fadeInUp 0.8s ease-out forwards; }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 overflow-x-hidden">

    <!-- NAVIGATION -->
    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="text-xl font-bold text-blue-600 tracking-tighter">ANSHU<span class="text-slate-400">.KOTLIN</span></span>
            <div class="hidden md:flex space-x-8 font-medium text-slate-600">
                <a href="#about" class="hover:text-blue-600 transition">About</a>
                <a href="#experience" class="hover:text-blue-600 transition">Experience</a>
                <a href="#projects" class="hover:text-blue-600 transition">Projects</a>
                <a href="#contact" class="bg-blue-600 text-white px-5 py-2 rounded-lg hover:bg-blue-700 transition shadow-lg shadow-blue-200">Let's Talk</a>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section class="hero-pattern min-h-screen flex items-center pt-20">
        <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div class="animate-fade">
                <div class="inline-block px-3 py-1 rounded-full bg-blue-500/10 border border-blue-500/20 text-blue-400 text-xs font-bold uppercase tracking-widest mb-6">
                    9+ Years of Excellence
                </div>
                <h1 class="text-5xl md:text-7xl font-bold text-white mb-6 leading-tight">
                    Engineering <span class="text-blue-500">Scalable</span> Android Apps.
                </h1>
                <p class="text-slate-400 text-lg mb-8 leading-relaxed">
                    Senior Android Developer specializing in <span class="text-white">Kotlin-first architecture</span>. I help businesses scale applications to 10k+ users with zero-crash reliability.
                </p>
                <div class="flex flex-wrap gap-4">
                    <a href="#experience" class="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-blue-700 transition">View Experience</a>
                    <a href="https://github.com/Anshuverma07" target="_blank" class="border border-slate-700 text-white px-8 py-3 rounded-lg font-semibold hover:bg-slate-800 transition">
                        <i class="fab fa-github mr-2"></i>GitHub
                    </a>
                </div>
            </div>
            <div class="hidden md:block relative animate-fade" style="animation-delay: 0.2s;">
                <div class="absolute -inset-10 bg-blue-500/10 blur-3xl rounded-full"></div>
                <div class="relative bg-slate-800 p-4 rounded-3xl border border-slate-700 shadow-2xl">
                    <!-- Code Editor Mockup -->
                    <div class="flex space-x-2 mb-4">
                        <div class="w-3 h-3 rounded-full bg-red-500"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500"></div>
                    </div>
                    <code class="text-sm text-blue-300">
                        <span class="text-purple-400">class</span> AndroidArchitect {<br>
                        &nbsp;&nbsp;<span class="text-purple-400">val</span> experience = <span class="text-orange-300">9.years</span><br>
                        &nbsp;&nbsp;<span class="text-purple-400">val</span> mission = <span class="text-green-400">"Build Clean Code"</span><br><br>
                        &nbsp;&nbsp;<span class="text-purple-400">fun</span> deploy(app: Mobile) {<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;app.optimize(crashRate = <span class="text-orange-300">0.01</span>)<br>
                        &nbsp;&nbsp;}<br>
                        }
                    </code>
                </div>
            </div>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-6">
            <h2 class="text-center text-3xl font-bold mb-12">The Story</h2>
            <div class="prose prose-lg text-slate-600 max-w-none text-center">
                <p>
                    I am a Senior Android Developer with a passion for building robust, high-performance mobile ecosystems. Over the last decade, I’ve transitioned from an individual contributor to a 
                    <span class="text-blue-600 font-bold">Technical Lead</span>, managing remote teams of engineers to deliver mission-critical apps.
                </p>
                <div class="mt-10 grid grid-cols-2 md:grid-cols-4 gap-8">
                    <div>
                        <p class="text-3xl font-bold text-slate-900">10k+</p>
                        <p class="text-sm text-slate-500">Active Users</p>
                    </div>
                    <div>
                        <p class="text-3xl font-bold text-slate-900">25%</p>
                        <p class="text-sm text-slate-500">Crash Reduction</p>
                    </div>
                    <div>
                        <p class="text-3xl font-bold text-slate-900">20%</p>
                        <p class="text-sm text-slate-500">Sprints Optimized</p>
                    </div>
                    <div>
                        <p class="text-3xl font-bold text-slate-900">9+</p>
                        <p class="text-sm text-slate-500">Years Exp</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SKILLS SECTION -->
    <section class="py-24 bg-slate-50">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-center text-3xl font-bold mb-16">Technical Mastery</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- App Architecture -->
                <div class="skill-card bg-white p-8 rounded-2xl border border-slate-200 transition-all duration-300">
                    <i class="fas fa-layer-group text-blue-600 text-3xl mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">Architecture</h3>
                    <ul class="text-slate-600 space-y-2">
                        <li>MVVM / Clean Architecture</li>
                        <li>Jetpack Components</li>
                        <li>Multi-module Setup</li>
                    </ul>
                </div>
                <!-- Core Android -->
                <div class="skill-card bg-white p-8 rounded-2xl border border-slate-200 transition-all duration-300">
                    <i class="fab fa-android text-green-500 text-3xl mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">Core Android</h3>
                    <ul class="text-slate-600 space-y-2">
                        <li>Kotlin & Java Coroutines</li>
                        <li>Room Database & SQLite</li>
                        <li>Retrofit & REST APIs</li>
                    </ul>
                </div>
                <!-- DevOps/Tools -->
                <div class="skill-card bg-white p-8 rounded-2xl border border-slate-200 transition-all duration-300">
                    <i class="fas fa-tools text-slate-700 text-3xl mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">Leadership & Tools</h3>
                    <ul class="text-slate-600 space-y-2">
                        <li>Agile/Scrum Leadership</li>
                        <li>Firebase Suite</li>
                        <li>Git & CI/CD Pipelines</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- EXPERIENCE SECTION -->
    <section id="experience" class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-6">
            <h2 class="text-center text-3xl font-bold mb-16">Work History</h2>
            <div class="space-y-12">
                <!-- Item 1 -->
                <div class="group relative pl-8 border-l-2 border-blue-100 hover:border-blue-600 transition-colors">
                    <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-white border-2 border-blue-600 group-hover:bg-blue-600 transition-colors"></div>
                    <div class="flex flex-wrap justify-between items-center mb-4">
                        <h3 class="text-xl font-bold">Technical Lead - Android</h3>
                        <span class="text-sm font-semibold text-slate-500 bg-slate-100 px-3 py-1 rounded-full">2022 — 2025</span>
                    </div>
                    <p class="text-blue-600 font-medium mb-4">Hashstudioz Technologies</p>
                    <p class="text-slate-600 leading-relaxed">
                        Led 6 production apps, managing 8+ engineers. Reduced resolution time by 40% and improved delivery consistency by 20% through rigorous refactoring and mentoring.
                    </p>
                </div>
                <!-- Item 2 -->
                <div class="group relative pl-8 border-l-2 border-blue-100 hover:border-blue-600 transition-colors">
                    <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-white border-2 border-blue-600 group-hover:bg-blue-600 transition-colors"></div>
                    <div class="flex flex-wrap justify-between items-center mb-4">
                        <h3 class="text-xl font-bold">Senior Software Engineer</h3>
                        <span class="text-sm font-semibold text-slate-500 bg-slate-100 px-3 py-1 rounded-full">2018 — 2020</span>
                    </div>
                    <p class="text-blue-600 font-medium mb-4">Mityung Infotech</p>
                    <p class="text-slate-600 leading-relaxed">
                        Migrated massive Java codebases to Kotlin (25% code reduction) and optimized Room database queries, boosting load performance by 15%.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- PROJECTS SECTION -->
    <section id="projects" class="py-24 bg-slate-900 text-white">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-center text-3xl font-bold mb-16">Featured Work</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="group bg-slate-800 rounded-2xl overflow-hidden border border-slate-700 hover:border-blue-500 transition">
                    <div class="h-48 bg-blue-600/20 flex items-center justify-center">
                        <i class="fas fa-calendar-check text-5xl text-blue-500"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Plann</h3>
                        <p class="text-slate-400 text-sm mb-4">Instagram scheduling platform with complex analytics and in-app purchase logic.</p>
                        <div class="flex space-x-2">
                            <span class="text-xs font-mono bg-slate-700 px-2 py-1 rounded">Kotlin</span>
                            <span class="text-xs font-mono bg-slate-700 px-2 py-1 rounded">API 21+</span>
                        </div>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="group bg-slate-800 rounded-2xl overflow-hidden border border-slate-700 hover:border-blue-500 transition">
                    <div class="h-48 bg-green-600/20 flex items-center justify-center">
                        <i class="fas fa-shopping-bag text-5xl text-green-500"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Bijnis</h3>
                        <p class="text-slate-400 text-sm mb-4">B2B wholesale marketplace application with high-traffic performance tuning.</p>
                        <div class="flex space-x-2">
                            <span class="text-xs font-mono bg-slate-700 px-2 py-1 rounded">MVVM</span>
                            <span class="text-xs font-mono bg-slate-700 px-2 py-1 rounded">Retrofit</span>
                        </div>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="group bg-slate-800 rounded-2xl overflow-hidden border border-slate-700 hover:border-blue-500 transition">
                    <div class="h-48 bg-red-600/20 flex items-center justify-center">
                        <i class="fas fa-video text-5xl text-red-500"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Medicosa</h3>
                        <p class="text-slate-400 text-sm mb-4">Healthcare app featuring real-time video consultations using Jitsi SDK integration.</p>
                        <div class="flex space-x-2">
                            <span class="text-xs font-mono bg-slate-700 px-2 py-1 rounded">WebRTC</span>
                            <span class="text-xs font-mono bg-slate-700 px-2 py-1 rounded">Jitsi</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-6">Get In Touch</h2>
            <p class="text-slate-500 mb-12">I'm currently open to Senior/Lead opportunities and technical consultations.</p>
            
            <div class="inline-flex flex-col md:flex-row items-center gap-6">
                <a href="mailto:anshuverma492@gmail.com" class="flex items-center space-x-3 px-6 py-4 bg-slate-50 rounded-2xl border border-slate-200 hover:bg-blue-50 hover:border-blue-200 transition">
                    <i class="fas fa-envelope text-blue-600 text-xl"></i>
                    <span class="font-semibold text-slate-800">anshuverma492@gmail.com</span>
                </a>
                <a href="https://linkedin.com/in/anshuverma492" target="_blank" class="flex items-center space-x-3 px-6 py-4 bg-slate-50 rounded-2xl border border-slate-200 hover:bg-blue-50 hover:border-blue-200 transition">
                    <i class="fab fa-linkedin text-blue-700 text-xl"></i>
                    <span class="font-semibold text-slate-800">LinkedIn Profile</span>
                </a>
            </div>
            
            <p class="mt-12 text-slate-400 text-sm">Lucknow, IN | Available for Remote Worldwide</p>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="py-10 bg-slate-50 border-t border-slate-200 text-center">
        <p class="text-slate-500 text-sm">© 2026 Anshu Verma. Built with Kotlin mindset & Tailwind CSS.</p>
    </footer>

</body>
</html>
