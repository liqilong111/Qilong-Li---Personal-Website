<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Qilong Li - Personal Website</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts (Inter) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Using Inter as the default font */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light gray background */
            color: #334155; /* Dark gray text */
        }
        .text-header {
            color: #0f172a;
        }
        .bg-card {
            background-color: #ffffff;
        }
        .border-custom {
            border-color: #e2e8f0;
        }
        .tag {
            background-color: #e0f2fe;
            color: #0c4a6e;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header / Navigation -->
    <header class="bg-white/90 backdrop-blur-sm fixed top-0 left-0 right-0 z-50 border-b border-custom">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-header">Qilong Li</a>
            <nav class="hidden md:flex space-x-8">
                <a href="#about" class="hover:text-sky-600 transition-colors duration-300">About</a>
                <a href="#publications" class="hover:text-sky-600 transition-colors duration-300">Publications</a>
                <a href="#awards" class="hover:text-sky-600 transition-colors duration-300">Awards & Honors</a>
                <a href="#contact" class="hover:text-sky-600 transition-colors duration-300">Contact</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden">
                <i data-lucide="menu"></i>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4 space-y-2">
            <a href="#about" class="block hover:text-sky-600 transition-colors duration-300">About</a>
            <a href="#publications" class="block hover:text-sky-600 transition-colors duration-300">Publications</a>
            <a href="#awards" class="block hover:text-sky-600 transition-colors duration-300">Awards & Honors</a>
            <a href="#contact" class="block hover:text-sky-600 transition-colors duration-300">Contact</a>
        </div>
    </header>

    <main class="container mx-auto px-6 pt-24">

        <!-- Hero Section -->
        <section id="home" class="text-center py-16 md:py-24">
            <img src="https://placehold.co/128x128/e0f2fe/0c4a6e?text=QL" alt="Qilong Li's Avatar" class="w-32 h-32 rounded-full mx-auto mb-6 border-4 border-sky-500 shadow-lg">
            <h1 class="text-4xl md:text-6xl font-bold text-header mb-4">Qilong Li</h1>
            <p class="text-xl md:text-2xl text-sky-600 mb-6">Professor | Doctoral Supervisor</p>
            <p class="max-w-3xl mx-auto text-lg text-slate-600">Dedicated researcher with a focus on immunology, parasitology, and the mechanisms of host-parasite interactions. Passionate about leveraging immunology and gene-editing to uncover novel therapeutic strategies.</p>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-20 bg-slate-50 rounded-lg">
             <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center text-header mb-12">About Me</h2>
                <div class="flex flex-col md:flex-row items-start gap-12">
                    <div class="md:w-2/3">
                        <p class="mb-4">I am a Professor and Doctoral Supervisor at the Key Laboratory of Important Zoonotic Diseases of Domestic Animals, Ministry of Education, Shenyang Agricultural University.</p>
                        <p class="mb-4">My research focuses on using immunological methods and gene-editing techniques to analyze the immunomodulatory effects of anti-malarial drugs and to elucidate the mechanisms of interaction between parasites (such as <em>Plasmodium</em>, <em>Toxoplasma gondii</em>, and <em>Trypanosoma</em>) and their hosts.</p>
                        <p class="mb-6">Previously, my master's research involved the discovery of natural compounds from food sources that can modulate immune responses and exhibit anti-triple-negative breast cancer activity, utilizing mass spectrometry.</p>
                        <p class="font-semibold text-header">To date, I have published 24 SCI-indexed papers as the first/corresponding author, with a cumulative impact factor of 236.3, including 4 papers in Nature series journals and 16 in CAS Q1 journals.</p>
                    </div>
                    <div class="md:w-1/3">
                        <div class="bg-card p-6 rounded-lg border border-custom">
                            <h3 class="text-xl font-semibold text-header mb-4">Positions & Education</h3>
                            <ul class="space-y-4">
                                <li>
                                    <p class="font-semibold">Professor & Doctoral Supervisor</p>
                                    <p class="text-sm text-slate-500">Shenyang Agricultural University</p>
                                </li>
                                <li>
                                    <p class="font-semibold">Ph.D. in Veterinary Medicine</p>
                                    <p class="text-sm text-slate-500">Shenyang Agricultural University</p>
                                </li>
                                <li>
                                    <p class="font-semibold">M.S. in Cell Biology</p>
                                    <p class="text-sm text-slate-500">Shenyang Agricultural University</p>
                                </li>
                                <li>
                                    <p class="font-semibold">B.S. in Biological Science</p>
                                    <p class="text-sm text-slate-500">Shenyang Agricultural University</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Publications Section -->
        <section id="publications" class="py-20">
            <h2 class="text-3xl font-bold text-center text-header mb-12">Selected Publications</h2>
            <div class="space-y-8 max-w-4xl mx-auto">
                <!-- Publication 1 -->
                <div class="bg-card p-6 rounded-lg border border-custom">
                    <p class="mb-2"><strong>Li Q</strong>, Yuan Q, et al. Dihydroartemisinin regulates immune cell heterogeneity by triggering a cascade reaction of CDK and MAPK phosphorylation. <em class="text-slate-600">Signal Transduction and Targeted Therapy</em>. 2022.</p>
                    <span class="tag text-xs font-medium px-2 py-1 rounded-full">Nature Series, IF 40.8</span>
                </div>
                <!-- Publication 2 -->
                <div class="bg-card p-6 rounded-lg border border-custom">
                    <p class="mb-2"><strong>Li Q</strong>, Liu T, et al. Malaria: past, present and future. <em class="text-slate-600">Signal Transduction and Targeted Therapy</em>. 2025. (Co-authored with Nobel laureate Prof. Youyou Tu)</p>
                     <span class="tag text-xs font-medium px-2 py-1 rounded-full">Nature Series, IF 40.8</span>
                </div>
                 <!-- Publication 3 -->
                <div class="bg-card p-6 rounded-lg border border-custom">
                    <p class="mb-2"><strong>Li Q</strong>, Lv K, et al. SOD3 suppresses early cellular immune responses to parasite infection. <em class="text-slate-600">Nature Communications</em>. 2024.</p>
                     <span class="tag text-xs font-medium px-2 py-1 rounded-full">Nature Series, IF 14.7</span>
                </div>
                 <!-- Publication 4 -->
                 <div class="bg-card p-6 rounded-lg border border-custom">
                    <p class="mb-2">Wei Z, Jiang N, Zhang Y, <strong>Li Q</strong>, et al. ß-hydroxybutyrate inhibits Plasmodium falciparum development and confers protection against rodent malaria. <em class="text-slate-600">Nature Metabolism</em>. 2025.</p>
                     <span class="tag text-xs font-medium px-2 py-1 rounded-full">Nature Series, IF 19.2</span>
                </div>
            </div>
            <p class="text-center mt-8 text-slate-600">Note: This is a selection of my 24 first/corresponding author publications.</p>
        </section>

         <!-- Awards & Honors Section -->
        <section id="awards" class="py-20 bg-slate-50 rounded-lg">
             <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center text-header mb-12">Awards & Honors</h2>
                <div class="grid md:grid-cols-2 gap-6 max-w-4xl mx-auto">
                    <!-- Award 1 -->
                    <div class="bg-card p-6 rounded-lg border border-custom">
                        <h3 class="font-semibold text-header mb-1">Young Top-notch Veterinary Talent</h3>
                        <p class="text-sm text-slate-500">Ministry of Agriculture and Rural Affairs (2023)</p>
                    </div>
                    <!-- Award 2 -->
                    <div class="bg-card p-6 rounded-lg border border-custom">
                        <h3 class="font-semibold text-header mb-1">National Scholarship for Doctoral Students</h3>
                        <p class="text-sm text-slate-500">Ministry of Education (2022-2024)</p>
                    </div>
                    <!-- Award 3 -->
                    <div class="bg-card p-6 rounded-lg border border-custom">
                        <h3 class="font-semibold text-header mb-1">First Prize, Academic Report</h3>
                        <p class="text-sm text-slate-500">Chinese Society of Parasitology (2024)</p>
                    </div>
                    <!-- Award 4 -->
                    <div class="bg-card p-6 rounded-lg border border-custom">
                        <h3 class="font-semibold text-header mb-1">Grand Prize, "Challenge Cup"</h3>
                        <p class="text-sm text-slate-500">Liaoning Provincial Competition (2017)</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 text-center">
            <h2 class="text-3xl font-bold text-header mb-4">Get In Touch</h2>
            <p class="max-w-xl mx-auto mb-8 text-slate-600">I am always open to discussing research, collaborations, or new opportunities. Please feel free to reach out.</p>
            <a href="mailto:drlql1995@163.com" class="bg-sky-600 hover:bg-sky-700 text-white font-bold py-3 px-8 rounded-lg transition-colors duration-300 inline-flex items-center">
                <i data-lucide="mail" class="w-5 h-5 mr-2"></i>
                Contact via Email
            </a>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-custom mt-16">
        <div class="container mx-auto px-6 py-6 text-center text-gray-500">
            <p>&copy; 2024 Qilong Li. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();

        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>



