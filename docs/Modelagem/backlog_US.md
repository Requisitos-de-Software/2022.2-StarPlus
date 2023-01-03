# Backlog do Produto + Histórias de Usuário

## 1. Introdução
&emsp;&emsp; Em um cenário de desenvolvimentos ágeis, a geração de um artefato amplo que acorda as necessidades do produto como um todo se faz necessário. Assim, o Product Backlog (Backlog do Produto) entra em ação.

&emsp;&emsp; Um conceito que melhor define Product Backlog pode ser o seguinte: é uma lista contendo todas as funcionalidades desejadas para um produto. Ele é definido e gerenciado pelo PO - Product Owner (membro da equipe responsável pelo entendimento dos desejos do cliente e do produto a ser desenvolvido).

&emsp;&emsp; É interessante que todo Backlog siga a técnica DEEP:

- **D**etailed (detalhado): os itens devem estar detalhados (e visíveis) para entendimento de todos os envolvidos no processo.
- **E**stimated (estimado): é importante que o Backlog possa ser estimável, isto é, quanto tempo demoraria e quantos recursos serão usados para cada item do desenvolvimento.
- **E**mergent (emergente): o Backlog não é estático, ele muda e é acrescentado ao longo do ciclo de vida do produto.
- **P**rioritized (priorizado): os itens devem ser priorizados, para que, assim, os itens mais valiosos e vitais possam ser mais visíveis e focados.

## 2. Metodologia

### 2.1. Especificação do Product Backlog
&emsp;&emsp; Para o desenvolvimento do Product Backlog do projeto, a equipe utilizou de uma técnica de especificação dividida em 3 níveis de granularidade:

- **Épico**: nível superior composto por features que possuem um objetivo específico, mas comum.
- **Features**: podem ser entendidas como as funcionalidades em si do Software, mas de forma geral, sem muito detalhamento.
- **Histórias de Usuário**: é o nível em que o detalhamento do item em si acontece.

### 2.2. Histórias de Usuário
&emsp;&emsp; As histórias de Usuário podem ser usadas para expressar uma funcionalidade/requisito de um Software na visão e perspectiva de um cliente que realmente usará a aplicação. Sendo assim, é possível entender quais são as expectativas e necessidades daqueles que serão os verdadeiros utilizadores do sistema.

&emsp;&emsp; É essencial que todas as histórias de Usuário possuam critérios de aceitação relacionadas a si, para que seja possível o levantamento da qualidade e do que seria uma história completa e bem-sucedida.

### 2.3 Estrutura do Product Backlog com Histórias de Usuário
&emsp;&emsp; Com o entedimento da especificação do Product Backlog e das Histórias de Usuário, a equipe montou o Product Backlog do aplicativo YouTube, seguindo o seguinte formato:

#### [EPCXX] Nome Épico

##### [FTRXX] Nome Feature

&emsp;&emsp; Lista de Histórias de Usuário ligadas a essa Feature e, consequentemente, Épico.

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| USXX | RFXX | Funcionalidade | Objetivo          | - Critério 1<br/>- Critério 2 | Alta/Média/Baixa |

&emsp;&emsp; As prioridades foram divididas entre Alta, Média ou Baixa. Sendo assim, itens de **Alta** prioridade são essenciais e mais recursos seriam destinados a eles, os de **Média** prioridade são importantes para o aplicativo, mas não vitais para seu funcionamento e os itens de **Baixa** prioridade são aperitivos sem foco inicial.

## 3. Product Backlog

### 3.1. [EPC01] Épico - [Conta](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Modelagem/lexicos?id=l06-conta)

