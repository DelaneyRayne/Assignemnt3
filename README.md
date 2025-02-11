<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion & Makeup Hub</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            display: grid;
            grid-template-areas: 
                "header header header"
                "sidebar main side-banner"
                "footer footer footer";
            grid-template-columns: 1fr 2fr 1fr;
            grid-template-rows: auto 1fr auto;
            gap: 15px;
            padding: 15px;
        }
        header {
            grid-area: header;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #f8f8f8;
            padding: 15px;
            border-bottom: 2px solid #ddd;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            display: flex;
            list-style: none;
            gap: 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        .rotating-banner {
            background: #ddd;
            text-align: center;
            padding: 50px;
            font-size: 18px;
            margin-top: 10px;
        }
        .sidebar {
            grid-area: sidebar;
            background: #f4f4f4;
            padding: 15px;
        }
        .advertising {
            margin-top: 20px;
            background: #ddd;
            text-align: center;
            padding: 30px;
        }
        .content {
            grid-area: main;
            padding: 15px;
        }
        .content h1 {
            margin-bottom: 10px;
        }
        .relevant-image {
            background: #ddd;
            text-align: center;
            padding: 40px;
            margin: 20px 0;
        }
        .side-banner {
            grid-area: side-banner;
            background: #ddd;
            text-align: center;
            padding: 50px;
        }
        footer {
            grid-area: footer;
            background: #222;
            color: white;
            text-align: center;
            padding: 10px;
        }
        footer ul {
            display: flex;
            justify-content: center;
            list-style: none;
            gap: 15px;
            padding: 0;
        }
        footer ul li a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">LOGO</div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Blogs</a></li>
                    <li><a href="#">About</a></li>
                </ul>
            </nav>
        </header>
        <div class="sidebar">
            <h3>Trends & Tutorials</h3>
            <ul>
                <li><a href="#">Trends</a></li>
                <li><a href="#">Inspiration</a></li>
                <li><a href="#">Tutorials</a></li>
                <li><a href="#">Tips</a></li>
            </ul>
            <div class="advertising">Advertising</div>
        </div>
        <div class="content">
            <h1>Heading</h1>
            <p>Content about beauty, fashion trends, and styling tips.</p>
            <div class="relevant-image">[Relevant Image]</div>
            <p>More engaging content...</p>
        </div>
        <div class="side-banner">Rotating Banner</div>
        <footer>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Lookbook</a></li>
                <li><a href="#">Quizzes</a></li>
                <li><a href="#">Video Tutorials</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="#">Social Media</a></li>
            </ul>
        </footer>
    </div>
</body>
</html>

