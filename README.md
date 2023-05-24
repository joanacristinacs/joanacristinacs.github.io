# joanacristinacs.github.
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tela De Login</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            background-image: linear-gradient(45deg, black, grey);
        }
        div{
            background-color: rgba(0, 0, 0, 0.7);
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            padding: 80px;
            border-radius: 15px;
            color: white;
        }
        input{
            padding: 15px;
            border: none;
            outline: none;
            font-size: 15px;
        }
        button{
            background-color: darkred;
            border: none;
            padding: 15px;
            width: 100%;
            border-radius: 10px;
            color: white;
            font-size: 15px;
            cursor: pointer;
        }
        button:hover{
            background-color: rgb(167, 11, 3);
        }
    </style>
</head>
<body>
    <div class="tela-login">
        <h1>Login</h1>
        <input type="text" placeholder="Nome" >
        <br><br>
        <input type="password" placeholder="Senha" >
        <br><br>
        <form action="tela-de-entrada.html"><button>Entrar</button></form>
        <br>
        <form action="formulario.html"><button>Cadastre-se</button></form>
    </div>
</body>
</html>
