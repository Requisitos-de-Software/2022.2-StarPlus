# NFR Framework
## Introdução
O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais. Tem como principal objetivo auxiliar os desenvolvedores no processo de implantação de soluções personalizadas com a perspectiva das características do domínio e do sistema em questão.Essas características incluem os Requisitos Não-Funcionais, Requsitos Funcionais, prioridades e carga de trabalho. Os Requisitos Não-Funcionais são considerados cidadãos de primeira ordem. O Framework trabalha com o conceito de softgoals, e possui um método de análise quantitativa para definir os status dos softgoals.

## Softgoals
Um softgoal é um objetivo que não tem definição clara nem critérios de aceitação precisos. São utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, indicando a influência de um softgoal em outro.

Para representar essa interdependência, usa-se um Softgoal Interdependency Graph (SIG). Esses gráficos armazenam um registro completo de todas as decisões de desenvolvimento e da lógica do projeto de forma gráfica e concisa, incluindo os Requisitos Não-Funcionais e suas alternativas, decisões e justificativas.

Existem três tipos de softgoals, e cada um deles possui uma notação gráfica associada.

<p style="font-size: 15px">Tabela1: Legenda dos diagramas<p>

| Imagem                                                                  | Legenda                                 |
| :---------------------------------------------------------------------- | :-------------------------------------- |
| ![softgoal](../assets/nfr/balao1.png) | Softgoal de NFR |
| ![softgoal](../assets/nfr/balao2.png) | Softgoal de Operacionalização |
| ![softgoal](../assets/nfr/balao3.png) | Softgoal de Afirmação |
| ![softgoal](../assets/nfr/critical.png) | Crítico |
| ![softgoal](../assets/nfr/aceito.png) | Aceito |
| ![softgoal](../assets/nfr/rejected.png) | Negado |
| ![softgoal](../assets/nfr/implicito.png) | Implícito |
| ![softgoal](../assets/nfr/explicito.png) | Explícito |
| ![softgoal](../assets/nfr/pSatisficing.png) | Muito Satisfeito |
| ![softgoal](../assets/nfr/PSatificing2.png) | Satisfeito |
| ![softgoal](../assets/nfr/negativeS.png) | Insatisfeito |
| ![softgoal](../assets/nfr/sNF.png) | Muito Insatisfeito |
<p style="font-size: 15px"> Fonte: Josué Teixeira <p>

## 2. Metodologia
  Através desse documento, buscamos definir as funcionalidades dos requisitos não-funcionais através da implementação de diagramas, representados nas Imagens 1 a 7, utilizando o NFR Framework, criando análises das possíveis situações.


## 3. Requisitos não funcionais
  Abaixo, na Tabela 2, estão os requisitos não-funcionais levantados através das técnicas de elicitação utilizadas no projeto, sendo os mesmo utilizados para elaboração do NFR Framework.
<br/>

<p align="center" style="font-size: 15px">Tabela 2: Requisitos não-funcionais selecionados</p>

|Número|Requisito|Técnica|
|----|----|----|
|RFN4|O sistema deve ser responsivo	|Brainstorm, Questionário|
|RNF5|O sistema deve ser multiplataforma|Questionário|
|RNF6	|O sistema deve possuir uma boa conexão com o servidor	|Observação, Brainstorm|
|RNF9|O sistema deve suportar o acesso simultâneo de mais de um perfil do mesmo usuário	|Introspecção|

<p align="center" style="font-size: 15px">Fonte: Josué Teixeira</p>

## Diagramas
### Geral

<p align="center" style="font-size: 15px">Imagem 1: Diagrama geral NFR</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/geral.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan</p>

### Disponibilidade

<p align="center" style="font-size: 15px">Imagem 2: Diagrama Disponibilidade NFR</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/disponibilidade.png' width="800" height="600">

<br/>
<p align="center" style="font-size: 15px">Fonte: Abdul Hannan</p>
</br>
<p align="center" style="font-size: 15px">Imagem 3: Diagrama Disponibilidade NFR - StarPlus (Autoria - Abdul Hannan)</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/disponibilidadepropagacao.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan</p>

### Segurança

<p align="center" style="font-size: 15px">Imagem 4: Diagrama Segurança NFR - StarPlus (Autoria - Abdul Hannan)</p><br/>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/seguranca.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan</p>
</br>
<p align="center" style="font-size: 15px">Imagem 5: Diagrama Segurança NFR - StarPlus (Autoria - Abdul Hannan)</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/segurancapropagacao.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan</p>

### Usabilidade

<p align="center" style="font-size: 15px">Imagem 6: Diagrama Usabilidade NFR - StarPlus (Autoria - Abdul Hannan)</p><br/>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/usabilidade.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan</p>
</br>
<p align="center" style="font-size: 15px">Imagem 7: Diagrama Usabilidade NFR - StarPlus (Autoria - Abdul Hannan)</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/usabilidadepropagacao.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan</p>

## Referências
Reinaldo Antônio da Silva. "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados". Universidade Federal de Pernambuco, 2019.

## Histórico de versão
|Versão|Data|Descrição|Autor|Revisor|
|-|-|-|-|-|
|1.0|03/01/2023|Criação do documento| [Abdul Hannan](https://github.com/hannanhunny01), [Thiago Vivan Bastos](https://github.com/thiago-vivan), [Josué Teixeira](https://github.com/zjosuez)|[Gabriel Roger](https://github.com/GabrielRoger07), [João Pedro de Camargo Vaz](https://github.com/JoaoPedro0803), [Vinícius Assumpção](https://github.com/viniman27)|
|1.1|04/01/2023|Adicionado tabela com as legendas, legendas das imagens e tabelas e correção ortográfica| [Josué Teixeira](https://github.com/zjosuez)|[Abdul Hannan](https://github.com/hannanhunny01), [Thiago Vivan Bastos](https://github.com/thiago-vivan)|
