# calculator  HTML CODE
A simple web calculator built with HTML for structure, CSS for styling, and JavaScript for functionality. Performs basic arithmetic operations. Clean design, responsive layout. See the code.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Calculator -by sandeep </title>
</head>
<body>
    <div class ="Calculator">
        <input type="text" placeholder="000000" id="inputBox">
        <div>
            <button class="operator">AC</button>
            <button class="operator">DEL</button>
            <button class="operator">%</button>
            <button class="operator">/</button>
        </div>
        <div>
            <button>7</button>
            <button>8</button>
            <button>9</button>
            <button class="operator">*</button>
        </div>
        <div>
            <button>4</button>
            <button>5</button>
            <button>6</button>
            <button class="operator">-</button>
        </div>
        <div>
            <button>1</button>
            <button>2</button>
            <button>3</button>
            <button class="operator"> +</button>
        </div>
        <div>
            <button>00</button>
            <button>0</button>
            <button>.</button>
            <button class="equalBtn">=</button>
        </div>
        
       
    </div>
    <script src="script.js"></script>
</body>
</html>
