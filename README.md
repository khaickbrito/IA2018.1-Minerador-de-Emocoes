# IA2018.1-Minerador-de-Emocoes
## Problema 1 de Inteligência Artificial Não Simbolica 2018.1

### Base de Dados

Mercado Livre Brasil

### Exemplo de páginas para extração

* https://produto.mercadolivre.com.br/noindex/catalog/reviews/search?itemId=MLB912080653&offset=15&limit=5&currentLimit=20&totalReviews=4619

### Passo a Passo

* Escolher a categoria
* Coletar os Ids dos produtos através do link contido nas tags <h2><a href=""></h2>
* Coletar o link do produto
* Acessar a página do produto (Usando o link do h2)
* Coletar o número de avaliações no <span class="average-legend">
* Acessar as páginas de extração iterando por ID e parametrando o numero de avaliações.
* * Iterar acrescendo +5 no offset e no Limit
* * Para se contar as estrelas verifica-se: <linearGradient <stop offset="100" para estrela amarela e <linearGradient <stop offset="0" para estrelas cinzas
    


#### Coletando os IDs

* Ex de Url: https://produto.mercadolivre.com.br/MLB-942029213-celular-lg-q6-lgm700-tv-preto-32gb-13mp-55-pol-3gb-ram-_JM
* Id do Produto: MLB-942029213


### Link para o Crawler
* Linguagem: Java
* http://www.netinstructions.com/how-to-make-a-simple-web-crawler-in-java/
* http://www.univale.com.br/unisite/mundo-j/artigos/59_Webcrawler.pdf
