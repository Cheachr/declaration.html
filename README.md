<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Declaration</title>
</head>
<body>

    <h1>Click the button to see a special message</h1>

    <button onclick="displayMessage()">Click me!</button>

    <p id="message"></p>

    <script>
        function displayMessage() {
            var answer = confirm("Do you love me?");
            if (answer) {
                document.getElementById("message").innerHTML = "I love you too!";
            } else {
                document.getElementById("message").innerHTML = "Well, maybe next time!";
            }
        }
    </script>

</body>
</html>
