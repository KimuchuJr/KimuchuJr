<!-- Glitch Text Background Animation -->
<div align="center" style="position: relative; overflow: hidden; padding: 20px 0; border-radius: 10px;">
    
    <!-- Animated Glitch Background SVG -->
    <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: -1; pointer-events: none; opacity: 0.07;">
        <svg width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
            <defs>
                <pattern id="glitchPattern" patternUnits="userSpaceOnUse" width="200" height="100">
                    <text x="10" y="40" font-family="Courier New, monospace" font-size="14" fill="#33FF33" opacity="0.7">
                        010101
                        <animate attributeName="x" values="10;15;10" dur="0.8s" repeatCount="indefinite"/>
                    </text>
                    <text x="50" y="70" font-family="Courier New, monospace" font-size="14" fill="#FF3366" opacity="0.7">
                        { } &lt;&gt;
                        <animate attributeName="y" values="70;72;70" dur="0.6s" repeatCount="indefinite"/>
                    </text>
                    <text x="100" y="20" font-family="Courier New, monospace" font-size="12" fill="#3366FF" opacity="0.7">
                        console.log()
                        <animate attributeName="opacity" values="0.7;0.3;0.7" dur="1.2s" repeatCount="indefinite"/>
                    </text>
                </pattern>
            </defs>
            <rect width="100%" height="100%" fill="url(#glitchPattern)" />
        </svg>
    </div>

    <!-- Your existing typing animation -->
    <h1>
        <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=40&duration=2800&pause=500&color=33FF33&center=true&vCenter=true&width=700&lines=Hey,+I'm+Kimuchu+👋;Founder+%7C+Software+Engineer;Building+Web+%26+IT+Solutions;Code.+Scale.+Innovate." alt="Typing SVG" />
    </h1>
    
    <p>
        <img src="termina-gh.gif" alt="Terminal animation" width="600"/>
    </p>
</div>

---

<div align="center">
    <h2>🚀 About Me</h2>
    <p>
        I'm a <strong>Software Engineer & IT Founder</strong> focused on building scalable web platforms, automation systems, and digital products.
        <br/>
        I combine <strong>engineering, systems thinking, and execution</strong> to turn ideas into production-ready solutions.
    </p>
    <p>
        💡 Currently building <strong>Pazet.io</strong> — an IT & Web Development company.
    </p>
</div>

---

<!-- Updated Connect Section with Animated Icons -->
<div align="center">
    <h2>🌐 Connect With Me</h2>
    <p>Let's collaborate, build, or talk tech.</p>
    <div>
        <!-- Animated LinkedIn Icon -->
        <a href="https://www.linkedin.com/in/kimuchu-njuguna-2a6031224/" style="display: inline-block; margin: 0 10px;">
            <svg width="50" height="50" viewBox="0 0 50 50">
                <rect x="10" y="10" width="30" height="30" rx="5" fill="#0077B5" stroke="#fff" stroke-width="2">
                    <animate attributeName="rx" values="5;15;5" dur="2s" repeatCount="indefinite"/>
                </rect>
                <text x="25" y="30" text-anchor="middle" font-family="Arial, sans-serif" font-size="14" fill="white" font-weight="bold">in</text>
                <animateTransform attributeName="transform" type="rotate" values="0 25 25;5 25 25;0 25 25;-5 25 25;0 25 25" dur="4s" repeatCount="indefinite"/>
            </svg>
        </a>
        
        <!-- Animated Instagram Icon -->
        <a href="https://www.instagram.com/kimuchu__/" style="display: inline-block; margin: 0 10px;">
            <svg width="50" height="50" viewBox="0 0 50 50">
                <defs>
                    <linearGradient id="instaGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                        <stop offset="0%" stop-color="#833ab4">
                            <animate attributeName="stop-color" values="#833ab4;#e1306c;#f56040;#833ab4" dur="3s" repeatCount="indefinite"/>
                        </stop>
                        <stop offset="50%" stop-color="#e1306c">
                            <animate attributeName="stop-color" values="#e1306c;#f56040;#833ab4;#e1306c" dur="3s" repeatCount="indefinite"/>
                        </stop>
                        <stop offset="100%" stop-color="#f56040">
                            <animate attributeName="stop-color" values="#f56040;#833ab4;#e1306c;#f56040" dur="3s" repeatCount="indefinite"/>
                        </stop>
                    </linearGradient>
                </defs>
                <rect x="10" y="10" width="30" height="30" rx="8" fill="url(#instaGrad)" stroke="#fff" stroke-width="2">
                    <animate attributeName="rx" values="8;15;8" dur="2s" repeatCount="indefinite"/>
                </rect>
                <circle cx="25" cy="25" r="6" fill="none" stroke="white" stroke-width="2"/>
                <circle cx="32" cy="18" r="2" fill="white"/>
            </svg>
        </a>
        
        <!-- Animated Facebook Icon -->
        <a href="https://www.facebook.com/kimuchu.jr" style="display: inline-block; margin: 0 10px;">
            <svg width="50" height="50" viewBox="0 0 50 50">
                <rect x="10" y="10" width="30" height="30" rx="5" fill="#1877F2" stroke="#fff" stroke-width="2">
                    <animate attributeName="width" values="30;28;30" dur="1.5s" repeatCount="indefinite"/>
                    <animate attributeName="height" values="30;28;30" dur="1.5s" repeatCount="indefinite"/>
                </rect>
                <text x="25" y="30" text-anchor="middle" font-family="Arial, sans-serif" font-size="16" fill="white" font-weight="bold">f</text>
            </svg>
        </a>
        
        <!-- Animated WhatsApp Icon -->
        <a href="https://wa.me/254746538783" style="display: inline-block; margin: 0 10px;">
            <svg width="50" height="50" viewBox="0 0 50 50">
                <circle cx="25" cy="25" r="15" fill="#25D366" stroke="#fff" stroke-width="2">
                    <animate attributeName="r" values="15;17;15" dur="1.8s" repeatCount="indefinite"/>
                </circle>
                <path d="M20,20 Q25,15 30,20 Q25,25 20,20" fill="white"/>
                <circle cx="30" cy="20" r="2" fill="white">
                    <animate attributeName="cy" values="20;22;20" dur="1s" repeatCount="indefinite"/>
                </circle>
            </svg>
        </a>
        
        <!-- Profile View Counter -->
        <img src="https://komarev.com/ghpvc/?username=KimuchuJr&style=for-the-badge" alt="Profile views" style="vertical-align: middle; margin-left: 15px;"/>
    </div>
