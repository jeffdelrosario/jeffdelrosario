<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maria, Will You Be My Valentine?</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: pink;
        }
        h1 {
            color: red;
        }
        #buttons {
            margin-top: 20px;
        }
        button {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            cursor: pointer;
        }
        #yes {
            background-color: lightgreen;
            border: none;
        }
        #no {
            background-color: lightcoral;
            border: none;
        }
        #cat-image {
            width: 250px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Maria, Will You Be My Valentine? 💖</h1>
    <img id="cat-image" src="YOUR_IMAGE_LINK_HERE" alt="Cute Emoji with Ring">
    <div id="buttons">
        <button id="yes" onclick="alert('Yay! Maria, you just made my day! 💕')">Yes</button>
        <button id="no" onclick="growYes()">No</button>
    </div>

    <script>
        let yesButton = document.getElementById("yes");
        let size = 20;  // Initial font size

        function growYes() {
            size += 10;  // Increase size
            yesButton.style.fontSize = size + "px";

            // Change text if it gets really big
            if (size > 80) {
                yesButton.innerHTML = "Maria, you have no choice! 😆💕";
            }
        }
    </script>

</body>
</html>
