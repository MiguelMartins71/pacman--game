# Pacman em C

Este projeto é uma implementação do clássico **Pacman** em linguagem **C**. O jogo foi desenvolvido como um desafio de programação e busca oferecer uma experiência divertida e desafiadora de jogo, além de ser uma ótima maneira de aprender sobre conceitos de programação em C.

![Pacman Game Screenshot](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/Pac-Man.svg/1200px-Pac-Man.svg.png)

## 🎮 Sobre o Jogo

O Pacman é um jogo de arcade onde o jogador controla um personagem (Pacman) que deve comer todos os pontos espalhados pelo labirinto, enquanto evita os fantasmas. O objetivo é completar o labirinto sem ser capturado pelos fantasmas.

### Regras:
- **Comer os pontos**: O objetivo principal é comer todos os pontos (ou "dots") no labirinto.
- **Evitar fantasmas**: Existem quatro fantasmas no labirinto. Se o Pacman colidir com um fantasma, o jogo termina.
- **Poderes especiais**: Ao comer os "Power Pellets", o Pacman pode comer os fantasmas temporariamente.

## ⚙️ Funcionalidades

- **Interface gráfica simples**: O jogo utiliza a biblioteca **ncurses** para criar uma interface de terminal.
- **Movimentação do Pacman**: Controle o Pacman com as teclas de direção.
- **Comportamento dos fantasmas**: Cada fantasma tem um comportamento distinto.
- **Contagem de pontos**: O jogo exibe a pontuação atual e a quantidade de pontos restantes.
- **Fim de jogo**: O jogo termina quando o Pacman é capturado pelos fantasmas ou come todos os pontos do labirinto.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Linguagem**: C
- **Biblioteca para interface gráfica**: [ncurses](https://invisible-island.net/ncurses/)
- **Compilador**: GCC ou qualquer compilador C compatível.

## 💻 Como Rodar o Jogo

### 1. Clonando o Repositório

Primeiro, clone o repositório para o seu computador:

```bash
git clone https://github.com/seu-usuario/pacman-em-c.git
```

### 2. Instalando Dependências

Para compilar e rodar o jogo, você precisa ter a biblioteca **ncurses** instalada. Em sistemas baseados em Debian/Ubuntu, você pode instalar usando:

```bash
sudo apt-get install libncurses5-dev
```

Em sistemas **macOS** com Homebrew, use:

```bash
brew install ncurses
```

### 3. Compilando o Código

Após clonar o repositório e instalar as dependências, você pode compilar o jogo com o seguinte comando:

```bash
gcc -o pacman pacman.c -lncurses
```

### 4. Jogando o Pacman

Agora, basta rodar o jogo com o comando:

```bash
./pacman
```

Use as teclas de **seta** para mover o Pacman pelo labirinto.

## 📝 Como Contribuir

Se você deseja contribuir para melhorar o projeto, sinta-se à vontade para abrir **issues** ou enviar **pull requests**. Algumas ideias para melhorias incluem:

- Melhorias na inteligência artificial dos fantasmas.
- Adicionar novos níveis e labirintos.
- Melhorias na interface gráfica (ou criar uma versão com gráficos reais).
- Música ou sons para tornar o jogo mais imersivo.

## 🔧 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Desenvolvedor

Este projeto foi desenvolvido por Miguel Carvalho.

----

