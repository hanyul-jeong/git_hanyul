<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hanyul</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #e0c3fc, #8ec5fc);
            color: #2e2e2e;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        .title {
            font-size: 72px;
            font-weight: 700;
            color: #6a1b9a;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 20px;
            animation: fadeIn 1.5s ease-out;
        }

        .subtitle {
            font-size: 24px;
            color: #555;
            font-weight: 400;
            margin-bottom: 30px;
            animation: fadeIn 2s ease-out;
        }

        .button {
            display: inline-block;
            padding: 10px 30px;
            background-color: #6a1b9a;
            color: white;
            font-size: 18px;
            font-weight: 600;
            border-radius: 50px;
            text-decoration: none;
            transition: all 0.3s ease;
        }

        .button:hover {
            background-color: #8e24aa;
            transform: translateY(-3px);
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="title">Hanyul</div>
        <div class="subtitle">Welcome to My World</div>
        <a href="#" class="button">Explore More</a>
    </div>

</body>
</html>
