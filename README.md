<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .container {
            display: flex;
        }
        .sidebar {
            width: 200px;
            background-color: #f4f4f4;
            padding: 20px;
            height: 100vh;
            position: fixed;
        }
        .sidebar a {
            display: block;
            color: black;
            padding: 10px 0;
            text-decoration: none;
        }
        .main-content {
            text-align: center;
            margin-left: 220px;
            padding: 20px;
            flex-grow: 1;
        }
        .header {
            background-color: skyblue;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .footer {
            background-color: #f1f1f1;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: calc(100% - 200px);
            left: 200px;
        }
        .button {
            background-color: skyblue;
            color: white;
            padding: 15px 25px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            margin: 20px 0;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="logo.jpg.png" alt="logo" height="100" width="100">
        <h1>JALSEVAK</h1>
    </div>
    <div class="container">
        <div class="sidebar">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Graph</a>
            <a href="#">about</a>
        </div>
        <div class="main-content">
            <h2>Discover Amazing Things</h2>
            <p>Join us on our journey to explore the wonderful world of web development.</p>
            <a href="#" class="button">Get Started</a>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </div>
</body>
</html>
