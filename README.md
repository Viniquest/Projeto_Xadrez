# Documentação Automática

Este README foi gerado automaticamente com base nos arquivos do repositório.

## src/application/Program.java
Resumo:
A classe Program é responsável por iniciar o programa e criar um tabuleiro de xadrez com dimensões 8x8. O método main é o ponto de entrada do programa e cria uma instância da classe Board com as dimensões especificadas.

## src/boardgame/Board.java
Resumo:
A classe Board representa um tabuleiro de jogo com um número específico de linhas e colunas. Ela mantém uma matriz bidimensional de peças (Piece) para representar o estado do jogo.

Métodos:
- Construtor Board(int rows, int columns): Inicializa o tabuleiro com um número especificado de linhas e colunas, criando a matriz de peças.
- int getRows(): Retorna o número de linhas do tabuleiro.
- void setRows(int rows): Define o número de linhas do tabuleiro.
- int getColumns(): Retorna o número de colunas do tabuleiro.
- void setColumns(int columns): Define o número de colunas do tabuleiro.

## src/boardgame/Piece.java
Resumo:

A classe Piece representa uma peça de um jogo de tabuleiro. Ela possui um atributo protegido position que representa a posição da peça no tabuleiro e um atributo privado board que representa o tabuleiro no qual a peça está contida.

O construtor da classe Piece recebe como parâmetro um objeto do tipo Board e inicializa o atributo board com esse valor.

A classe Piece possui um método protegido getBoard() que retorna o tabuleiro no qual a peça está contida.

## src/boardgame/Position.java
Resumo:
A classe Position representa uma posição em um tabuleiro de jogo, com atributos de linha e coluna. Ela possui métodos para acessar e modificar esses atributos, bem como um método toString() para retornar uma representação da posição em forma de string no formato "linha, coluna".

