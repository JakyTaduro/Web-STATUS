<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Document</title>
  </head>
  <body onload="sai">
    <div class="calculator">
      <div class="mini-calculator">Calculadora</div>
      <div id="display"></div>
      <div class="calculator-buttons">
        <button onclick="clean()">CE</button>
        <button onclick="clean()">C</button>
        <button onclick="back()">DEL</button>
        <button class="operation-button" onclick="insert('/')">/</button>
        <button onclick="insert('7')">7</button>
        <button onclick="insert('8')">8</button>
        <button onclick="insert('9')">9</button>
        <button class="operation-button" onclick="insert('*')">*</button>
        <button onclick="insert('4')">4</button>
        <button onclick="insert('5')">5</button>
        <button onclick="insert('6')">6</button>
        <button class="operation-button" onclick="insert('-')">-</button>
        <button onclick="insert('1')">1</button>
        <button onclick="insert('2')">2</button>
        <button onclick="insert('3')">3</button>
        <button class="operation-button" onclick="insert('+')">+</button>
        <button onclick="insert('+-')">+-</button>
        <button onclick="insert('0')">0</button>
        <button onclick="insert(',')">,</button>
        <button class="operation-button" id="equals" onclick="calcular()">=</button>
      </div>
    </div>
    <script src="calc.js"></script>
  </body>
</html>

