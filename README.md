<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tahmid mahdi search engine</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }
        .search-container {
            text-align: center;
        }
        input[type="text"] {
            width: 300px;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="search-container">
        <h1>tahmid mahdi search engine</h1>
        <form action="https://www.bing.com/search" method="get">
            <input type="text" name="q" placeholder="Search...">
            <input type="submit" value="Search">
        </form>
    </div>
</body>
</html>
