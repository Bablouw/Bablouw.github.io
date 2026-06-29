<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой сайт</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(135deg, #1f2937, #0f172a);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .card {
            text-align: center;
            background: rgba(255,255,255,0.08);
            padding: 40px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0,0,0,.3);
            max-width: 500px;
        }

        h1 {
            margin-bottom: 15px;
            font-size: 2.5rem;
        }

        p {
            margin-bottom: 25px;
            color: #d1d5db;
            line-height: 1.6;
        }

        a.button {
            display: inline-block;
            text-decoration: none;
            color: white;
            background: #3b82f6;
            padding: 12px 24px;
            border-radius: 8px;
            transition: .3s;
        }

        a.button:hover {
            background: #2563eb;
        }

        footer {
            margin-top: 30px;
            font-size: 0.9rem;
            color: #9ca3af;
        }
    </style>
</head>

<body>

<div class="card">
    <h1>Привет! 👋</h1>

    <p>
        Это мой первый сайт, размещённый на GitHub Pages.
    </p>

    <a class="button" href="https://github.com/" target="_blank">
        GitHub
    </a>

    <footer>
        © 2026 Roman D.
    </footer>
</div>

</body>
</html>
