# Projeto: Sistema de Jogo de Xadrez em Java

## Descrição do Projeto

Este projeto consiste na implementação de um sistema de jogo de xadrez em Java, desenvolvido como parte do curso "Programação Orientada a Objetos com Java", ministrado pelo Prof. Dr. Nelio Alves. O código-fonte e o design do sistema podem ser encontrados no repositório [chess-system-design](https://github.com/acenelio/chess-system-design).

## Estrutura do Projeto

O projeto é dividido em várias classes que representam diferentes componentes do jogo de xadrez, como peças, tabuleiro, partida, interface do usuário, entre outros.

## Funcionalidades Principais

1. **Criação do Projeto e Repositório Git:**
   - Inicialização do projeto com estrutura Java.
   - Configuração do repositório Git no GitHub.

2. **Implementação da Classe Position:**
   - Utilização de conceitos como encapsulamento, construtores e sobrescrita de toString.
   
3. **Desenvolvimento de Board e Piece:**
   - Implementação das classes `Piece` e `Board`.
   - Exploração de tópicos de orientação a objetos como associações e modificadores de acesso.

4. **Camada de Xadrez e Impressão do Tabuleiro:**
   - Criação da camada de xadrez com classes como `ChessPiece` e `ChessMatch`.
   - Implementação da interface de console (`ChessConsole.UI`) para visualização do tabuleiro.

5. **Posicionamento de Peças no Tabuleiro:**
   - Desenvolvimento do método `PlacePiece` em `Board`.
   - Introdução das classes `Rook` e `King`.

6. **Tratamento de Exceções e Programação Defensiva:**
   - Adição de exceções personalizadas (`BoardException` e `ChessException`).
   - Implementação de métodos defensivos em `Board`.

7. **Melhorias na Impressão do Tabuleiro:**
   - Adição de cores ao terminal para distinguir peças.

8. **Movimentação de Peças:**
   - Implementação dos métodos `RemovePiece` e `PerformChessMove`.
   - Introdução do método `ReadChessPosition` na interface do usuário.

9. **Tratamento de Exceções e Limpeza de Tela:**
   - Implementação de métodos para tratamento de exceções e limpeza da tela.

10. **Movimentos Possíveis de uma Peça:**
    - Desenvolvimento de métodos para calcular movimentos possíveis de peças.

11. **Implementação dos Movimentos da Torre (Rook):**
    - Adaptação da classe `Rook` para movimentos específicos.

12. **Impressão dos Movimentos Possíveis:**
    - Implementação de métodos para imprimir os movimentos possíveis.

13. **Implementação dos Movimentos do Rei (King):**
    - Desenvolvimento de métodos específicos para o movimento do Rei.

14. **Alternância de Jogadores e Impressão do Jogo:**
    - Controle da vez de cada jogador e impressão do estado do jogo.

15. **Tratamento de Peças Capturadas:**
    - Adição de métodos para rastrear e imprimir as peças capturadas.

16. **Lógica de Cheque (Check) e Cheque-Mate (Checkmate):**
    - Implementação de lógica para verificar situações de cheque e cheque-mate.

17. **Contagem de Movimentos das Peças:**
    - Adição de contadores de movimentos para cada peça.

18. **Implementação do Peão (Pawn):**
    - Desenvolvimento da classe `Pawn`.

19. **Implementação do Bispo (Bishop):**
    - Introdução da classe `Bishop`.

20. **Implementação do Cavalo (Knight):**
    - Adição da classe `Knight`.

21. **Implementação da Rainha (Queen):**
    - Desenvolvimento da classe `Queen`.

22. **Jogadas Especiais: Roque, En Passant, Promoção:**
    - Implementação de jogadas especiais como roque, en passant e promoção de peão.

## Como Executar o Projeto

1. Clone o repositório: `git clone https://github.com/acenelio/chess-system-java.git`
2. Navegue até o diretório do projeto: `cd chess-system-java`
3. Compile o código: `javac Program.java`
4. Execute o sistema: `java Program`

## Contribuições

Contribuições são bem-vindas! Se desejar contribuir para o projeto, siga as orientações descritas no arquivo [CONTRIBUTING.md](CONTRIBUTING.md).

## Licença

Este projeto é licenciado sob a [Licença XYZ] - consulte o arquivo [LICENSE.md](LICENSE.md) para obter detalhes.

---

Esperamos que este projeto de sistema de jogo de xadrez em Java seja útil para a prática de conceitos de programação orientada a objetos e lógica de programação. Divirta-se explorando o mundo do xadrez digital!
