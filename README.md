## Website Performance Optimization portfolio project

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

Passos realizados para otimizar a index.html:

1. Otimizar as imagens diminuindo o tamanho delas, imagens menores são carregadas em menos tempo.
2. Colocar o CSS inline para diminuir requisições.
3. Mudar os scripts para a parte inferior da pagina para que o navegador carregue a pagina primeiro, e nos scripts externos adicionar a propriedade **async**.
4. Melhorar o carregamento da fonte externa usando o `@font-face`

#### Part 2: Optimize Frames per Second in pizza.html

Passos realizados para otimizar a pizza.html e main.js

1. Otimizar as imagens diminuindo o tamanho delas, imagens menores são carregadas em menos tempo.
2. Eliminar layout síncrono forçado na função updatePositions(), para otimizar a pagina quando a barra de rolagem é acionada.
3. Eliminar layout síncrono forçado na função changePizzaSizes(), para otimizar a pagina quando as pizzas são redimensionadas.
4. Diminuir a quantidade de pizzas deslizantes de 200 para 28, na tela são exibidas somente 7 pizzas por 4 colunas, logo 28 pizzas são suficientes.
