<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vitae</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .header {
            text-align: left;
        }

        .header img {
            max-width: 100%;
            height: auto;
            border-radius: 50%;
            float: left; 
            margin-right: 10px; 
        }

        .main {
            display: flex;
        }

        .sidebar {
            flex: 0 0 30%;
            border-right: 1px solid #ddd;
            padding-right: 20px;
            margin-right: 20px;
        }

        .content {
            flex: 1;
        }

        .section {
            margin-bottom: 20px;
        }

        .section h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }

        .section p {
            color: #555;
            margin-bottom: 10px;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="main">
            <div class="sidebar">
                <div class="header">
                    <img src="caminho/para/imagem.jpg" alt="Foto de Perfil">
                  <br>
                    <h1>Penélope Antunes</h1>
                    <p>Engenheira de Software</p>
                </div>

                <h2>Informações Pessoais</h2>
                <p><strong>Data de Nascimento:</strong> 29/11/2005</p>
                <p><strong>Telefone:</strong> (31) 97811002</p>
                <p><strong>Email:</strong> penelopecristine@gmail.com</p>
                <p><strong>Localização:</strong> Belo Horizonte/MG</p>
            </div>

            <div class="content">
                <div class="section">
                    <h2>Resumo Profissional</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam convallis, neque eu posuere
                        ullamcorper, odio libero fringilla sapien, a fermentum diam velit eu ipsum.</p>
                </div>

                <div class="section">
                    <h2>Experiência Profissional</h2>
                    <p><strong>Empresa COPASA</strong> - Programador Júnior - Janeiro 2027 - Atual</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero.
                        Sed cursus ante dapibus diam.</p>

                    <p><strong>Empresa Mavimoto</strong> - Analista de Segurança - Maio 2024 - Dezembro 2026</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero.
                        Sed cursus ante dapibus diam.</p>
                </div>

                <div class="section">
                    <h2>Formação Acadêmica</h2>
                    <p><strong>Pontifícia Universidade Católica de Minas Gerais</strong> - Bacharelado em Engenharia de Software - 2024 - 2027</p>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
