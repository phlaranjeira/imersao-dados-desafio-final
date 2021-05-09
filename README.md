# PROJETO IMERSÃO DADOS ALURA - DRUG DISCOVERY
## PEDRO HENRIQUE DELLAMANO LARANJEIRA

![image](https://user-images.githubusercontent.com/83909784/117573445-3383b600-b0ae-11eb-9fcc-6311fba84c21.png)


### Temática e dados analisados

Este projeto será baseado nas aulas e discussões apresentadas na Imersão Dados Alura, a respeito da área de drug discovery.
Para isso serão utilizadas informações contidas em duas bases de dados:
 - Experimentos: dados correspondentes a experimentos com culturas celulares submetidas a diversas drogas em diferentes dosagens e tempos de exposição. Com isso foram obtidos resultados de expressão gênica (https://pt.khanacademy.org/science/biology/gene-expression-central-dogma/central-dogma-transcription/a/intro-to-gene-expression-central-dogma/) e viabilidade celular; (https://pt.wikipedia.org/wiki/Ensaios_de_viabilidade_celular#:~:text=Um%20ensaio%20de%20viabilidade%20celular,sua%20atividade%20qualitativa%20e%20quantitativamente.).
 - Resultados: para cada experimento são apresentados os resultados de diversos tipos de Mecânismos de Ação, ou, em inglês, Mechanisms of Action (MoA) (https://en.wikipedia.org/wiki/Mechanism_of_action).

### Escopo do projeto

Inicialmente serão realizadas algumas análises com as bases de dados com o objetivo de melhor compreendê-las. Nessa etapa serão verificados os tipos de classificação de tratamento, os tipos de drogas (ou compostos) utilizados, as dosagens utilizadas e os tempos de aplicação. Para essas variáveis serão avaliados os possíveis impactos nas expressões gênicas e nas viabilidades celulares.

Em seguida serão analisadas as correlações entre os dados de expressões gênicas e viabilidades celulares.

Por fim, serão desenvolvidos modelos de machine learning com a tentativa de prever três comportamentos:
 - Dados os resultados de expressões gênicas e viabilidades celulares de um experimento, é possível prever se ocorre algum mecanismo de ação?
 - Dados os resultados de expressões gênicas e viabilidades celulares de um experimento, é possível prever se ocorre um mecanismo de ação específico?
 - Dados os resultados de expressões gênicas de um experimento, é possível prever os dados de viabilidades celulares?

### Estrutura do projeto

1- Introdução

2- Importação das bibliotecas utilizadas

3- Importação dos dados analisados

4- Análise geral dos dados

5- Análise de algumas relações entre os dados experimentais

6- Análise de correlação entre os dados de expressões gênicas e viabilidades celulares

7- Modelos de machine learning para o questionamento 1

8- Modelos de machine learning para o questionamento 2

9- Modelos de machine learning para o questionamento 3

10- Conclusões
