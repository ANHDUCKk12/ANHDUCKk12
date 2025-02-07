<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phi Béo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
        }
        a {
            display: block;
            margin-top: 20px;
            color: blue;
            text-decoration: none;
            font-size: 18px;
        }
    </style>
    <script>
        document.addEventListener("keydown", function(event) {
            if (event.key === ".") {
                document.getElementById("response").innerText = "Phi Béo";
            }
        });
    </script>
</head>
<body>
    <h1>Phi Béo</h1>
    <p>This is a simple webpage.</p>
    <p id="response"></p>
    <a href="https://example.com">Visit Example</a>
</body>
</html>

