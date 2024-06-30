<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Projeto Menu de Jogos em C 🎮💻</h1>
<p>Este projeto é uma coleção de jogos desenvolvidos na linguagem de programação C, como parte da disciplina de Estrutura de Dados e Algoritmos. Cada jogo foi projetado para aplicar diferentes estruturas de dados e conceitos aprendidos durante o curso.</p>

<h2>Jogos Incluídos</h2>

<h3>Jogo da Velha ❌⭕</h3>
<ul>
    <li><strong>Descrição:</strong> Um jogo tradicional da velha onde dois jogadores se alternam para marcar seus símbolos em uma matriz 3x3.</li>
    <li><strong>Estruturas de Dados Utilizadas:</strong> Matriz para representar o tabuleiro.</li>
    <li><strong>Funções Principais:</strong></li>
    <ul>
        <li><code>void passoapasso()</code>: Instruções ao usuário.</li>
        <li><code>int menu(void)</code>: Menu inicial.</li>
        <li><code>void zeraTabuleiro(int tabuleiro[][DIM])</code>: Inicializa o tabuleiro.</li>
        <li><code>void exibeTabuleiro(int tabuleiro[][DIM])</code>: Exibe o tabuleiro.</li>
        <li><code>void jogar(int tabuleiro[][DIM])</code>: Controla a lógica do jogo.</li>
    </ul>
</ul>

<h3>Jogo da Cobrinha 🐍</h3>
<ul>
    <li><strong>Descrição:</strong> O jogador controla uma cobra que deve comer a comida que aparece aleatoriamente no mapa, fazendo a cobra crescer a cada comida ingerida.</li>
    <li><strong>Estruturas de Dados Utilizadas:</strong> Vetores para representar o corpo da cobra e a posição da comida.</li>
    <li><strong>Funções Principais:</strong></li>
    <ul>
        <li><code>void desenha()</code>: Desenha a cobrinha.</li>
        <li><code>void atualiza()</code>: Atualiza a posição da cobrinha.</li>
        <li><code>void geraComida()</code>: Gera a comida no mapa.</li>
    </ul>
</ul>

<h3>RPG Textual de Decisões 📝</h3>
<ul>
    <li><strong>Descrição:</strong> Um RPG onde o jogador cria um personagem e toma decisões que afetam o desenrolar da história e os atributos do personagem.</li>
    <li><strong>Estruturas de Dados Utilizadas:</strong> Pilhas para controle de buffs e debuffs.</li>
    <li><strong>Funções Principais:</strong></li>
    <ul>
        <li><code>void criarPersonagem()</code>: Cria e define as características do personagem.</li>
        <li><code>void tomarDecisao()</code>: Lógica de decisões do jogador.</li>
    </ul>
</ul>

<h3>Jogo da Forca 🔤</h3>
<ul>
    <li><strong>Descrição:</strong> Jogo da forca onde o jogador deve adivinhar a palavra correta antes de cometer seis erros.</li>
    <li><strong>Estruturas de Dados Utilizadas:</strong> TAD e ordenação de strings.</li>
    <li><strong>Funções Principais:</strong></li>
    <ul>
        <li><code>void iniciarJogoSolo()</code>: Inicia o jogo no modo solo.</li>
        <li><code>void iniciarJogoMultiplayer()</code>: Inicia o jogo no modo multiplayer.</li>
    </ul>
</ul>

<h3>Jogo do Pacman 👾</h3>
<ul>
    <li><strong>Descrição:</strong> Uma versão simplificada do clássico jogo Pacman.</li>
    <li><strong>Estruturas de Dados Utilizadas:</strong> Matrizes para representar o mapa e listas encadeadas para movimentação.</li>
    <li><strong>Funções Principais:</strong></li>
    <ul>
        <li><code>int acabou()</code>: Verifica se o jogo terminou.</li>
        <li><code>void instrucoes()</code>: Imprime as instruções do jogo.</li>
        <li><code>void jogopacman()</code>: Função principal que inicia o jogo.</li>
    </ul>
</ul>

<h2>Estruturas de Dados Implementadas 📚</h2>
<ul>
    <li><strong>Pilhas:</strong> Utilizadas para controlar a ordem das ações, buffs e debuffs nos jogos.</li>
    <li><strong>Matrizes:</strong> Principalmente usadas para representar tabuleiros e mapas.</li>
    <li><strong>TAD (Tipos Abstratos de Dados):</strong> Implementação de estruturas de dados específicas para cada jogo.</li>
</ul>

<h2>Como Compilar e Executar 🛠️</h2>
<p>Para compilar qualquer um dos jogos, utilize um compilador C como o GCC. Por exemplo, para compilar o Jogo da Velha, use o comando:</p>
<pre><code>gcc jogodavelha.c -o jogodavelha</code></pre>
<p>Para executar o jogo compilado, use:</p>
<pre><code>./jogodavelha</code></pre>

<h2>Conclusão 🎓</h2>
<p>Este projeto não apenas reforça os conceitos aprendidos em estrutura de dados e algoritmos, mas também demonstra a aplicação prática desses conceitos em jogos simples, tornando o aprendizado mais interativo e divertido. Cada jogo foi desenvolvido para utilizar diferentes estruturas de dados, mostrando a versatilidade e importância de se conhecer bem esses conceitos na programação.</p>

</body>
</html>
