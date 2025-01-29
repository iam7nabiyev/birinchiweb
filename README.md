<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="images/favicon.png">
    <link rel="shortcut icon" style="border-radius: 50%;" href="favicon-32x32.png" type="image/x-icon">
    <title>Shaxsiy Sayt</title>
    <style>

      /* Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background-color: #111;
    color: white;
}

/* HEADER STYLING */
header {
    background: #222;
    padding: 5px 0; /* Header balandligini kamaytirish */
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 1000;
    margin-left: 5px;
}

/* CONTAINER */
.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center; /* Logo va menyuni bitta chiziqqa joylash */
}

/* LOGO */
.logo img {
    height: 40px; /* Logotip hajmini kichikroq qilish */
    margin: 0; /* Qo‘shimcha bo‘shliqlarni olib tashlash */
}

/* NAVIGATION */
nav ul {
    list-style: none;
    display: flex;
    padding: 0;
    margin-left: 10px;
}

nav ul li {
    margin-left: 15px; /* Menyu bo‘limlari orasidagi masofani qisqartirish */
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: 600;
    transition: 0.3s;
    padding: 5px 8px; /* Tugmalarning balandligini kamaytirish */
    border-radius: 5px;
}

nav ul li a:hover {
    background: #00c3ff;
    color: #111;
}

/* HERO IMAGE */
.hero-image {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin-top: 60px; /* Header pastga yopishib qolmasligi uchun */
}

.hero-image img {
    max-width: 60%;
    border-radius: 45%;
}

/* RESPONSIVE DESIGN */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
        text-align: center;
    }

    nav ul {
        margin-top: 10px;
        flex-direction: column;
    }

    nav ul li {
        margin: 10px 0;
    }
}
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 format */
            height: 0;
            overflow: hidden;
            max-width: 100%;
            background: #000;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        </style>
        
        <div class="video-container">
            <iframe src="https://youtu.be/eGBqHzuUC3o?si=am1ah1nYMufxlIx7" allowfullscreen></iframe>
        </div>
</head>
<body>
    <div style="text-align: center;">
        <iframe width="560" height="315" src="https://youtu.be/eGBqHzuUC3o?si=am1ah1nYMufxlIx7" 
            title="YouTube video player" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
            allowfullscreen>
        </iframe>
    </div>    

    <header>
        <div class="container">
            <div class="logo">
                <img style="border-radius: 30px;" src="./status.jpg.jpg" alt="Sayt Logosi"></a>
            </div>
            <nav>
                <ul>
                    <li><a href="">Asosiy</a></li>
                    <li><a href="https://t.me/iam_nabiyev">Telegram</a></li>
                    <li><a href="https://instagram.com/iam_nabiyev">Instagram</a></li>
                    <li><a href="https://static3.tgstat.ru/channels/_0/62/62008c153d3e063849f3b8f3ca051ff4.jpg">Twitter</a></li>
                    <li><a href="https://www.instagram.com/abdulloh.domla?igsh=emJtbnAxcGR1eGZ3">Foydali</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="hero-image">
        <img src="" alt="Qandaydir rasm yoki matn bo'lishi mumkin bu joyda !?">
    </div>

</body>
</html>
