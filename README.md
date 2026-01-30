<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>GitHub Profile | Your Name</title>
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
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #fff;
            min-height: 100vh;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 40px 20px;
        }

        .profile {
            text-align: center;
            margin-bottom: 40px;
        }

        .profile img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            border: 4px solid #00e6e6;
            margin-bottom: 15px;
        }

        .profile h1 {
            font-size: 2.4rem;
            font-weight: 700;
        }

        .profile p {
            opacity: 0.85;
            font-size: 1.1rem;
        }

        .badges img {
            margin: 5px;
        }

        section {
            background: rgba(255, 255, 255, 0.08);
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 30px;
            backdrop-filter: blur(10px);
        }

        section h2 {
            margin-bottom: 15px;
            color: #00e6e6;
        }

        ul {
            list-style: none;
        }

        ul li {
            margin-bottom: 10px;
        }

        .skills span {
            display: inline-block;
            background: #00e6e6;
            color: #000;
            padding: 6px 14px;
            border-radius: 20px;
            margin: 6px;
            font-size: 0.9rem;
            font-weight: 500;
        }

        .stats img {
            width: 100%;
            max-width: 450px;
            margin: 10px auto;
            display: block;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            opacity: 0.7;
        }

        a {
            color: #00e6e6;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="container">

    <!-- Profile Section -->
    <div class="profile">
        <img src="https://avatars.githubusercontent.com/u/0000000?v=4" alt="Profile Image">
        <h1>Your Name</h1>
        <p>Java Full Stack Developer | Problem Solver | Tech Enthusiast 🚀</p>

        <div class="badges">
            <img src="https://komarev.com/ghpvc/?username=yourusername&color=00e6e6">
            <img src="https://img.shields.io/github/followers/yourusername?label=Followers&style=social">
        </div>
    </div>

    <!-- About Me -->
    <section>
        <h2>👨‍💻 About Me</h2>
        <p>
            I’m a passionate Full Stack Developer specializing in Java, Spring Boot,
            and modern web technologies. I love building scalable applications and
            continuously learning new tools and frameworks.
        </p>
    </section>

    <!-- Skills -->
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
            <span>Git</span>
        </div>
    </section>

    <!-- Projects -->
    <section>
        <h2>📂 Featured Projects</h2>
        <ul>
            <li>🚀 <b>Employee Management System</b> – Java, Spring Boot, MySQL</li>
            <li>🩺 <b>Disease Prediction System</b> – ML + Flask</li>
            <li>☁️ <b>Cloud Desktop Platform</b> – Virtual Desktop Access</li>
        </ul>
    </section>

    <!-- GitHub Stats -->
    <section class="stats">
        <h2>📊 GitHub Stats</h2>
        <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=tokyonight">
    </section>

    <!-- Contact -->
    <section>
        <h2>📫 Connect With Me</h2>
        <p>
            🔗 GitHub: <a href="https://github.com/yourusername">github.com/yourusername</a><br>
            💼 LinkedIn: <a href="#">linkedin.com/in/yourprofile</a><br>
            📧 Email: yourmail@gmail.com
        </p>
    </section>

    <footer>
        ⭐ If you like my work, consider starring my repositories!
    </footer>

</div>

</body>
</html>
