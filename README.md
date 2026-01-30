<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>GitHub Profile | Thejas M R</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            min-height: 100vh;
            background: linear-gradient(135deg, #141e30, #243b55);
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
        }

        .container {
            max-width: 900px;
            width: 100%;
            padding: 40px 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.08);
            border-radius: 20px;
            padding: 35px;
            backdrop-filter: blur(12px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }

        .profile {
            text-align: center;
            margin-bottom: 35px;
        }

        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #00f5ff;
            margin-bottom: 15px;
        }

        .profile h1 {
            font-size: 2.5rem;
            font-weight: 700;
        }

        .profile p {
            opacity: 0.85;
            margin-top: 6px;
            font-size: 1.1rem;
        }

        section {
            margin-top: 30px;
        }

        section h2 {
            color: #00f5ff;
            margin-bottom: 12px;
        }

        .skills span {
            display: inline-block;
            background: #00f5ff;
            color: #000;
            padding: 8px 16px;
            border-radius: 25px;
            margin: 6px;
            font-size: 0.9rem;
            font-weight: 600;
        }

        ul {
            list-style: none;
        }

        ul li {
            margin-bottom: 10px;
            opacity: 0.9;
        }

        .stats img {
            width: 100%;
            max-width: 420px;
            display: block;
            margin: 15px auto;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            opacity: 0.7;
        }

        a {
            color: #00f5ff;
            text-decoration: none;
            font-weight: 500;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="card">

    <!-- PROFILE -->
<div class="profile">
            <img src="https://avatars.githubusercontent.com/u/1?v=4" alt="Profile">
            <h1>Thejas M R</h1>
            <p>Java Full Stack Developer | Problem Solver 🚀</p>
        </div>

        <!-- ABOUT -->
<section>
            <h2>👋 About Me</h2>
            <p>
                I’m a passionate Java Full Stack Developer with strong knowledge
                in Core Java, Spring Boot, and web technologies.
                I love building clean, scalable, and real-world applications.
            </p>
        </section>

        <!-- SKILLS -->
<section>
            <h2>🛠 Skills</h2>
            <div class="skills">
                <span>Java</span>
                <span>Spring Boot</span>
                <span>Hibernate</span>
                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
                <span>MySQL</span>
                <span>Git & GitHub</span>
            </div>
        </section>

        <!-- PROJECTS -->
<section>
            <h2>📂 Projects</h2>
            <ul>
                <li>🚀 Employee Management System – Java, Spring Boot</li>
                <li>🩺 Disease Prediction System – ML + Flask</li>
                <li>☁️ Cloud Desktop Platform – Remote Virtual Desktop</li>
            </ul>
        </section>

        <!-- GITHUB STATS -->
<section class="stats">
            <h2>📊 GitHub Stats</h2>
            <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=tokyonight">
        </section>

        <!-- CONTACT -->
<section>
            <h2>📫 Contact</h2>
            <p>
                GitHub: <a href="https://github.com/yourusername">github.com/yourusername</a><br>
                LinkedIn: <a href="#">linkedin.com/in/yourprofile</a><br>
                Email: yourmail@gmail.com
            </p>
        </section>

 <footer>
            ⭐ Thanks for visiting my profile!
        </footer>

 </div>
</div>

</body>
</html>
