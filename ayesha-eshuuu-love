DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ayesha Mahad ❤️</title>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #ff4e8d, #ff9ecf);
    color: white;
    text-align: center;
    overflow: hidden;
}

.container {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    padding: 20px;
}

h1 {
    font-family: 'Dancing Script', cursive;
    font-size: 3em;
    margin-bottom: 10px;
}

p {
    font-size: 1.2em;
    margin: 15px 0;
}

button {
    background: white;
    color: #ff4e8d;
    border: none;
    padding: 15px 30px;
    font-size: 1.2em;
    border-radius: 30px;
    cursor: pointer;
    transition: 0.3s;
    margin-top: 20px;
}

button:hover {
    background: #ffe6f0;
    transform: scale(1.1);
}

.heart {
    position: absolute;
    color: rgba(255,255,255,0.8);
    font-size: 20px;
    animation: float 6s linear infinite;
}

@keyframes float {
    from { transform: translateY(100vh); }
    to { transform: translateY(-10vh); }
}
</style>
</head>

<body>

<audio autoplay loop>
  <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mpeg">
</audio>

<div class="container">
    <h1>My Beautiful Eshuuuu ❤️</h1>
    <p>Ayesha Mahad, you are my sunshine, my peace, my forever.</p>
    <p>Every heartbeat of mine whispers your name.</p>
    <p>Life became magical the day you became mine.</p>
    <h1>Will You Be My Valentine, Eshuuuu? 💖</h1>
    <button onclick="showLove()">YES, FOREVER 💍</button>
    <p id="response" style="margin-top:20px; font-size:1.5em;"></p>
</div>

<script>
function showLove() {
    document.getElementById("response").innerHTML = 
    "YAY Eshuuuu! You just made me the happiest husband alive! I love you endlessly, Ayesha ❤️🥰";
}

function createHearts() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = Math.random() * 20 + 15 + "px";
    heart.style.animationDuration = Math.random() * 3 + 3 + "s";
    document.body.appendChild(heart);
    setTimeout(() => {
        heart.remove();
    }, 6000);
}

setInterval(createHearts, 300);
</script>

</body>
</html>
