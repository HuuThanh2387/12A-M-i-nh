<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tết 2025</title>
    <style>
        /* CSS Cơ Bản */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: "Arial", sans-serif;
            background-color: #fff4e6;
            color: #333;
            overflow-x: hidden;
        }

        .container {
            position: relative;
            width: 100%;
            height: 100vh;
            overflow: hidden;
        }

        .slide {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: opacity 1s ease-in-out;
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .slide.active {
            opacity: 1;
            z-index: 1;
        }

        .slide h1 {
            margin: 10px 0;
            font-size: 2.5rem;
            text-transform: uppercase;
            color: #d32f2f;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
            animation: fadeIn 2s ease-in-out;
        }

        .slide p {
            margin: 15px 0;
            font-size: 1.5rem;
            text-align: center;
            line-height: 1.6;
            color: #f57c00;
            font-weight: bold;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.2);
        }

        .menu-item {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 70%;
            padding: 10px;
            margin: 10px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 50px;
            height: 50px;
            margin-right: 10px;
            border-radius: 5px;
            border: 3px solid #ff4d4d;
            background-color: #fff;
        }

        .menu-item span {
            font-size: 1.2rem;
            color: #d84315;
        }

        .tet-decoration {
            width: 100px;
            height: 100px;
            border: 4px solid #ffd700;
            border-radius: 5px;
            background-color: #ffcccc;
            color: #b30000;
            font-size: 12px;
            font-weight: bold;
            text-align: center;
            line-height: 100px;
            margin: 10px auto;
        }

        .rating-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }

        .rating-stars {
            display: flex;
            gap: 5px;
        }

        .rating-stars span {
            font-size: 1.5rem;
            cursor: pointer;
            color: #ffc107;
            transition: color 0.3s ease;
        }

        .rating-stars span.inactive {
            color: #ccc;
        }

        .rating-value {
            margin-top: 10px;
            font-size: 1.2rem;
            color: #333;
        }

        .animation {
            animation: bounce 2s infinite;
        }

        /* Pháo hoa */
        .fireworks {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
        }

        canvas {
            display: block;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }

        @media (max-width: 768px) {
            .slide h1 {
                font-size: 1.8rem;
            }

            .slide p {
                font-size: 1.2rem;
            }

            .menu-item span {
                font-size: 1rem;
            }

            .menu-item img {
                width: 40px;
                height: 40px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Slide 1 -->
        <div class="slide active" id="slide1" style="background-image: url('https://i.imgur.com/ZS5LRNo.jpeg/1024x760.png?text=Background');">
            <h1>Chào Đón Tết 2025</h1>
            <p>Năm Ất Tị - An Khang Thịnh Vượng</p>
            <img class="animation" src="https://i.ibb.co/g4RrfZZ/300x200.png?text=Bao+Lì+Xì" alt="Bao lì xì Tết 2025">
            <p>Chúc bạn và gia đình một năm mới tràn đầy niềm vui!</p>
        </div>

        <!-- Slide 2 -->
        <div class="slide" id="slide2" style="background-image: url('https://i.imgur.com/nX1riMf.jpeg/1024x760.png?text=Background');">
            <h1>12A Có Gì Nào?</h1>
            <p>Mua hàng được tặng 1 Chuốt + 1 Coca Cola</p>
            <div class="tet-decoration">
                <img src="https://i.ibb.co/4VQpB5w/QAnh-Chip.jpg" width="90" height="90" alt="QAnh Chip">
             </div>
            <div class="menu-item">
                <img src="https://i.ibb.co/yVw5XDf/Pngtree-winter-solstice-dumplings-winter-solstice-3828068.png/50" alt="Há cảo">
                <span>Há cảo chiên - 10k-15k</span>
            </div>
            <div class="menu-item">
                <img src="https://i.ibb.co/JKMBQ5R/Pngtree-sweet-and-sour-chicken-with-19752770.png/50" alt="Gà viên">
                <span>Gà viên sốt ngọt - 15k</span>
            </div>
            <div class="menu-item">
                <img src="https://i.ibb.co/hZLVPyQ/Pngtree-cute-hand-drawing-illustration-tteokbokki-7324402.png/50" alt="Tokbokki">
                <span>Tokbokki (chả cá, bánh gạo) - 20k</span>
            </div>
            <div class="menu-item">
                <img src="https://i.ibb.co/NnQM2C4/Pngtree-gimbap-kimbab-8952524.png/50" alt="Kimbap">
                <span>Kimbap - 13k</span>
            </div>
        </div>

        <!-- Slide 3 -->
        <div class="slide" id="slide3" style="background-image: url('https://i.imgur.com/GolYTAZ.jpeg/1024x760.png?text=Background');">
            <h1>Lời Cảm Ơn</h1>
            <p>Chúng tôi chân thành cảm ơn sự ủng hộ của bạn trong chương trình Tết năm nay!</p>
            <div class="rating-container">
                <h2>Đánh giá mức hài lòng</h2>
                <div class="rating-stars">
                    <span>⭐</span>
                    <span>⭐</span>
                    <span>⭐</span>
                    <span>⭐</span>
                    <span>⭐</span>
                </div>
                <div class="rating-value">Bạn đã chọn: <span id="selected-rating">0</span> sao</div>
            </div>
        </div>

        <!-- Hiệu ứng pháo hoa -->
        <div class="fireworks">
            <canvas id="fireworksCanvas"></canvas>
        </div>
    </div>

    <script>
        const slides = document.querySelectorAll('.slide');
        let currentSlide = 0;

        function showSlide(index) {
            slides.forEach((slide, i) => {
                slide.classList.remove('active');
                if (i === index) slide.classList.add('active');
            });
        }

        document.body.addEventListener('dblclick', () => {
            currentSlide = (currentSlide + 1) % slides.length;
            showSlide(currentSlide);
        });

        const stars = document.querySelectorAll('.rating-stars span');
        const selectedRating = document.getElementById('selected-rating');

        stars.forEach((star, index) => {
            star.addEventListener('click', () => {
                stars.forEach((s, i) => {
                    s.classList.toggle('inactive', i > index);
                });
                selectedRating.textContent = index + 1;
            });
        });

        // Pháo hoa
        const canvas = document.getElementById("fireworksCanvas");
        const ctx = canvas.getContext("2d");

        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;

        function random(min, max) {
            return Math.random() * (max - min) + min;
        }

        class Firework {
            constructor() {
                this.x = random(0, canvas.width);
                this.y = canvas.height;
                this.targetX = random(0, canvas.width);
                this.targetY = random(0, canvas.height / 2);
                this.size = random(2, 4);
                this.color = `hsl(${random(0, 360)}, 100%, 50%)`;
            }

            draw() {
                ctx.beginPath();
                ctx.arc(this.targetX, this.targetY, this.size, 0, Math.PI * 2);
                ctx.fillStyle = this.color;
                ctx.fill();
            }
        }

        function animateFireworks() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            const fireworks = new Firework();
            fireworks.draw();
            requestAnimationFrame(animateFireworks);
        }

        animateFireworks();
   animateFireworks();
    animateFireworks();
    </script>
</body>
</html>