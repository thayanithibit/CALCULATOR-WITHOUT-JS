# CALCULATOR-WITHOUT-JS

<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="style.css">
        <title>CALCULATOR</title>
              <style>
        *
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
}

body
{
    background-color: #141516;
    font-family: 'Times New Roman', Times, serif;
}

.container
{
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.calculator
{
    background-color: #3599e4;
    padding: 20px;
    border-radius: 30px;
    box-shadow: inset 5px 5px 12px #b7cbd7, 5px 5px 12px rgba(0, 0, 0, 0.60);
    display: grid;
    grid-template-columns: repeat(4, 68px);
}

input
{
    grid-column: span 4;
    height: 70px;
    width: 260px;
    background-color: #5a6e7d;
    box-shadow: inset -5px -5px 12px #3e575e, inset 5px 5px 5px 12px rgba(0, 0, 0, 0.16);
    border: none;
    border-radius: 30px;
    color: rgb(3, 2, 2);
    font-size: 50px;
    text-align: end;
    margin: auto;
    margin-top: 40px;
    margin-bottom: 30px;
    padding: 20px;
}

button
{
    height: 48px;
    width: 48px;
    background-color: #d5d5d5;
    box-shadow: -5px -5px 12px #312f2f, 5px 5px 12px rgba(0, 0, 0, 0.16);
    border: none;
    border-radius: 50%;
    margin: 8px;
    font-size: 16px;
}

.equal {
    width: 115px;
    border-radius: 40px;
    background-color: #b3a1d6;
    box-shadow: -5px -5px 12px #363333, 5px 5px 12px rgba(0, 0, 0, 0.16);
}
    </style>
      
    </head>
    <body>
        <div class="container">
            <div class ="calculator">
                <input type="text" placeholdder="0">
                <button>CLR</button>
                <button>DEL</button>
                <button>%</button>
                <button>/</button>
                <button>7</button>
                <button>8</button>
                <button>9</button>
                <button>X</button>
                <button>4</button>
                <button>5</button>
                <button>6</button>
                <button>-</button>
                <button>1</button>
                <button>2</button>
                <button>3</button>
                <button>+</button>
                <button>.</button>
                <button>0</button>
                <button onclick="calculate()"class="equal">=</button>
               
            </div>
        </div>
    <script>
       
            
    </script>

<script src="script.js"></script>


    </body>
