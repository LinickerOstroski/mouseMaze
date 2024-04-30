
# Observação
Este repositório é dedicado exclusivamente para estudo e aprendizado. Por favor, esteja ciente de que os códigos aqui presentes podem não aderir às melhores práticas e arquitetura. 


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

