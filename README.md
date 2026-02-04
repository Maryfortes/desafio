# desafio
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Clínica Vida Saudável</title>
    <style>
        html, body 
            margin: 0;
        
        body 
            background-color: #f1f1f1;
            display: flex;
            justify-content: center;
        

        .wrapper 
            width: 1200px;
            display: flex;
            margin: 0 auto;
            background-color: aquamarine;
        
        .main 
            display: flex;
            flex-flow: column;
            width: 85%;
        
        .menu 
            width: 15%;
            background-color: aqua;
            padding: 10px 20px 0px;
        
        .menu a 
            display: block;
            margin: 10px 0;
            text-decoration: none;
            font-weight: bold;
        
        .header 
            min-height: 150px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
        
        .header-principal 
            background-color: rgb(5, 108, 108);
        
        .header-sobre 
            background-color: rgb(0, 150, 80);
        
        .header-horarios 
            background-color: rgb(200, 120, 0);
    
        .header-contato 
            background-color: rgb(150, 0, 150);
        
        .content 
            background-color: white;
            min-height: 300px;
            padding: 20px;
        
        .footer 
            background-color: rgb(99, 56, 240);
            min-height: 150px;
            color: white;
            text-align: center;
            padding: 20px;
        
        table 
            border-collapse: collapse;
            width: 100%;
        
        table, th, td 
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        
        img {
            max-height: 150px;
            margin-right: 15px;
        
    </style>
</head>
<body>
    <div class="wrapper">
        <!-- Menu lateral -->
        <div class="menu">
            <a href="#principal">Página Principal</a>
            <a href="#sobre">Sobre a clínica</a>
            <a href="#horarios">Horário de Atendimento</a>
            <a href="#contato">Contato</a>
        </div>

        <!-- Área principal -->
        <div class="main">
            <!-- Página Principal -->
            <div id="principal">
                <div class="header header-principal">
                    <img src="imagens/clinica.jpg" alt="Clínica">
                    <h1>Clínica Vida Saudável</h1>
                </div>
                <div class="content">
                    <p>Bem-vindo à Clínica Vida Saudável! Somos especializados em cuidados médicos de qualidade, oferecendo atendimento humanizado e profissionais altamente capacitados.</p>
                </div>
            </div>

            <!-- Sobre a clínica -->
            <div id="sobre">
                <div class="header header-sobre">
                    <img src="imagens/sobre.jpg" alt="Equipe médica">
                    <h2>Sobre a Clínica</h2>
                </div>
                <div class="content">
                    <p>A Clínica Vida Saudável foi fundada com o objetivo de oferecer atendimento médico de excelência. Contamos com diversas especialidades e infraestrutura moderna para garantir o bem-estar dos nossos pacientes.</p>
                </div>
            </div>

            <!-- Horário de Atendimento -->
            <div id="horarios">
                <div class="header header-horarios">
                    <img src="imagens/horarios.jpg" alt="Relógio">
                    <h2>Horários e Serviços</h2>
                </div>
                <div class="content">
                    <p>Confira abaixo nossos horários de atendimento por especialidade:</p>
                    <table>
                        <tr>
                            <th>Serviços</th>
                            <th>Segunda a Sexta</th>
                            <th>Sábados</th>
                            <th>Feriados</th>
                        </tr>
                        <tr>
                            <td>Clínica geral</td>
                            <td>08h - 19h</td>
                            <td>08h - 14h</td>
                            <td>08h - 14h</td>
                        </tr>
                        <tr>
                            <td>Psicologia</td>
                            <td>08h - 19h</td>
                            <td>08h - 14h</td>
                            <td>08h - 14h</td>
                        </tr>
                        <tr>
                            <td>Pediatria</td>
                            <td>08h - 19h</td>
                            <td>08h - 18h</td>
                            <td>-</td>
                        </tr>
                        <tr>
                            <td>Oftalmologia</td>
                            <td>08h - 19h</td>
                            <td>08h - 18h</td>
                            <td>-</td>
                        </tr>
                    </table>
                </div>
            </div>

            <!-- Contato -->
            <div id="contato">
                <div class="header header-contato">
                    <img src="imagens/contato.jpg" alt="Contato">
                    <h2>Contato</h2>
                </div>
                <div class="content">
                    <p>Telefone: (31) 99999-9999 | WhatsApp: (31) 98888-8888</p>
                    <p>Endereço: Rua da Saúde, 123 - Buritizeiro, MG</p>

                    <!-- Google Maps -->
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!..." width="600" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>

                    <!-- Formulário -->
                    <form>
                        <label>Nome:</label><br>
                        <input type="text" name="nome"><br><br>

                        <label>E-mail:</label><br>
                        <input type="email" name="email"><br><br>

                        <label>Assunto:</label><br>
                        <input type="text" name="assunto"><br><br>

                        <label>Mensagem:</label><br>
                        <textarea name="mensagem" rows="5" cols="40"></textarea><br><br>

                        <input type="submit" value="Enviar">
                        <input type="reset" value="Limpar">
                    </form>
                </div>
            </div>

            <!-- Rodapé -->
            <div class="footer">
                <p>Telefone: (31) 99999-9999 | WhatsApp: (31) 98888-8888</p>
                <p>Endereço: Rua da Saúde, 123 - Buritizeiro, MG</p>
            </div>
        </div>
    </div>
</body>
</html>


