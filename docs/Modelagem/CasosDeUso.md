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

### Casos de uso para perfil com baixo dominio tecnológico

### 3.1 Fluxo de conta

<center>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/diagrama1.png" alt="drawing" width="400"/>

<figcaption>Imagem 5: Diagrama do fluxo de conta. Fonte: Grupo 6</figcaption>

| UC01 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de criar um perfil |
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário cria uma conta utilizando seus dados |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona a opção de criar uma conta</li><li>O usuário fornece seus dados</li></ul> |
| Pós-condições | O usuário poderá realizar login |

</center>


### 3.2 Fluxo de título

<center>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/diagrama2.png" alt="drawing" width="400"/>

<figcaption>Imagem 6: Diagrama do fluxo de título. Fonte: Grupo 6</figcaption>

| UC02 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de assistir um título |
| Pré-condições | Uma conta válida e um título |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário assiste um título |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um título</li></ul> |
| Pós-condições | O usuário poderá realizar operações no título |

</center>


### 3.3 Fluxo de conteúdo

<center>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.2-StarPlus/gh-pages/docs/assets/casos de uso/diagrama3.png" alt="drawing" width="400"/>

<figcaption>Imagem 7: Diagrama do fluxo de conteúdo. Fonte: Grupo 6</figcaption>

| UC03 | Informações | 
| :----: | :------:|
| Descrição | O usuário deve ser capaz de navegar pelo conteúdo |
| Pré-condições | Uma conta válida |
| Ator | Usuário com baixo dominio tecnológico |
| Ação | O usuário cria navega pelo conteúdo |
| Fluxo principal | <ul><li>O usuário acessa a aplicação</li><li>O usuário seleciona um perfil</li></ul> |
| Pós-condições | O usuário poderá navegar pelo conteúdo |


</center>

### Casos de uso para perfil com bom dominio tecnológico



## 4. Bibliografia

> - UML Use Case Diagrams. UML Diagrams. Disponível em: <https://www.uml-diagrams.org/use-case-diagrams.html> 
> - PIMENTEL, Andrey Ricardo. Projeto de Software Usando a UML. 2007.

## 5. Histórico de versão

| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 06/12/2022 | Criação da ata de reunião | [Vinícius Assumpção](https://github.com/viniman27)  | [João Pedro de Camargo Vaz](https://github.com/JoaoPedro0803) |
