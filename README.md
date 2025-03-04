# Resume-Craft
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full Screen Centered Image</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain; /* Keeps aspect ratio */
        }
    </style>
</head>
<body>
    <img src="abc.png" alt="Centered Image">
</body>
</html>
