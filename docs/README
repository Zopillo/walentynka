<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Walentynka ❤️</title>
<style>
    body {
        background: linear-gradient(135deg, #ff9a9e, #fad0c4);
        font-family: Arial, sans-serif;
        text-align: center;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0;
    }
    .card {
        background: white;
        padding: 40px;
        border-radius: 20px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    }
    h1 {
        color: #e60073;
    }
    button {
        padding: 12px 25px;
        margin: 15px;
        border: none;
        border-radius: 30px;
        font-size: 16px;
        cursor: pointer;
        transition: 0.3s;
    }
    .yes {
        background-color: #ff4d88;
        color: white;
    }
    .yes:hover {
        background-color: #e60073;
    }
    .no {
        background-color: #ccc;
        position: absolute;
    }
</style>
</head>
<body>

<div class="card">
    <h1>Zostaniesz moją Walentynką? ❤️</h1>
    <button class="yes" onclick="love()">Tak ❤️</button>
    <button class="no" onmouseover="moveButton()">Nie 😈</button>
</div>

<script>
function love() {
    document.body.innerHTML = "<h1 style='color:#e60073;'>Wiedziałem! ❤️ Kocham Cię 😘</h1>";
}

function moveButton() {
    const button = document.querySelector(".no");
    const x = Math.random() * (window.innerWidth - 100);
    const y = Math.random() * (window.innerHeight - 50);
    button.style.left = x + "px";
    button.style.top = y + "px";
}
</script>

</body>
</html>
