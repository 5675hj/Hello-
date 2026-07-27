
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Small Test</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: #f4f4f4;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
    }

    .box {
        background: white;
        padding: 30px;
        border-radius: 10px;
        text-align: center;
        box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    button {
        padding: 10px 20px;
        border: none;
        background: #007BFF;
        color: white;
        border-radius: 5px;
        cursor: pointer;
    }

    button:hover {
        background: #0056b3;
    }
</style>
</head>
<body>

<div class="box">
    <h2>Hello, Ibrahim!</h2>
    <p>Click the button below.</p>
    <button onclick="showMessage()">Click Me</button>
</div>

<script>
function showMessage() {
    alert("Congratulations! Your HTML, CSS, and JavaScript are working.");
}
</script>

</body>
</html>
