# Interective-Fibonacci-Series
It´s a HTML file that, when opened, asks to the user how many Fibonacci numbers are requested to appear on the screen.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fibonacci Series</title>
    <style>
        
        body {
            background-color: rgb(211, 233, 10);
            color: rgb(107, 26, 26);
            font-size: x-large;
            font:normal 80pt Arial;
        }
    </style>
</head>
<body>
    <script>
// Here the user defines the quantity of Fibonacci numbers he wants to see.
let nth = window.prompt('How many Fibonacci numbers you wish to see on the screen?')
parseInt(nth)
//This fb() function generates these numbers based in their basic mathematical property.
function fb(n) {
let answer = [0,1]
for(let i = 2; i < n; i++) {
    res.push(answer[i-2] + answer[i-1])
}
return answer;
}
//Here the fb() function is summoned to create a array that contains the numbers until the last, defined by the user as nth.
let allNumbers = [new fb(nth)]
//The result is converted to string and showed on the screen.
document.write(allNumbers.join())
    </script>
</body>
</html>
