# Modelos de documentos
O objetivo deste repositório é prover modelos de documentos acadêmicos e profissionais usando Markdown.
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

