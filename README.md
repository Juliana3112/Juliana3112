<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juliana Arruda - Estética e Cosmetologia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2c5e4e; /* Verde musgo */
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
            font-size: 2em;
        }
        .content {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section-title {
            color: #2c5e4e; /* Verde musgo */
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        label {
            display: block;
            margin-bottom: 10px;
            color: #333;
        }
        input[type="text"], input[type="email"], input[type="tel"], textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 20px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }
        input[type="radio"] {
            margin-right: 10px;
        }
        .radio-group {
            margin-bottom: 20px;
        }
        .observation {
            margin-top: -15px;
            font-size: 0.9em;
            color: #777;
        }
        button {
            background-color: #8fbf90; /* Verde claro */
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
        }
        button:hover {
            background-color: #2c5e4e; /* Verde musgo */
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #2c5e4e; /* Verde musgo */
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Juliana Arruda - Estética e Cosmetologia</h1>
    </header>

    <div class="content">
        <h2 class="section-title">Ficha de Anamnese</h2>
        <form>
            <label for="nome">Nome Completo:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefone">Telefone:</label>
            <input type="tel" id="telefone" name="telefone" required>

            <label for="idade">Idade:</label>
            <input type="text" id="idade" name="idade" required>

            <label>Você já realizou algum procedimento estético anteriormente?</label>
            <div class="radio-group">
                <input type="radio" id="procedimento-sim" name="procedimento" value="sim" required>
                <label for="procedimento-sim">Sim</label>
                <input type="radio" id="procedimento-nao" name="procedimento" value="não" required>
                <label for="procedimento-nao">Não</label>
            </div>

            <label>Você tem alguma condição de saúde que devemos saber?</label>
            <div class="radio-group">
                <input type="radio" id="saude-sim" name="saude" value="sim" required>
                <label for="saude-sim">Sim</label>
                <input type="radio" id="saude-nao" name="saude" value="não" required>
                <label for="saude-nao">Não</label>
            </div>
            <textarea id="saude-observacao" name="saude-observacao" rows="4" placeholder="Se sim, por favor, descreva." required></textarea>

            <label>Está ciente dos cuidados necessários após o procedimento?</label>
            <div class="radio-group">
                <input type="radio" id="cuidados-sim" name="cuidados" value="sim" required>
                <label for="cuidados-sim">Sim</label>
                <input type="radio" id="cuidados-nao" name="cuidados" value="não" required>
                <label for="cuidados-nao">Não</label>
            </div>

            <label>Observações adicionais:</label>
            <textarea id="observacoes" name="observacoes" rows="4" placeholder="Se houver algo mais que deseja compartilhar, escreva aqui."></textarea>

            <button type="submit">Enviar</button>
        </form>
    </div>

    <footer>
        <p>Juliana Arruda - Estética e Cosmetologia &copy; 2024</p>
    </footer>
</body>
</html>
