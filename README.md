<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Andrea's Anti-Jacket Checklist</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #ffe4ec, #fff7d6);
      color: #333;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    .card {
      width: 100%;
      max-width: 750px;
      background: white;
      border-radius: 24px;
      padding: 30px;
      box-shadow: 0 12px 35px rgba(0, 0, 0, 0.12);
      border: 3px solid #ffb6c1;
    }

    h1 {
      text-align: center;
      margin-top: 0;
      font-size: 2rem;
      color: #ff4f87;
    }

    .subtitle {
      text-align: center;
      font-size: 1rem;
      margin-bottom: 25px;
      color: #666;
    }

    .from {
      text-align: center;
      font-weight: bold;
      margin-bottom: 25px;
      color: #444;
    }

    ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    li {
      background: #fff6fa;
      margin-bottom: 12px;
      padding: 14px 16px;
      border-radius: 14px;
      border-left: 6px solid #ff6b9a;
      font-size: 1.05rem;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    li:hover {
      transform: translateX(6px);
      box-shadow: 0 6px 16px rgba(255, 107, 154, 0.18);
    }

    .button-wrap {
      text-align: center;
      margin-top: 25px;
    }

    button {
      background: #ff4f87;
      color: white;
      border: none;
      padding: 12px 22px;
      border-radius: 999px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.2s ease, transform 0.2s ease;
    }

    button:hover {
      background: #e63d74;
      transform: scale(1.04);
    }

    .message {
      text-align: center;
      margin-top: 20px;
      font-size: 1.1rem;
      font-weight: bold;
      color: #ff4f87;
      min-height: 28px;
    }

    .footer {
      text-align: center;
      margin-top: 30px;
      font-size: 0.95rem;
      color: #777;
    }

    @media (max-width: 600px) {
      .card {
        padding: 22px;
      }

      h1 {
        font-size: 1.6rem;
      }

      li {
        font-size: 0.98rem;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Andrea’s Anti-Jacket Checklist</h1>
    <p class="subtitle">A very serious and official report 💅</p>
    <p class="from">Made for Andrea Chicas — from Martin Jimenez</p>

    <ul>
      <li>❌ He has a girlfriend... this is not a side quest situation</li>
      <li>❌ If it has to be secret, it belongs in the trash with bad ideas</li>
      <li>❌ The jacket already got returned... case closed</li>
      <li>❌ A jacket is not an engagement ring, calm down sir</li>
      <li>❌ We are not doing “borrowed hoodie season” with emotionally unavailable men</li>
      <li>❌ If it comes with confusion, sneaking around, and drama... it’s defective</li>
      <li>❌ Andrea deserves peace, respect, and zero weird energy</li>
      <li>❌ Main character energy does not accept side-piece jackets</li>
      <li>❌ Return to sender was the correct shipping option</li>
      <li>❌ My peace &gt; your jacket</li>
    </ul>

    <div class="button-wrap">
      <button onclick="showMessage()">Final Decision</button>
    </div>

    <div class="message" id="message"></div>

    <div class="footer">
      Officially approved by Martin Jimenez 😌
    </div>
  </div>

  <script>
    function showMessage() {
      const message = document.getElementById("message");
      message.textContent = "Verdict: Keep the peace, not the jacket. 💖";
    }
  </script>
</body>
</html>
