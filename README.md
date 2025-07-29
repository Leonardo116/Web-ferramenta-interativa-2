<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ferramenta de Estudo Interativa</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Ferramenta de Estudo Interativa</h1>
        
        <div class="modes">
            <button class="mode-btn active" data-mode="flashcards">Flashcards</button>
            <button class="mode-btn" data-mode="quiz">Quiz</button>
            <button class="mode-btn" data-mode="test">Teste Prático</button>
        </div>
        
        <div class="progress">
            Cartão <span id="current-card">1</span> de <span id="total-cards">0</span>
        </div>
        
        <div class="card" id="study-card">
            Clique em "Adicionar Cartão" para começar ou "Carregar Exemplo" para ver uma demonstração.
        </div>
        
        <div class="controls">
            <button class="btn" id="prev-btn">Anterior</button>
            <button class="btn" id="flip-btn">Virar</button>
            <button class="btn" id="next-btn">Próximo</button>
        </div>
        
        <div class="add-card">
            <h3>Adicionar Novo Cartão</h3>
            <textarea id="question-input" placeholder="Pergunta/Frente do cartão"></textarea>
            <textarea id="answer-input" placeholder="Resposta/verso do cartão"></textarea>
            <button class="btn" id="add-card-btn">Adicionar Cartão</button>
            <button class="btn btn-secondary" id="load-sample">Carregar Exemplo</button>
            <button class="btn btn-secondary" id="clear-all">Limpar Tudo</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
