<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Changer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Color Changer</h1>
        <div id="color-box"></div>
        <button id="change-color-btn">Change Color</button>
    </div>

    <script src="script.js"></script>
    
</body>
</html>body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: flex-start; /* Align to the top initially, then margin will push it down */
    min-height: 100vh;
    margin: 0;
    background-color: #f4f4f4;
}

.container {
    text-align: center;
    margin-top: 50px; /* Adjust top margin for spacing */
    background-color: #fff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h1 {
    color: #333;
    margin-bottom: 20px;
}

#color-box {
    width: 200px;
    height: 200px;
    background-color: #3498db; /* Default background color */
    margin: 0 auto 30px auto; /* Center horizontally and add bottom margin */
    border: 1px solid #ccc;
    border-radius: 8px;
    transition: background-color 0.3s ease; /* Smooth transition for color change */
}

#change-color-btn {
    padding: 12px 25px;
    font-size: 16px;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    outline: none;
    transition: background-color 0.2s ease;
}

#change-color-btn:hover {
    background-color: #218838;
}

#change-color-btn:active {
    background-color: #1e7e34;
}
