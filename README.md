<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aabel Aby - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0F101E;
            color: #E0E0E0;
        }
        .gradient-text {
            background: linear-gradient(90deg, #A855F7, #6366F1);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
        }
        .btn-primary {
            @apply bg-purple-600 hover:bg-purple-700 text-white font-bold py-3 px-6 rounded-lg transition-transform transform hover:scale-105;
        }
        .btn-secondary {
            @apply bg-gray-700 hover:bg-gray-600 text-white font-bold py-3 px-6 rounded-lg transition-transform transform hover:scale-105;
        }
        .section-title {
            @apply text-3xl md:text-4xl font-bold text-center mb-12 gradient-text;
        }
        .card {
            @apply bg-gray-800/50 backdrop-blur-sm border border-gray-700 rounded-xl p-6 transition-all duration-300 hover:border-purple-500 hover:shadow-2xl hover:shadow-purple-500/10;
        }
        .icon-link {
             @apply text-gray-400 hover:text-purple-400 transition-colors;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-opacity-80 backdrop-blur-md bg-[#0F101E]/80 border-b border-gray-800">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold gradient-text">Aabel Aby</a>
            <nav class="hidden md:flex space-x-8">
                <a href="#about" class="text-gray-300 hover:text-purple-400 transition-colors">About</a>
                <a href="#projects" class="text-gray-300 hover:text-purple-400 transition-colors">Projects</a>
                <a href="#contact" class="text-gray-300 hover:text-purple-400 transition-colors">Contact</a>
            </nav>
            <!-- Mobile nav button can be added here if needed -->
        </div>
    </header>

    <main class="container mx-auto px-6">

        <!-- Hero Section -->
        <section id="home" class="min-h-screen flex flex-col justify-center items-center text-center pt-24">
            <h1 class="text-5xl md:text-7xl font-extrabold mb-4">
                <span class="gradient-text">Aabel Aby</span>
            </h1>
            <p class="max-w-3xl text-lg md:text-xl text-gray-400 mb-8">
                A student exploring web, design, and stories. I write code for people. Currently building tools and learning along the way.
            </p>
            <div class="flex flex-wrap justify-center gap-4 mb-12">
                <a href="#about" class="btn-primary">Explore My Work</a>
                <a href="https://github.com/aabelaby/Assets/blob/e206f515efec7446117d839ae39b172e6be26acc/final%20resume%20aabel.pdf" target="_blank" rel="noopener noreferrer" class="btn-secondary">Download CV</a>
                <a href="#contact" class="btn-secondary">Get In Touch</a>
            </div>
            <a href="#about" class="absolute bottom-10 animate-bounce">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-500 w-8 h-8"><path d="M12 5v14"/><path d="m19 12-7 7-7-7"/></svg>
            </a>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-20">
            <h2 class="section-title">About Me</h2>
            
            <div class="mb-16">
                <h3 class="text-2xl font-semibold text-center text-gray-200 mb-8">Leadership & Activities</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                    <div class="card text-center">
                        <h4 class="font-bold text-lg text-white">Lead Organizer</h4>
                        <p class="text-gray-400">Hack Club</p>
                    </div>
                    <div class="card text-center">
                        <h4 class="font-bold text-lg text-white">Google DSC Lead</h4>
                        <p class="text-gray-400">Google Developers</p>
                    </div>
                    <div class="card text-center">
                        <h4 class="font-bold text-lg text-white">Co-Founder</h4>
                        <p class="text-gray-400">TinkerHub</p>
                    </div>
                    <div class="card text-center">
                        <h4 class="font-bold text-lg text-white">Lead Organizer</h4>
                        <p class="text-gray-400">Pehia Foundation</p>
                    </div>
                </div>
            </div>

            <div class="mb-16">
                <h3 class="text-2xl font-semibold text-center text-gray-200 mb-8">Experiential Learning</h3>
                <div class="max-w-3xl mx-auto space-y-6">
                    <div class="card">
                        <h4 class="font-bold text-lg text-white">Young Innovators Programme S4.0</h4>
                        <p class="text-gray-400">Kerala Startup Mission (KSUM)</p>
                        <p class="text-sm text-gray-500 mt-2">Gained insights into the startup ecosystem and developed innovative project ideas.</p>
                    </div>
                     <div class="card">
                        <h4 class="font-bold text-lg text-white">Full Stack Web Development Intern</h4>
                        <p class="text-gray-400">TinkerHub Foundation</p>
                        <p class="text-sm text-gray-500 mt-2">Contributed to real-world projects, honing skills in both front-end and back-end technologies.</p>
                    </div>
                </div>
            </div>

            <div>
                <h3 class="text-2xl font-semibold text-center text-gray-200 mb-8">Technical Skills</h3>
                <div class="flex flex-wrap justify-center items-center gap-6 max-w-4xl mx-auto">
                    <!-- Icons for skills -->
                    <div class="p-3 bg-gray-800 rounded-full" title="Python"><svg class="w-8 h-8 text-yellow-400" fill="currentColor" viewBox="0 0 24 24"><path d="M12.23 8.42c-.32-.2-.68-.31-1.05-.31-1.01 0-1.83.82-1.83 1.83s.82 1.83 1.83 1.83c.37 0 .73-.11 1.05-.31v-1.21c.01-.56-.44-1.02-1-1.03zm-2.26 5.86c.32.2.68.31 1.05.31 1.01 0 1.83-.82 1.83-1.83s-.82-1.83-1.83-1.83c-.37 0-.73.11-1.05.31v1.21c-.01.56.44 1.02 1 1.03zm-1.81-3.64V6.5h6.16v1.24h-4.32v1.89h3.49v1.24h-3.49v1.94h4.41v1.24H8.16v-4.13zm10.23 3.64c-1.28 0-2.32-1.04-2.32-2.32s1.04-2.32 2.32-2.32 2.32 1.04 2.32 2.32-1.04 2.32-2.32 2.32zm0-3.4c-.6 0-1.08.48-1.08 1.08s.48 1.08 1.08 1.08 1.08-.48 1.08-1.08-.48-1.08-1.08-1.08z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="Java"><svg class="w-8 h-8 text-orange-500" fill="currentColor" viewBox="0 0 24 24"><path d="M12.23 8.42c-.32-.2-.68-.31-1.05-.31-1.01 0-1.83.82-1.83 1.83s.82 1.83 1.83 1.83c.37 0 .73-.11 1.05-.31v-1.21c.01-.56-.44-1.02-1-1.03zm-2.26 5.86c.32.2.68.31 1.05.31 1.01 0 1.83-.82 1.83-1.83s-.82-1.83-1.83-1.83c-.37 0-.73.11-1.05.31v1.21c-.01.56.44 1.02 1 1.03zm-1.81-3.64V6.5h6.16v1.24h-4.32v1.89h3.49v1.24h-3.49v1.94h4.41v1.24H8.16v-4.13zm10.23 3.64c-1.28 0-2.32-1.04-2.32-2.32s1.04-2.32 2.32-2.32 2.32 1.04 2.32 2.32-1.04 2.32-2.32 2.32zm0-3.4c-.6 0-1.08.48-1.08 1.08s.48 1.08 1.08 1.08 1.08-.48 1.08-1.08-.48-1.08-1.08-1.08z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="JavaScript"><svg class="w-8 h-8 text-yellow-300" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1.25 14.25H9.5V9.75h1.25v4.5zm2.5 0h-1.25V9.75h1.25v4.5z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="HTML5"><svg class="w-8 h-8 text-orange-600" fill="currentColor" viewBox="0 0 24 24"><path d="m12 2-10 3v11l10 5 10-5V5l-10-3zm-1.03 15.24-3.47-1.8V8.53l3.47 1.8v7.91zm2.06 0V10.33l3.47-1.8v7.03l-3.47 1.8zM5.19 7.47l6.81-3.57 6.81 3.57-6.81 3.57-6.81-3.57z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="CSS3"><svg class="w-8 h-8 text-blue-500" fill="currentColor" viewBox="0 0 24 24"><path d="m12 2-10 3v11l10 5 10-5V5l-10-3zm-1.03 15.24-3.47-1.8V8.53l3.47 1.8v7.91zm2.06 0V10.33l3.47-1.8v7.03l-3.47 1.8zM5.19 7.47l6.81-3.57 6.81 3.57-6.81 3.57-6.81-3.57z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="React"><svg class="w-8 h-8 text-cyan-400" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-13h2v2h-2zm0 4h2v6h-2z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="Node.js"><svg class="w-8 h-8 text-green-500" fill="currentColor" viewBox="0 0 24 24"><path d="M9 3v10.55c-.59-.34-1.27-.55-2-.55-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4V7h4V3H9z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="Git"><svg class="w-8 h-8 text-red-500" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 14H9V8h2v8zm4 0h-2V8h2v8z"/></svg></div>
                    <div class="p-3 bg-gray-800 rounded-full" title="Figma"><svg class="w-8 h-8 text-pink-500" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zM15 9H9v6h6V9z"/></svg></div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-20">
            <h2 class="section-title">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                <div class="card flex flex-col">
                    <h3 class="text-xl font-bold text-white mb-2">Personalized Skincare Recommendation System</h3>
                    <p class="text-gray-400 flex-grow mb-4">A machine learning model that suggests skincare products based on user's skin type, concerns, and ingredient preferences.</p>
                    <div class="mt-auto">
                        <a href="https://github.com/aabelaby/Personalized-Skincare-Recommendations" target="_blank" rel="noopener noreferrer" class="font-semibold text-purple-400 hover:text-purple-300">View Code &rarr;</a>
                    </div>
                </div>
                <div class="card flex flex-col">
                    <h3 class="text-xl font-bold text-white mb-2">YouTube Video Downloader</h3>
                    <p class="text-gray-400 flex-grow mb-4">A simple and efficient tool to download YouTube videos in various formats and resolutions directly to your device.</p>
                    <div class="mt-auto">
                        <a href="https://github.com/aabelaby/YouTube-Vedio-Converter" target="_blank" rel="noopener noreferrer" class="font-semibold text-purple-400 hover:text-purple-300">View Code &rarr;</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 text-center">
            <h2 class="section-title">Let's Connect</h2>
            <p class="max-w-2xl mx-auto text-lg text-gray-400 mb-8">
                I'm always open to discussing new projects, creative ideas or opportunities to be part of an amazing team.
            </p>
            
            <div class="flex justify-center space-x-6 mb-12">
                <a href="https://github.com/aabelaby" target="_blank" rel="noopener noreferrer" class="icon-link" title="GitHub">
                    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
                </a>
                <a href="https://www.linkedin.com/in/aabelaby1410/" target="_blank" rel="noopener noreferrer" class="icon-link" title="LinkedIn">
                    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
                </a>
                <a href="https://x.com/i_aabel" target="_blank" rel="noopener noreferrer" class="icon-link" title="Twitter">
                     <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 4H6c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2z"></path><path d="m9.5 8.5 5 7"></path><path d="m14.5 8.5-5 7"></path></svg>
                </a>
                <a href="mailto:aabelaby2003@gmail.com" class="icon-link" title="Email">
                    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
                </a>
            </div>

            <div class="max-w-2xl mx-auto bg-gray-800/50 border border-gray-700 rounded-xl p-8">
                <h3 class="text-2xl font-bold text-white mb-2">Ready to Collaborate?</h3>
                <p class="text-gray-400 mb-6">Whatever you have in mind, I'm here to listen. Let's create something amazing together.</p>
                <a href="mailto:aabelaby2003@gmail.com" class="btn-primary inline-block">Send me an email</a>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="text-center py-8 border-t border-gray-800">
        <p class="text-gray-500">Designed & Built by Aabel Aby</p>
    </footer>

</body>
</html>
