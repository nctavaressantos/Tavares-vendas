# Tavares-vendas<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tavares Vendas - Sua Loja Online</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f4f4f4;
        }
        header {
            background-color: #0077b6;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #023e8a;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .product {
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
            text-align: center;
        }
        .product img {
            width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #333;
        }
        .product button {
            background-color: #0077b6;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background-color: #023e8a;
        }
        footer {
            background-color: #0077b6;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        form {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
            max-width: 500px;
            margin: auto;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        form button {
            background-color: #0077b6;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        form button:hover {
            background-color: #023e8a;
        }
    </style>
</head>
<body>

<header>
    <h1>Tavares Vendas</h1>
    <p>Sua loja online de confiança!</p>
</header>

<nav>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Fale Conosco</a>
    <a href="#pagamento">Pagamento</a>
</nav>

<div class="container" id="produtos">
    <h2>Produtos em Destaque</h2>
    <div class="products">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Produto 1">
            <h3>Produto 1</h3>
            <p>R$ 99,90</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Produto 2">
            <h3>Produto 2</h3>
            <p>R$ 149,90</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Produto 3">
            <h3>Produto 3</h3>
            <p>R$ 79,90</p>
            <button>Comprar</button>
        </div>
    </div>
</div>

<div class="container" id="contato">
    <h2>Fale com o Vendedor</h2>
    <form>
        <input type="text" placeholder="Seu nome" required>
        <input type="email" placeholder="Seu e-mail" required>
        <textarea rows="5" placeholder="Digite sua mensagem" required></textarea>
        <button type="submit">Enviar</button>
    </form>
</div>

<div class="container" id="pagamento">
    <h2>Área de Pagamento</h2>
    <form>
        <input type="text" placeholder="Nome no cartão" required>
        <input type="text" placeholder="Número do cartão" required>
        <input type="text" placeholder="Validade (MM/AA)" required>
        <input type="text" placeholder="CVV" required>
        <button type="submit">Finalizar Compra</button>
    </form>
</div>

<footer>
    <p>&copy; 2025 Tavares Vendas - Todos os direitos reservados.</p>
</footer>

</body>
</html>
