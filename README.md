<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Change Color and Text on Click</title>
    <style>
        #myElement {
            width: 200px;
            height: 200px;
            background-color: lightblue;
            text-align: center;
            line-height: 200px;
            font-size: 20px;
        }
    </style>
</head>
<body>

<div id="myElement">Click me!</div>

<script>
    document.getElementById("myElement").addEventListener("click", function() {
        this.style.backgroundColor = "red";  // Change background color to red
        this.textContent = "Hi";             // Change text to "Hi"
    });
</script>

</body>
</html>

