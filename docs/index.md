# Seja bem vindo(a)! 

Este modelo adota o padrão Markdown.
Para mais detalhes com mkdocs, [clique aqui](https://www.mkdocs.org).

## Comandos para documentação com Mkdocs

* `mkdocs new [dir-name]` - Cria um novo projeto.
* `mkdocs gh-deploy` - Realiza  a implantação do repositório corrente através de página web no servidor do github.
* `mkdocs serve` - Inicia um servidor web com a página do repositório.
* `mkdocs build` - Realiza a geração da documentação web.
* `mkdocs -h` - Imprime mensagem de ajuda.


# Modelos de documentos
Os seguintes tópicos apresentam modelos de documentos acadêmicos usando markdown.
## Relatório
O modelo de relatório é destinado aos mais diversos tipos de documentação
## Artigo
O modelo de artigo é destinado para para trabalhos de disciplinas e publicação em eventos.
## Livro
O modelo de livro está em elaboração.
## Apresentação com slides
O modelo de apresentação está em elaboração.
# Geração dos resultados
Um comando para geração simples de PDF é:

$pandoc example1.md -o out/example1.pdf --filter=pandoc-fignos --filter=pandoc-eqnos --filter=pandoc-tablenos --filter=pandoc-citeproc
I

# Repositórios de referências

O repositório pandoc-examples contém vários outros modelos de markdown úteis. 
$git clone https://github.com/kikofernandez/pandoc-examples

O repositório pandoc-scholar contém subsídios para geração do código, usando docker e exemplos úteis. 

$git clone https://github.com/pandoc-scholar/pandoc-scholar

O repositório seguinte contém um modelo simples de artigo com markdown e suporte a referências.

$git clone https://github.com/andrewmarx/paper-template

O repositório seguinte contém um modelo de livro. 

$git clone https://github.com/mattcone/markdown-guide-book


