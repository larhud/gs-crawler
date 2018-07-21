# gs-crawler
Google Scholar Crawler

O Google Scholar Crawler tem como objetivo gerar uma planilha com os artigos encontrados a partir de um ou mais consultas no Google Scholar. Os dados retornados são:

* Titulo do Artigo/Livro
* Autores (em formato JSON)
* Tipo do Arquivo {PDF, DOC, HTML}
* Ano
* Número de Citações
* Origem: o índice da consulta que retornou o artigo.

Como o Google Scholar geralmente trava raspagens automatizadas, o script realiza sempre as buscas através de proxies públicos e da rotação de User Agents.

Planejamento do Projeto:

1) Execução via Jupyter para que haja facilidade nos testes (PRONTO)

2) Execução via linha de comando (EM CONSTRUÇÃO)

3) Execuço via interface web para os usuários que no dispõe de conhecimento para trabalhar com Python

