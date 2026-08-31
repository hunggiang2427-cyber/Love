<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Gửi Em ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    overflow: hidden;
    font-family: "Segoe UI", sans-serif;
    background:
        radial-gradient(circle at 50% 30%, #6d173c 0%, transparent 35%),
        linear-gradient(135deg, #170817, #300b24, #09030d);
    color: white;
    height: 100vh;
}

/* Ánh sáng nền */
.glow {
    position: fixed;
    width: 350px;
    height: 350px;
    background: #ff3b81;
    filter: blur(130px);
    opacity: .18;
    border-radius: 50%;
    top: 20%;
    left: 50%;
    transform: translate(-50%, -50%);
}

/* Màn hình */
.container {
    position: relative;
    z-index: 5;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 25px;
}

.card {
    width: min(650px, 95vw);
    max-height: 90vh;
    overflow-y: auto;
    padding: 45px 35px;
    text-align: center;
    background: rgba(255,255,255,.07);
    border: 1px solid rgba(255,255,255,.15);
    border-radius: 28px;
    backdrop-filter: blur(15px);
    box-shadow:
        0 0 50px rgba(255, 42, 117, .18),
        inset 0 0 30px rgba(255,255,255,.03);
    animation: appear 2s ease;
}

@keyframes appear {
    from {
        opacity: 0;
        transform: scale(.8) translateY(30px);
    }

    to {
        opacity: 1;
        transform: scale(1) translateY(0);
    }
}

/* Trái tim */
.heart {
    font-size: 70px;
    animation: heartbeat 1.4s infinite;
    filter: drop-shadow(0 0 18px #ff387c);
}

@keyframes heartbeat {
    0%, 100% {
        transform: scale(1);
    }

    50% {
        transform: scale(1.18);
    }
}

h1 {
    margin: 15px 0 25px;
    font-size: clamp(28px, 7vw, 46px);
    color: #ffb5cc;
    text-shadow: 0 0 20px rgba(255,70,130,.7);
}

.message {
    text-align: left;
    font-size: 17px;
    line-height: 1.9;
    color: #ffeaf1;
}

.message p {
    margin-bottom: 18px;
    opacity: 0;
    animation: textShow 1s forwards;
}

.message p:nth-child(1) {
    animation-delay: 1s;
}

.message p:nth-child(2) {
    animation-delay: 3s;
}

.message p:nth-child(3) {
    animation-delay: 5s;
}

.message p:nth-child(4) {
    animation-delay: 7s;
}

@keyframes textShow {
    to {
        opacity: 1;
    }
}

/* Lời kết */
.final {
    margin-top: 25px;
    font-size: 25px;
    font-weight: bold;
    color: #ff9fbd;
    text-shadow: 0 0 15px #ff3679;
    opacity: 0;
    animation: finalShow 2s forwards;
    animation-delay: 9s;
}

@keyframes finalShow {
    to {
        opacity: 1;
        transform: scale(1.05);
    }
}

/* Tim bay */
.floating-heart {
    position: fixed;
    bottom: -50px;
    font-size: 20px;
    animation: floatUp linear forwards;
    pointer-events: none;
    z-index: 2;
}

@keyframes floatUp {
    0% {
        transform: translateY(0) rotate(0deg);
        opacity: 0;
    }

    15% {
        opacity: 1;
    }

    100% {
        transform: translateY(-110vh) rotate(360deg);
        opacity: 0;
    }
}

/* Hoa rơi */
.petal {
    position: fixed;
    top: -30px;
    color: #ff8daf;
    font-size: 18px;
    animation: fall linear forwards;
    z-index: 1;
    pointer-events: none;
}

@keyframes fall {
    to {
        transform: translateY(110vh) rotate(720deg);
        opacity: .1;
    }
}

/* Nút */
button {
    margin-top: 30px;
    padding: 13px 28px;
    border: none;
    border-radius: 30px;
    color: white;
    font-size: 15px;
    cursor: pointer;
    background: linear-gradient(45deg, #ff2f70, #ff6795);
    box-shadow: 0 0 20px rgba(255,47,112,.5);
    transition: .3s;
}

button:hover {
    transform: scale(1.08);
    box-shadow: 0 0 35px rgba(255,47,112,.8);
}

/* Điện thoại */
@media (max-width:500px) {
    .card {
        padding: 35px 22px;
    }

    .message {
        font-size: 15px;
    }

    .heart {
        font-size: 55px;
    }
}
</style>
</head>

<body>

<div class="glow"></div>

<!-- NHẠC -->
<audio id="music" loop>
    <source src="until-you.mp3" type="audio/mpeg">
</audio>

<div class="container">

<div class="card">

    <div class="heart">❤️</div>

    <h1>Gửi em, người anh yêu</h1>

    <div class="message">

        <p>
            Em à, cảm ơn em vì <b>1 năm qua</b> đã cho anh cảm thấy
            hạnh phúc, cho anh được cảm giác bình yên và có một người
            luôn luôn đồng hành cùng anh.
        </p>

        <p>
            Cảm ơn em vì luôn lo lắng cho anh, luôn quan tâm đến anh
            và luôn bao dung, tha thứ cho những lỗi lầm của anh.
        </p>

        <p>
            Anh cảm ơn em rất nhiều. Anh biết mình vẫn còn nhiều
            thiếu sót, nhưng anh sẽ cố gắng hơn mỗi ngày để trở thành
            một người tốt hơn và để em có được cuộc sống tốt hơn.
        </p>

        <p>
            Cảm ơn em vì đã bước vào cuộc đời anh và đã ở bên anh
            suốt một năm qua. Anh mong rằng không chỉ một năm,
            mà thật nhiều năm sau nữa chúng ta vẫn sẽ luôn có nhau.
        </p>

    </div>

    <div class="final">
        Anh yêu em rất nhiều ❤️<br>
        <small>1 năm và còn rất nhiều năm nữa...</small>
    </div>

    <button onclick="moreLove()">
        💗 Bấm vào đây
    </button>

</div>

</div>

<script>

/* Tim bay */
function createHeart() {

    const heart = document.createElement("div");

    heart.className = "floating-heart";

    const hearts = [
        "❤️",
        "💕",
        "💗",
        "💖",
        "💘",
        "💞"
    ];

    heart.innerHTML =
        hearts[Math.floor(Math.random() * hearts.length)];

    heart.style.left =
        Math.random() * 100 + "vw";

    heart.style.fontSize =
        (14 + Math.random() * 25) + "px";

    heart.style.animationDuration =
        (5 + Math.random() * 7) + "s";

    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 12000);
}

setInterval(createHeart, 450);


/* Hoa rơi */
function createPetal() {

    const petal = document.createElement("div");

    petal.className = "petal";

    petal.innerHTML =
        Math.random() > 0.5 ? "🌸" : "🌹";

    petal.style.left =
        Math.random() * 100 + "vw";

    petal.style.fontSize =
        (12 + Math.random() * 15) + "px";

    petal.style.animationDuration =
        (5 + Math.random() * 8) + "s";

    document.body.appendChild(petal);

    setTimeout(() => {
        petal.remove();
    }, 14000);
}

setInterval(createPetal, 700);


/* Khi bấm nút */
function moreLove() {

    /* Phát nhạc */
    const music = document.getElementById("music");

    music.play().catch(() => {});

    /* Bắn nhiều tim */
    for (let i = 0; i < 35; i++) {

        setTimeout(() => {
            createHeart();
        }, i * 80);

    }

}

</script>

</body>
</html>
