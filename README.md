<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calcule</title>
</head>
<body>
    <h1>
        Atividade
    </h1>
    <script>
        var n = Number(window.prompt('Qual número será trabalhado ?'))

        document.write(`O número digitado foi: ${n}! <br/>`)  

        document.write(`A soma deste número a ele mesmo é igual a ${n+n}!<br/>`)

        document.write(`A multiplicação deste novo valor por 4 é igual a ${(n+n)*4}<br/>`)

        
        document.write(`A divisão deste resultado por 8 é igual a ${((n+n)*4)/8}`)
    </script>
    
</body>
</html>
