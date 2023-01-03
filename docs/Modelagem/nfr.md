# NFR Framework
## Introdução
O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais. Tem como principal objetivo auxiliar os desenvolvedores no processo de implantação de soluções personalizadas com a perspectiva das características do domínio e do sistema em questão.Essas características incluem os Requisitos Não-Funcionais, Requsitos Funcionais, prioridades e carga de trabalho. Os Requisitos Não-Funcionais são considerados cidadãos de primeira ordem.O Framework trabalha com o conceito de softgoals, e possui um método de análise quantitativa para definir os status dos softgoals.

## Softgoals
Um softgoal é um objetivo que não tem definição clara nem critérios de aceitação precisos. São utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, indicando a influência de um softgoal em outro.

Para representar essa interdependência, usa-se um Softgoal Interdependency Graph (SIG). Esses gráficos armazenam um registro completo de todas as decisões de desenvolvimento e da lógica do projeto de forma gráfica e concisa, incluindo os Requisitos Não-Funcionais e suas alternativas, decisões e justificativas.

Existem três tipos de softgoals, e cada um deles possui uma notação gráfica associada.

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-DisneyPlus/main/docs/assets/nfr/nfr_guide.png' width ="900"/>
<p align="center" >Imagem 1: Legenda dos elementos de definição do NFR Framework</p>
<br><br>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-DisneyPlus/main/docs/assets/nfr/nfr_line_guide.png'  width ="900"/>
<p align="center" >Imagem 2: Legenda dos elementos de relacionamento do NFR Framework</p>
<br>

## 2. Metodologia
  Através desse documento, buscamos definir as funcionalidades dos requisitos não-funcionais através da implementação de diagramas utilizando o NFR Framework, criando análises das possíveis situações.


## 3. Requisitos não funcionais
  Abaixo estão os requisitos não-funcionais levantados através das técnicas de elicitação utilizadas no projeto, sendo os mesmo utilizados para elaboração do NFR Framework.
<br/>

|Número|Requisito|Técnica|
|----|----|----|
|RFN4|O sistema deve ser responsivo	|Brainstorm, Questionário|
|RNF5|O sistema deve ser multiplataforma|Questionário|
|RNF6	|O sistema deve possuir uma boa conexão com o servidor	|Observação, Brainstorm|
|RNF9|O sistema deve suportar o acesso simultâneo de mais de um perfil do mesmo usuário	|Introspecção|

## Diagramas
### Geral
<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/geral.png' width="800" height="600">
<p align="center" >Imagem 3: Diagrama geral NFR - StarPlus (Autoria - Abdul Hannan)
</p>

### Disponibilidade
<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/disponibilidade.png' width="800" height="600">
<p align="center" >Imagem 4: Diagrama Disponibilidade NFR - StarPlus (Autoria - Abdul Hannan)</p><br/>


<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/disponibilidadepropagacao.png' width="800" height="600">
<p align="center" >Imagem 5: Diagrama Disponibilidade NFR - StarPlus (Autoria - Abdul Hannan)</p>


### Segurança
<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/seguranca.png' width="800" height="600">
<p align="center" >Imagem 6: Diagrama Segurança NFR - StarPlus (Autoria - Abdul Hannan)</p><br/>


<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/segurancapropagacao.png' width="800" height="600">
<p align="center" >Imagem 7: Diagrama Segurança NFR - StarPlus (Autoria - Abdul Hannan)</p>

### Usabilidade
<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/usabilidade.png' width="800" height="600">
<p align="center" >Imagem 8: Diagrama Usabilidade NFR - StarPlus (Autoria - Abdul Hannan)</p><br/>


<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/usabilidadepropagacao.png' width="800" height="600">
<p align="center" >Imagem 9: Diagrama Usabilidade NFR - StarPlus (Autoria - Abdul Hannan)</p>

## Referências
Reinaldo Antônio da Silva. "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados". Universidade Federal de Pernambuco, 2019.

## Histórico de versão
|Versão|Data|Descrição|Autor|Revisor|
|-|-|-|-|-|
|1.0|3/1/2023|Criação do documento| [Abdul Hannan](https://github.com/hannanhunny01), [Thiago Vivan Bastos](https://github.com/thiago-vivan), [Josué Teixeira](https://github.com/zjosuez)|[Gabriel Roger](https://github.com/GabrielRoger07), [João Pedro de Camargo Vaz](https://github.com/JoaoPedro0803), [Vinícius Assumpção](https://github.com/viniman27)|
