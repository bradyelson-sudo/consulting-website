<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Brass Anvil Group LLC | Business Systems Analysis & Consulting </title>
    <!-- Load Tailwind CSS --> 
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
            color: #1a202c;
        }
        /* Custom Brass Anvil colors based on a deep professional palette */
        .color-primary { background-color: #3b82f6; } /* Blue for trust/tech */
        .text-primary { color: #1e40af; } /* Darker Blue */
        .bg-anvil { background-color: #4a5568; } /* Dark gray/anvil look */
        .text-anvil { color: #1a202c; }
        .border-highlight { border-color: #fbbf24; } /* Amber/Brass highlight */
        /* Animation for scrolling effect */
        .scroll-section {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .scroll-section.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="antialiased">
    <!-- Header & Navigation -->
    <header class="bg-anvil shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-white tracking-widest">
                <span class="text-amber-400">BRASS</span> ANVIL
            </div>
            <nav class="hidden md:flex space-x-6 text-white text-sm font-medium">
                <a href="#expertise" class="hover:text-amber-400 transition duration-300">Expertise</a>
                <a href="#services" class="hover:text-amber-400 transition duration-300">Services</a>
                <a href="#about" class="hover:text-amber-400 transition duration-300">About</a>
                <a href="#contact" class="px-4 py-2 bg-amber-400 text-gray-900 rounded-full hover:bg-amber-300 transition duration-300 shadow-md">Contract Now</a>
            </nav>
            <!-- Mobile Menu Button Placeholder -->
            <button class="md:hidden text-white focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
    </header>
    <!-- Hero Section -->
    <section class="color-primary text-white py-20 sm:py-32 scroll-section visible">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-5xl sm:text-7xl font-extrabold mb-4 leading-tight">
                Driving Clarity in Complex Systems.
            </h1>
            <p class="text-xl sm:text-2xl font-light max-w-3xl mx-auto mb-8">
                Brass Anvil provides expert Business Systems Analysis to bridge the gap between business needs and technological solutions, ensuring profitable, sustainable outcomes.
            </p>
            <a href="#contact" class="inline-block px-8 py-4 bg-amber-400 text-gray-900 font-bold text-lg rounded-xl shadow-2xl hover:bg-amber-300 transition duration-300 transform hover:scale-105">
                Discuss Your Next Project
            </a>
            <p class="mt-4 text-sm opacity-80">Serving organizations globally on a contract basis.</p>
        </div>
    </section>
    <!-- Expertise Section -->
    <section id="expertise" class="py-20 bg-white scroll-section">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-extrabold text-anvil mb-12 text-center">My Expertise in Action</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Card 1: Requirements Elicitation -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                    <div class="text-3xl text-primary mb-3">🛠️</div>
                    <h3 class="text-xl font-bold mb-3 text-anvil">Requirements Engineering</h3>
                    <p class="text-gray-600">Mastery in eliciting, documenting (epics, user stories, functional/non-functional specs), and managing complex requirement sets across diverse stakeholders.</p>
                </div>
                <!-- Card 2: Process Modeling -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                    <div class="text-3xl text-primary mb-3">🗺️</div>
                    <h3 class="text-xl font-bold mb-3 text-anvil">Process Optimization & Modeling</h3>
                    <p class="text-gray-600">Utilizing BPMN and UML to map 'As-Is' and 'To-Be' states, identifying bottlenecks and driving efficiency improvements for maximum ROI.</p>
                </div>
                <!-- Card 3: Agile & Waterfall Delivery -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-lg border-t-4 border-primary hover:shadow-xl transition duration-300">
                    <div class="text-3xl text-primary mb-3">🚀</div>
                    <h3 class="text-xl font-bold mb-3 text-anvil">SDLC & Methodology</h3>
                    <p class="text-gray-600">Deep experience in Agile (Scrum/Kanban) and Waterfall environments, ensuring successful product delivery and system implementation.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50 scroll-section">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-extrabold text-anvil mb-12 text-center">My Consulting Offerings</h2>
            <div class="space-y-10">
                <!-- Service 1 -->
                <div class="md:flex md:space-x-10 p-6 bg-white rounded-xl shadow-xl hover:ring-2 ring-amber-400 transition duration-300">
                    <div class="md:w-1/3 flex items-center mb-4 md:mb-0">
                        <div class="text-5xl text-amber-500 mr-4">💡</div>
                        <h3 class="text-2xl font-semibold text-primary">Strategic Discovery</h3>
                    </div>
                    <p class="md:w-2/3 text-gray-600">Conducting initial feasibility studies, stakeholder alignment, and current state assessments to establish a clear project vision and scope definition.</p>
                </div>
                <!-- Service 2 -->
                <div class="md:flex md:space-x-10 p-6 bg-white rounded-xl shadow-xl hover:ring-2 ring-amber-400 transition duration-300">
                    <div class="md:w-1/3 flex items-center mb-4 md:mb-0">
                        <div class="text-5xl text-amber-500 mr-4">✍️</div>
                        <h3 class="text-2xl font-semibold text-primary">Detailed Documentation</h3>
                    </div>
                    <p class="md:w-2/3 text-gray-600">Production of high-quality artifacts, including user stories, acceptance criteria, wireframes, data dictionaries, and traceability matrices.</p>
                </div>
                <!-- Service 3 -->
                <div class="md:flex md:space-x-10 p-6 bg-white rounded-xl shadow-xl hover:ring-2 ring-amber-400 transition duration-300">
                    <div class="md:w-1/3 flex items-center mb-4 md:mb-0">
                        <div class="text-5xl text-amber-500 mr-4">✅</div>
                        <h3 class="text-2xl font-semibold text-primary">Testing & UAT Support</h3>
                    </div>
                    <p class="md:w-2/3 text-gray-600">Defining test strategies, creating test cases derived directly from requirements, and supporting User Acceptance Testing (UAT) to validate solutions.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section id="about" class="py-20 bg-white scroll-section">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="md:flex md:space-x-12 items-center">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <!-- Placeholder image/icon for professionalism -->
                    <div class="h-64 bg-gray-200 rounded-xl shadow-xl flex items-center justify-center text-8xl text-anvil">
                        <span class="text-6xl text-amber-500">A</span>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-4xl font-extrabold text-anvil mb-6">The Brass Anvil Advantage</h2>
                    <p class="text-lg text-gray-700 mb-4">
                        As a solo LLC, Brass Anvil offers the precision and dedication of a seasoned systems analyst without the overhead of a large consulting firm. My approach is rooted in clear, concise communication and a commitment to delivering system specifications that are both technically sound and strategically aligned with your business goals.
                    </p>
                    <p class="text-lg text-gray-700 font-semibold">
                        Ready to transform complexity into clarity? Let's connect.
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-anvil text-white scroll-section">
        <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-extrabold text-amber-400 mb-6 text-center">Contract Inquiry</h2>
            <p class="text-lg text-center mb-8 opacity-90">Send me a message to discuss your project requirements and contract needs.</p>
            <form id="contactForm" class="space-y-6 bg-gray-700 p-8 rounded-xl shadow-2xl">
                <div>
                    <label for="name" class="block text-sm font-medium text-gray-200 mb-1">Your Name / Company Contact</label>
                    <input type="text" id="name" name="name" required class="w-full px-4 py-2 rounded-lg bg-gray-800 border border-gray-600 focus:ring-amber-500 focus:border-amber-500 text-white placeholder-gray-400">
                </div>
                <div>
                    <label for="email" class="block text-sm font-medium text-gray-200 mb-1">Work Email</label>
                    <input type="email" id="email" name="email" required class="w-full px-4 py-2 rounded-lg bg-gray-800 border border-gray-600 focus:ring-amber-500 focus:border-amber-500 text-white placeholder-gray-400">
                </div>
                <div>
                    <label for="project" class="block text-sm font-medium text-gray-200 mb-1">Project Summary / Contract Need</label>
                    <textarea id="project" name="project" rows="4" required class="w-full px-4 py-2 rounded-lg bg-gray-800 border border-gray-600 focus:ring-amber-500 focus:border-amber-500 text-white placeholder-gray-400"></textarea>
                </div>
                <button type="submit" class="w-full px-6 py-3 bg-amber-400 text-gray-900 font-bold text-lg rounded-lg shadow-xl hover:bg-amber-300 transition duration-300 transform hover:scale-[1.01]">
                    Submit Inquiry
                </button>
                <div id="statusMessage" class="mt-4 text-center font-medium text-sm"></div>
            </form>
            <p class="text-center text-xs mt-4 opacity-70">Note: This form uses a secure mail protocol. You will be redirected to confirm the email.</p>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-400 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm">
            <p>&copy; <span id="currentYear"></span> Brass Anvil LLC. All rights reserved. | Business Systems Analysis & Strategy</p>
            <p class="mt-2">Connect: LinkedIn | <a href="#contact" class="text-amber-400 hover:underline">Contact</a></p>
        </div>
    </footer>
    <script>
        document.getElementById('currentYear').textContent = new Date().getFullYear();
        // --- Intersection Observer for Scroll Animation ---
        const scrollSections = document.querySelectorAll('.scroll-section');
        const observerOptions = {
            root: null,
            rootMargin: '0px',
            threshold: 0.1
        };
        const observer = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                    observer.unobserve(entry.target); // Stop observing once visible
                }
            });
        }, observerOptions);
        scrollSections.forEach(section => {
            if (!section.classList.contains('visible')) {
                 observer.observe(section);
            }
        });
        // --- Form Submission Logic (using mailto: as a static fallback) ---
        const contactForm = document.getElementById('contactForm');
        const statusMessage = document.getElementById('statusMessage');
        contactForm.addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const project = document.getElementById('project').value;
            // Simple mailto link creation (Requires user action to send)
            const subject = encodeURIComponent(`Contract Inquiry from ${name}`);
            const body = encodeURIComponent(`Sender Name/Contact: ${name}\nSender Email: ${email}\n\nProject Summary:\n${project}`);
            const mailtoLink = `mailto:your.professional.email@brass-anvil-llc.com?subject=${subject}&body=${body}`;
            // In a live environment using a host like Netlify, Vercel, or a traditional host,
            // you would use a backend script or a forms service endpoint here.
            statusMessage.textContent = 'Preparing email... Please click send in the new window/tab.';
            statusMessage.classList.add('text-amber-400');
            // Open the mail client
            window.location.href = mailtoLink;
            // Clear the message after a short delay (since the user leaves the page)
            setTimeout(() => {
                statusMessage.textContent = '';
                // In a true implementation with a backend, you'd show a success message here.
                // For a static site, we advise the user to check their email client.
            }, 3000);
        });
    </script>
</body>
</html>
