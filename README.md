# lista04_Ketlin_Lodi_1G
1 | 12
1) O contêiner é o elemento que organiza os itens, e os itens são os filhos diretos dele. E o display: flex é colocada no contêiner. 

2) O eixo principal é horizontal, da esquerda para a direita, pois o valor padrão de flex-direction é row.

3) A sobra é o espaço vazio que resta no contêiner. Quando todos os itens têm flex-grow: 0, nenhum deles cresce para ocupar esse espaço.

4) 0, não cresce para ocupar o espaço que sobra.

5) A mesa representa o contêiner; cada prato da pessoa representa um item inicial; a sobra de pizza representa o espaço livre; e o peso representa o valor de flex-grow, que determina quanto cada item recebe da sobra.

6) A declaração é flex-grow: 1;, colocada no elemento da marca, por exemplo, na classe .marca.

7) 2 + 3 + 1 = 6
   600 / 6 = 100px

8) 3 * 100 = 300
   600 - 300 = 300px
   0 + 1 + 2 = 3
   300/3 = 100px

   primeiro item = 100px | segundo item = 200px | terceiro item = 300px

9) Ele entra em ação quando falta espaço, e o valor padrão é 1.

10) 400 + 400 = 800px
    800 - 600 = 200px
    faltam 200px
    cada item fica com 300px.

11) O valor ficara 400px, porem contanto com os dois itens o valor resultara em 800 e a faixa é apenas de 600px, então o item ira transbordar da faixa.

12) Um bom exemplo seria um botão que quando a pessoa coloca flex-shirnk: 0 e o botão ficara do mesmo tamanho independente da alteração ou falta de espaço da pagina.
