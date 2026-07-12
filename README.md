# stitchProjects
<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>ALEX.DEV | Student Portfolio</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<style>
        @import url('https://fonts.googleapis.com/gh/saadeghi/geist-font@master/style.css');
        @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@500&display=swap');

        :root {
            --primary-glow: rgba(0, 212, 255, 0.2);
        }

        body {
            background-color: #121414;
            color: #e2e2e2;
            overflow-x: hidden;
        }

        .glass-card {
            background: #121212;
            border: 1px solid rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(20px);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .glass-card:hover {
            border-color: rgba(0, 212, 255, 0.5);
            box-shadow: 0 0 40px var(--primary-glow);
            transform: translateY(-4px);
        }

        .text-glow {
            text-shadow: 0 0 10px rgba(0, 212, 255, 0.3);
        }

        .pulse-dot {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 212, 255, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(0, 212, 255, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 212, 255, 0); }
        }

        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
    </style>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface": "#121414",
                        "surface-bright": "#38393a",
                        "on-secondary-fixed-variant": "#474646",
                        "inverse-primary": "#00677e",
                        "error": "#ffb4ab",
                        "on-background": "#e2e2e2",
                        "surface-tint": "#3cd7ff",
                        "secondary-container": "#4a4949",
                        "surface-container-low": "#1a1c1c",
                        "on-error-container": "#ffdad6",
                        "primary-fixed": "#b4ebff",
                        "surface-container-highest": "#333535",
                        "on-secondary-container": "#bab8b7",
                        "on-primary": "#003642",
                        "tertiary-container": "#c5c2c2",
                        "secondary-fixed-dim": "#c9c6c5",
                        "error-container": "#93000a",
                        "on-surface-variant": "#bbc9cf",
                        "on-surface": "#e2e2e2",
                        "on-primary-fixed": "#001f27",
                        "inverse-surface": "#e2e2e2",
                        "on-secondary-fixed": "#1c1b1b",
                        "on-tertiary": "#313030",
                        "outline-variant": "#3c494e",
                        "primary-container": "#00d4ff",
                        "secondary-fixed": "#e5e2e1",
                        "tertiary-fixed": "#e5e2e1",
                        "on-tertiary-fixed": "#1c1b1b",
                        "surface-container-high": "#282a2b",
                        "secondary": "#c9c6c5",
                        "inverse-on-surface": "#2f3131",
                        "tertiary": "#e1dedd",
                        "on-secondary": "#313030",
                        "surface-container": "#1e2020",
                        "on-error": "#690005",
                        "surface-container-lowest": "#0c0f0f",
                        "background": "#121414",
                        "on-primary-fixed-variant": "#004e5f",
                        "tertiary-fixed-dim": "#c8c6c5",
                        "primary": "#a8e8ff",
                        "surface-variant": "#333535",
                        "primary-fixed-dim": "#3cd7ff",
                        "surface-dim": "#121414",
                        "on-primary-container": "#00586b",
                        "on-tertiary-fixed-variant": "#474646",
                        "outline": "#859398",
                        "on-tertiary-container": "#515050"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "stack-lg": "48px",
                        "stack-md": "16px",
                        "stack-sm": "8px",
                        "margin-mobile": "20px",
                        "container-max": "1200px",
                        "margin-desktop": "64px",
                        "gutter": "24px"
                    },
                    "fontFamily": {
                        "headline-md": ["Geist"],
                        "body-lg": ["Geist"],
                        "headline-lg-mobile": ["Geist"],
                        "display": ["Geist"],
                        "label-mono": ["JetBrains Mono"],
                        "headline-lg": ["Geist"],
                        "body-md": ["Geist"]
                    },
                    "fontSize": {
                        "headline-md": ["24px", { "lineHeight": "32px", "fontWeight": "600" }],
                        "body-lg": ["18px", { "lineHeight": "28px", "fontWeight": "400" }],
                        "headline-lg-mobile": ["32px", { "lineHeight": "40px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "display": ["64px", { "lineHeight": "72px", "letterSpacing": "-0.04em", "fontWeight": "700" }],
                        "label-mono": ["14px", { "lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "500" }],
                        "headline-lg": ["40px", { "lineHeight": "48px", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "body-md": ["16px", { "lineHeight": "24px", "fontWeight": "400" }]
                    }
                },
            },
        }
    </script>
</head>
<body class="bg-surface text-on-surface font-body-md selection:bg-primary-container selection:text-on-primary">
<!-- TopNavBar -->
<nav class="fixed top-0 w-full z-50 flex justify-between items-center px-margin-desktop h-20 max-w-container-max mx-auto bg-surface/80 backdrop-blur-xl border-b border-white/10 left-1/2 -translate-x-1/2">
<div class="font-headline-md text-headline-md font-bold text-primary tracking-tighter">ALEX.DEV</div>
<div class="hidden md:flex gap-8 items-center">
<a class="text-primary font-bold border-b-2 border-primary pb-1 font-body-md text-body-md" href="#">Projects</a>
<a class="text-on-surface-variant hover:text-on-surface transition-colors font-body-md text-body-md" href="#">Experience</a>
<a class="text-on-surface-variant hover:text-on-surface transition-colors font-body-md text-body-md" href="#">About</a>
<a class="text-on-surface-variant hover:text-on-surface transition-colors font-body-md text-body-md" href="#">Contact</a>
<button class="ml-4 bg-primary-container text-on-primary-container px-6 py-2 rounded-lg font-bold active:scale-95 duration-200 transition-all hover:brightness-110">Resume</button>
</div>
<button class="md:hidden text-primary">
<span class="material-symbols-outlined">menu</span>
</button>
</nav>
<main class="relative">
<!-- Hero Section -->
<section class="min-h-screen flex flex-col justify-center items-center text-center px-margin-mobile relative overflow-hidden pt-20">

<div class="relative z-10 max-w-4xl mx-auto">
<div class="flex items-center justify-center gap-2 mb-6">
<span class="w-2 h-2 rounded-full bg-primary-container pulse-dot"></span>
<span class="font-label-mono text-label-mono text-primary uppercase tracking-widest">Available for internships</span>
</div>
<h1 class="font-display text-display mb-6 tracking-tight leading-[1.1]">
                    Developing the <span class="text-primary-container text-glow">future</span>, <br/>one line at a time.
                </h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl mx-auto mb-10">
                    I'm Alex, a computer science student passionate about building performant web applications and exploring the intersection of design and technology.
                </p>
<div class="flex flex-col sm:flex-row gap-4 justify-center">
<a class="bg-primary-container text-on-primary-container px-8 py-4 rounded-xl font-bold text-lg hover:shadow-[0_0_20px_rgba(0,212,255,0.4)] transition-all flex items-center justify-center gap-2" href="#work">
                        View My Work
                        <span class="material-symbols-outlined">arrow_downward</span>
</a>
<a class="border border-outline-variant text-on-surface px-8 py-4 rounded-xl font-bold text-lg hover:bg-white/5 transition-all" href="#about">
                        Learn More
                    </a>
</div>
</div>
</section>
<!-- About Section -->
<section class="py-stack-lg max-w-container-max mx-auto px-margin-desktop" id="about">
<div class="grid md:grid-cols-2 gap-16 items-center">
<div class="order-2 md:order-1">
<span class="font-label-mono text-label-mono text-primary mb-4 block uppercase">The Journey</span>
<h2 class="font-headline-lg text-headline-lg mb-6">Bridging Theory and Practice</h2>
<div class="space-y-4 text-on-surface-variant font-body-md text-body-md leading-relaxed">
<p>
                            Currently pursuing my BS in Computer Science, I focus on transforming complex problems into intuitive digital experiences. My approach combines rigorous academic fundamentals with a pragmatic eye for modern UI/UX patterns.
                        </p>
<p>
                            When I'm not coding, you can find me analyzing open-source repositories, experimenting with creative coding, or documenting my learning journey through technical writing.
                        </p>
</div>
<div class="mt-8 flex gap-6">
<div class="flex flex-col">
<span class="text-primary font-bold text-2xl">15+</span>
<span class="text-xs uppercase text-on-surface-variant">Completed Projects</span>
</div>
<div class="flex flex-col">
<span class="text-primary font-bold text-2xl">4.0</span>
<span class="text-xs uppercase text-on-surface-variant">Major GPA</span>
</div>
<div class="flex flex-col">
<span class="text-primary font-bold text-2xl">3</span>
<span class="text-xs uppercase text-on-surface-variant">Active Collaborations</span>
</div>
</div>
</div>
<div class="order-1 md:order-2">
<div class="relative group">
<div class="absolute -inset-1 bg-gradient-to-r from-primary-container to-blue-600 rounded-2xl blur opacity-25 group-hover:opacity-50 transition duration-1000 group-hover:duration-200"></div>
<div class="relative aspect-square overflow-hidden rounded-2xl glass-card">
<img class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" data-alt="A professional high-end portrait of a young developer in a dark studio setting, soft blue rim lighting highlighting the silhouette, sharp focus, cinematic atmosphere, representing technical competence and modern professional identity." src="https://lh3.googleusercontent.com/aida-public/AB6AXuClYdeziVlaGfIO_PQgW6zIWbkdwpmnoQFbZamprMlvY7NVyhXvpHKiHXQCt3d5X2uuj3rlkpDBHVZAYXUoUyNPTxx_chgKolV9rXoTrQYuKmBgUVIKrZa_psMQ228txYRnr-6juou-55xRU1wTJLqoqfmhGcvriKZ9zmW_EHVzRDUsCgP7q0XNTQeeMoJv5eqjhFFSdb9cUKPdOutc_iI0u-3MNmFScSeUVVemDSUoDh9gmWqmjkHSal4v7v9tsqD0zrIWz-uUdrQm"/>
</div>
</div>
</div>
</div>
</section>
<!-- Assignments Grid -->
<section class="py-stack-lg bg-surface-container-lowest" id="work">
<div class="max-w-container-max mx-auto px-margin-desktop">
<div class="flex flex-col md:flex-row justify-between items-end mb-12 gap-6">
<div class="max-w-xl">
<span class="font-label-mono text-label-mono text-primary mb-4 block uppercase">Assignments &amp; Labs</span>
<h2 class="font-headline-lg text-headline-lg">Selected Projects</h2>
</div>
<div class="flex gap-2">
<span class="px-4 py-2 rounded-full bg-white/5 border border-white/10 text-xs font-label-mono">ALL</span>
<span class="px-4 py-2 rounded-full bg-white/5 border border-white/10 text-xs font-label-mono opacity-50">WEB</span>
<span class="px-4 py-2 rounded-full bg-white/5 border border-white/10 text-xs font-label-mono opacity-50">DATA</span>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<!-- Project Card 1 -->
<div class="glass-card rounded-2xl overflow-hidden flex flex-col h-full group">
<div class="h-48 overflow-hidden relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" data-alt="A clean screenshot of a minimalist dashboard UI with dark glassmorphism effects, showing financial charts and data visualization in electric blue tones, high contrast, professional software engineering presentation." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA5KpKJgNlOOrvtlvAF7fVJGcU3OTnfTzYuB1QPQ5DDA0_wk7R0lLXJjWIP5MK7MMxBfN9lRGrcmdMBdqTdZJ4T6Ikx6ljO_L-6clOq1OK6bFDYWcSuoF_LF8FfZJDiC9F1feaGhE8K3BpAzyL2TzlrSj42nRlnPShgevCVLmlec2UbtGZLAwWn3-bGh0Obyh0AFBGnmo6T49CqnNK54-iHlRvOltekXSmsEg-AifQGoH6Yl0EvlooFxIE8FxN8ba_Bb5dZ3VNUTUKo"/>
</div>
<div class="p-8 flex flex-col flex-grow">
<div class="flex gap-2 mb-4">
<span class="bg-white/10 px-2 py-1 rounded text-[10px] font-label-mono uppercase tracking-wider text-primary">React</span>
<span class="bg-white/10 px-2 py-1 rounded text-[10px] font-label-mono uppercase tracking-wider text-primary">Tailwind</span>
</div>
<h3 class="font-headline-md text-headline-md mb-3">CryptoPulse Dashboard</h3>
<p class="text-on-surface-variant font-body-md mb-6 flex-grow">
                                Real-time cryptocurrency monitoring tool utilizing WebSockets for live price updates and Framer Motion for smooth transitions.
                            </p>
<a class="inline-flex items-center gap-2 text-primary-container font-bold group/link" href="#">
                                View Details
                                <span class="material-symbols-outlined transition-transform group-hover/link:translate-x-1">arrow_forward</span>
</a>
</div>
</div>
<!-- Project Card 2 -->
<div class="glass-card rounded-2xl overflow-hidden flex flex-col h-full group">
<div class="h-48 overflow-hidden relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" data-alt="Abstract 3D representation of data structures and algorithms, nodes and connecting lines in a dark space glowing with electric blue neon light, sophisticated aesthetic for computer science portfolio." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDJAIR7_FNufhW8Cz7YMFhr7kNsEt_WTT0Y7wRKoGyse15WnzzrZYCYfJs3gKDCzFlExZv8xcMPv50Bles7n4XglXSc4tmfr8KPgzqht4qliv31AXc3783jtEep-na-E1-zsP_PtehfSAfInrWQfmTr1T7EmuQB6CJEIoaWIo7qotfmJ43iz1mpXmCpaIIPEi25j0c8sMElaCTnp2NRnIQMlO3k3Z-qdzbx1M-c3LKz8Hrw1ZGt2wtCaoXkykzAwmNN49BNRiKwQl0S"/>
</div>
<div class="p-8 flex flex-col flex-grow">
<div class="flex gap-2 mb-4">
<span class="bg-white/10 px-2 py-1 rounded text-[10px] font-label-mono uppercase tracking-wider text-primary">Python</span>
<span class="bg-white/10 px-2 py-1 rounded text-[10px] font-label-mono uppercase tracking-wider text-primary">AI</span>
</div>
<h3 class="font-headline-md text-headline-md mb-3">NeuralPath Finder</h3>
<p class="text-on-surface-variant font-body-md mb-6 flex-grow">
                                A visualizer for A* and Dijkstra's algorithms applied to dynamic environments with real-time obstacle generation.
                            </p>
<a class="inline-flex items-center gap-2 text-primary-container font-bold group/link" href="#">
                                View Details
                                <span class="material-symbols-outlined transition-transform group-hover/link:translate-x-1">arrow_forward</span>
</a>
</div>
</div>
<!-- Project Card 3 -->
<div class="glass-card rounded-2xl overflow-hidden flex flex-col h-full group">
<div class="h-48 overflow-hidden relative">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" data-alt="A modern mobile app interface design on a dark phone mockup, featuring sleek typography and vibrant teal and blue accents, UI/UX focus, clean layout with card-based navigation." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA9Vzt_euUgeCoApyIXMsMWOMoieAhikJql4vkl8ZIoVZQn28Dwf4qGhcYf9SphKDYvsECwgBAAOI1e5nv9YHtkiglDC_Rh9suFEcPuafCmb40UVj5URJ2cQrh0kwqkj-NU6qMdJnCEMqojnvUZbfKjS-dpNFoFD5TzI0nsuPmtkAqUdK9ug4Ba1D87HDVmpgcVF7sEJdse_wisLzK9K2JTzr7M36tFK1mRgjRaRH1h4LY6MLVwthl4dXjSQM5mVdktfrlSIfgUbg2W"/>
</div>
<div class="p-8 flex flex-col flex-grow">
<div class="flex gap-2 mb-4">
<span class="bg-white/10 px-2 py-1 rounded text-[10px] font-label-mono uppercase tracking-wider text-primary">TypeScript</span>
<span class="bg-white/10 px-2 py-1 rounded text-[10px] font-label-mono uppercase tracking-wider text-primary">Node.js</span>
</div>
<h3 class="font-headline-md text-headline-md mb-3">SyncTask Mobile</h3>
<p class="text-on-surface-variant font-body-md mb-6 flex-grow">
                                End-to-end encrypted task management system for distributed teams, focusing on security and offline-first availability.
                            </p>
<a class="inline-flex items-center gap-2 text-primary-container font-bold group/link" href="#">
                                View Details
                                <span class="material-symbols-outlined transition-transform group-hover/link:translate-x-1">arrow_forward</span>
</a>
</div>
</div>
</div>
</div>
</section>
<!-- CTA / Connect -->
<section class="py-stack-lg max-w-container-max mx-auto px-margin-desktop text-center">
<div class="glass-card p-12 md:p-20 rounded-[2rem] relative overflow-hidden">
<div class="absolute inset-0 bg-gradient-to-tr from-primary/10 to-transparent pointer-events-none"></div>
<h2 class="font-headline-lg text-headline-lg mb-6 relative z-10">Have a project in mind?</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-10 max-w-xl mx-auto relative z-10">
                    I'm currently looking for summer internship opportunities for 2025. Let's build something extraordinary together.
                </p>
<a class="inline-flex items-center gap-3 bg-primary text-on-primary px-10 py-5 rounded-2xl font-extrabold text-xl hover:scale-105 transition-all duration-300 relative z-10 group" href="mailto:hello@alex.dev">
                    Get In Touch
                    <span class="material-symbols-outlined">mail</span>
</a>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full py-stack-lg px-margin-desktop flex flex-col md:flex-row justify-between items-center max-w-container-max mx-auto border-t border-white/10 bg-surface-container-lowest">
<div class="flex flex-col items-center md:items-start gap-2 mb-8 md:mb-0">
<div class="font-headline-md text-headline-md text-primary font-bold">ALEX.DEV</div>
<p class="text-on-surface-variant font-body-md text-body-md">© 2024 Alex Portfolio. Built for the future.</p>
</div>
<div class="flex gap-8">
<a class="text-on-surface-variant hover:text-primary transition-colors font-body-md text-body-md opacity-80 hover:opacity-100" href="#">Github</a>
<a class="text-on-surface-variant hover:text-primary transition-colors font-body-md text-body-md opacity-80 hover:opacity-100" href="#">LinkedIn</a>
<a class="text-on-surface-variant hover:text-primary transition-colors font-body-md text-body-md opacity-80 hover:opacity-100" href="#">Twitter</a>
<a class="text-on-surface-variant hover:text-primary transition-colors font-body-md text-body-md opacity-80 hover:opacity-100" href="#">Email</a>
</div>
</footer>
<script>
        // Micro-interactions for scrolling
        document.addEventListener('DOMContentLoaded', () => {
            const observerOptions = {
                threshold: 0.1
            };

            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('opacity-100', 'translate-y-0');
                        entry.target.classList.remove('opacity-0', 'translate-y-10');
                    }
                });
            }, observerOptions);

            document.querySelectorAll('section').forEach(section => {
                section.classList.add('transition-all', 'duration-1000', 'opacity-0', 'translate-y-10');
                observer.observe(section);
            });
        });

        // Mouse glow effect for cards
        document.querySelectorAll('.glass-card').forEach(card => {
            card.addEventListener('mousemove', (e) => {
                const rect = card.getBoundingClientRect();
                const x = e.clientX - rect.left;
                const y = e.clientY - rect.top;
                card.style.setProperty('--mouse-x', `${x}px`);
                card.style.setProperty('--mouse-y', `${y}px`);
            });
        });
    </script>
</body></html>
