<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Source Huts Agency | China Sourcing & Global Freight Forwarding</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        
        /* Note: We use Tailwind's orange palette (e.g., orange-600) for clean integration */

        body {
            font-family: 'Inter', sans-serif;
            background-color: #ffffff;
            color: #1f2937;
        }

        /* Custom shadow adjusted to reflect the new orange primary color */
        .shadow-trust {
            box-shadow: 0 10px 15px -3px rgba(249, 115, 22, 0.2), 0 4px 6px -2px rgba(249, 115, 22, 0.1);
        }

        /* Responsive grid adjustments for Service Cards */
        .service-grid {
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#" class="text-3xl font-extrabold tracking-tight text-gray-900">
                Source <span class="text-orange-600">Huts</span> <!-- COLOR UPDATED -->
            </a>
            
            <!-- Desktop Nav Links -->
            <div class="hidden md:flex space-x-8 items-center">
                <a href="#services" class="text-gray-600 hover:text-orange-600 transition duration-300 font-medium">Services</a>
                <a href="#about" class="text-gray-600 hover:text-orange-600 transition duration-300 font-medium">About Us</a>
                <a href="#freight" class="text-gray-600 hover:text-orange-600 transition duration-300 font-medium">Global Freight</a>
                <a href="#contact" class="px-5 py-2 bg-orange-600 text-white font-semibold rounded-lg hover:bg-orange-700 transition duration-300 shadow-lg"> <!-- COLOR UPDATED -->
                    Get a Quote
                </a>
            </div>

            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden p-2 rounded-lg text-gray-600 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-orange-500"> <!-- COLOR UPDATED -->
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
            </button>
        </nav>
    </header>

    <!-- Mobile Menu Drawer (Hidden by default) -->
    <div id="mobile-menu" class="hidden md:hidden fixed top-16 left-0 w-full bg-white z-40 shadow-xl rounded-b-lg">
        <div class="flex flex-col p-4 space-y-2">
            <a href="#services" class="text-gray-700 hover:bg-gray-50 p-2 rounded-lg transition duration-200">Services</a>
            <a href="#about" class="text-gray-700 hover:bg-gray-50 p-2 rounded-lg transition duration-200">About Us</a>
            <a href="#freight" class="text-gray-700 hover:bg-gray-50 p-2 rounded-lg transition duration-200">Global Freight</a>
            <a href="#contact" class="text-gray-700 hover:bg-gray-50 p-2 rounded-lg transition duration-200">Get a Quote</a>
        </div>
    </div>

    <main>
        <!-- Hero Section -->
        <section class="py-20 sm:py-32 bg-gray-50/50">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h1 class="text-5xl sm:text-7xl font-extrabold tracking-tight mb-6 text-gray-900">
                    Your <span class="text-orange-600">Reliable Partner</span> in China Sourcing <!-- COLOR UPDATED -->
                </h1>
                <p class="text-xl sm:text-2xl text-gray-600 mb-10 max-w-3xl mx-auto">
                    From Product Sourcing to Global Delivery, Source Huts streamlines your supply chain, guaranteeing quality and efficiency every step of the way.
                </p>
                <a href="#contact" class="inline-block px-10 py-4 bg-orange-600 text-white text-lg font-bold rounded-xl shadow-lg hover:bg-orange-700 transition duration-300 transform hover:scale-[1.02] shadow-trust"> <!-- COLOR UPDATED -->
                    Start Sourcing Today
                </a>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-16 sm:py-24 bg-white">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center mb-4 text-gray-900">Our Comprehensive Services</h2>
                <p class="text-xl text-center text-gray-500 mb-16 max-w-2xl mx-auto">
                    We manage the entire import process so you can focus on growing your business.
                </p>
                
                <div class="grid gap-8 service-grid">
                    
                    <!-- Service Card 1: Product Sourcing -->
                    <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-orange-500 hover:shadow-2xl transition duration-300"> <!-- COLOR UPDATED -->
                        <div class="w-12 h-12 mb-4 rounded-full bg-orange-100 text-orange-600 flex items-center justify-center"> <!-- COLOR UPDATED -->
                            <!-- Search Icon -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-900">Product Sourcing</h3>
                        <p class="text-gray-600">
                            Find reliable, high-quality manufacturers in China for any product category. We negotiate the best prices and minimum order quantities (MOQs).
                        </p>
                    </div>

                    <!-- Service Card 2: Freight Forwarding -->
                    <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-orange-500 hover:shadow-2xl transition duration-300"> <!-- COLOR UPDATED -->
                        <div class="w-12 h-12 mb-4 rounded-full bg-orange-100 text-orange-600 flex items-center justify-center"> <!-- COLOR UPDATED -->
                            <!-- Truck Icon -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10 17H5a2 2 0 0 1-2-2V9.5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v1"/><path d="M17 19h2a2 2 0 0 0 2-2v-4a2 2 0 0 0-2-2h-2"/><circle cx="7" cy="17" r="2"/><circle cx="17" cy="17" r="2"/></svg>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-900">Freight Forwarding</h3>
                        <p class="text-gray-600">
                            Seamless logistics and shipping from China to the USA, UK, European countries, Gulf countries, and other global destinations.
                        </p>
                    </div>

                    <!-- Service Card 3: Sample Management -->
                    <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-orange-500 hover:shadow-2xl transition duration-300"> <!-- COLOR UPDATED -->
                        <div class="w-12 h-12 mb-4 rounded-full bg-orange-100 text-orange-600 flex items-center justify-center"> <!-- COLOR UPDATED -->
                            <!-- Package Icon -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12.89 1.45L19.24 4.88c.83.43 1.25 1.34 1.25 2.22v9.8c0 .88-.42 1.79-1.25 2.22l-6.35 3.43c-.83.45-1.78.45-2.61 0L4.76 19.12c-.83-.43-1.25-1.34-1.25-2.22v-9.8c0-.88.42-1.79 1.25-2.22l6.35-3.43c.83-.45 1.78-.45 2.61 0z"/><path d="M16 4.04v7.75"/><line x1="8" y1="5.16" x2="8" y2="12.91"/><line x1="12" y1="2.2" x2="12" y2="14.8"/><line x1="4" y1="16.96" x2="20" y2="16.96"/></svg>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-900">Sample Evaluation & Consolidation</h3>
                        <p class="text-gray-600">
                            We receive, inspect, and consolidate samples from multiple suppliers, saving you time and international shipping costs.
                        </p>
                    </div>

                    <!-- Service Card 4: Factory Audit -->
                    <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-orange-500 hover:shadow-2xl transition duration-300"> <!-- COLOR UPDATED -->
                        <div class="w-12 h-12 mb-4 rounded-full bg-orange-100 text-orange-600 flex items-center justify-center"> <!-- COLOR UPDATED -->
                            <!-- Building Check Icon -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="10" width="18" height="12" rx="2"/><path d="M12 22V6M16 10v4M8 10v4"/><path d="M12 2l4 4H8z"/></svg>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-900">Factory Audit & Inspection</h3>
                        <p class="text-gray-600">
                            Comprehensive checks on factory production capability, quality control systems, and compliance before and during manufacturing.
                        </p>
                    </div>

                    <!-- Service Card 5: Product Photography -->
                    <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-orange-500 hover:shadow-2xl transition duration-300"> <!-- COLOR UPDATED -->
                        <div class="w-12 h-12 mb-4 rounded-full bg-orange-100 text-orange-600 flex items-center justify-center"> <!-- COLOR UPDATED -->
                            <!-- Camera Icon -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 4h1.9a2 2 0 0 1 2 2v4.2c-.44-.24-1.04-.45-1.63-.64-.59-.19-1.23-.33-1.87-.43-1.16-.18-2.34-.23-3.5-.18C8.97 8.94 8.01 9 7 9c-2.76 0-5 2.24-5 5s2.24 5 5 5 5-2.24 5-5c0-.99-.06-1.95-.18-2.88-.1-.64-.24-1.28-.43-1.87-.19-.59-.4-1.19-.64-1.63V6a2 2 0 0 1 2-2h.9z"/><circle cx="15.5" cy="14" r="3"/><path d="M10 2l4 4"/></svg>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-900">Product Photography</h3>
                        <p class="text-gray-600">
                            High-quality E-commerce photography and video services tailored for Amazon, Shopify, and your website, done directly in China.
                        </p>
                    </div>
                    
                    <!-- Service Card 6: Trademark Registration -->
                    <div class="bg-white p-8 rounded-2xl shadow-xl border-t-4 border-orange-500 hover:shadow-2xl transition duration-300"> <!-- COLOR UPDATED -->
                        <div class="w-12 h-12 mb-4 rounded-full bg-orange-100 text-orange-600 flex items-center justify-center"> <!-- COLOR UPDATED -->
                            <!-- File Text Icon -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/><line x1="10" y1="9" x2="8" y2="9"/></svg>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-900">Trademark Registration</h3>
                        <p class="text-gray-600">
                            Secure your brand identity in the Chinese market. We handle the process for Chinese trademark registration to protect your IP.
                        </p>
                    </div>

                </div>
            </div>
        </section>

        <!-- Global Freight & Logistics Focus Section -->
        <section id="freight" class="py-16 sm:py-24 bg-gray-900">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-6xl">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="text-4xl font-bold text-white mb-4">Freight Forwarding: Connect China to the World</h2>
                        <p class="text-xl text-gray-300 mb-8">
                            Our extensive logistics network ensures your goods move quickly, affordably, and safely across continents, handling all customs and documentation hassle-free.
                        </p>
                        
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <span class="text-orange-400 font-bold text-2xl mr-4">&#x2713;</span> <!-- COLOR UPDATED -->
                                <div>
                                    <h4 class="text-lg font-semibold text-white">North American Lanes</h4>
                                    <p class="text-gray-400 text-sm">Dedicated sea and air freight routes to the USA and Canada.</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <span class="text-orange-400 font-bold text-2xl mr-4">&#x2713;</span> <!-- COLOR UPDATED -->
                                <div>
                                    <h4 class="text-lg font-semibold text-white">European Union Expertise</h4>
                                    <p class="text-gray-400 text-sm">Full customs clearance and delivery to the UK and all major European countries.</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <span class="text-orange-400 font-bold text-2xl mr-4">&#x2713;</span> <!-- COLOR UPDATED -->
                                <div>
                                    <h4 class="text-lg font-semibold text-white">Middle East & GCC Shipping</h4>
                                    <p class="text-gray-400 text-sm">Reliable supply routes to Gulf Countries (KSA, UAE, Qatar, etc.) and surrounding markets.</p>
                                </div>
                            </div>
                        </div>
                        <a href="#contact" class="mt-8 inline-block px-8 py-3 bg-orange-500 text-white font-semibold rounded-lg hover:bg-orange-600 transition duration-300"> <!-- COLOR UPDATED -->
                            Calculate Shipping Costs
                        </a>
                    </div>
                    
                    <!-- Placeholder for image/map -->
                    <div class="hidden md:flex justify-center items-center">
                        <div class="w-full h-80 bg-orange-700/50 rounded-2xl flex items-center justify-center border-4 border-orange-500/50 p-4"> <!-- COLOR UPDATED -->
                            <p class="text-xl text-white font-bold text-center">Global Logistics Map Placeholder</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA & Contact Section -->
        <section id="contact" class="py-16 sm:py-24 bg-gray-50">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-4xl">
                <h2 class="text-4xl font-bold text-center mb-10 text-gray-900">Ready to Streamline Your Imports?</h2>
                
                <div class="max-w-xl mx-auto bg-white p-8 sm:p-10 rounded-2xl shadow-2xl border border-gray-100">
                    <p class="text-center text-gray-600 mb-6 text-lg">
                        Tell us about your product or sourcing needs, and our experts will follow up within 24 hours.
                    </p>
                    
                    <!-- Mock Form -->
                    <form action="#" method="POST" class="space-y-4" onsubmit="handleFormSubmit(event)">
                        <div>
                            <label for="c-name" class="block text-sm font-medium text-gray-700 mb-1">Company/Name</label>
                            <input type="text" id="c-name" name="name" required
                                   class="w-full p-3 rounded-lg bg-gray-50 border border-gray-300 text-gray-900 focus:border-orange-500 focus:ring-orange-500 transition duration-200"> <!-- COLOR UPDATED -->
                        </div>
                        <div>
                            <label for="c-email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label>
                            <input type="email" id="c-email" name="email" required
                                   class="w-full p-3 rounded-lg bg-gray-50 border border-gray-300 text-gray-900 focus:border-orange-500 focus:ring-orange-500 transition duration-200"> <!-- COLOR UPDATED -->
                        </div>
                        <div>
                            <label for="c-message" class="block text-sm font-medium text-gray-700 mb-1">Your Requirements (Product, Quantity, Destination)</label>
                            <textarea id="c-message" name="message" rows="4" required
                                      class="w-full p-3 rounded-lg bg-gray-50 border border-gray-300 text-gray-900 focus:border-orange-500 focus:ring-orange-500 transition duration-200"></textarea> <!-- COLOR UPDATED -->
                        </div>
                        <button type="submit" 
                                class="w-full py-3 bg-orange-600 text-white font-bold rounded-lg shadow-md hover:bg-orange-700 transition duration-300 transform hover:scale-[1.01]"> <!-- COLOR UPDATED -->
                            Submit Request
                        </button>
                        <!-- Form Submission Message Box -->
                        <div id="form-message" class="mt-4 p-4 rounded-lg text-center hidden bg-green-100 text-green-700 font-medium"></div>
                    </form>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 py-10">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-white">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 border-b border-gray-700 pb-8 mb-8">
                <div>
                    <h5 class="text-xl font-bold mb-4 text-orange-400">Source Huts</h5> <!-- COLOR UPDATED -->
                    <p class="text-sm text-gray-400">China Sourcing & Fulfillment Partner.</p>
                </div>
                <div>
                    <h5 class="text-lg font-semibold mb-4">Key Services</h5>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <li><a href="#services" class="hover:text-orange-400">Product Sourcing</a></li> <!-- COLOR UPDATED -->
                        <li><a href="#freight" class="hover:text-orange-400">Global Freight</a></li> <!-- COLOR UPDATED -->
                        <li><a href="#services" class="hover:text-orange-400">Factory Audit</a></li> <!-- COLOR UPDATED -->
                        <li><a href="#services" class="hover:text-orange-400">Trademark Registration</a></li> <!-- COLOR UPDATED -->
                    </ul>
                </div>
                <div>
                    <h5 class="text-lg font-semibold mb-4">Shipping Zones</h5>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <li><a href="#freight" class="hover:text-orange-400">USA & Canada</a></li> <!-- COLOR UPDATED -->
                        <li><a href="#freight" class="hover:text-orange-400">Europe & UK</a></li> <!-- COLOR UPDATED -->
                        <li><a href="#freight" class="hover:text-orange-400">Gulf Countries</a></li> <!-- COLOR UPDATED -->
                        <li><a href="#freight" class="hover:text-orange-400">Australia</a></li> <!-- COLOR UPDATED -->
                    </ul>
                </div>
                <div>
                    <h5 class="text-lg font-semibold mb-4">Contact</h5>
                    <!-- CONTACT INFO UPDATED -->
                    <p class="text-sm text-gray-400">Email: sourcehuts@gmail.com</p>
                    <p class="text-sm text-gray-400">Phone: +44 7883 186893</p>
                </div>
            </div>
            
            <div class="text-center text-gray-500 text-sm">
                &copy; 2025 Source Huts Agency. All rights reserved.
            </div>
        </div>
    </footer>

    <script>
        // --- Mobile Menu Toggler ---
        document.getElementById('mobile-menu-button').addEventListener('click', () => {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Close mobile menu on link click
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });

        // --- Mock Form Submission Handler ---
        function handleFormSubmit(e) {
            e.preventDefault();
            
            const form = e.target;
            const messageBox = document.getElementById('form-message');
            
            // Display a success message instead of actually submitting
            messageBox.textContent = 'Thank you! Your request has been received. An expert will contact you within 24 hours.';
            // COLOR UPDATED (text-blue-700 to text-orange-700, bg-blue-100 to bg-orange-100)
            messageBox.className = 'mt-4 p-4 rounded-lg text-center bg-orange-100 text-orange-700 font-medium block';
            
            // Clear the form fields after a small delay
            setTimeout(() => {
                form.reset();
            }, 2000);
        }
    </script>
</body>
</html>
