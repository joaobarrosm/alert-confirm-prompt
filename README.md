# alert-confirm-prompt
atividade de alert, confirm e prompt html + js
---> html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Only Carecas</title>
</head>
<body>
    
  <script src="js/script.js"></script>  
</body>
</html>

--->js/script.js

let num1 = prompt('digite um numero');
let num2 = prompt('digite outro numero');

num1 = Number(num1);
num2 = Number(num2);

alert(`o resuldado da sua conta foi: ${num1 + num2}`)

---->objetivo é que o prompt mostre o calculo em forma de number e não de string no navegador.
