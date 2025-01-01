<!DOCTYPE html>
<html lang="mk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>За Тебе</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ffe6e6, #f8b8d0);
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            text-align: center;
            background-size: 400% 400%;
            animation: gradientAnimation 10s ease infinite;
        }

        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        h1 {
            color: #d6336c;
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(255, 255, 255, 0.5);
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        p {
            font-size: 1.4rem;
            margin-bottom: 2rem;
            max-width: 650px;
            color: #4a4a4a;
            line-height: 1.6;
            font-style: italic;
            text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.7);
            animation: fadeIn 3s ease-in-out;
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 30px;
            background-color: #d6336c;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-size: 1.2rem;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            transition: background-color 0.3s, transform 0.3s;
        }

        .button:hover {
            background-color: #b82d58;
            transform: translateY(-5px);
        }

        .button:active {
            transform: translateY(0);
        }

        /* Heart Animation */
        .heart-background {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 150px;
            height: 150px;
            background: radial-gradient(circle, rgba(214,51,108,0.6) 30%, transparent 30%);
            transform: translate(-50%, -50%);
            animation: heartPulse 2s ease-in-out infinite;
        }

        @keyframes heartPulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="heart-background"></div>
    <h1>Специјална Порака за Ирина</h1>
    <p>
        Even if the night sky was filled with stars, I would
        rather see them through the reflection in your eyes.
    </p>
    <a href="#" class="button">ТЕ САКАМ - од Игор</a>
</body>
</html>
