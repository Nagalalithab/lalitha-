# lalitha -
<!DOCTYPE html>
<html>
<head>
    <title>A Simple Calculator</title>
    <link rel="stylesheet" type="text/css" href="css/custom.css">
</head>
<body>


<div id="calculator" align="center">

    <div>
        <input id="screen" value="0"><br>
    </div>

    <div>
        <button onclick="processNumberButton(this.innerHTML)">1</button>
        <button onclick="processNumberButton(this.innerHTML)">2</button>
        <button onclick="processNumberButton(this.innerHTML)">3</button>
        <button onclick="processOperatorButton(this.innerHTML)" class="operator">+</button>
    </div>

    <div>
        <button onclick="processNumberButton(this.innerHTML)">4</button>
        <button onclick="processNumberButton(this.innerHTML)">5</button>
        <button onclick="processNumberButton(this.innerHTML)">6</button>
        <button onclick="processOperatorButton(this.innerHTML)" class="operator">-</button>
    </div>

    <div>
        <button onclick="processNumberButton(this.innerHTML)">7</button>
        <button onclick="processNumberButton(this.innerHTML)">8</button>
        <button onclick="processNumberButton(this.innerHTML)">9</button>
        <button onclick="processOperatorButton(this.innerHTML)" class="operator">/</button>
    </div>

    <div>
        <button onclick="processNumberButton(this.innerHTML)">0</button>
        <button onclick="processDecimalButton(this.innerHTML)">.</button>
        <button onclick="processPercentageButton(this.innerHTML)">%</button>
        <button onclick="processOperatorButton(this.innerHTML)" class="operator">x</button>
    </div>

    <div>
        <button onclick="processNumberButton(this.innerHTML)">00</button>
        <button onclick="processParenthesesButton(this.innerHTML)">(</button>
        <button onclick="processParenthesesButton(this.innerHTML)">)</button>
        <button onclick="processOperatorButton(this.innerHTML)" class="operator">^</button>
    </div>

    <div>
        <button onclick="processResetButton()" class="reset">C</button>
        <button onclick="processEqualsButton()" class="eval">=</button>
    </div>

</div>

<script type="text/javascript" src="js/simplecalculator.js"></script>

</body>
</html>
