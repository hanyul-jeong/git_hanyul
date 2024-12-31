<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hanyul</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #e0c3fc, #8ec5fc); /* 부드러운 그라디언트 배경 */
            color: #2e2e2e; /* 텍스트 색상 */
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; /* 화면 전체 높이 */
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.9); /* 반투명 배경 */
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1); /* 그림자 효과 */
        }

        .title {
            font-size: 72px;
            font-weight: 700;
            color: #6a1b9a; /* 고급스러운 보라색 */
            text-transform: uppercase; /* 모든 텍스트 대문자 */
            letter-spacing: 2px; /* 글자 사이 간격 */
            margin-bottom: 20px;
            animation: fadeIn 1.5s ease-out; /* 부드럽게 나타나는 애니메이션 */
        }

        .subtitle {
            font-size: 24px;
            color: #555; /* 부드러운 회색 */
            font-weight: 400;
            margin-bottom: 30px;
            animation: fadeIn 2s ease-out; /* 부드럽게 나타나는 애니메이션 */
        }

        .button {
            display: inline-block;
            padding: 10px 30px;
            background-color: #6a1b9a; /* 고급스러운 보라색 버튼 */
            color: white;
            font-size: 18px;
            font-weight: 600;
            border-radius: 50px;
            text-decoration: none;
            transition: all 0.3s ease; /* 호버 시 부드러운 효과 */
        }

        .button:hover {
            background-color: #8e24aa; /* 호버 시 버튼 색상 변경 */
            transform: translateY(-3px); /* 살짝 떠오르는 효과 */
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
        <div class="subtitle">Welcome to My Elegant World</div>
        <a href="#" class="button">Explore More</a>
    </div>

</body>
</html>
