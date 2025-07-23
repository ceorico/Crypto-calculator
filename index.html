<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crypto Profit Calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0d1117;
      color: #c9d1d9;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }
    .calculator {
      background: #161b22;
      padding: 20px;
      border-radius: 12px;
      max-width: 400px;
      width: 100%;
    }
    input, select, button {
      width: 100%;
      margin-top: 10px;
      padding: 10px;
      border-radius: 6px;
      border: none;
    }
    button {
      background-color: #238636;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }
    .result {
      margin-top: 20px;
      padding: 10px;
      background-color: #21262d;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <h1>Crypto Profit Calculator</h1>
  <div class="calculator">
    <input type="text" id="coin" placeholder="Coin Name (e.g., BTC)" />
    <select id="position">
      <option value="long">Long</option>
      <option value="short">Short</option>
    </select>
    <input type="number" id="entryPrice" placeholder="Entry Price" />
    <input type="number" id="leverage" placeholder="Leverage (e.g., 10x)" />
    <input type="number" id="targetProfit" placeholder="Target Profit ($)" />
    <button onclick="calculateTargetPrice()">Calculate Target Price</button>
    <div class="result" id="result"></div>
  </div>

  <script>
    function calculateTargetPrice() {
      const position = document.getElementById('position').value;
      const entryPrice = parseFloat(document.getElementById('entryPrice').value);
      const leverage = parseFloat(document.getElementById('leverage').value);
      const targetProfit = parseFloat(document.getElementById('targetProfit').value);

      if (isNaN(entryPrice) || isNaN(leverage) || isNaN(targetProfit)) {
        document.getElementById('result').innerText = 'Please enter all fields correctly.';
        return;
      }

      let resultText = "";
      let priceChange = targetProfit / leverage;
      let targetPrice = 0;

      if (position === "long") {
        targetPrice = entryPrice + priceChange;
      } else {
        targetPrice = entryPrice - priceChange;
      }

      const returnPercentage = (priceChange / entryPrice) * 100;

      resultText += `Target Price: $${targetPrice.toFixed(2)}\n`;
      resultText += `Return Percentage: ${returnPercentage.toFixed(2)}%`;

      document.getElementById('result').innerText = resultText;
    }
  </script>
</body>
</html>
