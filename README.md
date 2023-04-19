<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu primeiro programa</title>

    <style>
        body {
            background-color: white
        }

        .luca {
            font-size: x-large;

        }

        
    </style>
</head>

<body>

    <h1>Olá, Ananda!</h1>

    <p class=luca>Eu te amo demais</p>

    <script>

        /*  window.alert("salve")
          var primeiro_nome = window.prompt('nome por favor') //pergunta seu nome e digite direito em
          window.alert('e um prazer te conhecer ' + primeiro_nome + '!') */

        var numero1 = Number.parseInt(window.prompt('Digite um numero'))
        var numero2 = Number.parseInt(window.prompt('digite um segundo numero'))
        var soma = numero1 + numero2
        window.alert(`a soma entre os valores de ${numero1} e ${numero2} eh de ${soma}`)




    </script>
</body>

</html>
