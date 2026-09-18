# lenovo-leap-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DRISHTI SPECS— AI-Powered Smart Glass for Farmers</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#1b4332',
                            green: '#2d6a4f',
                            light: '#d8f3dc',
                            sand: '#fefae0',
                            accent: '#f26419'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Inter', sans-serif; }
        .hero-gradient { background: linear-gradient(135deg, #1b4332 0%, #2d6a4f 100%); }
        .feature-card:hover { transform: translateY(-4px); transition: all 0.3s ease; }
        .orange-glow { filter: drop-shadow(0 0 8px rgba(242, 100, 25, 0.4)); }
    </style>
</head>
<body class="bg-[#fcf9f2] text-gray-900">

    <!-- Navigation -->
    <nav class="flex items-center justify-between px-12 py-6 max-w-7xl mx-auto">
        <div class="flex items-center gap-2">
            <i class="fa-solid fa-glasses text-brand-green text-2xl"></i>
            <span class="text-2xl font-black tracking-tighter text-brand-dark uppercase">DRISHTI SPECS</span>
        </div>
        <div class="hidden md:flex gap-10 text-sm font-bold uppercase tracking-widest text-gray-600">
            <a href="#features" class="hover:text-brand-accent transition-colors">Features</a>
            <a href="#how-it-works" class="hover:text-brand-accent transition-colors">Technology</a>
            <a href="#specifications" class="hover:text-brand-accent transition-colors">Impact</a>
        </div>
        <button class="bg-brand-accent hover:bg-orange-700 text-white px-8 py-3 rounded-sm font-black uppercase tracking-widest transition-all shadow-lg">
            Pre-order
        </button>
    </nav>

    <!-- Hero Section -->
    <header class="hero-gradient text-white px-12 pt-20 pb-28 overflow-hidden relative border-b-8 border-brand-accent">
        <div class="max-w-7xl mx-auto grid lg:grid-cols-2 items-center gap-16 relative z-10">
            <div>
                <div class="inline-flex items-center gap-2 bg-brand-accent/20 border border-brand-accent/30 px-4 py-1.5 rounded-sm text-sm font-black uppercase tracking-widest mb-8 text-brand-accent">
                    <span class="relative flex h-2 w-2">
                      <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-brand-accent opacity-75"></span>
                      <span class="relative inline-flex rounded-full h-2 w-2 bg-brand-accent"></span>
                    </span>
                    Next-Gen Agri-Tech
                </div>
                <h1 class="text-7xl font-black leading-[1.1] mb-8 uppercase italic tracking-tighter">
                    Empowering Farmers with <span class="text-brand-accent">AI-Powered</span> Vision
                </h1>
                <p class="text-xl text-brand-light/90 mb-10 max-w-xl leading-relaxed font-medium">
                    Detect diseases, translate dialects, and stay protected with the ultimate field companion. Rugged, waterproof, and built for the hands that feed the world.
                </p>
                <div class="flex flex-wrap gap-6">
                    <button class="bg-brand-accent hover:bg-orange-600 text-white px-10 py-5 rounded-sm font-black uppercase tracking-widest text-lg transition-all shadow-2xl flex items-center gap-3">
                        Join the waitlist <i class="fa-solid fa-arrow-right"></i>
                    </button>
                    <button onclick="document.getElementById('interactive-demo').scrollIntoView({behavior: 'smooth'})" class="bg-white/10 hover:bg-white/20 backdrop-blur-sm text-white px-10 py-5 rounded-sm font-black uppercase tracking-widest text-lg transition-all flex items-center gap-3 border border-white/20">
                        <i class="fa-solid fa-play text-brand-accent"></i> Watch in Action
                    </button>
                </div>
            </div>
            <div class="relative lg:h-[600px] flex items-center">
                <div class="absolute inset-0 bg-brand-accent/10 blur-[120px] rounded-full"></div>
                <img class="rounded-sm shadow-2xl w-full h-[500px] object-cover border-4 border-white/10" src="https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_c284767f87_11bf2c09d87e40dc.png" alt="DRISHTI SPECS Smart Glasses" />
            </div>
        </div>
    </header>

    <!-- Interactive Demo Section -->
    <section id="interactive-demo" class="py-32 px-12 bg-[#fcf9f2]">
        <div class="max-w-7xl mx-auto">
            <div class="grid lg:grid-cols-3 gap-16 items-start">
                <div class="lg:sticky lg:top-10">
                    <div class="inline-flex items-center gap-2 bg-brand-dark/5 px-4 py-1.5 rounded-sm text-sm font-black uppercase tracking-widest mb-8 text-brand-dark">
                        Experience
                    </div>
                    <h2 class="text-5xl font-black text-brand-dark mb-8 uppercase italic tracking-tighter leading-none">
                        See the Field Through <span class="text-brand-accent">DRISHTI SPECS</span>
                    </h2>
                    <p class="text-gray-600 text-lg font-medium leading-relaxed mb-10">
                        Our augmented reality interface doesn't just show you data—it helps you see the invisible. Toggle between modes to see how drishti specs identifies risks in real-time.
                    </p>
                    <div class="space-y-4">
                        <button onclick="toggleDemo('disease')" id="btn-disease" class="demo-btn active w-full flex items-center justify-between p-6 bg-brand-dark text-white rounded-sm font-black uppercase tracking-widest transition-all">
                            <span>Disease Detection</span>
                            <i class="fa-solid fa-virus-slash"></i>
                        </button>
                        <button onclick="toggleDemo('soil')" id="btn-soil" class="demo-btn w-full flex items-center justify-between p-6 bg-white border-2 border-brand-dark/10 text-brand-dark rounded-sm font-black uppercase tracking-widest transition-all hover:border-brand-dark">
                            <span>Soil Analysis</span>
                            <i class="fa-solid fa-seedling"></i>
                        </button>
                        <button onclick="toggleDemo('translation')" id="btn-translation" class="demo-btn w-full flex items-center justify-between p-6 bg-white border-2 border-brand-dark/10 text-brand-dark rounded-sm font-black uppercase tracking-widest transition-all hover:border-brand-dark">
                            <span>Voice Translation</span>
                            <i class="fa-solid fa-language"></i>
                        </button>
                    </div>
                </div>

                <div class="lg:col-span-2">
                    <div class="relative bg-black rounded-sm shadow-2xl overflow-hidden aspect-video group">
                        <!-- HUD Elements -->
                        <div class="absolute inset-0 z-20 pointer-events-none p-8 flex flex-col justify-between">
                            <div class="flex justify-between items-start">
                                <div class="bg-black/40 backdrop-blur-md p-4 border-l-4 border-brand-accent">
                                    <div class="text-[10px] font-black text-brand-accent uppercase tracking-[0.2em] mb-1">Status: Scanning</div>
                                    <div id="demo-label" class="text-xl font-black text-white uppercase italic">Yellow Rust Detection</div>
                                </div>
                                <div class="flex gap-4">
                                    <div class="bg-black/40 backdrop-blur-md p-4 text-right">
                                        <div class="text-[10px] font-black text-white/60 uppercase tracking-[0.2em] mb-1">Battery</div>
                                        <div class="text-lg font-black text-white">92%</div>
                                    </div>
                                </div>
                            </div>
                            
                            <!-- Reticle -->
                            <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-48 h-48 border border-white/20 rounded-full flex items-center justify-center">
                                <div class="w-2 h-2 bg-brand-accent rounded-full animate-pulse shadow-[0_0_15px_#f26419]"></div>
                                <div class="absolute inset-0 border-2 border-brand-accent/30 rounded-full border-t-transparent animate-spin duration-[3000ms]"></div>
                            </div>

                            <div class="flex justify-between items-end">
                                <div class="bg-black/40 backdrop-blur-md p-6 max-w-sm border-b-4 border-brand-accent">
                                    <div id="demo-advice" class="text-white font-medium text-sm italic">
                                        "Detected Yellow Rust in 12% of the crop. Recommended treatment: Propiconazole spray at 0.1% concentration."
                                    </div>
                                </div>
                                <div class="flex flex-col items-end gap-2">
                                    <div class="w-32 h-1 bg-white/20 overflow-hidden">
                                        <div class="w-2/3 h-full bg-brand-accent"></div>
                                    </div>
                                    <div class="text-[10px] font-black text-white uppercase tracking-[0.2em]">Processing Stream</div>
                                </div>
                            </div>
                        </div>

                        <!-- Video/Image Layer -->
                        <div id="demo-visuals" class="relative w-full h-full">
                            <img id="demo-img" class="w-full h-full object-cover opacity-80" src="https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_b52634f5f7_4cc6b670b69ccd2c.png" alt="Field POV" />
                            <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent"></div>
                        </div>
                    </div>
                    
                    <div class="mt-8 grid grid-cols-3 gap-6">
                        <div class="p-6 bg-white border border-brand-dark/5 rounded-sm">
                            <div class="text-3xl font-black text-brand-dark mb-1">0.4s</div>
                            <div class="text-[10px] font-black text-gray-400 uppercase tracking-widest">Inference Speed</div>
                        </div>
                        <div class="p-6 bg-white border border-brand-dark/5 rounded-sm">
                            <div class="text-3xl font-black text-brand-dark mb-1">4K</div>
                            <div class="text-[10px] font-black text-gray-400 uppercase tracking-widest">Sensor Res</div>
                        </div>
                        <div class="p-6 bg-white border border-brand-dark/5 rounded-sm">
                            <div class="text-3xl font-black text-brand-dark mb-1">Off</div>
                            <div class="text-[10px] font-black text-gray-400 uppercase tracking-widest">Cloud Sync</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <script>
        function toggleDemo(mode) {
            const label = document.getElementById('demo-label');
            const advice = document.getElementById('demo-advice');
            const img = document.getElementById('demo-img');
            const buttons = document.querySelectorAll('.demo-btn');
            
            buttons.forEach(btn => {
                btn.classList.remove('active', 'bg-brand-dark', 'text-white');
                btn.classList.add('bg-white', 'text-brand-dark');
            });

            const activeBtn = document.getElementById('btn-' + mode);
            activeBtn.classList.remove('bg-white', 'text-brand-dark');
            activeBtn.classList.add('active', 'bg-brand-dark', 'text-white');

            if (mode === 'disease') {
                label.innerText = 'Yellow Rust Detection';
                advice.innerText = '"Detected Yellow Rust in 12% of the crop. Recommended treatment: Propiconazole spray at 0.1% concentration."';
                img.src = 'https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_90ee56b535_03d9b3538f38eeac.png';
            } else if (mode === 'soil') {
                label.innerText = 'Nitrogen Analysis';
                advice.innerText = '"Soil Nitrogen levels at 1.4%. Below optimal for current growth stage. Apply urea (46-0-0) at 50kg/acre."';
                img.src = 'https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_5639fa3d70_be599948e6b1a6b6.png';
            } else if (mode === 'translation') {
                label.innerText = 'Bhojpuri Translation';
                advice.innerText = '"Translation active: Farmer says they noticed waterlogging in the north corner. Advice: Improve drainage to prevent root rot."';
                img.src = 'https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_93b70e06bb_f059988cb2cb12d3.png';
            }
        }
    </script>

    <!-- Features Grid -->
    <section id="features" class="py-32 px-12 bg-white">
        <div class="max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row items-end justify-between mb-20 gap-8">
                <div class="max-w-2xl">
                    <h2 class="text-5xl font-black text-brand-dark mb-6 uppercase italic tracking-tighter">Engineered for the <span class="text-brand-accent">Hardest Work</span></h2>
                    <p class="text-gray-600 text-lg font-medium leading-relaxed">We took the most advanced AI and bone-conduction tech and wrapped it in a frame that survives heat, dust, and rain.</p>
                </div>
                <div class="flex gap-4">
                    <div class="p-4 bg-brand-sand border-2 border-brand-dark flex flex-col items-center">
                        <span class="text-3xl font-black text-brand-dark">IP68</span>
                        <span class="text-[10px] font-bold uppercase tracking-widest">Waterproof</span>
                    </div>
                    <div class="p-4 bg-brand-sand border-2 border-brand-dark flex flex-col items-center">
                        <span class="text-3xl font-black text-brand-dark">12h</span>
                        <span class="text-[10px] font-bold uppercase tracking-widest">Battery</span>
                    </div>
                </div>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Feature 1 -->
                <div class="feature-card p-10 bg-brand-dark text-white rounded-sm group">
                    <div class="w-16 h-16 bg-brand-accent flex items-center justify-center mb-8 transform -rotate-3 group-hover:rotate-0 transition-transform">
                        <i class="fa-solid fa-microscope text-white text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase italic tracking-tight">Eye-Level Micro-Camera</h3>
                    <p class="text-brand-light/70 text-sm leading-relaxed font-medium">
                        Captures diseased crop leaves, seed packets, and soil patches from your perspective for instant AI diagnosis.
                    </p>
                </div>

                <!-- Feature 2 -->
                <div class="feature-card p-10 bg-brand-sand border-4 border-brand-dark rounded-sm group">
                    <div class="w-16 h-16 bg-brand-dark flex items-center justify-center mb-8 transform rotate-3 group-hover:rotate-0 transition-transform">
                        <i class="fa-solid fa-fingerprint text-brand-accent text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase italic tracking-tight">Tactile Frame Trigger</h3>
                    <p class="text-gray-700 text-sm leading-relaxed font-medium">
                        Oversized waterproof button easily clickable while wearing thick field gloves. No tiny touch sensors.
                    </p>
                </div>

                <!-- Feature 3 -->
                <div class="feature-card p-10 bg-brand-dark text-white rounded-sm group">
                    <div class="w-16 h-16 bg-brand-accent flex items-center justify-center mb-8 transform -rotate-3 group-hover:rotate-0 transition-transform">
                        <i class="fa-solid fa-ear-listen text-white text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase italic tracking-tight">Dialect Translation</h3>
                    <p class="text-brand-light/70 text-sm leading-relaxed font-medium">
                        Real-time translation for Awadhi, Bhojpuri, and Hindi. Bone-conduction keeps ears open for safety.
                    </p>
                </div>

                <!-- Feature 4 -->
                <div class="feature-card p-10 bg-brand-sand border-4 border-brand-dark rounded-sm group">
                    <div class="w-16 h-16 bg-brand-dark flex items-center justify-center mb-8 transform rotate-3 group-hover:rotate-0 transition-transform">
                        <i class="fa-solid fa-sun text-brand-accent text-3xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase italic tracking-tight">UV Visor Protection</h3>
                    <p class="text-gray-700 text-sm leading-relaxed font-medium">
                        UV Tinted Lenses and Visor Brim Protection. Protects from harsh field glare during long outdoor hours.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="py-32 px-12 bg-brand-dark relative overflow-hidden">
        <div class="absolute top-0 right-0 w-1/2 h-full opacity-10 pointer-events-none">
            <div class="grid grid-cols-10 h-full">
                <div class="border-r border-white/20 h-full"></div>
                <div class="border-r border-white/20 h-full"></div>
                <div class="border-r border-white/20 h-full"></div>
                <div class="border-r border-white/20 h-full"></div>
                <div class="border-r border-white/20 h-full"></div>
            </div>
        </div>
        
        <div class="max-w-7xl mx-auto relative z-10">
            <div class="grid lg:grid-cols-2 gap-20 items-center">
                <div class="space-y-12">
                    <div>
                        <h2 class="text-5xl font-black text-white mb-6 uppercase italic tracking-tighter">AI Knowledge <br/><span class="text-brand-accent">In Every Grain</span></h2>
                        <p class="text-brand-light/80 text-xl font-medium leading-relaxed">Integrated with massive agricultural databases, KisanLens understands your field better than any manual.</p>
                    </div>
                    
                    <div class="space-y-8">
                        <div class="flex gap-6 items-start">
                            <div class="text-4xl font-black text-brand-accent opacity-50">01</div>
                            <div>
                                <h4 class="text-xl font-bold text-white uppercase tracking-tight mb-2 italic">Capture & Identify</h4>
                                <p class="text-brand-light/60 text-sm">Target any leaf or seed. The Eye-Level Micro-Camera captures high-resolution data for immediate processing.</p>
                            </div>
                        </div>
                        <div class="flex gap-6 items-start">
                            <div class="text-4xl font-black text-brand-accent opacity-50">02</div>
                            <div>
                                <h4 class="text-xl font-bold text-white uppercase tracking-tight mb-2 italic">Instant Diagnosis</h4>
                                <p class="text-brand-light/60 text-sm">On-device AI identifies 500+ pests and diseases without needing an internet connection.</p>
                            </div>
                        </div>
                        <div class="flex gap-6 items-start">
                            <div class="text-4xl font-black text-brand-accent opacity-50">03</div>
                            <div>
                                <h4 class="text-xl font-bold text-white uppercase tracking-tight mb-2 italic">Voice Guidance</h4>
                                <p class="text-brand-light/60 text-sm">Bone-conduction speakers deliver treatment plans in Awadhi, Bhojpuri, or Hindi.</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="grid grid-cols-2 gap-4">
                    <img class="rounded-sm w-full h-[300px] object-cover grayscale hover:grayscale-0 transition-all duration-500" src="https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_90ee56b535_03d9b3538f38eeac.png" alt="Disease analysis" />
                    <img class="rounded-sm w-full h-[300px] object-cover grayscale hover:grayscale-0 transition-all duration-500" src="https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_5639fa3d70_be599948e6b1a6b6.png" alt="Smart HUD scanning" />
                    <img class="rounded-sm w-full h-[300px] object-cover grayscale hover:grayscale-0 transition-all duration-500" src="https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_72b43be963_a5dd5ed5cb11df2a.png" alt="Rugged tactile button" />
                    <img class="rounded-sm w-full h-[300px] object-cover grayscale hover:grayscale-0 transition-all duration-500" src="https://storage.googleapis.com/uxpilot-auth.appspot.com/gen_93b70e06bb_f059988cb2cb12d3.png" alt="Farmer in the field" />
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="py-32 px-12 bg-brand-accent text-white relative overflow-hidden">
        <div class="absolute -right-20 -bottom-20 opacity-10">
            <i class="fa-solid fa-glasses text-[400px] rotate-12"></i>
        </div>
        <div class="max-w-4xl mx-auto text-center relative z-10">
            <h2 class="text-7xl font-black mb-10 uppercase italic tracking-tighter leading-none">Join the <br/>Agri-Revolution</h2>
            <p class="text-2xl font-bold mb-14 text-white/90 max-w-2xl mx-auto">Limited pre-order slots available for the 2026 planting season. Secure your KisanLens today.</p>
            <div class="flex flex-col sm:flex-row gap-6 justify-center items-center">
                <input type="email" placeholder="Enter your mobile or email" class="w-full sm:w-96 px-8 py-5 bg-white/10 border-2 border-white/30 text-white placeholder:text-white/60 font-black uppercase tracking-widest focus:outline-none focus:border-white transition-all">
                <button class="w-full sm:w-auto bg-brand-dark hover:bg-black text-white px-12 py-5 rounded-sm font-black uppercase tracking-widest text-lg transition-all shadow-2xl">
                    Pre-order Now
                </button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-brand-dark text-white py-20 px-12 border-t border-white/5">
        <div class="max-w-7xl mx-auto">
            <div class="grid md:grid-cols-4 gap-12 mb-20">
                <div class="col-span-2">
                    <div class="flex items-center gap-2 mb-8">
                        <i class="fa-solid fa-glasses text-brand-accent text-3xl"></i>
                        <span class="text-3xl font-black uppercase tracking-tighter">DRISHTI SPECS</span>
                    </div>
                    <p class="text-brand-light/50 max-w-sm font-medium">Bridging the gap between ancient wisdom and cutting-edge technology to secure the future of global food production.</p>
                </div>
                <div>
                    <h5 class="font-black uppercase tracking-widest mb-6 text-brand-accent">Support</h5>
                    <ul class="space-y-4 text-brand-light/70 font-medium">
                        <li><a href="#" class="hover:text-white transition-colors">Field Training</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Warranty</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Bulk Orders</a></li>
                    </ul>
                </div>
                <div>
                    <h5 class="font-black uppercase tracking-widest mb-6 text-brand-accent">Contact</h5>
                    <ul class="space-y-4 text-brand-light/70 font-medium">
                        <li>support@drishtispecs.ai</li>
                        <li>+91 7388977433</li>
                        <li> UP,India</li>
                    </ul>
                </div>
            </div>
            <div class="pt-12 border-t border-white/5 flex flex-col md:flex-row justify-between items-center gap-6 opacity-40">
                <p class="text-sm font-bold uppercase tracking-widest">&copy; 2026 DRISHTI SPECS Agri-Technologies. Designed for the Field.</p>
                <div class="flex gap-8">
                    <a href="#"><i class="fa-brands fa-whatsapp text-2xl"></i></a>
                    <a href="#"><i class="fa-brands fa-x-twitter text-2xl"></i></a>
                    <a href="#"><i class="fa-brands fa-instagram text-2xl"></i></a>
                </div>
            </div>
        </div>
    </footer>
</body>
</html>
