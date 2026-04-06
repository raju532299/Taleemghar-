# Taleemghar-
<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taleem Ghar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0077b6;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #023e8a;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        .video-container {
            text-align: center;
            margin-bottom: 30px;
        }
        iframe {
            width: 80%;
            height: 450px;
            border: none;
        }
        .mcq, .awards {
            margin-bottom: 30px;
        }
        h2 {
            color: #0077b6;
        }
        button {
            padding: 10px 20px;
            background-color: #0077b6;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #023e8a;
        }
    </style>
</head>
<body>
    <header>
        <h1>Taleem Ghar</h1>
        <p>Ghar baithe taleem hasil karein</p>
    </header>

    <nav>
        <a href="#videos">Videos</a>
        <a href="#mcqs">MCQs</a>
        <a href="#awards">Awards</a>
    </nav>

    <section id="videos">
        <h2>Video Lessons</h2>
        <div class="video-container">
            <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
        </div>
        <div class="video-container">
            <iframe src="https://www.youtube.com/embed/3JZ_D3ELwOQ" allowfullscreen></iframe>
        </div>
    </section>

    <section id="mcqs">
        <h2>MCQs Practice</h2>
        <div class="mcq">
            <p>1. Pakistan ka darul hukoomat ka shehar kon sa hai?</p>
            <button onclick="alert('Sahi Jawab: Islamabad')">Islamabad</button>
            <button onclick="alert('Galat Jawab')">Karachi</button>
            <button onclick="alert('Galat Jawab')">Lahore</button>
        </div>
        <div class="mcq">
            <p>2. Suraj ka rang kya hai?</p>
            <button onclick="alert('Galat Jawab')">Neela</button>
            <button onclick="alert('Sahi Jawab: Peela')">Peela</button>
            <button onclick="alert('Galat Jawab')">Hara</button>
        </div>
    </section>

    <section id="awards">
        <h2>Awards</h2>
        <div class="awards">
            <p>Apki progress: 80%</p>
            <p>Aapko Silver Medal mila hai!</p>
        </div>
    </section>

    <footer style="text-align:center; padding:20px; background:#0077b6; color:white;">
        &copy; 2026 Taleem Ghar. Sab rights mehfooz hain.
    </footer>
</body>
</html>
