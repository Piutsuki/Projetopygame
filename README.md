# Projetopygame — Naruto Lego: Batalha Ninja

Jogo 2D de sobrevivência e ação feito em Python com Pygame. O jogador controla um ninja, enfrenta inimigos que se aproximam e tenta permanecer vivo enquanto acumula pontos.

O código-fonte está dentro de `jogo_coletor.zip`, no arquivo `jogo_coletor.py`.

## Como jogar

- **Setas** ou **WASD**: mover o personagem.
- **W**, **A**, **S**, **D**: lançar uma shuriken para cima, esquerda, baixo ou direita, respectivamente.
- **Fechar a janela**: sair do jogo.

As teclas WASD também movimentam o personagem; ao pressioná-las, o jogo dispara a shuriken na direção correspondente.

## Regras do jogo

- Inimigos surgem pelas bordas da tela e perseguem o jogador. O jogo mantém até oito inimigos simultaneamente.
- Cada inimigo derrotado com shuriken vale 10 pontos.
- O jogador começa com três vidas; encostar em um inimigo no estado normal perde uma vida.
- A cada 100 pontos, o jogador se transforma por 10 segundos, ganha velocidade e pode derrotar inimigos ao encostar neles.
- Ao ficar sem vidas, aparece a pontuação final e o jogo encerra.

A tela tem resolução de 800 × 600. Personagem, inimigos e cenário são desenhados com formas do Pygame; o ZIP não inclui imagens externas.

## Requisitos e execução

Requisitos: Python 3 e Pygame. O repositório não inclui um arquivo `requirements.txt`.

1. Extraia `jogo_coletor.zip`.
2. Instale o Pygame, se ainda não estiver instalado:
   ```bash
   python -m pip install pygame
   ```
   No Windows, também pode usar `py -m pip install pygame`.
3. Execute o arquivo extraído:
   ```bash
   python jogo_coletor.py
   ```

## Escopo

Este é um projeto demonstrativo/fan-made, sem afiliação oficial às marcas citadas no título interno do jogo. O código não inclui menu inicial, sistema de fases ou opção de reiniciar após o fim da partida.

