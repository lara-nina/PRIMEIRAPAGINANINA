# PRIMEIRAPAGINANINA
primeira pagina feita na aula o prof marcos
box-sizing: border-box;
            border-radius: 0 0 8px 8px;
            border: 1px solid #ddd; /* Borda fina */
            border-top: none; /* Une com o header */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);

            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        /* Estilização da imagem */
        img {
            width: 120px;
            height: 120px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 16px;
            border: 2px solid #d8bffb; /* Borda da imagem combinando com fundo */
        }

        main h2 {
            margin: 0 0 8px 0;
            color: DarkSlateBlue;
        }

        .autor {
            font-style: italic;
            color: #666;
            margin: 0 0 16px 0;
        }

        .mensagem {
            font-size: 1.1rem;
            max-width: 500px;
            line-height: 1.5;
        }
    </style>
</head>
<body>

    <header>
        <h1>Crie um nome para sua página</h1>
        <p>Faça uma introdução interessante, diga algo que chame a atenção</p>
    </header>

    <main>
        <p><img src="entregue.png" alt="Pessoa atribulada com trabalhos para entregar"></p>
        <h2>Meu primeiro post</h2>
        <p class="autor">Por: Marcos Felix</p>
        <p class="mensagem">
            Seja muito bem-vindo(a)! Este é um espaço criado para compartilhar ideias,
            experiências e conteúdos especiais. Espero que você aproveite a visita e
            volte sempre para acompanhar as novidades.
        </p>
    </main>

</body>
</html>
