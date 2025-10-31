# Chess System Java

Um jogo de xadrez desenvolvido em Java para ser jogado diretamente no terminal. Este projeto implementa toda a lógica do xadrez, incluindo movimentos das peças, captura, xeque e xeque-mate.


## Funcionalidades

- Movimentação de todas as peças do xadrez (Peão, Torre, Cavalo, Bispo, Rainha, Rei)

- Validação de movimentos válidos

- Captura de peças adversárias

- Verificação de Xeque e Xeque-mate

- Jogo completo jogável no terminal
## Tecnologias e Conceitos

- Java (POO e programação estruturada)

- Conceitos de lógica de jogos

- Manipulação de arrays e matrizes para representar o tabuleiro

- Tratamento de exceções (para movimentos inválidos)
## Como executar

Siga os passos abaixo para rodar o jogo no seu computador:

1.&nbsp;Clone o repositorio:

```bash
  git clone https://github.com/seu-usuario/chess-system-java.git

```

2.&nbsp;Entre na pasta do projeto:

```bash
  cd chess-system-java/src

```

3.&nbsp;Compile o código Java:

```bash
  javac application/*.java boardgame/*.java chess/*.java chess/pieces/*.java

```

4.&nbsp;Execute o jogo:

```bash
  java application.Program

```

5.&nbsp;Jogue!

Siga as instruções no terminal para mover as peças usando a notação padrão (ex.: e2 e4).

## Estrutura do projeto

```bash
    chess-system-java/
    │
    ├── src/
    │   ├── application/
    │   │   ├── Program.java   # Classe principal
    │   │   └── UI.java        # Interface do terminal
    │   ├── boardgame/
    │   │   ├── Board.java
    │   │   ├── BoardException.java
    │   │   ├── Piece.java
    │   │   └── Position.java
    │   ├── chess/
    │   │   ├── ChessException.java
    │   │   ├── ChessMatch.java
    │   │   ├── ChessPiece.java
    │   │   ├── ChessPosition.java
    │   │   ├── Color.java
    │   │   └── pieces/         # Classes das peças específicas
    └── README.md
```
## Possíveis melhorias

- Criar interface gráfica (GUI)

- Adicionar modo multiplayer online

- Implementar undo/redo de movimentos

- Sistema de salvar e carregar partidas
## Autores

- [@theyvison](https://www.github.com/theyvison)

- Projeto desenvolvido durante o curso Java COMPLETO Programação Orientada a Objetos + Projetos, do professor [@acenelio](https://github.com/acenelio)

