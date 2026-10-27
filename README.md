# lista04_Ketlin_Lodi_1G
1 | 29
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

13) É o tamanho do item antes de crescer ou encolher,o tamanho inicial será de 160px.

14) Porque o flex-basis:0 faz cada item começar com tamanho zero, ai divide toda a largura disponível entre os itens, de acordo com os pesos, e não pelo espaço que sobra somente depois do tamanho inicial.

15) flex: initial equivale a crescimento 0, encolhimento 1 e base auto.
flex: 10 equivale a crescimento 1, encolhimento 1 e base 0.
flex: auto equivale a crescimento 1, encolhimento 1 e base auto.
flex: none equivale a crescimento 0, encolhimento 0 e base auto.

16) O primeiro item com flex: 1, fica com 300px e o segundo também fica com 300px, pois ambos começam com base 0 e dividem igualmente os 600px.
Ja com flex: Auto o primeiro item fica com 200px e o segundo com 400px, pois começam com seus tamanhos de conteúdo (100px e 300px) e dividem igualmente os 200px que sobram.
Os resultados são diferentes porque flex: 1 começa do zero e divide toda a faixa, enquanto flex: auto começa do tamanho do conteúdo e divide apenas o espaço que sobra.

17) é falso porque mesmo tendo o mesmo conteudo eles não começam com o mesmo valor.

18) O min-width: auto impede que o item fique menor que seu conteúdo e para ajustar isto,] basta usar min-width: 0, ele permite que o item encolha e que o texto quebre em linhas.

19) Quando o texto é muito longo e não cabe no espaço ao lado do menu.

20) 
