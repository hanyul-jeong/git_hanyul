<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hanyul</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #f5f7fa, #c3cfe2); /* 부드러운 그라디언트 배경 */
            color: #333; /* 기본 텍스트 색상 */
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            line-height: 1.6;
        }

        .container {
            width: 80%;
            max-width: 1000px;
            padding: 40px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
            font-size: 16px;
        }

        .title {
            text-align: center;
            font-size: 60px;
            font-weight: 700;
            color: #6a1b9a; /* 고급스러운 보라색 */
            margin-bottom: 30px;
            letter-spacing: 2px;
        }

        .section-title {
            font-size: 28px;
            color: #4a4a4a;
            font-weight: 600;
            border-bottom: 3px solid #6a1b9a;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .tech-stack img {
            margin: 5px;
            border-radius: 5px;
            transition: all 0.3s ease;
        }

        .tech-stack img:hover {
            transform: scale(1.1);
        }

        .contact a {
            text-decoration: none;
            color: #ffffff;
            padding: 10px 25px;
            background-color: #6a1b9a;
            border-radius: 25px;
            font-size: 18px;
            font-weight: 500;
            margin: 10px;
            transition: background-color 0.3s ease;
        }

        .contact a:hover {
            background-color: #8e24aa;
        }

        .stat-img {
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .contact, .tech-stack, .stats {
            margin-bottom: 40px;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .fadeIn {
            animation: fadeIn 1s ease-out;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Title -->
        <div class="title fadeIn">✨ Hanyul's Code Farm ✨</div>

        <!-- Tech Stacks Section -->
        <div class="tech-stack fadeIn">
            <h2 class="section-title">🛠️ Tech Stacks</h2>
            <div>
                <img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=for-the-badge&logo=Tensorflow&logoColor=white" alt="Tensorflow">
                <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" alt="MySQL">
                <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white" alt="Bootstrap">
                <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white" alt="Django">
                <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white" alt="Git">
                <br/>
                <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white" alt="Github">
                <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" alt="Python">
                <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
                <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white" alt="Flask">
                <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white" alt="Amazon S3">
                <br/>
                <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=Linux&logoColor=white" alt="Linux">
            </div>
        </div>

        <!-- Contact Section -->
        <div class="contact fadeIn">
            <h2 class="section-title">🧑‍💻 Contact Me</h2>
            <a href="https://velog.io/@hktysh/posts">Velog</a>
            <a href="mailto:hktysh@nextrunners.co.kr">Gmail</a>
        </div>

        <!-- Stats Section -->
        <div class="stats fadeIn">
            <h2 class="section-title">🏅 Stats</h2>
            <div>
                <img class="stat-img" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hanyul-jeong&layout=compact&hide=javascript,css,scss&langs_count=8" alt="Top Languages">
                <img class="stat-img" src="https://github-readme-stats.vercel.app/api?username=hanyul-jeong&show_icons=true" alt="GitHub Stats">
            </div>
        </div>
    </div>

</body>
</html>
