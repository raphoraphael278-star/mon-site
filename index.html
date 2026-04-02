<!DOCTYPE html>
<html>
<head>
    <title>Mon Super Site 🔥</title>

    <style>
    <style>
body {
    margin: 0;
    font-family: Arial;
    background: #0f0f0f;
    color: white;
}

/* MENU */
header {
    background: #111;
    padding: 15px;
    display: flex;
    justify-content: space-around;
    border-bottom: 2px solid red;
}

header button {
    background: none;
    border: none;
    color: white;
    font-size: 16px;
    cursor: pointer;
    transition: 0.3s;
}

header button:hover {
    color: red;
    transform: scale(1.1);
}

/* SECTIONS */
.section {
    display: none;
    padding: 20px;
    animation: fade 0.5s;
}

.active {
    display: block;
}

@keyframes fade {
    from {opacity: 0;}
    to {opacity: 1;}
}

/* CARTES */
.box {
    background: #1f1f1f;
    padding: 20px;
    margin: 15px;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(255,0,0,0.3);
    transition: 0.3s;
}

.box:hover {
    transform: scale(1.03);
}

/* BOUTONS */
button {
    padding: 10px;
    background: red;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 8px;
}

button:hover {
    background: darkred;
}

/* INPUT */
input {
    padding: 10px;
    width: 220px;
    border-radius: 5px;
    border: none;
}
</style>
    </style>
</head>

<body>

<header>
    <button onclick="show('home')">🏠 Accueil</button>
    <button onclick="show('video')">🎥 Vidéos</button>
    <button onclick="show('blog')">📰 Blog</button>
    <button onclick="show('game')">🎮 Jeux</button>
    <button onclick="show('profile')">👤 Profil</button>
</header>

<!-- ACCUEIL -->
<div id="home" class="section active">
    <h1>🔥 Bienvenue sur mon site</h1>
    <p>Explore : vidéos, blog, jeux et profil !</p>

    <div class="box">
        <h3>🚀 Nouveautés</h3>
        <p>✔ Nouveau jeu disponible</p>
        <p>✔ Nouveau blog ajouté</p>
    </div>
</div>

<!-- VIDEOS -->
<div id="video" class="section">
    <div class="box">
        <h2>🎥 Vidéo 1</h2>
        <video class="video" controls>
            <source src="video.mp4" type="video/mp4">
        </video>
    </div>

    <div class="box">
        <h2>🎥 Vidéo 2</h2>
        <video class="video" controls>
            <source src="video.mp4" type="video/mp4">
        </video>
    </div>
</div>

<!-- BLOG -->
<div id="blog" class="section">
    <div class="box">
        <h2>📰 Article 1</h2>
        <p>Bienvenue sur mon premier article !</p>
    </div>

    <div class="box">
        <h2>📰 Article 2</h2>
        <p>Voici un autre contenu intéressant 🔥</p>
    </div>
</div>

<!-- JEU -->
<div id="game" class="section">
    <div class="box">
        <h2>🐍 Snake (simple)</h2>
        <p>Utilise les flèches du clavier</p>
        <canvas id="gameCanvas" width="300" height="300" style="background:black;"></canvas>
    </div>
</div>

<!-- PROFIL -->
<div id="profile" class="section">
    <div class="box">
        <h2>🔐 Connexion</h2>

        <input type="text" id="username" placeholder="Nom"><br><br>
        <input type="password" id="password" placeholder="Mot de passe"><br><br>

        <button onclick="login()">Se connecter</button>

        <p id="message"></p>
    </div>
</div>

<script>
let score = 0;

function show(section) {
    let sections = document.querySelectorAll('.section');
    sections.forEach(s => s.classList.remove('active'));
    document.getElementById(section).classList.add('active');
}

function jouer() {
    score++;
    document.getElementById("score").innerText = "Score : " + score;
let canvas = document.getElementById("gameCanvas");
let ctx = canvas.getContext("2d");

let snake = [{x:10,y:10}];
let dx = 1;
let dy = 0;

document.addEventListener("keydown", changeDirection);

function changeDirection(e) {
    if(e.key === "ArrowUp") { dx=0; dy=-1; }
    if(e.key === "ArrowDown") { dx=0; dy=1; }
    if(e.key === "ArrowLeft") { dx=-1; dy=0; }
    if(e.key === "ArrowRight") { dx=1; dy=0; }
}

function draw() {
    ctx.clearRect(0,0,300,300);

    snake.forEach(part => {
        ctx.fillStyle = "lime";
        ctx.fillRect(part.x*10, part.y*10, 10, 10);
    });

    let head = {x: snake[0].x + dx, y: snake[0].y + dy};
    snake.unshift(head);
    snake.pop();
}

setInterval(draw, 100);
}
function login() {
    let user = document.getElementById("username").value;
    let pass = document.getElementById("password").value;

    if(user === "admin" && pass === "1234") {
        localStorage.setItem("user", user);
        document.getElementById("message").innerText = "Bienvenue " + user + " 🔥";
    } else {
        document.getElementById("message").innerText = "Erreur ❌";
    }
}


</script>
window.onload = function() {
    let user = localStorage.getItem("user");
    if(user) {
        document.getElementById("message").innerText = "Déjà connecté : " + user;
    }
}

</script>
</body>
</html>
