# Casos de Uso

## 1. Introdução

&emsp;&emsp;Os casos de usos, também chamados de diagramas comportamentais na notação UML, são usados para descrever um conjunto de ações que um sistema ou um conjunto de sistemas deve desempenhar em colaboração com um ou mais usuários externos ao sistema. Os casos de uso devem prover um resultado observável e de valor para os atores ou outros interessados do sistema.

## 2. Diagrama de Casos de Uso

&emsp;&emsp;Na notação UML, o diagrama de casos de uso é o principal diagrama para modelar requisitos, com foco em requisitos funcionais.

<center>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/elementos.png" alt="drawing" width="400"/>

<figcaption>Imagem 1: Elementos do Diagrama de Casos de Uso. Fonte: Andrey Ricardo </figcaption>

</center>

### 2.1 Casos de uso

&emsp;&emsp;Representam a funcionalidade fornecida pelo sistema, modelando um diálogo entre um ator e o sistema. O conjunto de casos de uso para um sistema constitui todos os caminhos definidos nos quais o sistema pode ser usado. São representados por elipses e devem ser escritos como verbos no infinitivo, para indicar que são ações.

### 2.2 Atores
&emsp;&emsp;Representam algo ou alguém que deve interagir com o sistema, não fazendo parte do mesmo. Um ator é representado pela figura do boneco palito.

### 2.3 Limite do sistema

&emsp;&emsp;Delimita os limites do sistema e é representado por um retângulo.

### 2.4 Relacionamentos

&emsp;&emsp;São utilizados para representar as interações entre os atores e os casos de uso.

#### 2.4.1 Associação

&emsp;&emsp;Podem existir entre um ator e um caso de uso, representando uma comunicação entre os mesmos. É representado por uma linha que liga os elementos relacionados.

#### 2.4.2 Relacionamentos include

&emsp;&emsp;São criados entre um novo caso de uso e qualquer outro caso de uso que utilize esta funcionalidade. São representados pela seta pontilhada ligando os elementos relacionados.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/include.png" alt="drawing" width="400"/>

<figcaption>Imagem 2: Relacionamento include. Fonte: UML Use Case Diagrams</figcaption>

</center>

#### 2.4.3 Relacionamentos extend

&emsp;&emsp;São usados para mostrar um comportamento opcional, que somente é executado sobre determinadas condições. São representados pela seta pontilhada ligando os elementos relacionados.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/extend.png" alt="drawing" width="400"/>

<figcaption>Imagem 3: Relacionamento extend. Fonte: UML Use Case Diagrams</figcaption>

</center>

#### 2.4.4 Generalizações
&emsp;&emsp;Representam uma especialização entre casos de uso ou entre atores. São representados por uma seta de generalização.

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/generalization.png" alt="drawing" width="400"/>

<figcaption>Imagem 4: Generalização. Fonte: UML Use Case Diagrams</figcaption>

</center>

## 3. Diagramas

### OBS: É importante notar que no caso do Star+, os usuários de bom domínio tecnológico também estão incluídos nos casos dos usuários de baixo domínio tecnológico, mas não o contrário

## Casos de uso para perfil com baixo dominio tecnológico


<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/diagramaperfil1.png" alt="drawing" width="400"/>
<figcaption>Imagem 5: Casos de uso do usuário com baixo dominio tecnológico. Fonte: Grupo 6</figcaption>

### 3.1 Fluxo de perfil

<center>

| UC01 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de criar um perfil |
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário cria uma conta utilizando seus dados |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona a opção de criar uma conta</li><li>O usuário fornece seus dados</li></ul> |
| Pós-condições | O usuário poderá acessar um perfil específico |

</center>


### 3.2 Fluxo de título

<center>

| UC02 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de assistir um título |
| Pré-condições | Uma conta válida e um título |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário assiste um título |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li></ul> |
| Pós-condições | O usuário poderá assisitir a um título |

</center>


### 3.3 Fluxo de conteúdo

<center>

| UC03 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de navegar pelo conteúdo |
| Pré-condições | Uma conta válida |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário cria navega pelo conteúdo |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um perfil</li></ul> |
| Pós-condições | O usuário poderá navegar pelo conteúdo |
  
  
 ### 3.4 Fluxo de lista
  
