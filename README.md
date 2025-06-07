# Batalha Naval em C

![Linguagem](https://img.shields.io/badge/linguagem-C-blue.svg)
![Licença](https://img.shields.io/badge/licença-MIT-green.svg)

## 📖 Descrição

Projeto de iniciante para a criação de um jogo de Batalha Naval em modo texto (terminal), desenvolvido em C. O objetivo principal deste estágio é praticar a manipulação de matrizes, a lógica de posicionamento de elementos e a implementação de regras de validação.

## 🎯 Funcionalidades Atuais (v1.0)

-   Criação de um tabuleiro de jogo com dimensões 10x10.
-   Inicialização de todo o tabuleiro com `0`, representando a água.
-   Posicionamento estático de dois navios de tamanho 3 (um na vertical e um na horizontal).
-   **Validação de Limites:** O programa verifica se os navios cabem completamente dentro do tabuleiro.
-   **Verificação de Sobreposição:** O programa impede que um navio seja posicionado sobre o outro.
-   Exibição do estado final do tabuleiro no terminal.

## ⚙️ Como Compilar e Executar

Você precisará de um compilador C, como o **GCC**, para rodar este projeto.

1.  Clone este repositório ou baixe o arquivo `batalha_naval.c`.
2.  Abra seu terminal e navegue até a pasta onde o arquivo está localizado.
3.  Compile o programa com o seguinte comando:
    ```bash
    gcc batalha_naval.c -o batalha_naval
    ```
4.  Execute o arquivo gerado:
    ```bash
    ./batalha_naval
    ```

## 💻 Saída de Exemplo

Ao executar o programa, o seguinte tabuleiro será exibido no terminal:

```
============================
 Tabuleiro de Batalha Naval
============================
0 0 0 0 0 0 0 3 0 0 
0 0 0 0 0 0 0 3 0 0 
0 0 0 0 0 0 0 3 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 3 3 3 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 

## 🚀 Próximos Passos

O plano é continuar desenvolvendo este projeto para incluir:

-   [ ] Permitir que o jogador insira as coordenadas do ataque.
-   [ ] Implementar um loop de jogo para múltiplos turnos.
-   [ ] Adicionar um sistema para registrar acertos (`X`) e erros (`-`).
-   [ ] Contabilizar navios afundados.
-   [ ] Criar um modo de jogo contra o computador (IA simples).

## ✍️ Autor

Feito por **Carlos André Sabino**.

*(Dica: Você pode trocar o nome acima pelo seu e até colocar um link para o seu perfil do GitHub, assim: `[Seu Nome](https://github.com/seu-usuario)`)*

## 📄 Licença

Este projeto está sob a licença MIT.