#### 3.1.1. [FTR01] Feature - Gerenciamento de [conta](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Modelagem/lexicos?id=l06-conta)

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US01 | [RF1](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Criar uma [conta](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Modelagem/lexicos?id=l06-conta) | Ter uma [conta](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Modelagem/lexicos?id=l06-conta) cadastrada para [acessar](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Modelagem/lexicos?id=l01-acesso-ao-aplicativo) o aplicativo | - O [Usuário](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Modelagem/lexicos?id=l02-usu%c3%a1rio) deve fornecer informações válidas<br/>- A transação financeira deve ser confirmada | Alta |
| US02 | [RF3](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Cancelar minha assinatura | Parar de pagar o serviço | - O sistema deve desabilitar as funcionalidades para a conta do usuário<br/>- O sistema deve cancelar qualquer futura transação financeira | Alta |
| US03 | [RF4](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Alterar dados da minha conta | Corrigir ou atualizar algum dado pessoal cadastrado | - O usuário deve inserir dados válidos<br/>- O sistema deve salvar os novos dados do usuário | Alta |
| US04 | [RF5](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Visualizar os termos de privacidade | Averiguar como a empresa lida com meus dados |  | Alta |
| US05 | [RF23](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Alterar meus meios de pagamento | Continuar com a assinatura | - O usuário deve informar um meio de pagamento válido<br/>- O sistema deve alterar o meio de pagamento do usuário | Média |
| US06 | [RF37](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Ver informações da minha conta | Verificar meus dados e certificar que estão corretos | - O sistema deve apresentar os dados do usuário | Alta |
| US07 | [RF42](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Alterar a senha da minha conta | Ter acesso ao serviço | - O usuário deve informar o email cadastrado<br/>- O usuário deve receber um email para alterar a senha<br/>- O usuário deve informar uma senha válida<br/>- O sistema deve alterar a senha da conta do usuário | Alta |
| US08 | [RF34](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Desvincular os dispositivos | Controlar quem está acessando a minha conta | - O sistema deve encerrar a sessão do usuário no dispositivo utilizado no momento<br/>- O sistema deve encerrar a sessão do usuário de todos os dispositivos conectados a esta conta | Baixa |

#### 3.1.2. [FTR02] Feature - Plataforma e Interface da Conta

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US09 | [RF2](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Realizar login | Acessar o conteúdo da plataforma | - O usuário deve fornecer dados válidos<br/>- O usuário deve acessar a aplicação | Alta |
| US10 | [RF7](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Realizar logout | Desconectar minha conta do dispositivo | - O sistema deve remover a sessão do usuário no dispositivo | Alta |
| US11 | [RF27](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Escolher o idioma do aplicativo | Ter uma melhor compreensão das funcionalidades | - O usuário deve escolher qual idioma ele deseja<br/>- O sistema deve alterar o idioma da sua aplicação no perfil do usuário| Média |
| US12 | [RF38](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais)   | Diminuir o consumo de dados do celular | Economizar meus dados móveis | - O usuário deve escolher a opção 'economia de dados móveis'<br/>- O sistema deve alterar reduzir o consumo de dados móveis do dispositivo do usuário| Baixa |

### 3.2. [EPC02] Épico - Perfil

#### 3.2.1. [FTR03] Feature - Gerenciamento de perfil

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US13 | [RF6](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Adicionar novos perfis à minha conta | Criar perfis para meus familiares | - O usuário deve fornecer informações válidas para o perfil<br/>- O sistema deve salvar o perfil na conta do usuário | Alta |
| US14 | [RF18](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Alterar minha foto de perfil | Ter um perfil mais personalizado | - O usuário deve selecionar um dos perfis existentes<br/>- O usuário deve selecionar uma imagem na lista de imagens disponíveis<br/>- O sistema deve atualizar a imagem do perfil| Média |
| US15 | [RF31](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Excluir um perfil | Remover um perfil da minha conta | - O usuário deve selecionar o perfil que deseja excluir<br/>- O sistema deve excluir o perfil da conta do usuário | Alta |
| US16 | [RF40](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Criar um perfil infantil | Ter um perfil para meu filho assistir os conteúdos apropriados para a idade dele | - O usuário deve fornecer informações válidas para o perfil<br/>- O usuário deve definir o perfil como infantil<br/>- O sistema deve fornecer apenas títulos infantis para este perfil | Média |

#### 3.2.2. [FTR04] Feature - Plataforma e Interface do perfil

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US17 | [RF8](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Remover títulos da minha lista | Limpar a minha lista e deixar apenas os títulos que eu desejo assistir depois | - O usuário deve acessar sua lista de títulos<br/>- O usuário deve selecionar o título que deseja excluir<br/>- O sistema deve retirar o título escolhido da lista de títulos deste perfil | Baixa |
| US18 | [RF20](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Adicionar títulos na minha lista | Salvar um título para que eu possa assistir em outro momento | - O usuário deve escolher o título que deseja adicionar na lista<br/>- O sistema deve adicionar o título na lista deste perfil | Baixa |


### 3.3. [EPC03] Épico - Conteúdo

#### 3.3.1. [FTR05] Feature - Reprodução de Conteúdo

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US19 | [RF11](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Passar para o próximo episódio ainda na reprodução atual | Assistir ao próximo episódio | - O usuário deve estar assistindo a um título válido<br/>- O título deve possuir um próximo episódio | Baixa |
| US20 | [RF12](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Escolher o episódio de uma série | Assistir ao episódio que eu desejo | - O usuário deve selecionar um conteúdo que tenha episódios<br/>- O usuário deve selecionar um determinado episódio | Alta |
| US21 | [RF13](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Assistir a um trailer de algum título | Decidir se vou assistir ao conteúdo ou não | - O usuário deve selecionar um título valido<br/>- O usuário deve clicar no botão de trailer | Baixa |
| US22 | [RF16](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Pular a abertura de um título | Começar a assistir o episódio de maneira mais rápida | - Ao assistir a um conteúdo, o usuário deve ter a opção de pular a abertura | Média |
| US23 | [RF17](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Escolher a temporada de um título | Assistir o conteúdo do episódio que eu quiser | - O usuário deve selecionar um título que possua temporadas<br/>- O usuário deve selecionar uma temporada disponível | Alta |
| US24 | [RF25](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Escolher o idioma de áudio | Assistir a um título no idioma de áudio que eu quero | - Ao selecionar um título, o usuário deve possuir opções de idiomas para o áudio do título | Alta |
| US25 | [RF26](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Escolher o idioma de legenda | Assistir a um título no idioma de legenda que eu quero  | - Ao selecionar um título, o usuário deve possuir opções de idiomas para a legenda do título | Alta |
| US26 | [RF28](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Retirar a legenda do título | Assistir a um título sem legenda | - Ao selecionar um título, o usuário deve possuir opção de retirar a legenda do título | Alta |
| US27 | [RF29](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Escolher a qualidade da imagem | Definir a qualidade do vídeo da maneira que eu prefiro  | - Ao assistir a um conteúdo, o usuário deve poder selecionar em qual qualidade o conteúdo será reproduzido | Média |
| US28 | [RF30](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Usar a opção de tela cheia | Definir o tamanho da tela da maneira que eu desejo  | - Ao assistir a um conteúdo, o usuário deve ter a opções de assistir a reprodução em tela cheia. | Média |
| US29 | [RF32](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Usar a opção de Watch Party | Assistir a um título com meus melhores amigos  | - Todos do grupo devem possuir assinatura Star+<br/>- Todos do grupo devem possuir uma boa conexão com a internet | Baixa |
| US30 | [RF43](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Assistir a um título | Aproveitar meu tempo livre assistindo a minha série favorita  | - O usuário deve selecionar um título válido | Alta |
| US31 | [RF44](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Pausar a reprodução de um título | Buscar um lanche para comer assistindo meu filme predileto, mas sem perder um segundo do filme  | - O usuário deve selecionar um título válido | Alta |
| US32 | [RF45](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Avançar ou retroceder na reprodução de um título | Voltar e assistir a parte que eu achei muito engraçada de um episódio | - O usuário deve selecionar um título válido | Alta |

#### 3.3.2. [FTR06] Feature - Interação com Conteúdo

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US33 | [RF9](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Avaliar um título | Contribuir com a comunidade do Star+ | - O usuário deve selecionar um título válido<br/>- O usuário deve dar uma avaliação que esteja entre os limites permitidos | Baixa |
| US34 | [RF14](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Desabilitar a reprodução automática | Terminar um episódio e não ir automaticamente para o próximo | - O usuário deve estar reproduzindo um título<br/>- O título deve possuir uma sequência | Média |
| US35 | [RF24](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Baixar um título | Assistir ao título baixado em outro momento, quando eu não possuir conexão com a internet | - O usuário deve selecionar um título válido<br/>- O usuário deve possuir espaço de armazenamento disponível em seu dispositivo | Alta |
| US36 | [RF33](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Ocultar um título | Não ver esse título | - Deve haver a opção de ocultar título em todos os títulos disponíveis para assistir | Baixa |
| US37 | [RF36](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Ver informações dos autores | Obter mais informações sobre o elenco do título | - Todo título deve possuir uma opção para visualizar o elenco que participou na produção do título | Baixa |
| US38 | [RF46](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Ver informações do título | Obter mais informações sobre o título | - Todo título deve possuir uma sinopse do conteúdo do título | Média |
| US39 | [RF47](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Ver categoria(s) do título | Identificar o gênero do título | - Todo título deve possuir ao menos uma categoria | Baixa |

#### 3.3.3. [FTR07] Feature - Busca

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US40 | [RF21](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Realizar uma busca | Encontrar o título desejado | - Input para a digitação do conteúdo a ser buscado<br/>- Os resultados da busca serem atualizados conforme o usuário digita<br/>- O usuário deve buscar um título válido | Alta |
| US41| [RF22](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Filtrar uma busca | Encontrar o título desejado por meio de ferramentas | - Diversos filtros selecionáveis<br/>- Opções de remover filtros previamente selecionados<br/>- Os resultados da busca devem refletir os filtros aplicados | Alta |
| US42 | [RF35](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Excluir histórico de navegação | Limpar todas as buscas feitas anteriormente | - O usuário precisa já ter feito pelo menos uma busca | Média |
| US43 | [RF39](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Acessar um título por apenas uma parte do nome | Encontrar o título desejado mesmo sem saber o nome completo | - Após realizar uma busca digitando apenas parte do nome, o usuário deve ter a sua disposição uma lista com todos os conteúdos relacionados à busca. | Alta |

#### 3.3.4. [FTR08] Feature - Interface Inicial

| ID   | Rastreabilidade     | Eu, como usuário, gostaria de         | Para que eu possa | Critérios de Aceitação        | Prioridade       |
| :--: | :----------- | :------------- | :---------------- | :---------------------------- | :--------------: |
| US44 | [RF10](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Acessar a página de ajuda da plataforma | Resolver uma dúvida de acesso que estou tendo | - O sistema deve possuir uma página de ajuda para os usuários tirarem suas dúvidas de usabilidade | Alta |
| US45 | [RF15](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Visualizar títulos recomendados | Encontrar indicações de títulos | - O sistema deve oferecer indicações de títulos de maneira personalizada ao usuário, de acordo com o que ele geralmente assiste | Média |
| US46 | [RF19](https://requisitos-de-software.github.io/2022.2-StarPlus/#/docs/Elicitacao/Resultado?id=_31-requisitos-funcionais) | Ver títulos assistidos anteriormente | Relembrar quais títulos eu já assisti desde que fiz o cadastro na plataforma | - O usuário precisa já ter assistido ao menos um título<br/>- O sistema deve ter uma aba de títulos assistidos anteriormente | Alta |

## 4. Referências

> - Milene Serrano, Requisitos - Aula 15. Disponível em: Aprender3.
> - LuizTools, Product Backlog - Introdução. Disponível em: https://www.youtube.com/watch?v=z4ubaBwjCsU&feature=youtu.be.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 29/12/2022 | Criação do documento e introdução inicial. | [Vinícius Assumpção](https://github.com/viniman27)  | [Gabriel Roger](https://github.com/GabrielRoger07) e [João Pedro](https://github.com/JoaoPedro0803) |
| 1.1    | 31/12/2022 | Adição de histórias, features e épicos. | [Gabriel Roger](https://github.com/GabrielRoger07) | [Vinícius Assumpção](https://github.com/viniman27) e [João Pedro](https://github.com/JoaoPedro0803) |