<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Asaad - Professional Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for the Inter font */
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Smooth scroll for navigation */
        html {
            scroll-behavior: smooth;
        }
        /* Basic styling for section padding */
        section {
            padding: 4rem 1rem; /* Responsive padding */
        }
        /* Ensure images are responsive */
        img {
            max-width: 100%;
            height: auto;
        }
        /* Highlight search results */
        .highlight {
            background-color: #fceb02; /* Yellow highlight */
            padding: 2px 4px;
            border-radius: 4px;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header and Navigation -->
    <header class="bg-white shadow-lg py-4 px-6 fixed top-0 left-0 w-full z-50 rounded-b-xl">
        <nav class="container mx-auto flex justify-between items-center flex-wrap">
            <!-- Brand/Logo -->
            <a href="#home" class="text-2xl font-bold text-emerald-700 rounded-lg p-2 hover:text-emerald-900 transition duration-300">Mohamed Asaad</a>

            <!-- Mobile Menu Button -->
            <div class="block lg:hidden">
                <button id="nav-toggle" class="flex items-center px-3 py-2 border rounded text-emerald-600 border-emerald-600 hover:text-emerald-800 hover:border-emerald-800">
                    <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
                </button>
            </div>

            <!-- Navigation Links and Search Bar -->
            <div id="nav-content" class="w-full flex-grow lg:flex lg:items-center lg:w-auto hidden mt-4 lg:mt-0">
                <div class="text-sm lg:flex-grow lg:flex lg:justify-end lg:items-center">
                    <a href="#home" class="block mt-4 lg:inline-block lg:mt-0 text-gray-700 hover:text-emerald-700 mr-6 py-2 px-4 rounded-lg transition duration-300">Home</a>
                    <a href="#about" class="block mt-4 lg:inline-block lg:mt-0 text-gray-700 hover:text-emerald-700 mr-6 py-2 px-4 rounded-lg transition duration-300">About</a>
                    <a href="#skills" class="block mt-4 lg:inline-block lg:mt-0 text-gray-700 hover:text-emerald-700 mr-6 py-2 px-4 rounded-lg transition duration-300">Skills</a>
                    <a href="#experience" class="block mt-4 lg:inline-block lg:mt-0 text-gray-700 hover:text-emerald-700 mr-6 py-2 px-4 rounded-lg transition duration-300">Experience</a>
                    <a href="#portfolio" class="block mt-4 lg:inline-block lg:mt-0 text-gray-700 hover:text-emerald-700 mr-6 py-2 px-4 rounded-lg transition duration-300">Portfolio</a>
                    <a href="#contact" class="block mt-4 lg:inline-block lg:mt-0 text-gray-700 hover:text-emerald-700 py-2 px-4 rounded-lg transition duration-300">Contact</a>
                    <!-- Search Input -->
                    <div class="relative mt-4 lg:mt-0 lg:ml-6">
                        <input type="text" id="search-input" placeholder="Search..." class="pl-4 pr-10 py-2 rounded-full border border-gray-300 focus:outline-none focus:border-emerald-500 w-full lg:w-48 text-gray-700 text-base">
                        <button id="search-button" class="absolute right-0 top-0 mt-2 mr-3 text-gray-500 hover:text-emerald-700">
                            <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                        </button>
                    </div>
                </div>
            </div>
        </nav>
    </header>

    <!-- Home Section (Hero) -->
    <section id="home" class="min-h-screen flex items-center justify-center bg-gradient-to-r from-emerald-500 to-teal-600 text-white pt-20 lg:pt-0">
        <div class="container mx-auto text-center px-4">
            <img src="https://placehold.co/150x150/047857/FFFFFF?text=MOHAMED+ASAAD" alt="Mohamed Asaad Photo" class="rounded-full w-40 h-40 mx-auto mb-6 border-4 border-white shadow-lg">
            <h1 class="text-5xl lg:text-6xl font-extrabold mb-4 leading-tight">Hello, I'm <span class="text-lime-300">Mohamed Asaad</span></h1>
            <p class="text-xl lg:text-2xl mb-8 font-light">An Electrical Engineer specializing in <span class="font-semibold">transformer design, R&D innovation, and renewable energy solutions</span>.</p>
            <a href="#portfolio" class="bg-white text-emerald-700 hover:bg-gray-100 px-8 py-4 rounded-full text-lg font-semibold shadow-xl transition transform hover:scale-105 duration-300">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="bg-white py-16">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">About Me</h2>
            <div class="flex flex-col lg:flex-row items-center gap-8">
                <div class="lg:w-1/2">
                    <img src="https://placehold.co/400x300/065F46/FFFFFF?text=ABOUT+MOHAMED" alt="About Mohamed Asaad Image" class="rounded-xl shadow-lg w-full">
                </div>
                <div class="lg:w-1/2 text-lg leading-relaxed content-searchable">
                    <p class="mb-4">
                        I am an Electrical Engineer specializing in transformer design, R&D innovation, and renewable energy solutions.
                    </p>
                    <p class="mb-4">
                        Currently, I serve as an Electrical Design & R&D Engineer at TECTRAFO, where I focus on developing advanced transformer technologies, driving new product innovation, and supporting the future of sustainable energy infrastructure.
                    </p>
                    <p class="mb-4">
                        I am also pursuing a Master of Science in Electrical Power & Machines Engineering at Ain Shams University, with ongoing research in Energy Management for Smart Buildings — combining academic knowledge with real-world engineering applications.
                    </p>
                    <p>
                        My experience covers transformer design optimization, power system analysis, solar PV solutions, industrial energy efficiency, and smart energy systems. I am passionate about sustainable innovation, smart grid transformation, and delivering engineering excellence that meets future energy demands. Always open to new collaborations, technical discussions, and opportunities that push the boundaries of what energy engineering can achieve.
                    </p>
                    <!-- No specific resume URL provided, keeping as placeholder or remove if not needed -->
                    <!-- <a href="path/to/your/resume.pdf" download class="inline-block mt-8 bg-emerald-600 text-white hover:bg-emerald-700 px-6 py-3 rounded-lg font-semibold shadow-md transition duration-300">Download My Resume</a> -->
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="bg-gray-100 py-16">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">My Skills & Certifications</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-8">
                <!-- Top Skills -->
                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 transform hover:scale-105 content-searchable">
                    <h3 class="text-2xl font-semibold text-emerald-700 mb-4 flex items-center">
                        <svg class="w-6 h-6 mr-3 text-emerald-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 4l-4 4 4 4"></path></svg>
                        Top Skills
                    </h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li>Research and Development (R&D)</li>
                        <li>Renewable Energy Systems</li>
                        <li>Facilities Engineering</li>
                        <li>Transformer Design Optimization</li>
                        <li>Power System Analysis</li>
                        <li>Solar PV Solutions</li>
                        <li>Industrial Energy Efficiency</li>
                        <li>Smart Energy Systems</li>
                        <li>Compliance with International Standards (IEC 60076, IEEE)</li>
                    </ul>
                </div>
                <!-- Certifications -->
                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 transform hover:scale-105 content-searchable">
                    <h3 class="text-2xl font-semibold text-lime-700 mb-4 flex items-center">
                        <svg class="w-6 h-6 mr-3 text-lime-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        Certifications
                    </h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li>Scientific Writing for MSc Students</li>
                        <li>Fundamentals of Digital Marketing</li>
                        <li>Renewable Energy and Green Building Entrepreneurship</li>
                        <li>The Test of English Language Proficiency</li>
                        <li>UP SKILL SECOND EDITION'24</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="bg-white py-16">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">My Experience</h2>
            <div class="relative wrap overflow-hidden p-10 h-full">
                <!-- Timeline Line -->
                <div class="border-2-2 absolute border-opacity-20 border-emerald-700 h-full border" style="left: 50%; transform: translateX(-1px);"></div>

                <!-- Experience Item 1: TEC TRAFO - Research And Development Engineer -->
                <div class="mb-8 flex justify-between items-center w-full right-timeline">
                    <div class="order-1 w-5/12"></div>
                    <div class="z-20 flex items-center order-1 bg-emerald-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">1</h1>
                    </div>
                    <div class="order-1 bg-emerald-100 rounded-lg shadow-xl w-5/12 px-6 py-4 transition duration-300 transform hover:scale-105 content-searchable">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Research And Development Engineer</h3>
                        <p class="text-md leading-snug tracking-wide text-gray-700">TEC TRAFO - April 2025 – Present (3 months)</p>
                        <p class="text-md leading-snug tracking-wide text-gray-700 mb-2">Cairo, Egypt</p>
                        <ul class="list-disc list-inside text-gray-600 mt-2">
                            <li>Designing and developing advanced transformer solutions (medium and low voltage).</li>
                            <li>Conducting full transformer calculations: temperature rise, short-circuit forces, efficiency, and losses.</li>
                            <li>Leading R&D projects focused on green energy technologies like solar inverter transformers, battery energy storage, and smart grid solutions.</li>
                            <li>Driving new product innovation: developing and prototyping next-generation transformer designs for renewable energy and smart infrastructure.</li>
                            <li>Preparing technical documentation: datasheets, AutoCAD design drawings, and engineering reports.</li>
                            <li>Ensuring compliance with international standards (IEC 60076, IEEE).</li>
                            <li>Supporting company strategy in expanding into sustainable and energy-efficient product lines.</li>
                        </ul>
                    </div>
                </div>

                <!-- Experience Item 2: TEC TRAFO - Electrical Design Engineer -->
                <div class="mb-8 flex justify-between flex-row-reverse items-center w-full left-timeline">
                    <div class="order-1 w-5/12"></div>
                    <div class="z-20 flex items-center order-1 bg-emerald-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">2</h1>
                    </div>
                    <div class="order-1 bg-emerald-100 rounded-lg shadow-xl w-5/12 px-6 py-4 transition duration-300 transform hover:scale-105 content-searchable">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Electrical Design Engineer</h3>
                        <p class="text-md leading-snug tracking-wide text-gray-700">TEC TRAFO - August 2024 – April 2025 (9 months)</p>
                        <p class="text-md leading-snug tracking-wide text-gray-700 mb-2">Al Jizah, Egypt</p>
                        <ul class="list-disc list-inside text-gray-600 mt-2">
                            <li>Developing detailed transformer designs that meet client and industry standards.</li>
                            <li>Conducting technical analysis to optimize performance.</li>
                            <li>Collaborating with cross-functional teams to ensure smooth production.</li>
                            <li>Ensuring compliance with international standards like IEC.</li>
                            <li>Focused on delivering innovative, high-quality solutions that enhance TEC TRAFO’s global reputation.</li>
                        </ul>
                    </div>
                </div>

                <!-- Experience Item 3: iSON Xperiences - Electrical Engineer -->
                <div class="mb-8 flex justify-between items-center w-full right-timeline">
                    <div class="order-1 w-5/12"></div>
                    <div class="z-20 flex items-center order-1 bg-emerald-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">3</h1>
                    </div>
                    <div class="order-1 bg-emerald-100 rounded-lg shadow-xl w-5/12 px-6 py-4 transition duration-300 transform hover:scale-105 content-searchable">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Electrical Engineer</h3>
                        <p class="text-md leading-snug tracking-wide text-gray-700">iSON Xperiences - September 2024 – April 2025 (8 months)</p>
                        <p class="text-md leading-snug tracking-wide text-gray-700 mb-2">Cairo, Egypt</p>
                        <ul class="list-disc list-inside text-gray-600 mt-2">
                            <li>Oversee maintenance, inspection, and troubleshooting of electrical systems across multiple company facilities, including UPS, batteries, diesel generators, and HVAC systems.</li>
                            <li>Develop and implement energy-efficient solutions to reduce power consumption and enhance operational efficiency.</li>
                            <li>Ensure compliance with electrical safety standards, local codes, and industry regulations across all branches.</li>
                            <li>Manage and lead electrical projects from design to implementation, ensuring timely and budget-compliant delivery.</li>
                            <li>Maintain detailed documentation for electrical systems, including schematics and maintenance logs.</li>
                            <li>Perform regular diagnostics and repairs using advanced electrical testing equipment to ensure optimal system performance.</li>
                        </ul>
                    </div>
                </div>

                <!-- Experience Item 4: ARAB INTERNATIONAL OPTRONICS - Electrical Engineer -->
                <div class="mb-8 flex justify-between flex-row-reverse items-center w-full left-timeline">
                    <div class="order-1 w-5/12"></div>
                    <div class="z-20 flex items-center order-1 bg-emerald-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">4</h1>
                    </div>
                    <div class="order-1 bg-emerald-100 rounded-lg shadow-xl w-5/12 px-6 py-4 transition duration-300 transform hover:scale-105 content-searchable">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Electrical Engineer</h3>
                        <p class="text-md leading-snug tracking-wide text-gray-700">ARAB INTERNATIONAL OPTRONICS - May 2023 – May 2024 (1 year 1 month)</p>
                        <p class="text-md leading-snug tracking-wide text-gray-700 mb-2">Cairo, Egypt</p>
                        <ul class="list-disc list-inside text-gray-600 mt-2">
                            <li>As an Engineer (in military service) responsible for factory operations, with a pivotal role in ensuring the smooth functioning of various production units.</li>
                            <li>Expertise spans across different factories, including: LED factory, Camera factory, Electronics factory, Cables factory, Solar Cells factory.</li>
                        </ul>
                    </div>
                </div>

                <!-- Experience Item 5: Dar Alkahrbaa - Engineering Trainee -->
                <div class="mb-8 flex justify-between items-center w-full right-timeline">
                    <div class="order-1 w-5/12"></div>
                    <div class="z-20 flex items-center order-1 bg-emerald-600 shadow-xl w-8 h-8 rounded-full">
                        <h1 class="mx-auto font-semibold text-lg text-white">5</h1>
                    </div>
                    <div class="order-1 bg-emerald-100 rounded-lg shadow-xl w-5/12 px-6 py-4 transition duration-300 transform hover:scale-105 content-searchable">
                        <h3 class="mb-3 font-bold text-gray-800 text-xl">Engineering Trainee</h3>
                        <p class="text-md leading-snug tracking-wide text-gray-700">Dar Alkahrbaa - June 2022 – August 2022 (3 months)</p>
                        <p class="text-md leading-snug tracking-wide text-gray-700 mb-2">Cairo, Egypt</p>
                        <ul class="list-disc list-inside text-gray-600 mt-2">
                            <li>Gained foundational engineering experience in the field.</li>
                        </ul>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Education Section (Inserted after Experience) -->
    <section id="education" class="bg-gray-100 py-16">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">Education</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Master's Degree -->
                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 transform hover:scale-105 content-searchable">
                    <h3 class="text-2xl font-semibold text-teal-700 mb-4 flex items-center">
                        <svg class="w-6 h-6 mr-3 text-teal-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path></svg>
                        Master of Science - MS
                    </h3>
                    <p class="text-lg text-gray-800">Electrical Engineering Electrical Power & Machines</p>
                    <p class="text-md text-gray-700">Ain Shams University</p>
                    <p class="text-sm text-gray-600">February 2023 - Present (Ongoing research in Energy Management for Smart Buildings)</p>
                </div>
                <!-- Bachelor's Degree -->
                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 transform hover:scale-105 content-searchable">
                    <h3 class="mb-3 font-bold text-gray-800 text-xl">Bachelor's degree</h3>
                    <p class="text-lg text-gray-800">Electrical Power & Machines Engineering</p>
                    <p class="text-md text-gray-700">Ain Shams University (Faculty of engineering ain sham’s university)</p>
                    <p class="text-sm text-gray-600">2017 - 2022</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="bg-gray-100 py-16">
        <div class="container mx-auto px-4 max-w-5xl">
            <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">My Portfolio</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 (Generic for Electrical Engineering / R&D) -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transition duration-300 transform hover:scale-105 content-searchable">
                    <img src="https://placehold.co/400x250/047857/FFFFFF?text=R%26D+Project" alt="R&D Project" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-2">Advanced Transformer Solutions</h3>
                        <p class="text-gray-700 mb-4">Development of next-generation medium and low voltage transformers with optimized performance and efficiency.</p>
                        <!-- No specific link provided, keeping general link -->
                        <a href="#" target="_blank" rel="noopener noreferrer" class="text-emerald-600 hover:text-emerald-800 font-semibold flex items-center">
                            Learn More
                            <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0l-7 7m7-7v6"></path></svg>
                        </a>
                    </div>
                </div>
                <!-- Project 2 (Generic for Renewable Energy) -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transition duration-300 transform hover:scale-105 content-searchable">
                    <img src="https://placehold.co/400x250/6EE7B7/000000?text=Renewable+Energy" alt="Renewable Energy Project" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-2">Smart Energy Management Systems</h3>
                        <p class="text-gray-700 mb-4">Research and application in energy management for smart buildings, integrating renewable sources.</p>
                        <!-- No specific link provided, keeping general link -->
                        <a href="#" target="_blank" rel="noopener noreferrer" class="text-emerald-600 hover:text-emerald-800 font-semibold flex items-center">
                            Learn More
                            <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0l-7 7m7-7v6"></path></svg>
                        </a>
                    </div>
                </div>
                <!-- Project 3 (Generic for Power Systems) -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transition duration-300 transform hover:scale-105 content-searchable">
                    <img src="https://placehold.co/400x250/34D399/FFFFFF?text=Power+Systems" alt="Power Systems Project" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-2">Industrial Energy Efficiency Solutions</h3>
                        <p class="text-gray-700 mb-4">Implementation of energy-efficient solutions and optimization of electrical systems for industrial facilities.</p>
                        <!-- No specific link provided, keeping general link -->
                        <a href="#" target="_blank" rel="noopener noreferrer" class="text-emerald-600 hover:text-emerald-800 font-semibold flex items-center">
                            Learn More
                            <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0l-7 7m7-7v6"></path></svg>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-white py-16">
        <div class="container mx-auto px-4 max-w-3xl">
            <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">Get In Touch</h2>
            <p class="text-center text-lg text-gray-700 mb-10">
                I'm currently open to new opportunities and collaborations. Feel free to reach out!
            </p>
            <div class="bg-gray-100 p-8 rounded-xl shadow-lg content-searchable">
                <form class="space-y-6">
                    <div>
                        <label for="name" class="block text-lg font-medium text-gray-700 mb-2">Name</label>
                        <input type="text" id="name" name="name" class="w-full px-4 py-3 rounded-lg border-gray-300 focus:border-emerald-500 focus:ring-emerald-500 shadow-sm transition duration-200" placeholder="Your Name" required>
                    </div>
                    <div>
                        <label for="email" class="block text-lg font-medium text-gray-700 mb-2">Email</label>
                        <input type="email" id="email" name="email" class="w-full px-4 py-3 rounded-lg border-gray-300 focus:border-emerald-500 focus:ring-emerald-500 shadow-sm transition duration-200" placeholder="you@example.com" required>
                    </div>
                    <div>
                        <label for="message" class="block text-lg font-medium text-gray-700 mb-2">Message</label>
                        <textarea id="message" name="message" rows="6" class="w-full px-4 py-3 rounded-lg border-gray-300 focus:border-emerald-500 focus:ring-emerald-500 shadow-sm transition duration-200" placeholder="Tell me about your project or opportunity..." required></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-emerald-600 text-white hover:bg-emerald-700 px-8 py-4 rounded-full text-lg font-semibold shadow-xl transition transform hover:scale-105 duration-300">Send Message</button>
                    </div>
                </form>
            </div>

            <!-- Social Links / Direct Contact -->
            <div class="flex justify-center space-x-6 mt-12 content-searchable">
                <a href="mailto:mohamedasad4444@gmail.com" class="text-gray-600 hover:text-emerald-700 transition duration-300 flex items-center text-lg">
                    <svg class="w-6 h-6 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    Email
                </a>
                <a href="https://www.linkedin.com/in/mohamed-asaad-38b710162/" target="_blank" rel="noopener noreferrer" class="text-gray-600 hover:text-emerald-700 transition duration-300 flex items-center text-lg">
                    <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5s-2.48-1.119-2.48-2.5c0-1.381 1.11-2.5 2.48-2.5s2.48 1.119 2.48 2.5zm.02 4.5h-5v16h5v-16zm7.982 0h-4.968v16h4.969v-8.399c0-4.67 6.003-4.271 6.003 0v8.399h4.983v-10.136c0-6.627-7.004-6.36-8.981-3.14z"></path></svg>
                    LinkedIn
                </a>
                <a href="https://github.com/MohamedAsaaad/Asaad.git" target="_blank" rel="noopener noreferrer" class="text-gray-600 hover:text-emerald-700 transition duration-300 flex items-center text-lg">
                    <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M12 0C5.373 0 0 5.373 0 12c0 5.303 3.438 9.8 8.207 11.387.6.11.82-.26.82-.58v-2.09c-3.338.724-4.042-1.61-4.042-1.61-.546-1.387-1.332-1.758-1.332-1.758-1.088-.745.083-.73.083-.73 1.205.086 1.838 1.238 1.838 1.238 1.07 1.83 2.809 1.3 3.492.993.109-.773.418-1.3.762-1.6C8.595 16.4 5.253 15.148 5.253 9.47c0-1.3.465-2.36 1.238-3.2-.12-.3-.537-1.517.117-3.153 0 0 1.008-.32 3.3.93.957-.266 1.983-.399 3.003-.399 1.02 0 2.046.133 3.003.399 2.292-1.25 3.3-0.93 3.3-0.93.654 1.636.237 2.853.117 3.153.774.84 1.238 1.9 1.238 3.2 0 5.688-3.345 6.937-6.577 7.27.538.465.986 1.393.986 2.804v4.15c0 .32.22.69.827.57C20.565 21.792 24 17.3 24 12c0-6.627-5.373-12-12-12z"></path></svg>
                    GitHub
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 text-center rounded-t-xl">
        <div class="container mx-auto px-4">
            <p>&copy; <span id="current-year"></span> Mohamed Asaad. All rights reserved.</p>
            <p class="text-sm mt-2">Built with ❤️ and Tailwind CSS</p>
        </div>
    </footer>

    <script>
        // Set current year in footer
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Mobile navigation toggle
        const navToggle = document.getElementById('nav-toggle');
        const navContent = document.getElementById('nav-content');

        navToggle.addEventListener('click', () => {
            navContent.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const navLinks = navContent.querySelectorAll('a');
        navLinks.forEach(link => {
            link.addEventListener('click', () => {
                if (!navContent.classList.contains('hidden') && window.innerWidth < 1024) { // 1024px is Tailwind's 'lg' breakpoint
                    navContent.classList.add('hidden');
                }
            });
        });

        // --- Search Functionality ---
        const searchInput = document.getElementById('search-input');
        const searchButton = document.getElementById('search-button');
        let originalContent = {}; // Store original HTML content of searchable elements

        // Function to reset highlights and show all content
        function resetSearch() {
            document.querySelectorAll('.highlight').forEach(span => {
                const parent = span.parentNode;
                parent.replaceChild(document.createTextNode(span.textContent), span);
                parent.normalize(); // Combine adjacent text nodes
            });

            // Restore original display for all sections and content areas
            document.querySelectorAll('section').forEach(section => {
                section.style.display = ''; // Reset to default display
            });
            document.querySelectorAll('.content-searchable').forEach(el => {
                el.closest('section').style.display = ''; // Ensure parent section is visible
            });
        }

        // Function to perform the search
        function performSearch() {
            resetSearch(); // Clear previous highlights and show all sections

            const searchTerm = searchInput.value.trim();
            if (searchTerm === '') {
                return; // Do nothing if search term is empty
            }

            // Regular expression for the search term (case-insensitive)
            const regex = new RegExp(searchTerm, 'gi');
            let foundMatches = false;

            // Iterate over all sections that contain content-searchable elements
            document.querySelectorAll('section').forEach(section => {
                let sectionHasMatch = false;
                // Only search within elements marked with content-searchable or their children
                section.querySelectorAll('.content-searchable, .content-searchable *').forEach(element => {
                    // Temporarily store the original innerHTML if not already stored
                    if (!originalContent[element.id]) {
                        originalContent[element.id] = element.innerHTML;
                    }

                    // Only process text nodes to avoid breaking HTML structure
                    Array.from(element.childNodes).forEach(node => {
                        if (node.nodeType === Node.TEXT_NODE) { // Check if it's a text node
                            const text = node.nodeValue;
                            if (regex.test(text)) {
                                foundMatches = true;
                                sectionHasMatch = true;
                                const highlightedText = text.replace(regex, (match) => `<span class="highlight">${match}</span>`);
                                const tempDiv = document.createElement('div');
                                tempDiv.innerHTML = highlightedText;
                                // Replace the text node with the new highlighted nodes
                                while (tempDiv.firstChild) {
                                    element.insertBefore(tempDiv.firstChild, node);
                                }
                                element.removeChild(node);
                            }
                        }
                    });
                });

                // Hide sections that do not contain matches
                if (!sectionHasMatch && section.id !== 'home' && section.id !== 'contact') { // Keep Home and Contact always visible
                    section.style.display = 'none';
                } else {
                    section.style.display = ''; // Ensure matching sections are visible
                }
            });

            if (!foundMatches) {
                // You could add a "No results found" message here if needed
                console.log("No results found for '" + searchTerm + "'");
            }
        }

        // Event listener for search button click
        searchButton.addEventListener('click', performSearch);

        // Event listener for "Enter" key press in search input
        searchInput.addEventListener('keypress', (event) => {
            if (event.key === 'Enter') {
                performSearch();
            }
        });

        // Event listener for search input clear (e.g., backspace all text)
        searchInput.addEventListener('input', () => {
            if (searchInput.value.trim() === '') {
                resetSearch();
            }
        });

        // Initialize original content storage when the page loads
        document.addEventListener('DOMContentLoaded', () => {
            document.querySelectorAll('.content-searchable').forEach(el => {
                // Assign a unique ID if not present for tracking original content
                if (!el.id) {
                    el.id = 'searchable-element-' + Math.random().toString(36).substr(2, 9);
                }
                originalContent[el.id] = el.innerHTML;
            });
        });
    </script>
</body>
</html>
