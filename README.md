<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escolha seu Jogo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .games {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }
        .game {
            text-align: center;
        }
        .game img {
            width: 100%;
            max-width: 150px;
            border-radius: 8px;
        }
        .game button {
            margin-top: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            font-size: 14px;
            border-radius: 4px;
            cursor: pointer;
        }
        .game button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <header>
        <h1>Escolha seu Jogo</h1>
    </header>
    <div class="container">
        <h2>Selecione o jogo e a quantidade de coins</h2>
        <div class="games">
            <div class="game">
                <img src="https://via.placeholder.com/150" alt="Free Fire">
                <p>Free Fire</p>
                <button>Selecionar</button>
            </div>
            <div class="game">
                <img src="https://via.placeholder.com/150" alt="Fortnite">
                <p>Fortnite</p>
                <button>Selecionar</button>
            </div>
            <div class="game">
                <img src="https://via.placeholder.com/150" alt="Roblox">
                <p>Roblox</p>
                <button>Selecionar</button>
            </div>
            <div class="game">
                <img src="https://via.placeholder.com/150" alt="FIFA">
                <p>FIFA</p>
                <button>Selecionar</button>
            </div>
            <div class="game">
                <img src="https://via.placeholder.com/150" alt="eFootball">
                <p>eFootball</p>
                <button>Selecionar</button>
            </div>
        </div>
    </div>
</body>
</html>
