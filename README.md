<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Black Money - Gestão Financeira</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #e0e0e0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #00c6ff;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #00c6ff;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .box {
            background-color: #1f1f1f;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            width: 45%;
            box-shadow: 0 0 10px rgba(0, 198, 255, 0.5);
        }
        .box h2 {
            color: #00c6ff;
        }
        footer {
            background-color: #1f1f1f;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Black Money - Gestão Financeira</h1>
    </header>
    <nav>
        <a href="#sobre">Sobre Mim</a>
        <a href="#graficos">Gráficos</a>
        <a href="#calculadoras">Calculadoras</a>
        <a href="#gestao">Gestão Financeira</a>
    </nav>
    <section id="sobre">
        <div class="box">
            <h2>Sobre Mim</h2>
            <p>Garoto de 21 anos de Ceará-Mirim que quer ser milionário.</p>
        </div>
    </section>
    <section id="graficos">
        <div class="container">
            <div class="box">
                <h2>Gráfico de Despesas</h2>
                <!-- Gráfico de pizza aqui -->
            </div>
            <div class="box">
                <h2>Gráfico de Ganhos</h2>
                <!-- Gráfico de linha aqui -->
            </div>
            <div class="box">
                <h2>Comparação de Receitas e Despesas</h2>
                <!-- Gráfico de barras aqui -->
            </div>
        </div>
    </section>
    <section id="calculadoras">
        <div class="container">
            <div class="box">
                <h2>Calculadora de Ganhos Futuros</h2>
                <!-- Ferramenta de cálculo aqui -->
            </div>
            <div class="box">
                <h2>Calculadora de Gastos Futuros</h2>
                <!-- Ferramenta de cálculo aqui -->
            </div>
        </div>
    </section>
    <section id="gestao">
        <div class="container">
            <div class="box">
                <h2>Registro de Receitas</h2>
                <!-- Ferramenta de registro aqui -->
            </div>
            <div class="box">
                <h2>Registro de Despesas</h2>
                <!-- Ferramenta de registro aqui -->
            </div>
            <div class="box">
                <h2>Projeção de Renda Futura</h2>
                <!-- Ferramenta de projeção aqui -->
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Black Money. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
