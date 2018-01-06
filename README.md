## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

Passos realizados para otimizar a index.html:

1. Diminuir o tamanho das imagens para Diminuir o tamanho das imagens a serem baixadas e baixar as imagens externas.
2. Colocar o CSS inline para diminuir requisições.
3. Mudar os scripts para a parte inferior da pagina para que o navegador carregue a pagina primeiro, e nos scripts externos adicionar a propriedade **async**.
4. Melorar o carregamento da fonte externa usando o `@font-face`

#### Part 2: Optimize Frames per Second in pizza.html



### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
