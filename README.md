<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Roupas Femininas - Monica Pedroso Moda Evangélica</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #ff1493;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            margin: 0;
            padding: 15px;
            background-color: #ff69b4;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        .hero {
            background-color: #ffe4e1;
            padding: 50px;
            text-align: center;
        }

        .hero h1 {
            color: #ff1493;
            font-size: 2.5rem;
        }

        .catalogo {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
        }

        .produto {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 20px;
            width: 250px;
            text-align: center;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .produto img {
            max-width: 100%;
            border-radius: 8px;
        }

        footer {
            background-color: #ff69b4;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .social-links {
            margin: 10px;
        }

        .social-links a {
            margin: 0 10px;
            color: white;
            font-size: 1.2rem;
            text-decoration: none;
        }

        .whatsapp-button {
            background-color: #25d366;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
            font-size: 1.2rem;
        }

        .whatsapp-button:hover {
            background-color: #20b358;
        }
    </style>
</head>

<body>

    <header>
        <h1>Monica Pedroso Moda Evangélica</h1>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Catálogo</a>
        <a href="#">Sobre Nós</a>
        <a href="#">Contato</a>
    </nav>

    <section class="hero">
        <h1>Roupas Femininas, Evangélicas e Sociais</h1>
        <p>Explore nossa coleção de roupas estilosas e modestas.</p>
        <a class="whatsapp-button" href="https://wa.me/SEU_NUMERO_DE_WHATSAPP" target="_blank">Fale Conosco no WhatsApp</a>
    </section>

    <section class="catalogo">
        <div class="produto">
            <img src="https://via.placeholder.com/250" alt="Produto 1">
            <h2>Vestido Social</h2>
            <p>R$ 120,00</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/250" alt="Produto 2">
            <h2>Saia Midi</h2>
            <p>R$ 80,00</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/250" alt="Produto 3">
            <h2>Blusa Elegante</h2>
            <p>R$ 70,00</p>
        </div>
    </section>

    <footer>
        <p>Siga-nos nas redes sociais!</p>
        <div class="social-links">
            <a href="https://www.instagram.com/seu_perfil" target="_blank">Instagram</a>
            <a href="https://www.facebook.com/seu_perfil" target="_blank">Facebook</a>
        </div>
        <p>© 2024 Monica Pedroso Moda Evangélica - Todos os direitos reservados</p>
    </footer>

</body>

</html>
