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

        input {
            width: 100%;
            border-radius: 20px;
            padding: 0.5rem;
            margin: 0.2rem;
        }


        .seila {
            display: block;
            margin-bottom: 1.5%;

        }

        #etapa-dois {
            display: none;
        }

        #etapa-tres {
            display: none;
        }
    </style>

</head>

<body>


    <form id="formulario">


        </ul>




        <div id="etapa-um" style="display: block;">
            <div style="width: 100%; justify-content: center; align-items: center; display: flex;">
                <div>

                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; margin-bottom: 5%; color:#048BA8;font-size: 2.5rem; font-weight: 400;">
                        Cadastro</p>
                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; color: #01C3BC; font-weight: 200; font-size: 1.5rem;">
                        Informações pessoais</p>
                </div>
            </div>

            <div class="etapa_one">
                <label>Nome</label>
                <input type="text" placeholder="Ex: Bernardo Silva" class="nome" id="name" name="nome">
                <label>CPF</label>
                <input type="text" placeholder="Ex: 123.456.789-00" class="cpf" id="cpff" name="cpf">
                <div style="display: flex; align-items: center;">
                    <div style="width: 50%;">
                        <label style="display: block;">Nascimento</label>
                        <input type="date" class="nascimento" id="nascido" style="width: 100%;" name="datadenascimento">
                    </div>
                    <div style="width: 5%;"></div>
                    <div style="align-items: center; width: 50%;">
                        <label>Sexo</label>
                        <select class="sexo" style="width: 100%;" name="sexo">
                            <option>Feminino</option>
                            <option>Masculino</option>
                            <option>Prefiro não responder</option>
                            <option>Outros</option>
                        </select>
                    </div>
                </div>
                <label>Telefone</label>
                <input type="tel" class="telefone" placeholder="Ex: (12) 3456-7890" id="celular"
                    name="numerodetelefone">
                <br>
                <div style="text-align: center;">
                    <input type="button" name="enviar" class="envi_ar" value="Proximo"
                        style="width: 50%; border-color:#048BA8; background-color: #FFFFFF;" id="enviar_um"
                        onclick="next1()">
                </div>
            </div>
        </div>




        <div id="etapa-dois">
            <div style="width: 100%; justify-content: center; align-items: center; display: flex;">
                <div>

                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; margin-bottom: 5%; color:#048BA8;font-size: 2.5rem; font-weight: 400;">
                        Cadastro</p>
                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; color: #01C3BC; font-weight: 200; font-size: 1.5rem;">
                        Endereço</p>
                </div>
            </div>
            <div class="etapa_two">
                <div style="display: flex; align-items: center;">
                    <div style="width: 50%;">
                        <label style="display: block;">Estado</label>
                        <input type="text" name="estado" class="esta_do" placeholder="Ex: RN">
                    </div>
                    <div style="width: 5%;"></div>
                    <div style="width: 50%;">
                        <label>Cidade</label>
                        <input type="text" name="cidade" class="cida_de" placeholder="Ex: Mossoro">
                    </div>
                </div>
                <div style="display: flex; align-items: center;">
                    <div style="width: 50%;">
                        <label>Bairro</label>
                        <input type="text" name="bairro" class="bair_ro" placeholder="Ex: Nova Betania">
                    </div>
                    <div style="width: 5%;"></div>
                    <div style="width: 50%;">
                        <label>Rua</label>
                        <input type="text" name="rua" class="r_ua" placeholder="Ex: R. Martins">
                    </div>
                </div>
                <label>CEP</label>
                <input type="text" name="cep" class="c_ep" placeholder="Ex: 123.456-789">
                <label>Complemento</label>
                <input type="text" name="complemento_endereco" class="complemen_to"
                    placeholder="Ex: Proximo a prefeitura">
                <br>
                <div style="display: flex; align-items: center;">
                    <div style="width: 50%;">
                        <input type="button" nome="anterior" class="anteri_or" value="Anterior"
                            style="border-color:#048BA8; background-color: #FFFFFF;" onclick="anterior2()">
                    </div>
                    <div style="width: 5%;"></div>
                    <div style="width: 50%;">
                        <input type="button" name="enviar" class="envi_ar" value="Proximo"
                            style="border-color:#048BA8; background-color: #FFFFFF;" id="proximo_dois"
                            onclick="next2()">
                    </div>
                </div>
            </div>
        </div>



        <div id="etapa-tres">
            <div style="width: 100%; justify-content: center; align-items: center; display: flex;">
                <div>

                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; margin-bottom: 5%; color:#048BA8;font-size: 2.5rem; font-weight: 400;">
                        Cadastro</p>
                    <p
                        style="margin: 0%; justify-content: center; align-items: center; display: flex; color: #01C3BC; font-weight: 200; font-size: 1.5rem;">
                        Email e senha</p>
                </div>
            </div>
            <div class="etapa_three">
                <label>E-mail</label>
                <input type="email" name="email" class="enderecodeemail" placeholder="Ex: bernardo@outlook.com">
                <label>Confirmar e-mail</label>
                <input type="email" name="confirmaremail" class="confirmar_email" placeholder="Ex:bernardo@outlook.com">
                <div style="display: flex; align-items: center;">
                    <div style="width: 50%;">
                        <label>Senha</label>
                        <input type="password" name="senha" class="password" placeholder="*******">
                    </div>
                    <div style="width: 5%;"></div>
                    <div style="width: 50%;">
                        <label>Confirmar senha</label>
                        <input type="password" name="confirmarsenha" class="confirmar_senha" placeholder="*******">
                    </div>
                </div>
                <br>
                <div style="display: flex; align-items: center;">
                    <div style="width: 50%;">
                        <input type="button" nome="anterior" class="anteri_or" value="anterior"
                            style="border-color:#048BA8; background-color: #FFFFFF;" id="anterior_dois"
                            onclick="anterior3()">
                    </div>
                    <div style="width: 5%;"></div>
                    <div style="width: 50%;">
                        <input type="submit" name="enviar" class="confirm_ar" value="Confirmar"
                            style="border-color:#048BA8; background-color: #FFFFFF;">
                    </div>
                </div>
            </div>
        </div>


    </form>


    <script>
        const tela_um = document.getElementById("etapa-um")
        const tela_dois = document.getElementById("etapa-dois")
        const tela_tres = document.getElementById("etapa-tres")

        function next1() {
            tela_um.style.display = "none"
            tela_dois.style.display = "block"
            tela_tres.style.display = "none"
        }

        function next2() {
            tela_um.style.display = "none"
            tela_dois.style.display = "none"
            tela_tres.style.display = "block"
        }

        function anterior2() {
            tela_dois.style.display = "none"
            tela_um.style.display = "block"
            tela_tres.style.display = "none"
        }

        function anterior3() {
            tela_tres.style.display = "none"
            tela_dois.style.display = "block"
            tela_um.style.display = "none"
        }
    </script>
</body>

</html>
