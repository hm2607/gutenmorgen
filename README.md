#<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>guten morgen</title>
    <style>
        body {
            text-align: center;
            background-color: pink;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: red;
            font-size: 3em;
        }
        .heart {
            color: red;
            font-size: 100px;
            cursor: pointer;
        }
        button {
            background: red;
            color: white;
            padding: 10px 20px;
            border: none;
            font-size: 1.5em;
            cursor: pointer;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>guten morgen</h1>
    <p>Click the heart for a surprise!</p>
    <div class="heart" onclick="showMessage()">💖</div>
    <p id="message"></p>



    <script>
        function showMessage() {
            document.getElementById("message").innerHTML = "wanna be my valentine??🤤";
        }
    </script>
</body>
</html>
