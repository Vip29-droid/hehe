<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffcccb;
            text-align: center;
            padding-top: 50px;
        }
        h1 {
            color: #d63447;
            font-size: 3em;
        }
        p {
            color: #333;
            font-size: 1.5em;
        }
        img {
            margin-top: 20px;
            border-radius: 10px;
        }
        button {
            padding: 10px 20px;
            font-size: 1.2em;
            margin: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        #yesButton {
            background-color: #4CAF50;
            color: white;
        }
        #noButton {
            background-color: #f44336;
            color: white;
        }
        #response {
            margin-top: 20px;
            font-size: 1.5em;
            color: #d63447;
        }
    </style>
</head>
<body>
    <img src=https://media1.tenor.com/m/K_E6ORTmXMoAAAAC/milk-and-mocha-love.gif alt="Cute Bear GIF">
    <br>
    <button id="yesButton">Yes</button>
    <button id="noButton">No</button>
    <div id="response"></div>

    <script>
        const yesButton = document.getElementById('yesButton');
        const noButton = document.getElementById('noButton');
        const response = document.getElementById('response');

        yesButton.addEventListener('click', () => {
            response.innerHTML = "Yehey! I love you! 💖";
        });

        noButton.addEventListener('click', () => {
            response.innerHTML = "DE WAO";
        });
    </script>
</body>
</html>
