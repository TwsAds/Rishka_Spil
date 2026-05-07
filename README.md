# Rishka_Spil
маникюрный салон
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Маникюр на дому | Цветочный Салон</title>
    <style>
        /* Настройки фона всего сайта */
        body {
            background-image: url('https://i.pinimg.com/webp70/1200x/cd/3d/2d/cd3d2d8be8ebfd8b46e7a3357f21d0ed.webp');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            font-family: 'Arial', sans-serif;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Шапка сайта */
        header {
            width: 100%;
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        /* Центральный блок с контентом */
        .content-wrapper {
            background-color: rgba(255, 255, 255, 0.85); /* Белый полупрозрачный фон */
            max-width: 700px;
            margin: 40px 20px;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
        }

        /* Стиль ссылок-кнопок */
        .messenger-links a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background-color: #ffb6c1; /* Нежно-розовый */
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: 0.3s;
        }

        .messenger-links a:hover {
            background-color: #ff91a4;
            transform: scale(1.05);
        }

        h1 { color: #d46a7a; }
        h2 { border-bottom: 2px solid #ffb6c1; display: inline-block; padding-bottom: 5px; }
        ul { list-style: none; padding: 0; }
        li { margin: 10px 0; font-size: 1.1em; }
    </style>
</head>
<body>

    <header>
        <h1>🌸 Имя Мастера / Название 🌸</h1>
        <p>Профессиональный маникюр на дому</p>
    </header>

    <div class="content-wrapper">
        <h2>Наши услуги</h2>
        <ul>
            <li>✨ Классический маникюр — 300 грн.</li>
            <li>✨ Аппаратный маникюр — 380 грн.</li>
            <li>✨ Покрытие гель-лаком — 300 грн.</li>
            <li>✨ Укрепление и дизайн — от 400 грн.</li>
        </ul>

        <div class="messenger-links">
            <h3>Записаться или спросить:</h3>
            <a href="#">Telegram</a>
            <a href="#">Viber</a>
            <a href="#">Instagram</a>
        </div>

        <br>
        <a href="reviews.html" style="color: #d46a7a;">📖 Читать отзывы клиентов</a>
    </div>

</body>
</html>
