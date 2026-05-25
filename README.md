<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Goutam Pradhan | Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
        }

        header {
            background-color: #161b22;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #238636;
        }

        header h1 {
            color: #58a6ff;
            font-size: 2.5rem;
            margin-bottom: 5px;
        }

        header p {
            color: #8b949e;
            font-size: 1.1rem;
            font-weight: bold;
        }

        .container {
            max-width: 900px;
            margin: 30px auto;
            padding: 0 20px;
        }

        section {
            background-color: #161b22;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 6px;
            border: 1px solid #30363d;
        }

        h2 {
            color: #238636;
            margin-bottom: 15px;
            border-bottom: 1px solid #30363d;
            padding-bottom: 5px;
        }

        .skills-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }

        .tag {
            background-color: #21262d;
            color: #58a6ff;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
            border: 1px solid #30363d;
        }

        .project-card {
            background-color: #21262d;
            border: 1px solid #30363d;
            padding: 20px;
            border-radius: 6px;
            margin-bottom: 15px;
        }

        .project-card h3 {
            color: #58a6ff;
            margin-bottom: 8px;
        }

        .project-card p {
            font-size: 0.95rem;
            color: #8b949e;
            margin-bottom: 12px;
        }

        .btn {
            display: inline-block;
            background-color: #238636;
            color: white;
            padding: 8px 16px;
            text-decoration: none;
            border-radius: 6px;
            font-size: 0.9rem;
            font-weight: bold;
            transition: background 0.2s;
        }

        .btn:hover {
            background-color: #2ea043;
        }

        .contact-links a {
            color: #58a6ff;
            text-decoration: none;
            margin-right: 20px;
            font-weight: bold;
        }

        .contact-links a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #8b949e;
            font-size: 0.9rem;
            border-top: 1px solid #30363d;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Goutam Pradhan</h1>
        <p>Cybersecurity Student | Python Developer | Ethical Hacker</p>
    </header>

    <div class="container">
        
        <!-- About Me Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>
                Hello! Ami Goutam. Ami ekti Government Polytechnic college-er student ebong cyber security niye kaj korte khub bhalobashi. 
                Linux terminal, automation, tools development ebong security testing-e amar bishesh agroho ache. 
                Ami nijoswo scripting ebong open-source tools banano shikhi ebong segoor upore kaj kori.
            </p>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="skills-tags">
                <span class="tag">Linux / Kali Linux</span>
                <span class="tag">Python Programming</span>
                <span class="tag">Network Security</span>
                <span class="tag">Ethical Hacking</span>
                <span class="tag">Penetration Testing</span>
                <span class="tag">Git & GitHub</span>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2>My Projects</h2>

            <!-- Project 1 -->
            <div class="project-card">
                <h3>G-CYBER SCAN</h3>
                <p>Eti ekti Python-based OSINT framework jeta data leaks track korte ebong security information verify korte sahajjo kore. Ete email breach check system dynamic bhabe implement kora hoyeche.</p>
                <a href="#" class="btn">View Source Code</a>
            </div>

            <!-- Project 2 -->
            <div class="project-card">
                <h3>AI Linux Terminal Assistant</h3>
                <p>Gemini API logic use kore ekti custom script jeta Linux terminal-er command errors automatic monitor kore ebong voice-enabled query ba correction recommendation provide kore.</p>
                <a href="#" class="btn">View Source Code</a>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact & Socials</h2>
            <p style="margin-bottom: 15px;">Amar sathe jogajog korte ba amar kaj dekhte nicher link gulo follow korte paro:</p>
            <div class="contact-links">
                <a href="https://github.com" target="_blank">GitHub</a>
                <a href="https://linkedin.com" target="_blank">LinkedIn</a>
                <a href="https://youtube.com" target="_blank">YouTube Channel</a>
            </div>
        </section>

    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2026 Goutam Pradhan. All Rights Reserved.</p>
    </footer>

</body>
</html>
