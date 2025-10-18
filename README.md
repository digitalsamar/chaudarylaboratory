<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chaudary Lab | Medical Test Laboratory</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        :root {
            --color-primary: #1e3a8a; /* Dark Blue */
            --color-secondary: #06b6d4; /* Teal/Cyan */
            --color-accent: #10b981; /* Green Accent */
        }
        body {
            font-family: 'Inter', sans-serif;
            color: #333;
            background-color: #f8fafc;
        }
        .header-bg {
            background-color: var(--color-primary);
        }
        .text-primary {
            color: var(--color-primary);
        }
        .bg-secondary {
            background-color: var(--color-secondary);
        }
        .bg-accent {
            background-color: var(--color-accent);
        }
        .btn-primary {
            background-color: var(--color-accent);
            color: white;
            transition: background-color 0.3s;
        }
        .btn-primary:hover {
            background-color: #059669;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Navigation -->
    <header class="header-bg text-white shadow-lg sticky top-0 z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <i data-lucide="microscope" class="w-8 h-8 text-white"></i>
                    <span class="text-3xl font-extrabold tracking-tight">CHAUDARY <span class="text-secondary">LAB</span></span>
                </div>
                <nav class="hidden md:flex space-x-6 text-lg">
                    <a href="#services" class="hover:text-secondary transition duration-150">Services</a>
                    <a href="#collection" class="hover:text-secondary transition duration-150">Home Collection</a>
                    <a href="#contact" class="hover:text-secondary transition duration-150">Contact Us</a>
                </nav>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="py-16 md:py-24 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <h1 class="text-5xl md:text-6xl font-extrabold text-primary leading-tight">
                        Reliable Medical <br class="hidden sm:inline">
                        <span class="text-secondary">Testing, Simplified.</span>
                    </h1>
                    <p class="text-xl text-gray-600">
                        Chaudary Lab provides comprehensive, accurate, and timely testing services. Get your samples collected from the comfort of your **Home or Hospital**.
                    </p>
                    <a href="#collection" class="inline-flex items-center px-8 py-4 text-lg font-semibold rounded-xl btn-primary shadow-lg hover:shadow-xl transform hover:scale-[1.02] transition duration-300">
                        Book Home Sample Collection
                        <i data-lucide="chevron-right" class="w-5 h-5 ml-2"></i>
                    </a>
                </div>
                <!-- Mock Image/Illustration placeholder -->
                <div class="hidden md:block">
                    <div class="bg-gray-100 p-8 rounded-2xl shadow-xl border-4 border-secondary">
                        <i data-lucide="vials" class="w-20 h-20 text-secondary mx-auto mb-4"></i>
                        <p class="text-center text-lg font-medium text-gray-700">Expertise in Blood, Urine, Saliva, Semen, Sugar & more. All Kinds of Tests Done Here.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Home Collection Feature -->
        <section id="collection" class="py-16 bg-secondary text-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <i data-lucide="home" class="w-12 h-12 mx-auto mb-4"></i>
                <h2 class="text-4xl font-bold mb-4">Samples Collected From Home & Hospitals</h2>
                <p class="text-xl font-light max-w-3xl mx-auto">
                    We bring the lab to you! Enjoy the convenience of professional, hygienic sample collection service at your doorstep or facility.
                </p>
                <div class="mt-8">
                    <a href="tel:+918014560002" class="inline-flex items-center px-8 py-3 text-xl font-bold rounded-xl bg-white text-primary shadow-2xl transform hover:scale-105 transition duration-300">
                        <i data-lucide="phone" class="w-6 h-6 mr-3"></i>
                        Call Now: 8014560002
                    </a>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-16 md:py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center text-primary mb-12">Our Comprehensive Testing Services</h2>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    
                    <!-- Service Card 1 -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                        <i data-lucide="droplet" class="w-8 h-8 text-primary mb-3"></i>
                        <h3 class="text-xl font-semibold mb-2">Blood Analysis</h3>
                        <p class="text-gray-600">Complete Blood Count (CBC), Lipid Profiles, Kidney and Liver Function Tests, and more.</p>
                    </div>

                    <!-- Service Card 2 -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                        <i data-lucide="thermometer" class="w-8 h-8 text-primary mb-3"></i>
                        <h3 class="text-xl font-semibold mb-2">Diabetes & Sugar Testing</h3>
                        <p class="text-gray-600">Fasting Blood Sugar (FBS), Post Prandial Sugar (PPBS), and HbA1c testing.</p>
                    </div>

                    <!-- Service Card 3 -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                        <i data-lucide="beaker" class="w-8 h-8 text-primary mb-3"></i>
                        <h3 class="text-xl font-semibold mb-2">Urine & Saliva Tests</h3>
                        <p class="text-gray-600">Routine and specialized testing for urine analysis and saliva samples.</p>
                    </div>

                    <!-- Service Card 4 -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                        <i data-lucide="dna" class="w-8 h-8 text-primary mb-3"></i>
                        <h3 class="text-xl font-semibold mb-2">Specialized Tests</h3>
                        <p class="text-gray-600">Hormonal assays, infectious disease panels, and other specialized diagnostic needs.</p>
                    </div>
                    
                    <!-- Service Card 5 -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                        <i data-lucide="package-search" class="w-8 h-8 text-primary mb-3"></i>
                        <h3 class="text-xl font-semibold mb-2">All Kinds of Tests</h3>
                        <p class="text-gray-600">If it's a diagnostic test, we likely do it. Contact us for any specific requirements.</p>
                    </div>
                    
                    <!-- Service Card 6 (Call to Action) -->
                    <div class="bg-accent p-6 rounded-xl shadow-lg border-t-4 border-primary flex flex-col justify-center items-center text-center">
                        <h3 class="text-2xl font-bold text-white mb-3">Need a Specific Test?</h3>
                        <a href="tel:+918014560002" class="inline-flex items-center px-6 py-3 text-lg font-bold rounded-xl bg-white text-accent shadow-lg transform hover:scale-105 transition duration-300">
                            <i data-lucide="circle-call" class="w-5 h-5 mr-2"></i>
                            Enquire Now
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact & Location Section -->
        <section id="contact" class="py-16 bg-gray-50 border-t">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-3 gap-10">
                
                <!-- Contact Info -->
                <div class="md:col-span-1 space-y-6">
                    <h2 class="text-3xl font-bold text-primary mb-4">Get In Touch</h2>
                    
                    <div class="flex items-start space-x-3">
                        <i data-lucide="phone" class="w-6 h-6 text-secondary flex-shrink-0 mt-1"></i>
                        <div>
                            <p class="font-semibold text-lg">Mobile Number</p>
                            <a href="tel:+918014560002" class="text-primary hover:text-secondary font-medium">8014560002</a>
                        </div>
                    </div>

                    <div class="flex items-start space-x-3">
                        <i data-lucide="map-pin" class="w-6 h-6 text-secondary flex-shrink-0 mt-1"></i>
                        <div>
                            <p class="font-semibold text-lg">Our Location</p>
                            <p class="text-gray-600">Opp. Sharma Medical Store,<br>Near Raj Hospital, Lalheri Road,<br>Khanna (141401) Ldh.</p>
                        </div>
                    </div>

                </div>

                <!-- Google Maps Embed Placeholder -->
                <div class="md:col-span-2 rounded-xl shadow-2xl overflow-hidden h-64 md:h-full">
                    <!-- This is a placeholder for a Google Map iframe, which cannot be loaded dynamically here. -->
                    <div class="w-full h-full bg-gray-200 flex items-center justify-center text-center p-4">
                         <p class="text-gray-500 font-medium">Map Location Preview (Please visit in a real browser to see the map) <br> **Opp. Sharma Medical Store, Khanna**</p>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="header-bg text-white py-6">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p>&copy; 2025 Chaudary Lab. All Rights Reserved.</p>
            <p class="text-sm text-gray-300 mt-1">Medical Test Laboratory, Khanna, Ldh.</p>
        </div>
    </footer>

    <!-- Initialize Lucide Icons -->
    <script>
        lucide.createIcons();
    </script>
</body>
</html>
