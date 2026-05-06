
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anshu Verma | Senior Android Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .hero-gradient { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); }
        .glass-card { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .skill-tag { transition: all 0.3s ease; }
        .skill-tag:hover { transform: translateY(-3px); background-color: #3b82f6; color: white; }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="text-xl font-bold tracking-tight text-blue-600">AV.DEV</span>
            <div class="hidden md:flex space-x-8 font-medium text-slate-600">
                <a href="#about" class="hover:text-blue-600 transition">About</a>
                <a href="#experience" class="hover:text-blue-600 transition">Experience</a>
                <a href="#projects" class="hover:text-blue-600 transition">Projects</a>
                <a href="#contact" class="bg-blue-600 text-white px-5 py-2 rounded-full hover:bg-blue-700 transition">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-gradient min-h-screen flex items-center pt-20">
        <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div class="animate-fade-in-up">
                <h2 class="text-blue-400 font-semibold tracking-widest uppercase text-sm mb-4">Senior Android Developer</h2>
                <h1 class="text-5xl md:text-7xl font-bold text-white mb-6 leading-tight">Anshu Verma</h1>
                <p class="text-slate-400 text-lg mb-8 leading-relaxed max-w-lg">
                    Building & scaling high-performance Android applications for <span class="text-white">10,000+ users</span>. Specialist in Kotlin, Clean Architecture, and technical leadership.
                </p>
                <div class="flex space-x-4">
                    <a href="#projects" class="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-blue-700 transition">View My Work</a>
                    <a href="#experience" class="border border-slate-700 text-white px-8 py-3 rounded-lg font-semibold hover:bg-slate-800 transition">Experience</a>
                </div>
            </div>
            <div class="hidden md:flex justify-center">
                <div class="relative">
                    <div class="absolute -inset-4 bg-blue-500/20 blur-2xl rounded-full"></div>
                    <img src="https://images.unsplash.com/photo-1605379399642-870262d3d051?auto=format&fit=crop&q=80&w=500" alt="Work Setup" class="relative rounded-2xl shadow-2xl grayscale hover:grayscale-0 transition duration-500">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-8">Engineering with Precision</h2>
            <p class="text-slate-600 text-xl leading-relaxed">
                With over <span class="text-blue-600 font-bold">9 years</span> in the Android ecosystem, I bridge the gap between complex technical requirements and seamless user experiences. From migrating legacy Java codebases to leading remote engineering teams, my focus is on <span class="font-semibold">reliability, scalability, and clean code.</span>
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="py-24 bg-slate-50">
        <div class="max-w-6xl mx-auto px-6">
            <h3 class="text-sm font-bold text-blue-600 uppercase tracking-widest mb-12 text-center">Technical Arsenal</h3>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <!-- Skill Groups -->
                <div class="p-6 bg-white rounded-xl shadow-sm border border-slate-100">
                    <h4 class="font-bold mb-4 text-slate-800">Languages</h4>
                    <div class="flex flex-wrap gap-2">
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Kotlin</span>
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Java</span>
                    </div>
                </div>
                <div class="p-6 bg-white rounded-xl shadow-sm border border-slate-100">
                    <h4 class="font-bold mb-4 text-slate-800">Frameworks</h4>
                    <div class="flex flex-wrap gap-2">
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Android SDK</span>
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Jetpack</span>
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Compose</span>
                    </div>
                </div>
                <div class="p-6 bg-white rounded-xl shadow-sm border border-slate-100">
                    <h4 class="font-bold mb-4 text-slate-800">Architecture</h4>
                    <div class="flex flex-wrap gap-2">
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">MVVM</span>
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Clean Arch</span>
                    </div>
                </div>
                <div class="p-6 bg-white rounded-xl shadow-sm border border-slate-100">
                    <h4 class="font-bold mb-4 text-slate-800">Data & Cloud</h4>
                    <div class="flex flex-wrap gap-2">
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Room</span>
                        <span class="skill-tag px-3 py-1 bg-slate-100 rounded text-sm">Firebase</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-6">
            <h3 class="text-3xl font-bold mb-16 text-center">Professional Journey</h3>
            
            <div class="space-y-12 border-l-2 border-slate-100 ml-4 pl-8 relative">
                <!-- Hashstudioz -->
                <div class="relative">
                    <div class="absolute -left-11 top-1 w-5 h-5 bg-blue-600 rounded-full"></div>
                    <div class="mb-2 flex justify-between items-center flex-wrap">
                        <h4 class="text-xl font-bold text-slate-900">Technical Lead - Android</h4>
                        <span class="text-slate-500 font-medium">Feb 2022 – Apr 2025</span>
                    </div>
                    <p class="text-blue-600 font-semibold mb-4">Hashstudioz Technologies</p>
                    <ul class="text-slate-600 space-y-3 list-disc ml-4">
                        <li>Led development for 6 production apps serving 10,000+ monthly users.</li>
                        <li>Reduced crash rates by 25% through performance optimization.</li>
                        <li>Mentored a team of 8, improving delivery speed by 20%.</li>
                    </ul>
                </div>

                <!-- Alps Softech -->
                <div class="relative">
                    <div class="absolute -left-11 top-1 w-5 h-5 bg-slate-300 rounded-full"></div>
                    <div class="mb-2 flex justify-between items-center flex-wrap">
                        <h4 class="text-xl font-bold text-slate-900">Android Developer</h4>
                        <span class="text-slate-500 font-medium">Aug 2020 – Jan 2022</span>
                    </div>
                    <p class="text-blue-600 font-semibold mb-4">Alps Softech Solutions</p>
                    <ul class="text-slate-600 space-y-3 list-disc ml-4">
                        <li>Developed a UAE-based driving school app with 500+ active users.</li>
                        <li>Increased API reliability, reducing crashes by 20%.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-24 bg-slate-900 text-white">
        <div class="max-w-6xl mx-auto px-6">
            <h3 class="text-3xl font-bold mb-16 text-center">Key Projects</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="glass-card p-8 rounded-2xl group hover:border-blue-500 transition">
                    <div class="w-12 h-12 bg-blue-600/20 rounded-lg flex items-center justify-center text-blue-400 mb-6 group-hover:bg-blue-600 group-hover:text-white transition">
                        <i class="fab fa-instagram text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Plann</h4>
                    <p class="text-slate-400 mb-6">Instagram scheduling platform processing thousands of posts daily with deep analytics integration.</p>
                    <div class="flex gap-2">
                        <span class="text-xs font-bold px-2 py-1 bg-white/10 rounded">Kotlin</span>
                        <span class="text-xs font-bold px-2 py-1 bg-white/10 rounded">Analytics</span>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="glass-card p-8 rounded-2xl group hover:border-blue-500 transition">
                    <div class="w-12 h-12 bg-blue-600/20 rounded-lg flex items-center justify-center text-blue-400 mb-6 group-hover:bg-blue-600 group-hover:text-white transition">
                        <i class="fas fa-shopping-cart text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Bijnis</h4>
                    <p class="text-slate-400 mb-6">B2B wholesale sourcing platform. Led the Java to Kotlin migration to improve maintainability.</p>
                    <div class="flex gap-2">
                        <span class="text-xs font-bold px-2 py-1 bg-white/10 rounded">MVVM</span>
                        <span class="text-xs font-bold px-2 py-1 bg-white/10 rounded">B2B</span>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="glass-card p-8 rounded-2xl group hover:border-blue-500 transition">
                    <div class="w-12 h-12 bg-blue-600/20 rounded-lg flex items-center justify-center text-blue-400 mb-6 group-hover:bg-blue-600 group-hover:text-white transition">
                        <i class="fas fa-heartbeat text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3">Medicosa</h4>
                    <p class="text-slate-400 mb-6">Health-tech app featuring video consultations and appointment management using Jitsi SDK.</p>
                    <div class="flex gap-2">
                        <span class="text-xs font-bold px-2 py-1 bg-white/10 rounded">Jitsi</span>
                        <span class="text-xs font-bold px-2 py-1 bg-white/10 rounded">Video SDK</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h3 class="text-3xl font-bold mb-4">Let's Build Something Together</h3>
            <p class="text-slate-600 mb-12">Available for senior leadership roles and architectural consulting.</p>
            
            <div class="grid md:grid-cols-3 gap-6 mb-12">
                <a href="mailto:anshuverma492@gmail.com" class="p-6 bg-slate-50 rounded-xl hover:bg-blue-50 transition border border-slate-100">
                    <i class="fas fa-envelope text-blue-600 text-2xl mb-4"></i>
                    <p class="font-medium">Email Me</p>
                </a>
                <a href="https://linkedin.com/in/anshuverma492" class="p-6 bg-slate-50 rounded-xl hover:bg-blue-50 transition border border-slate-100">
                    <i class="fab fa-linkedin text-blue-600 text-2xl mb-4"></i>
                    <p class="font-medium">LinkedIn</p>
                </a>
                <a href="tel:+917409719047" class="p-6 bg-slate-50 rounded-xl hover:bg-blue-50 transition border border-slate-100">
                    <i class="fas fa-phone text-blue-600 text-2xl mb-4"></i>
                    <p class="font-medium">Contact</p>
                </a>
            </div>
            
            <p class="text-slate-400 text-sm">Lucknow, India • Remote Friendly</p>
        </div>
    </section>

    <footer class="py-8 border-t border-slate-100 text-center text-slate-500 text-sm">
        &copy; 2026 Anshu Verma. Built for the modern Android ecosystem.
    </footer>

</body>
</html>
