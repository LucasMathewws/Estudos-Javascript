<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap" rel="stylesheet">
    <title>Document</title>

    <style>
        body {
            font-family: 'Roboto', sans-serif;

        }


        .seila {
            display: block;
            margin-bottom: 1.5%;

        }

        .nome {
            display: block;
        }

        .cpf {
            display: block;
        }

        .sexo {
            display: block
        }

        .telefone {
            display: block;
        }

        .primeiraetapa {
            display: block;
        }

        .enderecodeemail {
            display: block;
        }

        .confirmar_email {
            display: block;
        }

        .password {
            display: block;
        }

        .confirmar_senha {
            display: block;
        }

        /*  #formulario fieldset {
            border: 0 none;
            position: absolute;
        } 

        #formulario fieldset:not(:first-of-type) {
            display: none;
        } */

        .esta_do {
            display: block;
        }

        .cida_de {
            display: block;
        }

        .bair_ro {
            display: block;
        }

        .r_ua {
            display: block;
        }

        .c_ep {
            display: block;
        }

        .complemen_to {
            display: block;
        }

        /*
        #formulario #progresso {
            margin-bottom: 30px;
            overflow: hidden;

            counter-reset: step;
        }

        #formulario #progesso li {
            list-style-type: none;
            color: white;
            font-weight: bold;
            float: left;
            width: 33.33%;
            position: relative;
        }

        #formulario #progresso li:before {
            content: counter(step);
            counter-increment: step;
            width: 20px;
            display: block;

 
        }

        #formulario #progresso li:after {
            content: '';
            width: 100%;
            position: absolute;
        } */
    </style>

</head>

<body>


    <form id="formulario">

        <ul id="progresso">
            <li>Informações pessoais</li>
            <li>Localização</li>
            <li>Email e senha</li>

        </ul>

        <fieldset>

            <!-- <h3 class="cadastro">Cadastra-se</h3>
            <p><strong>Informações pessoais</strong></p> -->
            <div style="; width: 100%; justify-content: center; align-items: center; display: flex;">
                <div>

                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; margin-bottom: 5%; color:#048BA8;font-size: 2.5rem; font-weight: 400;">
                        Cadastro</p>
                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; color: #01C3BC; font-weight: 200; font-size: 1.5rem;">
                        Informações pessoais</p>
                </div>
            </div>
            <label>Nome</label>
            <input type="text" placeholder="Ex: Bernardo Silva" class="nome" id="name">
            <label>CPF</label>
            <input type="text" placeholder="Ex: 123.456.789-00" class="cpf" id="cpff">
            <div style="display: flex; align-items: center;">
                <div>
                    <label style="display: block;">Nascimento</label>
                    <input type="date" class="nascimento" id="nascido">
                </div>
                <div style="align-items: center;">
                    <label>Sexo</label>
                    <select class="sexo">
                        <option>Feminino</option>
                        <option>Masculino</option>
                        <option>Prefiro não responder</option>
                        <option>Outros</option>
                    </select>
                </div>
            </div>
            <label>Telefone</label>
            <input type="tel" class="telefone" placeholder="Ex: (12) 3456-7890" id="celular">
            <input type="submit" name="enviar" class="envi_ar" value="Proximo">

        </fieldset>

        <fieldset>
            <!-- <h3>Endereco</h3> -->
            <div style="; width: 100%; justify-content: center; align-items: center; display: flex;">
                <div>

                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; margin-bottom: 5%; color:#048BA8;font-size: 2.5rem; font-weight: 400;">
                        Cadastro</p>
                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; color: #01C3BC; font-weight: 200; font-size: 1.5rem;">
                        Endereço</p>
                </div>
            </div>
            <div style="display: flex; align-items: center;">
                <div>
                    <label style="display: block;">Estado</label>
                    <input type="text" name="estado" class="esta_do" placeholder="Ex: RN">
                </div>
                <div>
                    <label>Cidade</label>
                    <input type="text" name="cidade" class="cida_de" placeholder="Ex: Mossoro">
                </div>
            </div>
            <div style="display: flex; align-items: center;">
                <div>
                    <label>Bairro</label>
                    <input type="text" name="bairro" class="bair_ro" placeholder="Ex: Nova Betania">
                </div>
                <div>
                    <label>Rua</label>
                    <input type="text" name="rua" class="r_ua" placeholder="Ex: R. Martins">
                </div>
            </div>
            <label>CEP</label>
            <input type="text" name="cep" class="c_ep" placeholder="Ex: 123.456-789">
            <label>complemento</label>
            <input type="text" name="complemento_endereco" class="complemen_to" placeholder="Ex: Proximo a prefeitura">
            <input type="submit" nome="anterior" class="anteri_or" value="anterior">
            <input type="submit" name="enviar" class="envi_ar" value="Proximo">

        </fieldset>

        <fieldset>
            <!-- <h3>Email e senha</h3> -->
            <div style="; width: 100%; justify-content: center; align-items: center; display: flex;">
                <div>

                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; margin-bottom: 5%; color:#048BA8;font-size: 2.5rem; font-weight: 400;">
                        Cadastro</p>
                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; color: #01C3BC; font-weight: 200; font-size: 1.5rem;">
                        Email e senha</p>
                </div>
            </div>
            <label>E-mail</label>
            <input type="email" name="email" class="enderecodeemail" placeholder="Ex: bernardo@outlook.com">
            <label>Confirmar e-mail</label>
            <input type="email" name="confirmaremail" class="confirmar_email" placeholder="Ex:bernardo@outlook.com">
            <div style="display: flex; align-items: center;">
                <div>
                    <label>Senha</label>
                    <input type="password" name="senha" class="password" placeholder="*******">
                </div>
                <div>
                    <label>Confirmar senha</label>
                    <input type="password" name="confirmarsenha" class="confirmar_senha" placeholder="*******">
                </div>
            </div>
            <input type="submit" nome="anterior" class="anteri_or" value="anterior">
            <input type="submit" name="enviar" class="confirm_ar" value="Confirmar">
        </fieldset>

    </form>


    <script>

    </script>
</body>

</html>
