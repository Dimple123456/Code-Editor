# Code-Editor

This is a web-based code editor that allows users to write, edit, and run HTML, CSS, and JavaScript code. It provides a "Copy" option to copy the code and a "Run" button to execute the code and display the output in a preview window.

For example run this code:

#html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button Click Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <button id="changeTextButton">Click Me!</button>
        <p id="textDisplay">Hello, World!</p>
    </div>
    <script src="script.js"></script>
</body>
</html>

#css:
body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
}

.container {
    text-align: center;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background-color: #4CAF50;
    color: white;
}

p {
    font-size: 18px;
    color: #333;
}

#js:
document.getElementById("changeTextButton").addEventListener("click", function() {
    document.getElementById("textDisplay").textContent = "You clicked the button!";
});
