<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Online - Curso</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8; /* Fundo claro */
        }
        header {
            background-color: #004d40; /* Verde escuro */
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Sombra */
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
        }
        header img {
            height: 40px; /* Ajuste o tamanho do ícone */
            vertical-align: middle;
        }
        nav {
            background-color: #00796b; /* Verde médio */
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Sombra */
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .product {
            background-color: #ffffff; /* Branco para destacar os produtos */
            border: 1px solid #d0e5e5; /* Verde claro para a borda */
            margin: 15px;
            padding: 20px;
            width: 300px;
            text-align: center;
            border-radius: 8px; /* Bordas arredondadas */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Sombra */
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .product:hover {
            transform: translateY(-10px); /* Efeito de elevação */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15); /* Sombra mais forte */
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px; /* Bordas arredondadas nas imagens */
        }
        .product h3 {
            margin: 15px 0;
            font-size: 20px;
        }
        .product p {
            color: #4caf50; /* Verde para a descrição */
            font-size: 16px;
        }
        .product button {
            background-color: #004d40; /* Verde escuro para o botão */
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px; /* Bordas arredondadas do botão */
            transition: background-color 0.3s ease;
        }
        .product button:hover {
            background-color: #00796b; /* Verde médio ao passar o mouse */
        }
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                align-items: center;
            }
        }
        footer {
            background-color: #004d40; /* Verde escuro */
            color: #fff;
            text-align: center;
            padding: 15px 0;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1); /* Sombra */
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .footer-link {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            background-color: #00796b; /* Verde médio */
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .footer-link:hover {
            background-color: #004d40; /* Verde escuro ao passar o mouse */
        }
        .social-button {
            background-color: #c13584; /* Cor do Instagram */
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
            margin: 10px;
            transition: background-color 0.3s ease;
        }
        .social-button:hover {
            background-color: #a02d68; /* Cor mais escura do Instagram ao passar o mouse */
        }
    </style>
</head>
<body>

<header>
    <img src="https://via.placeholder.com/40" alt="Ícone Kiwify"> <!-- Substitua pelo URL do ícone da Kiwify -->
    <h1>Bem-vindo à Loja de E-book Marketing Digital!</h1>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#">Sobre Nós</a>
    <a href="#">Contato</a>
</nav>

<div class="container">
    <div class="product">
        <img src="/mnt/data/file-oo7VzO0idAEAmXoj8IWUx4hT" alt="Produto 1">
        <h3>Produto 1</h3>
        <p>Descrição breve do produto.</p>
        <a href="https://pay.kiwify.com.br/1Jxo4Kk" target="_blank">
            <button>Comprar Agora</button>
        </a>
    </div>
    <div class="product">
        <img src="produto3.jpg" alt="Produto 3">
        <h3>Produto 3</h3>
        <p>Descrição breve do produto.</p>
        <a href="https://pay.kiwify.com.br/aJJtXL4" target="_blank">
            <button>Comprar Agora</button>
        </a>
    </div>
</div>

<footer>
    <a href="http://curso.com.br" class="footer-link" target="_blank">Visite nosso site</a>
    <a href="https://www.instagram.com/milonario_curso?igsh=MXJzc2thYzFzczV2cA==" class="social-button" target="_blank">Rede Social</a>
    <p>&copy; 2024 Loja Online - Curso</p>
</footer>

</body>
</html>-
