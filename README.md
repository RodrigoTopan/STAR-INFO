<H2>STAR-INFO</H2>
<p>Projeto criado com foco no aprendizado de consumo e utilização de APIs e JQuery
Um projeto simples, bem interessante e didático. Ainda mais se você for fã de star wars<br>
</p>
<hr>
<p>A API que utilizamos foi a https://swapi.co/ que retorna um JSON de informações pesquisadas.<br>
O nosso desafio foi apenas montar o jquery para receber os valores de busca e concatenar com a url da api. A api então recebe a busca e retorna os dados.<br>
Utilizando a função .each() do jquery percorremos todos
os indices retornados pela api. Como a api retorna um objeto e nós estamos interessados apenas nos valores de seus atributos,
fizemos referência a estes através do comando result.results[i].nome_do_atributo o qual retorna o valor atributo do objeto pesquisado que se encontra no indice 1. 
O valor retornado do comando result.results[i].nome_do_atributo é então
por final, utilizado como parâmetro para a função .html(); que imprime na página o conjunto de dados como html.
