# NFR Framework
## Introdução
O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais. Tem como principal objetivo auxiliar os desenvolvedores no processo de implantação de soluções personalizadas com a perspectiva das características do domínio e do sistema em questão.Essas características incluem os Requisitos Não-Funcionais, Requsitos Funcionais, prioridades e carga de trabalho. Os Requisitos Não-Funcionais são considerados cidadãos de primeira ordem. O Framework trabalha com o conceito de softgoals, e possui um método de análise quantitativa para definir os status dos softgoals.

## Softgoals
Um softgoal é um objetivo que não tem definição clara nem critérios de aceitação precisos. São utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, indicando a influência de um softgoal em outro.

Para representar essa interdependência, usa-se um Softgoal Interdependency Graph (SIG). Esses gráficos armazenam um registro completo de todas as decisões de desenvolvimento e da lógica do projeto de forma gráfica e concisa, incluindo os Requisitos Não-Funcionais e suas alternativas, decisões e justificativas.

Existem três tipos de softgoals, e cada um deles possui uma notação gráfica associada.

### Contribuições

Conforme os softgoals são refinados sucessivamente, um softgoal descendente
pode contribuir de forma total ou parcial, de forma negativa ou positiva,
para a satisfação do ascendente.

Contribuições descrevem como a satisfação ou não de um softgoal descendente
contribui para a satisfação de um softgoal ascendente, podem ser positivas ou negativas,
ou até satisfazendo completamente o ascendente.

Tipos de contribuição utilizadas pelo framework:

- **AND:** Determina que se os softgoals descendentes forem satisfeitos os softgoals ascendentes serão satisfeitos.
- **OR:** Determina que, se algum softgoal descendente for satisfeito, o ascendente será satisfeito.
- **MAKE(++):** Fornece uma contribuição suficientemente positiva (MAKE) entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de satisfação.
- **BREAK(--):** Fornece uma contribuição suficientemente negativa (BREAK) entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de negação.
- **HELP(+):** Fornece uma contribuição parcialmente positiva entre um softgoal descendente e um softgoal ascendente.
- **HURT(-):** Fornece uma contribuição parcialmente negativa entre um softgoal descendente e um softgoal ascendente.
- **UNKNOWN(?):** Fornece uma contribuição desconhecida entre um softgoal descendente e um softgoal ascendente, podendo ser tanto positiva quanto negativa.
- **EQUALS:** Determina que o softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito e que softgoal descendente será negado se o softgoal ascendente for negado.
- **SOME:** É utilizada quando o sinal da contribuição é conhecido (positivo ou negativo), mas a extensão (parcial ou total) não é. Nesses casos, quando há alguma incerteza em se utilizar HELP ou MAKE deve-se utilizar o tipo de contribuição SOME +. Da mesma forma quando não há certeza em se utilizar HURT ou BREAK deve-se utilizar SOME - .

### Procedimento de Avaliação
O procedimento de Avaliação é responsável por dizer o grau que os requisitos não funcionais são satisfeitos por um conjunto de decisões. Assim, é determinado se cada softgoal ou interdependência do SIG foi satisfeito. Para isso, são utilizados rótulos para os softgoals, que são nomeados como satisfeito, fracamente satisfeito, negado, fracamente negado, conflitante e indeterminado. Uma breve legenda dos rótulos pode ser verificada na figura 1 logo abaixo:

<div align="center">
<p>Figura 1: Rótulos para softgoals<p>

