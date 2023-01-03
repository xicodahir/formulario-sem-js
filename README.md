# formulario-sem-js
formulario criado atraves de um site porem sem JS
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario responsivo com html e css</title>
    <link rel="stylesheet" href="form.css">
</head>
<body>
    <div class="box">
        <div class="img-box">
            <img src="imagem/box.png" alt="img box">
        </div>
        <div class="form-box">
            <h2>Criar Conta</h2>
            <p>Ja é um membro? <a href="#">Login</a></p>
            <form action="#">
                <div class="input-group">
                    <label for="nome"> Nome completo</label>
                    <input type="text" id="nome" placeholder="Digite o seu nome completo" required>
                </div>
                <div class="input-group">
                    <label for="email"> E-mail</label>
                    <input type="email" id="email" placeholder="Digite o seu email" required>
                </div>
                <div class="input-group">
                    <label for="telefone"> Telefone</label>
                    <input type="tel" id="telefone" placeholder="Digite o seu telefone" required>
                </div>
                <div class="input-group w50">
                    <label for="senha"> Senha</label>
                    <input type="password" id="senha" placeholder="Digite a sua senha" required>
                </div>
                <div class="input-group w50">
                    <label for="Confirmarsenha"> Confirmar Senha</label>
                    <input type="password" id="Confirmarsenha" placeholder="Confirme a sua senha" required>
                </div>
                <div class="input-group">
                    <button>Cadastrar</button>
                </div>
            </form>
        </div>
    </div>
    <footer>
        <p>Realizado por Xico Dahir dia 02/01/2023</p>
    </footer>
</body>
</html>
