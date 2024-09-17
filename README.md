<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Натисни на екран</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        #text {
            display: none;
            font-size: 24px;
            color: #333;
        }
    </style>
</head>
<body>
    <div id="text">Це ваш заданий текст!</div>

    <script>
        document.body.addEventListener('click', function() {
            document.getElementById('text').style.display = 'block';
        });
    </script>
</body>
</html>
