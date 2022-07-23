# CSS GRID


# GRID
- Bidimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão
# GRID OU FLEXBOX
- Grid Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Um complementa o trabalho do outro
- Verificar quais navegadores ainda não estão aceitando o Grid

## PROPRIEDADES
Vamos separar em 2 grupos:
`container` e  `item(s)`
## CONTAINER
- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-row-gap;
- grid-columns-gap;
- grid-template-areas;
... e mais 4 propriedades e **alinhamento**
## ITEM(S)
- grid-column;
- grid-column-start;

##alinhamento

# Grid: Alinhhamento

Existem 6 propriedades de alinhamento:

1. `justify-content`
2  `align-content`
3  `justify-items`
4  `align-items`
5  `justify-self`
6  `align-self`

Vamos separar em 2 grupos
1. `justify` e `align`
2. `content`, `items` e `self`

## Justify e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

o **eixo x** é posicionamento horizontal, da esquerda para a direita.

o **eixo y** é posicionamento vertical, de cima para baixo.

## content, Items e self

Juntando o `justify`, ou `align`,com esses elementos:`content`, `items` e `self`; nós observamos nossas propriedades

### Content

`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora de grid.

o Uso dessas propriedades são raras, pois é aplicado caso o grid seja menor que a area definida.
(por exemplo, quando usamos em px o tamanho do grid, podemos terminar com grid pequeno, para o tamanho da area do grid)

Podemos usar **7 valores**:

1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. apace-evenly

`justify-items` e `align-items` vai permitir alinhar os items do nosso grid, em qualquer espaço disponível, na célula que ele habitar.

1. start
2. end
3. center
4. stretch

###  self

`justify-self` e `align-self` vai nos permitir alinhar o item em si.