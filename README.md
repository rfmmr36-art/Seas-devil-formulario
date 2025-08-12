# Seas-devil-formulario
Formulário da tripulação 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário Seas Devil</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0a0a0a;
            color: white;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #ff0000;
        }
        form {
            max-width: 500px;
            margin: auto;
            background: rgba(255, 255, 255, 0.05);
            padding: 20px;
            border-radius: 10px;
        }
        label {
            display: block;
            margin-top: 15px;
            text-align: left;
        }
        input, textarea, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: none;
            border-radius: 5px;
            background: #1a1a1a;
            color: white;
        }
        button {
            background-color: #ff0000;
            color: white;
            padding: 10px;
            margin-top: 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #cc0000;
        }
    </style>
</head>
<body>

    <h1>☠️ Boas-vindas, Pirata! ☠️</h1>
    <p>✨ Preencha todos os campos com atenção ✨</p>

    <form action="https://formspree.io/f/mseadev" method="POST">
        <label>📛 Nome:
            <input type="text" name="nome" required>
        </label>

        <label>🎮 Nick do Roblox:
            <input type="text" name="nick_roblox" required>
        </label>

        <label>🏝 Nome de Pirata:
            <input type="text" name="nome_pirata" required>
        </label>

        <label>📅 Idade:
            <input type="number" name="idade" required>
        </label>

        <label>⚓ Objetivo dentro da tripulação:
            <textarea name="objetivo" rows="2" required></textarea>
        </label>

        <label>📊 Seu nível:
            <input type="number" name="nivel" required>
        </label>

        <label>💰 Seu Bounty:
            <input type="text" name="bounty" required>
        </label>

        <label>🍏 Sua fruta:
            <input type="text" name="fruta" required>
        </label>

        <label>⚔️ Seu modelo (Ex: Pirata, Espadachim, etc):
            <input type="text" name="modelo" required>
        </label>

        <button type="submit">☠️ Enviar Formulário ☠️</button>
    </form>

    <p>☠️ Seja bem-vindo aos Seas Devil! ☠️</p>

</body>
</html>
