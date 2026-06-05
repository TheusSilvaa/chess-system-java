# ♟️ Sistema de Jogo de Xadrez (Chess System)

## 💻 Sobre o projeto
Este é um sistema completo de jogo de xadrez desenvolvido para rodar no terminal (console). O projeto foi construído com o objetivo principal de aplicar e consolidar conceitos avançados de **Programação Orientada a Objetos (POO)** em Java. 

Durante o desenvolvimento, a lógica do xadrez foi separada da lógica do tabuleiro, permitindo uma arquitetura limpa e organizada.

## 🛠️ Tecnologias e Conceitos Aplicados
- **Java** (Linguagem principal)
- **Matrizes** (Estrutura de dados para o tabuleiro)
- **Encapsulamento, Herança e Polimorfismo** (Para as peças e movimentos)
- **Upcasting e Downcasting**
- **Exceções Personalizadas** (Para tratar movimentos inválidos e erros de regras do xadrez)
- **Padrões de Projeto** (Board layer vs Chess layer)

## ⚙️ Funcionalidades
- Tabuleiro dinâmico renderizado no console.
- Movimentos válidos validados para cada tipo de peça (Rei, Rainha, Torre, Bispo, Cavalo, Peão).
- Identificação de Xeque e Xeque-Mate.
- Jogadas especiais: Roque (pequeno e grande), En Passant e Promoção de Peão.

## 🚀 Como executar o projeto

Certifique-se de ter o [JDK](https://www.oracle.com/java/technologies/downloads/) instalado na sua máquina.

```bash
# Clone este repositório
$ git clone [https://github.com/TheusSilvaa/chess-system-java.git](https://github.com/TheusSilvaa/chess-system-java.git)

# Acesse a pasta do projeto
$ cd chess-system-java

# Compile e execute a aplicação pela sua IDE de preferência (IntelliJ, Eclipse, VS Code)
# O ponto de entrada da aplicação é a classe Program.java na pasta application.