| UC04 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de criar uma lista de favoritos |
| Pré-condições | Uma conta válida |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário cria uma lista de favoritos |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um perfil</li><li>O usuário seleciona um titulo</li><li>O usuário adiciona à lista</li></ul> |
| Pós-condições | O usuário poderá acessar uma lista de favoritos |
  
  
### 3.5 Fluxo de busca
  
| UC05 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de buscar um título |
| Pré-condições | Uma conta válida |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário busca um título de interesse |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona a barra de pesquisa</li></ul><li>O usuário busca pelo título de interesse, com ou sem o uso de filtros</li> |
| Pós-condições | O usuário poderá buscar pelo conteúdo |
  
### 3.6 Fluxo de alteração do idioma
  
| UC06 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de alterrar o idioma da dublagem e/ou legenda do título |
| Pré-condições | Uma conta válida |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário muda o idioma da dublagem e/ou legenda do título|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li></ul><li>O usuário muda o idioma da dublagem e/ou legenda do título</li> |
| Pós-condições | O usuário poderá navegar pelo conteúdo |


</center>

## Casos de uso para perfil com bom dominio tecnológico

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/diagramaperfil3.png" alt="drawing" width="400"/>
<figcaption>Imagem 6: Casos de uso do usuário com bom dominio tecnológico. Fonte: Grupo 6</figcaption>


### 3.7 Fluxo de reprodução em segundo plano

| UC07 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de alterar a configuração de reprodução em segundo plano|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário altera para permitido a reprodução de um título em segundo plano |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona a opção de configurações</li><li>O usuário permite a reprodução de um título em segundo plano</li></ul> |
| Pós-condições | O usuário poderá reproduzir um título em segundo plano |

### 3.8 Fluxo de compartilhamento do título

| UC08 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de compartilhar um título em diversas redes sociais|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário compartilha um título em suas redes sociais|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li><li>O usuário seleciona a opção de compartilhar o título</li><li>O usuário seleciona  alguma das diversas redes sociais disponíveis</li></ul> |
| Pós-condições | O usuário poderá compartilhar um título|

### 3.9 Fluxo de detalhamento do título

| UC09 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ver com mais detalhes as informações do título|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário observa o título de forma mais detalhada|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li><li>O usuário seleciona a opção de detalhar o título</li></ul> |
| Pós-condições | O usuário poderá conhecer em detalhes o título |

### 3.10 Fluxo de configurações da legenda

| UC10 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve alterar as configuraçoes da legenda|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário muda as configurações da legenda|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li><li>O usuário seleciona a opção de configuração da legenda</li></ul> |
| Pós-condições | O usuário poderá alterar diversos aspectos da legenda |

### 3.11 Fluxo de configurações da velocidade de reprodução

| UC11 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve alterar as configuraçoes da velocidade da reprodução|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário muda as da velocidade da reprodução|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li><li>O usuário seleciona a opção de configuração da velocidade</li></ul> |
| Pós-condições | O usuário poderá alterar a velocidade de reprodução do título |

### 3.12 Fluxo de configurações da velocidade de reprodução

| UC12 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve alterar as configuraçoes da velocidade da reprodução|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário muda as da velocidade da reprodução|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li><li>O usuário seleciona a opção de configuração da velocidade</li></ul> |
| Pós-condições | O usuário poderá alterar a velocidade de reprodução do título |

### 3.13 Fluxo de download

| UC13 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve baixar um título|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário baixa um título|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li><li>O usuário seleciona a opção de baixar o título</li></ul> |
| Pós-condições | O usuário poderá acessar o títlo mesmo offline |

### 3.14 Fluxo de configuração de rede móvel

| UC14 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve alterar as configurações de funcionamneto com base em redes móveis|
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com bom dominio tecnológico |
| Ação | O usuário altera as configurações de funcionamneto com base em redes móveis|
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona as configurações do app</li><li>O usuário seleciona a opção de alterar o limite de funcionamento com base em redes móveis</li></ul> |
| Pós-condições | O usuário poderá alterar o limite de funcionamneto do app com base em redes móveis |


## 4. Bibliografia

> - UML Use Case Diagrams. UML Diagrams. Disponível em: <https://www.uml-diagrams.org/use-case-diagrams.html> 
> - PIMENTEL, Andrey Ricardo. Projeto de Software Usando a UML. 2007.

## 5. Histórico de versão

| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 06/12/2022 | Criação da ata de reunião | [Vinícius Assumpção](https://github.com/viniman27)  | [João Pedro de Camargo Vaz](https://github.com/JoaoPedro0803) |
