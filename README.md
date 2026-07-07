# PRIMEIRAPAGINANINA
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olivia Rodrigo</title>

    <style>
        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #4b0082;
            color: #333;
        }

        header {
            background-color: #c9a0ff;
            color: #4b0082;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
            padding: 24px 16px;
            border-radius: 8px 8px 0 0;
            border: 1px solid #ffffff;
        }

        header h1 {
            margin: 0 0 10px 0;
        }

        header p {
            margin: 0;
            opacity: 0.85;
        }

        main {
            background-color: #ffffff;
            max-width: 800px;
            margin: 0 auto;
            padding: 32px 16px;
            box-sizing: border-box;
            border-radius: 0 0 8px 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);

            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;

            border: 1px solid #ffffff;
            border-top: none;
        }

        img {
            width: 120px;
            height: 120px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 16px;
        }

        main h2 {
            margin: 0 0 8px 0;
            color: #4b0082;
        }

        .autor {
            font-style: italic;
            color: #666;
            margin: 0 0 16px 0;
        }

        .mensagem {
            font-size: 1.05rem;
            max-width: 600px;
            line-height: 1.6;
        }

        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            background-color: #c9a0ff;
            color: #4b0082;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background-color: #b084f7;
        }
    </style>
</head>

<body>

    <header>
        <h1>OLIVIA RODRIGO</h1>
        <p>Bem-vindo ao universo da artista</p>
    </header>

    <main>
        <p><img src="or.png" alt="Imagem da Olivia Rodrigo"></p>

        <h2>Olivia Rodrigo</h2>
        <p class="autor">Por: Nina Lara</p>

        <p class="mensagem">
            Bem-vindo ao site sobre a Olivia Rodrigo!<br><br>

            Aqui é o lugar certo pra quem curte as músicas dela, quer saber mais sobre a carreira e descobrir um pouco do universo da Olivia. Ela ficou famosa com “drivers license” e, desde então, vem lançando músicas que falam de sentimentos reais, tipo amor, términos e aquelas fases meio confusas da vida que todo mundo já viveu.<br><br>

            Fica à vontade pra explorar o site e mergulhar nesse mundo dela — tem muita coisa legal pra conhecer!
        </p>

        <button>❤️ <span>0</span></button>

    </main>

    <main>
        <p><img src="ORdrivers.png" alt="Imagem da Olivia Rodrigo"></p>

        <h2>Olivia Rodrigo</h2>
        <p class="autor">Por: Nina Lara</p>

        <p class="mensagem">
          
           A música "drivers license", de Olivia Rodrigo,a sua musica mais famosas, foi lançada em 2021 e fala sobre a tristeza após o fim de um relacionamento. A carteira de motorista representa um sonho que perdeu o sentido com a separação. A canção fez grande sucesso mundial e ganhou um Grammy.<br><br>
           </p>

        <button>❤️ <span>0</span></button>

    </main>

    <script>
        const botao = document.querySelector("button");

        botao.addEventListener("click", botaoClicado);

        function botaoClicado() {
            let texto = botao.querySelector("span");
            texto.textContent++;
        }
    </script>

</body>
</html>
