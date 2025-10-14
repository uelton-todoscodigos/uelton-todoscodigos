<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Portfólio - Uelton Santos da Silva</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background: #121212;
            color: #eee;
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            padding: 20px;
        }

        .container {
            max-width: 700px;
            background: #1e1e1e;
            border-radius: 10px;
            padding: 30px 40px;
            box-shadow: 0 0 15px rgba(0,0,0,0.7);
        }

        header h1 {
            font-size: 2.2rem;
            margin-bottom: 20px;
        }

        header h1 span {
            color: #61dafb; /* cor azul JS */
        }

        section {
            margin-bottom: 25px;
        }

        h2 {
            color: #ff6f61;
            margin-bottom: 15px;
            border-bottom: 2px solid #ff6f61;
            padding-bottom: 5px;
        }

        ul {
            list-style-type: none;
        }

        ul li {
            padding-left: 1.3em;
            position: relative;
            margin-bottom: 8px;
        }

        ul li::before {
            content: "•";
            position: absolute;
            left: 0;
            color: #61dafb;
            font-weight: bold;
        }

        a {
            color: #61dafb;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .project-item {
            background: #292929;
            padding: 15px 20px;
            border-radius: 8px;
            box-shadow: inset 0 0 10px rgba(97, 218, 251, 0.2);
        }

        footer {
            text-align: center;
            margin-top: 30px;
            font-style: italic;
            color: #999;
            font-size: 0.9rem;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet" />
</head>
<body>
    <main class="container">
        <header>
            <h1>👋 Olá! Eu sou <span>Uelton Santos da Silva</span></h1>
        </header>

        <section class="about">
            <h2>🚀 Sobre mim</h2>
            <p>Sou estudante de IoT, apaixonado por programação com JavaScript, C++ e desenvolvimento com Arduino. Estou em constante aprendizado e explorando novas tecnologias para criar projetos inovadores e práticos.</p>
        </section>

        <section class="tech">
            <h2>💻 Tecnologias e Plataformas</h2>
            <ul>
                <li>JavaScript (JS)</li>
                <li>C++</li>
                <li>Arduino</li>
                <li>Visual Studio Code</li>
                <li>Outras tecnologias (adicione aqui)</li>
            </ul>
        </section>

        <section class="projects">
            <h2>🛠️ Projetos</h2>
            <div class="project-item">
                <h3>Projetos Prime</h3>
                <p><strong>Repositório:</strong> <a href="https://github.com/uelton-todoscodigos/uelton-todoscodigos.git" target="_blank" rel="noopener noreferrer">github.com/uelton-todoscodigos/uelton-todoscodigos</a></p>
                <p><strong>Descrição:</strong> (adicione uma breve descrição do projeto aqui)</p>
                <p><strong>Tecnologias usadas:</strong> JS, C++, Arduino</p>
            </div>
        </section>

        <section class="goals">
            <h2>🎯 Objetivos</h2>
            <p>Estou focado em aprimorar minhas habilidades em IoT, desenvolvimento embarcado e programação para dispositivos conectados. Quero criar soluções que unam software e hardware para melhorar a vida das pessoas.</p>
        </section>

        <section class="contact">
            <h2>📫 Contato</h2>
            <ul>
                <li>GitHub: <a href="https://github.com/uelton-todoscodigos" target="_blank" rel="noopener noreferrer">uelton-todoscodigos</a></li>
                <li>Email: (adicione seu email aqui)</li>
                <li>LinkedIn: (adicione seu LinkedIn aqui)</li>
            </ul>
        </section>

        <footer>
            <p>✨ Obrigado por visitar meu portfólio!</p>
        </footer>
    </main>
</body>
</html>