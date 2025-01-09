# :open_book: FIES

Meu foco nesse projeto é entender as mudanças que ocorreram dentro do programa governamental, utilizando os dados públicos de 2019, 2020 e 2021. Com base nisso, decidi por iniciar o processo extraindo os dados, realizando a limpeza e manutenção necessaria nas informações, e então realizar a análise dos dados.

Não querendo me prender apenas nos dados disponíveis no MEC, fui atrás de informações relevantes que possam explicar as alterações nos números conforme o andamento dos anos. Deixarei o link de minhas pesquisas no final do projeto.


**Extração:** Se tratava de arquivos CSV com disponibilização pública.

**Transformação:** Utilizei primeiramente o Python para mesclar todos os arquivos CSV em um só, para facilitar a análise.

**Carregamento:** Visualização dos dados em Python, com relatório descritivo das operações realizadas.

### :wrench: Ferrramentas

-**Python**

-**Pandas**

-**Pandas_Profiling**

-**Matplotlib**

-**Anaconda**

-**JupyterLab**

### :memo: Skills utilizadas

-**Limpeza de dados**

-**Tratamento dos dados**

-**Coleta de informações**

-**Transformação das informações em insights**

-**Data visualization**

-**Data Storytelling**

# Etapas
## Extração

Arquivos retirados do site do MEC, onde possuiam arquivos de 2019 a 2021, existem 2 tipos de planilha, uma contendo os dados dos inscritos e outra com as informações das vagas disponibilizadas pelas instituições públicas.

Cada ano possui 2 semestres, os dois arquivos são organizados da mesma maneira, resultando no total de 12 planilhas.

## Transformação / Limpeza

Por se tratar de diversas planilhas contendo as mesmas colunas, decidi por mesclar em um unico arquivo, facilitando na hora de realizar as análises futuras. Para isso utilizei Pandas e OS, bibliotecas do Python que facilitam essa operação. 

Os arquivos estavam corretamente classificados, tendo que fazer pequenas correções para facilitar a análise.

## Análise

Iniciei com o processo de Análise Exploratória, indo atrás da visão geral dos dados, verificando dados faltantes ou duplicados, distribuição e tipos.

Após isso iniciei com algumas análises, começando pela evolução na procura por cada curso em cada ano, a quantidade de inscritos por cada estado, estados que ofertam mais vagas e outras análises listadas no código.

## Informações Obtidas pela Análise

Conforme informações obtidas pelos dados, notamos uma queda nas inscrições e no número de vagas disponibilizadas pelas universidades, isso tudo ocorreu devido a alterações feitas pelo MEC no programa, diminuindo vagas e aumentando a dificuldade de novos entrantes.

Encontramos alguns padrões, como por exemplo, dentro do curso de medicina, que se encontra entre um dos cursos mais procurados, tornando o curso com maior dificuldade de novos entrantes, visto que possui uma média de 500 inscritos por vaga.

Já na questão racial, dentre os 3 anos, tivemos quase 50% de pardos e apenas 12% de negros.

Entre a questão de sexo, as mulheres se destacam nas inscritas, ultrapassando a marca de 65% nas inscrições.

## Referências

**Dados Analisados**

[MEC](https://dadosabertos.mec.gov.br/)

**Alterações no FIES**

[Agencia Brasil](https://agenciabrasil.ebc.com.br/educacao/noticia/2019-12/mec-oficializa-mudancas-no-fies-e-no-p-fies?utm_source=chatgpt.com)

[G1](https://g1.globo.com/educacao/noticia/2019/12/27/mec-muda-regras-para-o-fies-e-p-fies-e-reduz-numero-de-vagas-a-partir-de-2021.ghtml?utm_source=chatgpt.com)

# Como abrir o projeto

Será necessário o download dos dados em CSV, então a utilização do software *Anacondas*, utilizando o *JupiterLab 4.2.5*.

Realize o clone desse repositório para o seu GitHub, então salve em seu computador.

Após isso rode o projeto dentro do *JupyterLab*

