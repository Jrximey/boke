<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram风格的网页导航</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('background.jpg'); /* 设置背景图片 */
            background-size: cover; /* 背景图片覆盖整个屏幕 */
            background-position: center; /* 背景图片居中 */
            background-repeat: no-repeat; /* 背景图片不重复 */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }
        .navbar {
            background-color: #ffffff;
            border: 1px solid #dbdbdb;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            display: flex;
            justify-content: space-around;
            width: 300px;
            padding: 10px;
            position: relative;
            z-index: 1;
        }
        .navbar a {
            color: #262626;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 4px;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }
        .navbar a:hover {
            background-color: #efefef;
            transform: scale(1.1);
        }
        .navbar a:active {
            background-color: #ddd;
            transform: scale(0.95);
        }
        .background-music {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <a href="#home">首页</a>
        <a href="#explore">探索</a>
        <a href="#notifications">通知</a>
        <a href="#profile">个人主页</a>
    </div>

    <audio class="background-music" autoplay loop>
        <source src="background-music.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

</body>
</html>
# 2025-2-3
