!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Meu Primeiro Projeto</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Projeto HTML e CSS</h1>
    </header>

    <section>
        <p>Este é um exemplo de como criar uma página web simples com HTML e CSS.</p>
        <button class="button">Clique Aqui</button>
    </section>

    <footer>
        <p>Desenvolvido por [Seu Nome]</p>
    </footer>
</body>
</html>

Arquivo CSS (style.css)

/* Estilizando o body da página */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

/* Estilizando o header */
header {
    background-color: #007BFF;
    color: white;
    text-align: center;
    padding: 20px 0;
}

/* Estilizando o título */
h1 {
    margin: 0;
    font-size: 2.5em;
}

/* Estilizando a seção */
section {
    margin: 20px;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

/* Estilizando o parágrafo */
section p {
    font-size: 1.2em;
    line-height: 1.5;
}

/* Estilizando o botão */
.button {
    background-color: #007BFF;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 1em;
    cursor: pointer;
    transition: background-color 0.3s;
}

/* Efeito hover no botão */
.button:hover {
    background-color: #0056b3;
}

/* Estilizando o footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
