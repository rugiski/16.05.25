# 16.05.25<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Aula de Projetos Autorais</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <h1>Projetos Autorais - Aula de Criação de Sites</h1>
        <nav>
            <ul>
                <li><a href="#introducao">Introdução</a></li>
                <li><a href="#estrutura">Estrutura do Código</a></li>
                <li><a href="#estilo">Estilo com CSS</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="introducao">
            <h2>Introdução</h2>
            <p>Nesta aula, aprendemos a criar projetos autorais, entendendo a importância de uma estrutura organizada de HTML e CSS para desenvolver sites originais e bem planejados.</p>
        </section>

        <section id="estrutura">
            <h2>Estrutura de um Código HTML</h2>
            <p>O HTML deve ser organizado com tags semânticas, como &lt;header&gt;, &lt;main&gt;, &lt;section&gt;, &lt;footer&gt;, além de usar títulos, parágrafos, listas e links para estruturar o conteúdo de forma clara.</p>
        </section>

        <section id="estilo">
            <h2>Estilo com CSS</h2>
            <p>O CSS é utilizado para personalizar cores, fontes, espaçamentos e layout do site. É importante criar variáveis de cores e fontes para manter a consistência visual e dar personalidade ao projeto.</p>
        </section>
    </main>

    <footer>
        <p>Projeto criado para a aula de projetos autorais. Desenvolvido por [Seu Nome].</p>
    </footer>
</body>
</html>
Arquivo: style.css

/* Variáveis de cores e fontes */
:root {
    --primary-color: #4CAF50;
    --secondary-color: #8BC34A;
    --text-color: #333;
    --background-color: #f4f4f4;
    --font-body: 'Arial', sans-serif;
    --font-title: 'Georgia', serif;
}

/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: var(--font-body);
}

/* Estilo do corpo da página */
body {
    background-color: var(--background-color);
    color: var(--text-color);
    line-height: 1.6;
    padding: 20px;
}

/* Cabeçalho */
header {
    background-color: var(--primary-color);
    padding: 20px;
    color: white;
    text-align: center;
}

header h1 {
    font-family: var(--font-title);
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

/* Main content */
main {
    margin-top: 20px;
}

section {
    background
