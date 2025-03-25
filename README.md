<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gustavo Carvalho - Corretor de Imóveis</title>
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #333; /* Fundo cinza escuro */
            color: #eee; /* Texto cinza claro */
            line-height: 1.6;
        }
        header {
            background-color: #222; /* Cabeçalho cinza escuro */
            color: #ff4d4d; /* Texto vermelho */
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 20px;
        }
        nav ul li a {
            color: #ff4d4d; /* Links vermelhos */
            text-decoration: none;
            font-weight: 600;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        nav ul li a:hover {
            background-color: #444;
        }
        .hero {
            background-image: url('rio.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 150px 20px;
            background-color: rgba(0, 0, 0, 0.7);
            background-blend-mode: multiply;
        }
        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
            font-weight: 700;
        }
        section {
            padding: 60px 20px;
            text-align: center;
            background-color: #444;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        section h2 {
            color: #ff4d4d;
            margin-bottom: 30px;
            font-weight: 600;
            font-size: 2em;
        }
        .service-list {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .service-list li {
            text-align: left;
            padding: 20px;
            border: 1px solid #555;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        .service-list li:hover {
            transform: translateY(-5px);
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 90%;
            max-width: 600px;
            margin: 30px auto;
        }
        input, textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #555;
            border-radius: 8px;
            box-sizing: border-box;
            font-size: 1em;
            background-color: #222;
            color: #eee;
        }
        button {
            background-color: #ff4d4d;
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1em;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #cc0000; /* Hover do botão vermelho escuro */
        }
        footer {
            background-color: #222; /* Rodapé cinza escuro */
            color: #ff4d4d; /* Texto do rodapé vermelho */
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        .contact-info {
            margin-top: 30px;
        }
        .contact-info p {
            margin: 10px 0;
        }
        .contact-info a {
            color: #ff4d4d; /* Links de contato vermelhos */
            text-decoration: none;
            font-weight: 600;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <script type="text/javascript">
        window.onload = function(){
            (function(d, script) {
                script = d.createElement('script');
                script.type = 'text/javascript';
                script.async = true;
                script.src = 'https://w.app/widget-v1/Hy4bWf.js';
                d.getElementsByTagName('head')[0].appendChild(script);
            }(document));
        };
    </script>
</head>
<body>
    <header>
        <h1>Gustavo Carvalho - Corretor de Imóveis</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <div class="hero">
        <h1>Encontre o imóvel dos seus sonhos</h1>
        <p style="font-size: 1em; margin-top: 10px;">Com segurança, transparência e dedicação.</p>
    </div>
    
    <section id="sobre">
        <h2>Sobre Mim</h2>
        <div style="text-align: center;">
            <img src="https://i.imgur.com/rznusrJ.png" alt="Foto de Gustavo Silva" style="max-width: 150px; border-radius: 50%;">
        </div>
        <p>Olá, sou Gustavo Carvalho, corretor de imóveis na Lopes & Icaraí (CRECI: 101920). Estou à disposição para ajudá-lo a encontrar o imóvel dos seus sonhos com segurança, transparência e dedicação. Vamos juntos transformar seu desejo em realidade!</p>
    </section>
    
    <section id="servicos">
        <h2>Nossos Serviços</h2>
        <ul class="service-list">
            <li>Compra e Venda de Imóveis</li>
            <li>Suporte Completo</li>
            <li>Avaliação de Imóveis</li>
            <li>Financiamento Imobiliário</li>
        </ul>
    </section>
    
    <section id="contato">
        <h2>Fale comigo!</h2>
        <div class="contact-info">
            <p>Entre em contato diretamente:</p>
            <p>Telefone: (21) 98113-4363</p>
            <p>Email: <a href="mailto:contato@exemplo.com">gustavo.silva@associadoslopesniteroi.com.br</a></p>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 Gustavo Carvalho - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