![rotulos_softgoals](https://user-images.githubusercontent.com/56610229/182727377-db2f3c30-6c9e-413b-bfd6-16c061b51046.png)

<p> Fonte: Projeto de Requisitos - Exército Brasileiro 2022.1</p>
</div>

## 2. Metodologia
  Através desse documento, buscamos definir as funcionalidades dos requisitos não-funcionais através da implementação de diagramas, representados nas tabelas 3 a 7, utilizando o NFR Framework, criando análises das possíveis situações.


## 3. Requisitos não funcionais
  Abaixo, na Tabela 1, estão os requisitos não-funcionais levantados através das técnicas de elicitação utilizadas no projeto, sendo os mesmo utilizados para elaboração do NFR Framework.
<br/>

<p align="center" style="font-size: 15px">Tabela 1: Requisitos não-funcionais selecionados</p>

|Número|Requisito|Técnica|
|----|----|----|
|RFN4|O sistema deve ser responsivo	|Brainstorm, Questionário|
|RNF5|O sistema deve ser multiplataforma|Questionário|
|RNF6	|O sistema deve possuir uma boa conexão com o servidor	|Observação, Brainstorm|
|RNF9|O sistema deve suportar o acesso simultâneo de mais de um perfil do mesmo usuário	|Introspecção|

<p align="center" style="font-size: 15px">Fonte: Josué Teixeira</p>

## Diagramas

### Legenda
&emsp;&emsp;Abaixo, na tabela 2, está a legenda relacionada aos diagramas das figuras 2 até 8.
<p>Tabela 2: Legenda dos diagramas<p>

| Imagem                                                                  | Legenda                                 |
| :---------------------------------------------------------------------- | :-------------------------------------- |
| <img height="100px" weight="100px" src="../assets/nfr/balao1.png"/> | Softgoal de NFR |
| <img height="100px" weight="100px" src="../assets/nfr/balao2.png"/> | Softgoal de Operacionalização |
| <img height="100px" weight="100px" src="../assets/nfr/balao3.png"/> | Softgoal de Afirmação |
| <img height="85px" weight="100px" src="../assets/nfr/critical.png"/> | Crítico |
| <img height="85px" weight="100px" src="../assets/nfr/aceito.png"/> | Aceito |
| <img height="65px" weight="100px" src="../assets/nfr/rejected.png"/> | Negado |
| ![softgoal](../assets/nfr/implicito.png) | Implícito |
| ![softgoal](../assets/nfr/explicito.png) | Explícito |
| ![softgoal](../assets/nfr/pSatisficing.png) | Muito Satisfeito |
| ![softgoal](../assets/nfr/PSatificing2.png) | Satisfeito |
| ![softgoal](../assets/nfr/negativeS.png) | Insatisfeito |
| ![softgoal](../assets/nfr/sNF.png) | Muito Insatisfeito |
<p style="font-size: 15px"> Fonte: Josué Teixeira, integrante do grupo 6 <p>

### Geral

<p align="center" style="font-size: 15px">Figura 2: Diagrama geral NFR</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/geral.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan, integrante do grupo 6</p>

### Disponibilidade

<p align="center" style="font-size: 15px">Figura 3: Diagrama Disponibilidade NFR</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/disponibilidade.png' width="800" height="600">

<br/>
<p align="center" style="font-size: 15px">Fonte: Abdul Hannan, integrante do grupo 6</p>
</br>
<p align="center" style="font-size: 15px">Figura 4: Diagrama Disponibilidade NFR</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/disponibilidadepropagacao.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan, integrante do grupo 6</p>

### Segurança

<p align="center" style="font-size: 15px">Figura 5: Diagrama Segurança NFR</p><br/>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/seguranca.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan, integrante do grupo 6</p>
</br>
<p align="center" style="font-size: 15px">Figura 6: Diagrama Segurança NFR</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/segurancapropagacao.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan, integrante do grupo 6</p>

### Usabilidade

<p align="center" style="font-size: 15px">Figura 7: Diagrama Usabilidade NFR</p><br/>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/usabilidade.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan, integrante do grupo 6</p>
</br>
<p align="center" style="font-size: 15px">Figura 8: Diagrama Usabilidade NFR</p>

<img src='https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/nfr/usabilidadepropagacao.png' width="800" height="600">

<p align="center" style="font-size: 15px">Fonte: Abdul Hannan, integrante do grupo 6</p>

## Referências
- Reinaldo Antônio da Silva. "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados". Universidade Federal de Pernambuco, 2019.
- Projeto de Requisitos - Exército Brasileiro 2022.1. Disponível em: [link](https://requisitos-de-software.github.io/2022.1-Exercito-Brasileiro/#/modelagemRequisitos/NFR/). Acesso em: 10 jan. 2023

## Histórico de versão
|Versão|Data|Descrição|Autor|Revisor|
|-|-|-|-|-|
|1.0|03/01/2023|Criação do documento| [Abdul Hannan](https://github.com/hannanhunny01), [Thiago Vivan Bastos](https://github.com/thiago-vivan), [Josué Teixeira](https://github.com/zjosuez)|[Gabriel Roger](https://github.com/GabrielRoger07), [João Pedro de Camargo Vaz](https://github.com/JoaoPedro0803), [Vinícius Assumpção](https://github.com/viniman27)|
|1.1|04/01/2023|Adicionado tabela com as legendas, legendas das imagens e tabelas e correção ortográfica| [Josué Teixeira](https://github.com/zjosuez)|[Abdul Hannan](https://github.com/hannanhunny01), [Thiago Vivan Bastos](https://github.com/thiago-vivan)|
|1.2|10/01/2023| Correção dos artefatos [verificados pelo grupo 5](https://requisitos-de-software.github.io/2022.2-GoogleMaps/analise/verificacao/5.Modelagem2/) | [Josué Teixeira](https://github.com/zjosuez)|[Abdul Hannan](https://github.com/hannanhunny01), [Thiago Vivan Bastos](https://github.com/thiago-vivan)|
