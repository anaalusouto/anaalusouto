<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil do GitHub</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .container h1 {
            margin-bottom: 20px;
        }
        .skills {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .skill {
            margin: 10px;
            padding: 20px;
            border-radius: 10px;
            background-color: #eaeaea;
            width: 100px;
            transition: transform 0.3s;
        }
        .skill:hover {
            transform: scale(1.1);
        }
        .skill i {
            font-size: 40px;
            margin-bottom: 10px;
        }
        .skill p {
            margin: 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Minhas Habilidades</h1>
        <div class="skills">
            <div class="skill">
                <i class="fas fa-laptop-code"></i>
                <p>Front-end</p>
            </div>
            <div class="skill">
                <i class="fas fa-server"></i>
                <p>Back-end</p>
            </div>
            <div class="skill">
                <i class="fab fa-java"></i>
                <p>Java</p>
            </div>
            <div class="skill">
                <i class="fas fa-code"></i>
                <p>C</p>
            </div>
        </div>
    </div>
</body>
</html>

<div>
<a href="https://github.com/seu-usuário-aqui">
<img loading="lazy" height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anaalusouto&layout=compact&langs_count=7&theme=dracula"/>
<img loading="lazy" height="180em" src="https://github-readme-stats.vercel.app/api?username=anaalusouto&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>

