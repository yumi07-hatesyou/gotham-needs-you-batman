<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Come Here, adiii.</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      background: #f6cfd6;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: "Segoe UI", sans-serif;
      overflow: hidden;
    }

    .card {
      background: #ffe9ee;
      padding: 30px 25px;
      border-radius: 20px;
      text-align: center;
      width: 320px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.2);
      position: relative;
    }

    img {
      width: 150px;
      margin-bottom: 15px;
    }

    h1 {
      font-size: 22px;
      margin: 10px 0;
      color: #111;
    }

    p {
      font-size: 14px;
      color: #333;
      margin-bottom: 20px;
      line-height: 1.5;
    }

    .buttons {
      display: flex;
      justify-content: space-around;
      position: relative;
      height: 60px;
    }

    button {
      padding: 10px 22px;
      font-size: 15px;
      border-radius: 12px;
      border: none;
      cursor: pointer;
      position: absolute;
    }

    .yes {
      background: #ff5c75;
      color: white;
      left: 30px;
    }

    .no {
      background: #d3d3d3;
      right: 30px;
    }
  </style>
</head>

<body>

  <div class="card">
    <img src="https://i.imgur.com/0Z8FQYF.png" alt="batman">

    <h1>Will you come meet me, adiii? 🦇</h1>

    <p>
      I miss you, idiot.<br><br>
      <strong>YOU ARE VENGEANCE.</strong><br>
      You are the night.<br>
      So act like it.<br><br>
      I hate you.<br>
      Now come here.
    </p>

    <div class="buttons">
      <button class="yes"
        onclick="alert('Good. Gotham is safe again. Come meet me 🖤')">
        Yes
      </button>

      <button class="no" id="noBtn">
        No
      </button>
    </div>
  </div>

  <script>
    const noBtn = document.getElementById("noBtn");

    noBtn.addEventListener("mouseover", () => {
      const x = Math.random() * 200 - 100;
      const y = Math.random() * 80 - 40;
      noBtn.style.transform = `translate(${x}px, ${y}px)`;
    });
  </script>

</body>
</html>
# gotham-needs-you-batman
