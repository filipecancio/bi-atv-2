# Trabalho Prático - Tarefas de Mineração de Dados

**Objetivo do Trabalho**: Descobrir informações relevantes de base de dados recente (a partir de 2019) em uma das tarefas de descoberta de conhecimento (Classificação, Agrupamento ou Associação), relatar os resultados em slides no dia da apresentação e entregar por escrito artigo no template da SBC (opcional). O trabalho prático deverá ser entregue de acordo com o Cronograma de Atividade.

**Base de Dados**: Utilizar base de dados real preferencialmente do local de trabalho de vocês. Caso não tenham, podem utilizar uma base de dados de um dos repositórios a seguir:

- https://dados.gov.br/dados/conjuntos-dados
- https://www.gov.br/anm/pt-br/acesso-a-informacao/dados-abertos
- https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos

**Pontos a serem considerados na avaliação**: Base de dados recente com um grande volume de dados (pelo menos 500 transações). Comparar os resultados com pelo menos 2 algoritmos no ambiente Weka.

**Características da Apresentação**: Organizar a apresentação em slides contendo explicação das principais características dos algoritmos; explicação da base dados; discussão e comparação do resultado dos algoritmos com duração de 15 a 20 minutos.

**Características do Artigo (opcional)**: Incluir as seguintes seções em exatamente 4 páginas: Introdução, Trabalhos Correlatos, Proposta do Trabalho, Análise de Dados, Considerações Finais e Referências.

**Grupos/Tema** (grupo de até duas pessoas):
| Grupo | Tema | Base de Dados|
|--|--|--|
|Filipe Cancio|sem tema| sem base|

**Anexar no Classroom os seguintes arquivos**: Base de dados utilizada, Resultado dos algoritmos, Slide (PPTX e PDF) e Artigo (DOCX e PDF) (opcional)
> Anexar os arquivos em um único arquivo compactado (ZIP, WINRAR,...)

**Cronograma de Atividade:**
|Data  | Atividade|
|--|--| 
|26/10/2023 | Orientação via Meet|
|16/11/2023 | Apresentação do projeto prático da II Unidade|

>OBS: A nota será individual conforme participação de cada aluno e em grupo. Nota máxima pelo trabalho é 8,0 pontos, nota da segunda unidade.

## Sobre o repositorio
Modelo de artigo sbc latex

Repositório base para template de artigo tcc em Tex baseado no modelo da SBC - Sociedade Brasileira de Computação disponidel no [site oficial](https://www.sbc.org.br/documentos-da-sbc/summary/169-templates-para-artigos-e-capitulos-de-livros/878-modelosparapublicaodeartigos). Este modelo utiliza o projeto [latex-devcontainer](https://github.com/a-nau/latex-devcontainer) para executar o projeto via [codespaces](https://github.com/features/codespaces).

## Executando o projeto local
Como pre requisito você precisará instalar na sua máquina:
- [MikTex](https://miktex.org/howto/download-miktex).
- [VsCode](https://code.visualstudio.com/)
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [latex-formatter](https://marketplace.visualstudio.com/items?itemName=nickfode.latex-formatter)
- [LaTeX](https://marketplace.visualstudio.com/items?itemName=mathematic.vscode-latex)
- [LTeX – LanguageTool grammar/spell checking](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex)
- [code runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

Após isso basta clicar no play no canto superior esquerdo no arquivo `main.tex` e gerar o .pdf (de preferência remover o pdf atual antes de gerar um novo).

## Executando o projeto no codespaces

Para o codespaces só precisa criar uma nova instância. o Container ja oferece todas as dependências instaladas. 
Após isso basta clicar no play no canto superior esquerdo no arquivo 'sbc-template.tex' e gerar o .pdf (de preferência remover o pdf atual antes de gerar um novo).

## Estrutura

O artigo consta na pasta `article`. Em `util` vemos as configurações e as referências. Na pasta `images`, colocamos os arquivos `.jpg` e `.png`. E por último em `sections` é onde é feito o artigo de fato. Os artigos possuem prefixo numérico pra facilitar a visualização em ordem nas pastas. Os arquivos Header e Abstract são obrigatórios. os demais podem ser substituídos.
