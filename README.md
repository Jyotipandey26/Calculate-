# Calculate-
A calculator created using HTML, CSS, and JavaScript performs basic arithmetic operations with a responsive design, featuring a display screen and interactive buttons for user input.
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="calculator">
        <input type="text" id="display" disabled>
        <div class="buttons">
            <button class="operator" onclick="clearDisplay()">AC</button>
            <button class="operator" onclick="deleteLast()">DE</button>
            <button class="operator" onclick="appendValue('.')">.</button>
            <button class="operator" onclick="appendValue('/')">/</button>
            
            <button onclick="appendValue('7')">7</button>
            <button onclick="appendValue('8')">8</button>
            <button onclick="appendValue('9')">9</button>
            <button class="operator" onclick="appendValue('*')">*</button>

            <button onclick="appendValue('4')">4</button>
            <button onclick="appendValue('5')">5</button>
            <button onclick="appendValue('6')">6</button>
            <button class="operator" onclick="appendValue('-')">-</button>

            <button onclick="appendValue('1')">1</button>
            <button onclick="appendValue('2')">2</button>
            <button onclick="appendValue('3')">3</button>
            <button class="operator" onclick="appendValue('+')">+</button>

            <button onclick="appendValue('00')">00</button>
            <button onclick="appendValue('0')">0</button>
            <button class="equal" onclick="calculateResult()">=</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
