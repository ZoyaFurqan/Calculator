<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style4.css">
    <script src="script .js"></script>
</head>
<body>
    <div class="calculator">
        <h1>Calculator</h1>
        <div class="input-section">
            <input type="number" id="num1" placeholder="First number"><br><br>
            <input type="number" id="num2" placeholder="Second number">
        </div><br>
        <div class="buttons">
            <button  onclick="add()">+</button>
            <button  onclick="sub()">-</button>
            <button  onclick="multiply()">x</button>
            <button  onclick="divide()">÷</button>
            <button  onclick="remd()">%</button>
           
            
        </div>
        <div class="result">
            <h2>Result: <span id="result">0</span></h2>
        </div>
    </div> 
    
</body>
</html>
