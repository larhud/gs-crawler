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

=Como executar a rotina=

1) Partindo do pressuposto que você já tem o Python 3 e o git instalados em seu computador, abra o prompt (ou linha de comando no Windows)

    git clone
    pip install -r req-jupyter.txt
    jupyter notebook    

2) Nesse ponto, o Jupyter irá abrir o navegador. 

3) Crie um arquivo texto cesta.txt que conterá a relação de URLs de busca que você quer realizar e grave na mesma pasta.

4) abra o arquivo scholar.ipynb e mande executar a primeira célula. Nesse ponto, a rotina ir iniciar o processamento e irá lhe indicar cada etapa do processamento até que emita a mensagem de "Fim"
