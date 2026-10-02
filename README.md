<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O Incrível Mundo de Neco Radical</title>
    <style>
        :root {
            --bg-color: #ff007f;
            --panel-color: #230046;
            --accent-color: #00f0ff;
            --text-color: #ffffff;
            --yellow-neon: #fffb00;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Courier New', Courier, monospace;
        }

        body {
            background-color: var(--bg-color);
            background-image: linear-gradient(45deg, #ff007f 25%, #7928ca 25%, #7928ca 50%, #ff007f 50%, #ff007f 75%, #7928ca 75%, #7928ca 100%);
            background-size: 80px 80px;
            color: var(--text-color);
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            background-color: var(--panel-color);
            border: 4px solid var(--accent-color);
            box-shadow: 10px 10px 0px #000000;
            max-width: 600px;
            width: 100%;
            padding: 30px;
            text-align: center;
        }

        header h1 {
            color: var(--yellow-neon);
            font-size: 2.5rem;
            text-transform: uppercase;
            margin-bottom: 10px;
            text-shadow: 3px 3px 0px #ff007f;
        }

        header p {
            font-style: italic;
            color: var(--accent-color);
            margin-bottom: 25px;
        }

        .avatar-box {
            background-color: #000;
            border: 2px dashed var(--yellow-neon);
            display: inline-block;
            padding: 20px;
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .bio h2 {
            color: var(--accent-color);
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        .bio p {
            line-height: 1.6;
            margin-bottom: 20px;
            text-align: justify;
        }

        .facts {
            background-color: rgba(255, 255, 255, 0.1);
            border-left: 5px solid var(--yellow-neon);
            padding: 15px;
            text-align: left;
            margin-bottom: 25px;
        }

        .facts h3 {
            color: var(--yellow-neon);
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        .facts ul {
            list-style-type: '⚡ ';
            margin-left: 20px;
        }

        .facts li {
            margin-bottom: 8px;
        }

        footer {
            border-top: 2px solid var(--accent-color);
            padding-top: 15px;
            font-size: 0.8rem;
            color: #888;
        }

        footer a {
            color: var(--yellow-neon);
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Neco Radical</h1>
            <p>— O Lendário Campeão do Fliperama de 1995 —</p>
        </header>

        <div class="avatar-box">
            🕹️😎📟
        </div>

        <section class="bio">
            <h2>Quem é essa lenda?</h2>
            <p>
                Se você frequentou a "Cyber-Estação" do bairro no meio dos anos 90, com certeza ouviu falar de <strong>Neco Radical</strong>. Conhecido por jogar usando óculos escuros em ambientes fechados e por nunca soltar sua pochete, Neco detém até hoje o recorde invicto de pontuação máxima no clássico <em>Street Fighter II</em> da cidade.
            </p>
        </section>

        <section class="facts">
            <h3>Fatos Rápidos:</h3>
            <ul>
                <li><strong>Bebida favorita:</strong> Suco artificial de uva em saquinho.</li>
                <li><strong>Habilidade secreta:</strong> Consegue zerar qualquer jogo com apenas uma ficha.</li>
                <li><strong>Gíria mais usada:</strong> "Cabuloso, bicho!"</li>
            </ul>
        </section>

        <footer>
            <p>Página criada em 1997. Atualizada hoje.</p>
            <p>Deixe um recado no nosso <a href="#">Livro de Visitas</a>!</p>
        </footer>
    </div>

</body>
</html>

