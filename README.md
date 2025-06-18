🎯 Desafio: Fuga do Labirinto
🧠 Objetivo:
Crie um jogo em que o jogador controla um círculo usando as setas do teclado, tentando chegar até o objetivo final no outro lado da tela. No caminho, ele precisa evitar encostar nas paredes do labirinto!

✅ Requisitos:
Movimento com setas do teclado (← ↑ → ↓)

O personagem principal deve ser um círculo branco

Deve haver paredes representando o labirinto (retângulos fixos)

Se o jogador encostar em uma parede, ele volta ao ponto inicial

Um objetivo final visível, como um quadrado verde

Se o jogador chegar no objetivo, mostrar uma mensagem: "Você venceu!"

💡 Dicas:
Crie um array com objetos representando as paredes, com x, y, largura, altura.

Use ctx.rect() para desenhá-las.

Para detectar colisão entre o círculo e as paredes, use verificação de sobreposição de áreas (bounding box).

O movimento deve respeitar os limites da tela.

⭐ Extras (opcional):
Contador de tempo até o jogador vencer

Música de fundo ou som ao vencer

Vidas limitadas

Mais de uma fase (desbloqueada ao vencer a anterior)


