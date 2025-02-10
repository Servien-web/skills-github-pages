<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
  <style>
     body {
           font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}
header {
    background: #007bff;
    color: white;
    padding: 20px;
}
button {
    padding: 10px 20px;
    font-size: 16px;
    margin-top: 10px;
}
</style>
    <link rel="stylesheet" href="./styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <main>
        <p>This is a simple website created on an iPhone.</p>
        <button onclick="showMessage()">Click Me</button>
        <p id="message"></p>
    </main>
    <script>
     function showMessage() {
    document.getElementById("message").innerHTML = "Hello ,you've clicked the button!";
        }
  </sript>
</body>
</html>
