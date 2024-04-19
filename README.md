# Labirinto do Rato

<img src=./image.jpg>

Este é um pequeno projeto em C# que simula um rato em busca de queijo dentro de um labirinto representado por uma matriz de caracteres. O rato pode se mover em todas as direções (acima, abaixo, esquerda, direita) para encontrar o queijo ('Q'), evitando obstáculos representados por paredes ('*').

## Funcionamento

O programa utiliza um algoritmo de busca em profundidade (DFS) para encontrar o queijo dentro do labirinto. O labirinto é gerado aleatoriamente a cada execução, com o rato começando em uma posição aleatória na borda do labirinto.

### Representação dos Caracteres

- `Q`: Posição do queijo, o objetivo do rato.
- `*`: Paredes que o rato não pode atravessar.
- `r`: Posição atual do rato durante a busca.
- `.`: Marcador das posições visitadas pelo rato durante a busca.

### Executando o Programa

1. Certifique-se de ter o ambiente de desenvolvimento C# configurado em sua máquina.
2. Clone este repositório em seu ambiente local.
3. Abra o projeto em seu editor de código preferido.
4. Compile e execute o projeto para iniciar a simulação do labirinto do rato.

## Instruções de Uso

Ao executar o programa, você verá o labirinto sendo exibido no console, com o rato representado pela letra `r`. O rato tentará encontrar o queijo (`Q`) navegando pelo labirinto. As seguintes teclas podem ser úteis durante a execução:

- `Seta para cima`: Movimenta o rato para cima.
- `Seta para baixo`: Movimenta o rato para baixo.
- `Seta para esquerda`: Movimenta o rato para a esquerda.
- `Seta para direita`: Movimenta o rato para a direita.
- `Enter`: Avança para o próximo passo da simulação.

Ao finalizar a execução, o programa exibirá se o rato encontrou o queijo ou não.