</div>

---

<!-- Confetti Animation Section -->
<div align="center">
    <div style="position: relative; height: 100px; margin: 20px 0; overflow: hidden;">
        <!-- Confetti Elements -->
        <svg width="100%" height="100" style="position: absolute; top: 0; left: 0;">
            <!-- Confetti pieces -->
            <rect x="5%" y="0" width="8" height="8" fill="#FF3366" transform="rotate(45)">
                <animate attributeName="y" values="0;100;0" dur="3s" repeatCount="indefinite" begin="0s"/>
            </rect>
            <circle cx="15%" cy="0" r="4" fill="#33FF33">
                <animate attributeName="cy" values="0;100;0" dur="2.5s" repeatCount="indefinite" begin="0.5s"/>
            </circle>
            <rect x="25%" y="0" width="6" height="6" fill="#3366FF" transform="rotate(30)">
                <animate attributeName="y" values="0;100;0" dur="2.8s" repeatCount="indefinite" begin="1s"/>
            </rect>
            <circle cx="35%" cy="0" r="5" fill="#FFCC00">
                <animate attributeName="cy" values="0;100;0" dur="3.2s" repeatCount="indefinite" begin="0.8s"/>
            </circle>
            <rect x="45%" y="0" width="7" height="7" fill="#9933FF" transform="rotate(60)">
                <animate attributeName="y" values="0;100;0" dur="2.7s" repeatCount="indefinite" begin="1.5s"/>
            </rect>
            <circle cx="55%" cy="0" r="4" fill="#FF6633">
                <animate attributeName="cy" values="0;100;0" dur="3s" repeatCount="indefinite" begin="0.3s"/>
            </circle>
            <rect x="65%" y="0" width="8" height="8" fill="#00CCCC" transform="rotate(45)">
                <animate attributeName="y" values="0;100;0" dur="2.9s" repeatCount="indefinite" begin="1.2s"/>
            </rect>
            <circle cx="75%" cy="0" r="5" fill="#FF33CC">
                <animate attributeName="cy" values="0;100;0" dur="3.1s" repeatCount="indefinite" begin="0.7s"/>
            </circle>
            <rect x="85%" y="0" width="6" height="6" fill="#66FF33" transform="rotate(30)">
                <animate attributeName="y" values="0;100;0" dur="2.6s" repeatCount="indefinite" begin="2s"/>
            </rect>
        </svg>
        
        <h2>💻 Core Skills & Technologies</h2>
        <p><em>Focused on real-world, production-ready systems</em></p>
    </div>
</div>

<!-- Skills Section - Rest of your badges here -->
<div align="center">
    ### 🧠 Programming & Scripting
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
    <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
    <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
    <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white"/>

    ### 🌍 Web Development (Core Niche)
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>

    ### ⚙️ DevOps & Systems
    <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
    <img src="https://img.shields.io/badge/Git-181717?style=for-the-badge&logo=git&logoColor=white"/>
    <img src="https://img.shields.io/badge/YAML-0A0A0A?style=for-the-badge"/>

    ### 🎨 UI / Motion Identity
    <img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white"/>
    <img src="https://img.shields.io/badge/UI%20Motion-Flair%20Confetti-ff69b4?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/UX%2FUI-System%20Driven-blueviolet?style=for-the-badge"/>
</div>

---

<div align="center">
    <h2>✨ Design Philosophy</h2>
    <p>
        Clean UI. Purposeful motion. Performance-first systems.
        <br/>
        Inspired by <strong>GSAP motion, micro-interactions, and confetti-style visual flair</strong>.
    </p>
    
    <!-- Additional confetti at bottom -->
    <svg width="100%" height="40" style="margin: 20px 0;">
        <circle cx="10%" cy="20" r="3" fill="#33FF33">
            <animate attributeName="cy" values="20;10;20" dur="1.5s" repeatCount="indefinite"/>
        </circle>
        <rect x="20%" y="15" width="6" height="6" fill="#FF3366" transform="rotate(45)">
            <animate attributeName="y" values="15;25;15" dur="1.8s" repeatCount="indefinite"/>
        </rect>
        <circle cx="30%" cy="20" r="4" fill="#3366FF">
            <animate attributeName="cy" values="20;12;20" dur="2s" repeatCount="indefinite"/>
        </circle>
        <rect x="40%" y="18" width="5" height="5" fill="#FFCC00" transform="rotate(30)">
            <animate attributeName="y" values="18;28;18" dur="1.7s" repeatCount="indefinite"/>
        </rect>
        <circle cx="50%" cy="20" r="3" fill="#9933FF">
            <animate attributeName="cy" values="20;15;20" dur="1.9s" repeatCount="indefinite"/>
        </circle>
    </svg>
</div>
