<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aabel Aby - Software Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0d1117;
            --border-color: #30363d;
            --text-primary: #c9d1d9;
            --text-secondary: #8b949e;
            --accent-color: #58a6ff;
            --card-bg: #161b22;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-primary);
        }
        .icon-link {
            color: var(--text-secondary);
        }
        .icon-link:hover {
            color: var(--accent-color);
        }
        .skill-icon {
            transition: transform 0.2s;
        }
        .skill-icon:hover {
            transform: scale(1.2);
        }
    </style>
</head>
<body class="antialiased">

    <div class="container mx-auto p-4 md:p-8">
        
        <!-- Main Content -->
        <main>
            <div class="border border-gray-700 rounded-lg p-6 bg-[var(--card-bg)]">
                <div class="flex items-center mb-6">
                    <img class="rounded-full w-24 h-24 border-2 border-gray-700 mr-6" src="https://raw.githubusercontent.com/aabelaby/aabelaby.github.io/refs/heads/main/files/images/Firefly%2020241019190438.png" alt="Aabel Aby">
                    <div>
                        <h1 class="text-3xl font-bold text-white">Aabel Aby</h1>
                        <p class="text-xl text-gray-400">aabelaby</p>
                    </div>
                </div>

                <p class="text-lg">👋 Hi, I'm Aabel Aby</p>
                <p class="mt-4 text-gray-400">
                    I'm a passionate and dedicated student pursuing a B.Tech in Computer Science, with a strong focus on **Software Engineering** and **Full-Stack Development**.
                </p>
                <p class="mt-2 text-gray-400">
                    I thrive on building elegant and effective solutions to complex problems. My journey in technology is driven by a deep interest in Python, Django, and AI/ML. I enjoy the process of turning creative ideas into tangible applications and have a solid background in both front-end and back-end development.
                </p>
                <ul class="mt-4 text-gray-400 space-y-2">
                    <li class="flex items-center gap-2">
                        <i class="fas fa-globe"></i> See my portfolio at <a href="https://aabelaby.pages.dev" target="_blank" class="text-blue-400 hover:underline">aabelaby.pages.dev</a>
                    </li>
                    <li class="flex items-center gap-2">
                        <i class="fab fa-github"></i> Find me on <a href="https://github.com/aabelaby" target="_blank" class="text-blue-400 hover:underline">GitHub</a>
                    </li>
                     <li class="flex items-center gap-2">
                        <i class="fab fa-linkedin"></i> Connect with me on <a href="https://www.linkedin.com/in/aabelaby" target="_blank" class="text-blue-400 hover:underline">LinkedIn</a>
                    </li>
                    <li class="flex items-center gap-2">
                        <i class="fas fa-envelope"></i> You can contact me at <a href="mailto:aabelaby2003@gmail.com" class="text-blue-400 hover:underline">aabelaby2003@gmail.com</a>
                    </li>
                    <li class="flex items-center gap-2">
                        <i class="fas fa-lightbulb"></i> I’m open to collaborating on innovative open-source projects.
                    </li>
                </ul>
                <div class="flex flex-wrap gap-4 mt-6">
                    <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" class="w-8 h-8 skill-icon" title="Python">
                    <img src="https://www.vectorlogo.zone/logos/djangoproject/djangoproject-icon.svg" class="w-8 h-8 skill-icon" title="Django">
                    <img src="https://www.vectorlogo.zone/logos/java/java-icon.svg" class="w-8 h-8 skill-icon" title="Java">
                    <img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" class="w-8 h-8 skill-icon" title="HTML5">
                    <img src="https://www.vectorlogo.zone/logos/w3_css/w3_css-icon.svg" class="w-8 h-8 skill-icon" title="CSS3">
                    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" class="w-8 h-8 skill-icon" title="Git">
                </div>
            </div>

            <div class="mt-8">
                <h2 class="text-xl font-semibold text-white mb-4">Pinned</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div class="border border-gray-700 rounded-lg p-4 bg-[var(--card-bg)]">
                        <a href="https://github.com/aabelaby/Personalized-Skincare-Recommendations" target="_blank" class="font-bold text-blue-400 hover:underline">Personalized Skincare Recommendation System</a>
                        <p class="text-sm text-gray-400 mt-2">A web application providing tailored skincare recommendations based on user input, with secure authentication and database storage using Django.</p>
                    </div>
                    <div class="border border-gray-700 rounded-lg p-4 bg-[var(--card-bg)]">
                        <a href="https://github.com/aabelaby/YouTube-Vedio-Converter" target="_blank" class="font-bold text-blue-400 hover:underline">YouTube Video Downloader</a>
                        <p class="text-sm text-gray-400 mt-2">A Django-based web application that allows users to download YouTube videos in various formats and qualities.</p>
                    </div>
                </div>
            </div>

            <div class="mt-8">
                 <h2 class="text-xl font-semibold text-white mb-4">Contribution Activity</h2>
                 <div class="border border-gray-700 rounded-lg p-4 bg-[var(--card-bg)]">
                    <p class="text-gray-400">Contribution graph placeholder. This would typically be a dynamic SVG generated by GitHub.</p>
                    <div class="mt-4 bg-gray-800 p-4 rounded">
                        <svg width="100%" height="120">
                            <!-- Placeholder for contribution graph -->
                            <rect x="10" y="20" width="10" height="10" fill="#161b22" />
                            <rect x="25" y="35" width="10" height="10" fill="#0e4429" />
                            <rect x="40" y="50" width="10" height="10" fill="#006d32" />
                            <rect x="55" y="20" width="10" height="10" fill="#26a641" />
                            <rect x="70" y="60" width="10" height="10" fill="#39d353" />
                            <rect x="85" y="20" width="10" height="10" fill="#161b22" />
                            <!-- ... more placeholder rects -->
                        </svg>
                    </div>
                 </div>
            </div>

        </main>
    </div>

</body>
</html>
