<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-shipcxc-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-shipcxc-primary)]"></span>
                        <span class="text-white text-sm font-medium">Instant Quotes</span>
                        <span class="text-gray-400 text-sm">in under 15 minutes</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Reliable freight shipping. Transparent pricing.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        North American freight shipping that manufacturers trust. Get instant quotes, guaranteed rates, and seamless coordination across our carrier network. Stop overpaying for inconsistent service.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Get a Quote
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            View Network
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Shipment Quote -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500">QUOTE #SH-4829</div>
                                <div class="px-3 py-1.5 bg-[var(--color-shipcxc-primary)]/20 rounded text-[var(--color-shipcxc-primary)] text-sm font-bold">$1,245.00</div>
                            </div>
                            <div class="space-y-3">
                                <div class="flex justify-between text-sm">
                                    <span class="text-gray-500">Origin</span>
                                    <span class="font-medium">Chicago, IL</span>
                                </div>
                                <div class="flex justify-between text-sm">
                                    <span class="text-gray-500">Destination</span>
                                    <span class="font-medium">Dallas, TX</span>
                                </div>
                                <div class="flex justify-between text-sm">
                                    <span class="text-gray-500">Weight</span>
                                    <span class="font-medium">12,500 lbs</span>
                                </div>
                                <div class="h-px bg-gray-100 my-2"></div>
                                <div class="flex justify-between text-sm">
                                    <span class="text-gray-500">Delivery</span>
                                    <span class="font-medium text-green-600">2-3 days</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Tracking -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-[var(--color-shipcxc-primary)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-semibold">Shipment Tracking</div>
                                    <div class="w-8 h-8 bg-white/20 rounded-full flex items-center justify-center">
                                        <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                    </div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="space-y-4">
                                    <div class="flex gap-3">
                                        <div class="w-2 h-2 rounded-full bg-green-500 mt-1.5"></div>
                                        <div class="flex-1">
                                            <div class="text-sm font-medium">Picked up</div>
                                            <div class="text-xs text-gray-500">Chicago, IL - 8:30 AM</div>
                                        </div>
                                    </div>
                                    <div class="flex gap-3">
                                        <div class="w-2 h-2 rounded-full bg-green-500 mt-1.5"></div>
                                        <div class="flex-1">
                                            <div class="text-sm font-medium">In transit</div>
                                            <div class="text-xs text-gray-500">St. Louis, MO - 2:15 PM</div>
                                        </div>
                                    </div>
                                    <div class="flex gap-3">
                                        <div class="w-2 h-2 rounded-full bg-gray-300 mt-1.5"></div>
                                        <div class="flex-1">
                                            <div class="text-sm font-medium text-gray-400">Out for delivery</div>
                                            <div class="text-xs text-gray-400">Dallas, TX - Pending</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Rate Comparison -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500">BEST RATES</div>
                                <div class="px-2 py-1 bg-green-100 rounded text-green-700 text-xs font-bold">SAVE 23%</div>
                            </div>
                            <div class="space-y-3">
                                <div class="p-3 bg-gray-50 rounded-lg border-2 border-[var(--color-shipcxc-primary)]">
                                    <div class="flex justify-between items-center">
                                        <span class="text-sm font-medium">Ship CXC Network</span>
                                        <span class="font-bold text-[var(--color-shipcxc-primary)]">$1,245</span>
                                    </div>
                                </div>
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <div class="flex justify-between items-center">
                                        <span class="text-sm text-gray-600">Competitor A</span>
                                        <span class="text-gray-600 line-through">$1,620</span>
                                    </div>
                                </div>
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <div class="flex justify-between items-center">
                                        <span class="text-sm text-gray-600">Competitor B</span>
                                        <span class="text-gray-600 line-through">$1,580</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by manufacturers across North America</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50 grayscale">
                    <!-- Manufacturing Company 1 -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <rect x="10" y="8" width="15" height="14" />
                        <rect x="30" y="5" width="60" height="20" />
                    </svg>
                    <!-- Manufacturing Company 2 -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                         <circle cx="15" cy="15" r="10" />
                         <rect x="35" y="8" width="55" height="14" />
                    </svg>
                    <!-- Manufacturing Company 3 -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <path d="M10,5 L20,5 L20,25 L10,25 Z M30,10 L40,10 L40,25 L30,25 Z M50,8 L60,8 L60,25 L50,25 Z M70,12 L80,12 L80,25 L70,25 Z" />
                    </svg>
                    <!-- Manufacturing Company 4 -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <path d="M10,5 L30,5 L30,10 L15,10 L15,12.5 L25,12.5 L25,17.5 L15,17.5 L15,25 L10,25 L10,5 Z" />
                         <rect x="40" y="8" width="50" height="14" />
                    </svg>
                    <!-- Manufacturing Company 5 -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 100 30" fill="currentColor">
                        <rect x="10" y="8" width="80" height="14" />
                    </svg>
                </div>
            </div>
        </section>

        <!-- Ship CXC Platform Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-shipcxc-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Ship CXC Network</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">A freight coordination platform.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">And so much more.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Teal Card -->
                    <div class="bg-gradient-to-br from-[#0D9488] to-[#115E59] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Shipping Document -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="absolute top-0 right-0 p-6 opacity-30">
                                    <svg class="w-16 h-16 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1">
                                        <rect x="1" y="3" width="15" height="13" rx="2"></rect>
                                        <path d="M16 8h2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H6"></path>
                                        <circle cx="8" cy="18" r="2"></circle>
                                        <circle cx="16" cy="18" r="2"></circle>
                                    </svg>
                                </div>
                                <div class="space-y-3 relative z-10">
                                    <div class="flex justify-between items-center">
                                        <div class="text-white/60 text-xs uppercase tracking-wider font-medium">BOL #</div>
                                        <div class="text-white font-mono text-sm">SH-482901</div>
                                    </div>
                                    <div class="h-px bg-white/20"></div>
                                    <div class="flex justify-between items-center">
                                        <div class="text-white/60 text-xs">Origin</div>
                                        <div class="text-white text-sm font-medium">Chicago, IL</div>
                                    </div>
                                    <div class="flex justify-between items-center">
                                        <div class="text-white/60 text-xs">Destination</div>
                                        <div class="text-white text-sm font-medium">Dallas, TX</div>
                                    </div>
                                    <div class="h-px bg-white/20"></div>
                                    <div class="flex justify-between items-center">
                                        <div class="text-white/60 text-xs">Rate</div>
                                        <div class="text-white text-lg font-bold">$1,245.00</div>
                                    </div>
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center text-blue-600">
                                        <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                                    </div>
                                    LTL Freight
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-teal-500/30 flex items-center justify-center text-teal-200">
                                        <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                    </div>
                                    Full Truckload
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Scale with reliability.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Markets shift. Demand fluctuates. Ship CXC provides modern freight coordination built to adapt and grow with your manufacturing business and shipping needs.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Ship CXC Platform</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">One platform for managing and scaling freight operations.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">However complex.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore our network
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-shipcxc-primary)]"></span>
                                Instant Quotes
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Carrier Network</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Real-Time Tracking</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Rate Analytics</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Freight Audit</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Agent Portal</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Instant Quotes" 
                            description="Get rates in under 15 minutes. Ship CXC delivers guaranteed freight quotes faster than any competitor, eliminating rate uncertainty for manufacturers."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Carrier Network" 
                            description="Access our vetted partners. Ship CXC coordinates across a curated network of reliable carriers, ensuring consistent service quality and competitive pricing."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Real-Time Tracking" 
                            description="Know where your freight is. Monitor shipments with live updates and detailed tracking information, giving you complete visibility from pickup to delivery."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Rate Analytics" 
                            description="Optimize your shipping costs. Compare historical rates, identify savings opportunities, and make data-driven decisions about your freight strategy."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Freight Audit" 
                            description="Catch billing errors before they cost you. Automated freight audit tools verify charges against quoted rates, protecting your bottom line."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Agent Portal" 
                            description="Scale through partnerships. Our agent network portal enables freight brokers and logistics partners to access our platform and expand our reach."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Manufacturer Focus Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-teal-100 to-cyan-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-teal-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Built for manufacturers who ship regularly — from small operations to enterprise facilities.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        See how it works
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by manufacturers across North America. Learn from our customers.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Customer Story Card -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">MidWest Manufacturing</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-shipcxc-primary)] flex items-center justify-center text-black font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M3 18L12 22L21 18M3 12L12 16L21 12M12 2L3 6L12 10L21 6L12 2Z" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                        </svg>
                                        Ship CXC
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    How MidWest Manufacturing cut freight costs by 23% with Ship CXC
                                </h3>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-teal-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-semibold text-lg mb-2">Precision Parts Co.</div>
                                    <p class="text-gray-400 text-sm">"15-minute quotes changed our business"</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-teal-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-cyan-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-semibold text-lg mb-2">Industrial Solutions LLC</div>
                                    <p class="text-gray-400 text-sm">"Reliable carriers, every time"</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-cyan-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-teal-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-cyan-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Ship smarter, not harder. <span class="text-[var(--color-shipcxc-primary)]">Save 20%+ on freight.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Join manufacturers who've discovered the power of transparent pricing and reliable carrier partnerships.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                            Getting Started Guide
                            <kbd class="bg-black/30 px-1.5 py-0.5 rounded text-xs text-gray-400 font-mono">→</kbd>
                        </div>
                    </div>
                </div>

                <!-- Carrier Partners -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        National carriers. Regional specialists.<br>
                        LTL and FTL. <span class="text-gray-400">Whatever you need,<br>our network delivers.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        View carrier network
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['XPO Logistics', 'Old Dominion', 'YRC Freight', 'Estes Express', 'Saia Motor', 'ABF Freight', 'R+L Carriers', 'TForce Freight'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-lg tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn more about modern freight shipping.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-teal-100 to-cyan-200 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-40">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-teal-600 transform rotate-12" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Insights</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-teal-600 transition-colors">Why manufacturers are switching to network freight coordination</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-teal-400 blur-xl opacity-80"></div>
                                    <div class="w-20 h-20 rounded-full bg-cyan-400 blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-blue-400 blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Insights</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-teal-600 transition-colors">The complete guide to LTL vs FTL freight shipping</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

