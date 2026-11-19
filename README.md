# 🔢 Jogo do Número Secreto

Jogo web interativo de adivinhação desenvolvido com **HTML5**, **CSS3** e **JavaScript**, com feedback por voz em português através da API **ResponsiveVoice**.

## 📌 Sobre o Projeto

O objetivo do jogo é descobrir um número secreto gerado aleatoriamente entre **1 e 10** no menor número de tentativas possível. A aplicação conta com histórico de números já sorteados (evitando repetições até que todos os números do intervalo sejam utilizados), dicas dinâmicas na tela e narração em áudio das instruções e resultados.

### ✨ Funcionalidades

- **Sorteio sem repetição:** Armazena os números já sorteados (`listaDeNumerosSorteados`) e reinicia a lista automaticamente quando todos os números de 1 a 10 já foram utilizados.
- **Dicas interativas:** Informa ao jogador se o número secreto é **maior** ou **menor** que o palpite digitado.
- **Contador de tentativas:** Exibe a quantidade exata de tentativas ao acertar o número.
- **Acessibilidade e áudio:** Narração automática das mensagens em português (`Brazilian Portuguese Female`) com **ResponsiveVoice**.
- **Reinício rápido:** Habilita o botão **Novo jogo** assim que o jogador acerta, permitindo iniciar uma nova partida.
- **Layout responsivo:** Adaptação visual para diferentes tamanhos de tela via Media Queries.

## 🚀 Tecnologias Utilizadas

- **HTML5** (`index.html`) — Estrutura semântica da interface e carregamento de scripts/fontes.
- **CSS3** (`style.css`) — Estilização com gradiente, Flexbox, efeitos visuais, fontes Google Fonts (*Chakra Petch* e *Inter*) e responsividade.
- **JavaScript** (`app.js`) — Lógica do jogo, manipulação do DOM, controle de tentativas e sorteio sem repetição.
- **ResponsiveVoice JS** — Síntese de voz para leitura das mensagens na tela.

## 📂 Estrutura de Pastas

```text
jogo-do-numero-secreto/
├── img/
│   ├── code.png      # Textura de fundo
│   ├── ia.png        # Ilustração principal da tela
│   └── Ruido.png     # Sobreposição visual do container
├── app.js            # Lógica do jogo e síntese de voz
├── index.html        # Página principal do jogo
└── style.css         # Estilos e responsividade