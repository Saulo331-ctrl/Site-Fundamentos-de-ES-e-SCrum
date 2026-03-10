# Site-Fundamentos-de-ES-e-SCrum

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundamentos de ES e Scrum</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --bg-color: #f4f7f6;
            --text-color: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            background-color: var(--bg-color);
            color: var(--text-color);
        }

        header {
            background: var(--primary-color);
            color: white;
            padding: 2rem text-align center;
            text-align: center;
        }

        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        section {
            background: white;
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        h2 {
            color: var(--secondary-color);
            border-bottom: 2px solid var(--secondary-color);
            padding-bottom: 0.5rem;
        }

        .topic {
            margin-bottom: 1.5rem;
        }

        .badge {
            display: inline-block;
            background: var(--accent-color);
            color: white;
            padding: 0.2rem 0.6rem;
            border-radius: 4px;
            font-size: 0.9rem;
            margin-bottom: 0.5rem;
        }

        ul {
            list-style-type: square;
        }

        footer {
            text-align: center;
            padding: 2rem;
            font-size: 0.9rem;
            color: #777;
        }
    </style>
</head>
<body>

<header>
    <h1>Educação em Tecnologia</h1>
    <p>Guia Rápido de Engenharia de Software e Agilidade</p>
</header>

<div class="container">
    <section id="engenharia">
        <h2>1. Fundamentos de Engenharia de Software</h2>
        <p>A Engenharia de Software (ES) é a aplicação de uma abordagem sistemática, disciplinada e quantificável ao desenvolvimento, operação e manutenção de software.</p>
        
        <div class="topic">
            <span class="badge">Ciclo de Vida</span>
            <p>Compreende as etapas desde a concepção até a descontinuação do produto. As fases principais incluem:</p>
            <ul>
                <li><strong>Análise de Requisitos:</strong> Entender o que o cliente precisa.</li>
                <li><strong>Design/Projeto:</strong> Definir a arquitetura e interface.</li>
                <li><strong>Implementação:</strong> A escrita do código propriamente dita.</li>
                <li><strong>Testes:</strong> Garantir que o sistema funcione sem falhas.</li>
                <li><strong>Manutenção:</strong> Correção de bugs e melhorias contínuas.</li>
            </ul>
        </div>
    </section>

    <section id="scrum">
        <h2>2. O Método Scrum</h2>
        <p>O Scrum é um framework ágil utilizado para gerenciar projetos complexos, focando na entrega iterativa e incremental de valor.</p>
        
        <div class="topic">
            <span class="badge">Papéis Principais</span>
            <ul>
                <li><strong>Product Owner (PO):</strong> Define as prioridades do que será feito.</li>
                <li><strong>Scrum Master:</strong> Facilita o processo e remove impedimentos.</li>
                <li><strong>Developers:</strong> O time técnico que executa as tarefas.</li>
            </ul>
        </div>

        <div class="topic">
            <span class="badge">Eventos (Cerimônias)</span>
            <ul>
                <li><strong>Sprint:</strong> O ciclo de trabalho (geralmente de 1 a 4 semanas).</li>
                <li><strong>Daily Scrum:</strong> Reunião diária de 15 min para alinhamento.</li>
                <li><strong>Sprint Review:</strong> Demonstração do que foi entregue.</li>
                <li><strong>Sprint Retrospective:</strong> Análise do que o time pode melhorar no processo.</li>
            </ul>
        </div>
    </section>
</div>

<footer>
    <p>Material de Estudo &copy; 2026</p>
</footer>

</body>
</html>
