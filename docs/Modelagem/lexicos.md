# Léxicos

## 1. Introdução
O Léxico é uma técnica que procura descrever os símbolos de uma linguagem. Buscar frases e símbolos do domínio da aplicação é o principal objetivo dos Engenheiros de Requisitos. Cada símbolo é descrito com noção e impacto, sendo noção o símbolo e o impacto a descrição do efeito do símbolo na aplicação ou do efeito de algo na aplicação sobre o símbolo.

Essas descrições seguem o princípio circular e o princípio do vocabulário mínimo. O princípio da circularidade torna cada extensão da descrição ou a conotação se refere a outros símbolos da linguagem. A parte não simbólica da descrição deve vir de um subconjunto reduzido de palavras com significado claro (vocabulário mínimo).

O léxico é a base para o entendimento entre clientes, usuários e profissionais de software [Sayão, Carvalho, 2006]. É nesse contexto que, um léxico, consiste em uma técnica que procura descrever os símbolos de uma linguagem e, de acordo com o fato mencionado, é um dos principais objetivos a ser perseguido pelos engenheiros de requisitos, pois facilita a identificação de palavras ou frases peculiares ao meio social da aplicação sob estudo.

## 2. Metodologia

Os léxicos possuem passei dentro do sistema, podendo estes serem do tipo: Verbo, Objeto ou Estado. A tabela a seguir apresenta os tipos e suas definições.

| Verbo | Noção | Impacto |
|-------|-------|---------|
| Verbo | Quem realiza, quando acontece e quais os procedimentos envolvidos | Quais os reflexos da ação no ambiente e quais novos estados decorrentes |
| Objeto | Definir o objeto e definir com quais outros objetos ele se relaciona | Ações que podem ser aplicadas no objeto |
| Estado | Quais ações levaram a esse estado | Identificar outros estados a ações que podem ocorrer a partir do estado que se descreve |
<figcaption style="font-size: 15px" align="center">Tabela 1: Noções sobre léxicos. (Fonte: Autores, 2022)</figcaption>

<br>

Os léxicos foram divididos em ordem alfabética seguindo a tabela abaixo:

| Léxico       | Noção | Impacto           | Sinônimo         | Classificação               |
| ------------ | ----- | ------------------| --------         | --------------------------- |
|Nome do Léxico|Símbolo|Descrição do efeito|Sinônimos         | Verbo/Objeto/Estado         |
<figcaption style="font-size: 15px" align="center">Tabela 2: Divisão dos léxicos. (Fonte: Autores, 2022)</figcaption>

## 3. Léxicos

### L01 - Acesso ao aplicativo

| Léxico | Noção | Impacto | Sinônimo         | Classificação |
| ------ | ----- | ------- | --------         | ------------- |
|Acessar |O usuário acessa a plataforma da Star+.|O usuário pode acessar a Star+ pelo navegador.</br> O usuário pode acessar a Star+ pelo aplicativo mobile.</br>O usuário pode acessar a Star+ pela Android TV.</br>O usuário pode acessar a Star+ pela Apple TV.</br>O usuário pode acessar a Star+ pelo PlayStation 4.</br>O usuário pode acessar a Star+ pelo Xbox One.</br>O usuário pode acessar a Star+ por uma smartTV.</br>O usuário pode acessar a Star+ pelo Amazon Fire TV. | Conectar, entrar  | Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 3: Léxico 01 (Fonte: Autores, 2022)</figcaption>

### L02 - Usuário

| Léxico | Noção | Impacto | Sinônimo          | Classificação |
| ------ | ----- | ------- | --------          | ------------- |
|Usuário |Pessoa(s) que utiliza a plataforma da Star+.|Pessoa(s) que poderá usufrir das funcionalidades do Star+.|Utilizador, cliente| Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 4: Léxico 02 (Fonte: Autores, 2022)</figcaption>

### L03 - Criar Conta

| Léxico | Noção | Impacto | Sinônimo      | Classificação |
| ------ | ----- | ------- | --------      | ------------- |
|Criar Conta  |É possível criar uma conta, perfis e listas no Star+.|O usuário poderá criar uma conta no Star+.</br> Dentro de uma conta, o usuário poderá criar perfis.</br>Dentro de um perfil, o usuário poderá criar listas com os títulos presentes na plataforma.|Gerar, produzir| Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 5: Léxico 03  (Fonte: Autores, 2022)</figcaption>

### L04 - Login

| Léxico | Noção | Impacto | Sinônimo      | Classificação |
| ------ | ----- | ------- | --------      | ------------- |
|Login   |Entrar na conta|O usuário precisará fazer login para acessar os conteúdos presentes na plataforma do Star+.|Entrar, acessar| Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 6: Léxico 04  (Fonte: Autores, 2022)</figcaption>

### L05 - Logout

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Logout  |Sair da conta|O usuário precisará fazer logout para sair de uma conta Star+.|Sair      | Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 7: Léxico 05  (Fonte: Autores, 2022)</figcaption>

### L06 - Conta

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Conta   |Local onde o usuário tem acesso as funcionalidades do Star+ e perfis daquela conta.|O usuário entra na conta para ter acesso aos recursos do Star+.</br> O usuário pode alterar o email e a senha vinculados aquela conta.</br>O usuário pode visualizar e alterar a sua assinatura.</br>O usuário pode restringir a criação de perfis.|-         | Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 8: Léxico 06 (Fonte: Autores, 2022)</figcaption>

### L07 - Assinatura

| Léxico   | Noção | Impacto | Sinônimo | Classificação |
| ------   | ----- | ------- | -------- | ------------- |
|Assinatura|Contrato de assinatura com o Star+ para usufruir dos conteúdos presentes na plataforma.|O usuário escolhe qual plano de assinatura ele deseja. <br />O usuário poderá usufrir os recursos presentes na plataforma do Star+ após a assinatura.|Contrato  |Objeto|
<figcaption style="font-size: 15px" align="center">Tabela 9: Léxico 07. (Fonte: Autores, 2022)</figcaption>

### L08 - Perfil

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Perfil  |Local onde o usuário poderá assistir conteúdos do Star+. O Star+ permite criação de até 7 perfis diferentes. Os perfis podem ser editados ou excluídos. |Após selecionar um perfil, o usuário poderá assitir conteúdos da plataforma e as recomendações baseadas na preferência daquele perfil.|-         | Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 10: Léxico 08. (Fonte: Autores, 2022)</figcaption>

### L09 - Selecionar perfil

| Léxico          | Noção | Impacto | Sinônimo      | Classificação |
| --------------- | ----- | ------- | --------      | ------------- |
|Selecionar perfil|Escolher um perfil criado.|O usuário pode escolher qual dos perfis criados deseja utilizar.|Escolher perfil| Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 11: Léxico 09. (Fonte: Autores, 2022)</figcaption>

### L10 - Editar Perfil

| Léxico | Noção | Impacto | Sinônimo          | Classificação |
| ------ | ----- | ------- | --------          | ------------- |
|Editar Perfil  |Os perfis do Star+ podem ser editados alterando o ícone ou nome.|O usuário poderá escolher qual avatar ele deseja escolher e também o nome que deseja colocar no perfil.|Personalizar, mudar perfil| Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 12: Léxico 10. (Fonte: Autores, 2022)</figcaption>

### L11 - Títulos

| Léxico | Noção | Impacto | Sinônimo                    | Classificação |
| ------ | ----- | ------- | --------                    | ------------- |
|Título  |Conteúdo presente no Star+.|O usuário pode assistir títulos.</br>O usuário pode buscar títulos.</br>O usuário pode adicionar títulos a sua lista.|Filmes, séries, documentários| Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 13: Léxico 11. (Fonte: Autores, 2022)</figcaption>

### L12 - Filme

| Léxico | Noção | Impacto | Sinônimo                            | Classificação |
| ------ | ----- | ------- | --------                            | ------------- |
|Filme   |Sequência de cenas projetadas.|O usuário poderá assistir os filmes presentes no Star+.|Vídeo, longa-metragem, curta-metragem| Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 14: Léxico 12  (Fonte: Autores, 2022)</figcaption>

### L13 - Série

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Série   |Obra televisiva ou cinematográfica dividida em episódios.|O usuário poderá assistir séries presentes no Star+.|Seriado   | Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 15: Léxico 13  (Fonte: Autores, 2022)</figcaption>

### L14 - Documentário

| Léxico     | Noção | Impacto | Sinônimo | Classificação |
| ---------- | ----- | ------- | -------- | ------------- |
|Documentário|Gênero de título que tem como objetivo a apresentação de uma visão da realidade por meio da tela|O usuário poderá assistir documentários presentes no Star+.|-         | Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 16: Léxico 14  (Fonte: Autores, 2022)</figcaption>


### L15 - Gênero

| Léxico | Noção | Impacto | Sinônimo           | Classificação |
| ------ | ----- | ------- | --------           | ------------- |
|Gênero  |Categoria que uma série, documentário ou filme está inserido.|O usuário poderá buscar por um gênero específico.</br>O usuário pode visulizar qual gênero um determinado título pertence.| Categoria, variedade|Estado         |
<figcaption style="font-size: 15px" align="center">Tabela 17: Léxico 15. (Fonte: Autores, 2022)</figcaption>

### L16 - Sinopse

| Léxico | Noção | Impacto | Sinônimo               | Classificação |
| ------ | ----- | ------- | --------               | ------------- |
|Sinopse |Descrição sintética da ideia do filme, série ou documentário.|O usuário poderá visualizar a sinopse do filme.</br>O usuário poderá visualizar a sinopse da série.</br>O usuário poderá visualizar a sinopse do documentário.</br>|Resenha, resumo, síntese| Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 18: Léxico 16. (Fonte: Autores, 2022)</figcaption>

### L17 - Episódio

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Episódio|Um episódio é uma parte de uma sequência de um corpo de trabalho cinematográfico.|O usuário poderá assistir um episódio de série do Star+. </br>O usuário poderá assistir um episódio de documentário do Star+.|Capítulo  | Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 19: Léxico 17. (Fonte: Autores, 2022)</figcaption>

### L18 - Assistir

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Assistir|Assistir títulos na Star+.|Com uma assinatura ativa, dispositivo compatível, acesso a internet ou título baixado, o usuário poderá assistir um título do Star+.</br>O usuário pode assistir filmes, séries ou documentários.|Ver       | Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 20: Léxico 18. (Fonte: Autores, 2022)</figcaption>

### L19 - Controlar

| Léxico  | Noção | Impacto | Sinônimo          | Classificação |
| ------- | ----- | ------- | --------          | ------------- |
|Controlar|Controle parental, de tempo, linguagem ou legenda.|O usuário poderá controlar um perfil infantil.</br>O usuário poderá controlar um título, podendo avançar, pausar, retomar ou voltar.</br>O usuário poderá controlar a linguagem do áudio e da legenda.|Comandar, coordenar| Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 21: Léxico 19. (Fonte: Autores, 2022)</figcaption>

### L20 - Download

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Download|Baixar título temporariamente.|O usuário pode fazer download temporário de um conteúdo de forma a possibilitar a visualização sem conexão com à Internet. <br />O usuário poderá assistir offline aquele conteúdo por um periodo de 30 dias a partir da data de download.|Baixar    | Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 22: Léxico 20. (Fonte: Autores, 2022)</figcaption>

### L21 - Explorar

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Explorar|Opção presente quando seleciona a opção de pesquisar sem ter digitado nada.|O usuário poderá navegar pelos títulos apresentados na função explorar.|Descobrir | Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 23: Léxico 21. (Fonte: Autores, 2022)</figcaption>

### L22 - Filtrar

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Filtrar |Entende-se por filtro algo que seleciona o que passa por ele.|O usuário poderá filtrar filmes de acordo com o gênero.</br>O usuário poderá filtrar séries de acordo com o gênero.</br>O usuário poderá filtrar documentários de acordo com o gênero.|Escolher  | Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 24: Léxico 22. (Fonte: Autores, 2022)</figcaption>

### L23 - Idioma

| Léxico | Noção | Impacto | Sinônimo      | Classificação |
| ------ | ----- | ------- | --------      | ------------- |
|Idioma  |O idioma é uma língua própria de um povo.|O usuário poderá escolher o idioma da dublagem.</br>O usuário poderá escolher o idioma da legenda.|Língua, dialeto|Estado|
<figcaption style="font-size: 15px" align="center">Tabela 25: Léxico 23. (Fonte: Autores, 2022)</figcaption>

### L24 - Legenda

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Legenda |Textos que acompanham uma imagem, conferindo-lhe um significado ou esclarecimento.|O usuário poderá ativar as legendas.</br>O usuário poderá personalizar as legendas.|Letreiro  |Objeto|
<figcaption style="font-size: 15px" align="center">Tabela 26: Léxico 24. (Fonte: Autores, 2022)</figcaption>

### L25 - Lista

| Léxico | Noção | Impacto | Sinônimo | Classificação |
| ------ | ----- | ------- | -------- | ------------- |
|Lista   |Coleção de títulos selecionados pelo usuário.|O usuário poderá adicionar títulos a sua lista.</br>O usuário poderá remover títulos da sua lista.</br>O usuário poderá assistir os títulos da sua lista.|Listagem  | Objeto        |
<figcaption style="font-size: 15px" align="center">Tabela 27: Léxico 25. (Fonte: Autores, 2022)</figcaption>

### L26 - Pesquisar

| Léxico  | Noção | Impacto | Sinônimo       | Classificação |
| ------- | ----- | ------- | --------       | ------------- |
|Pesquisar|Buscar título ou gênero.|O usuário poderá pesquisar por um título específico.</br>O usuário poderá pesquisar por títulos similares.</br>O usuário poderá pesquisar por um gênero específico.|Buscar, explorar| Verbo         |
<figcaption style="font-size: 15px" align="center">Tabela 28: Léxico 26. (Fonte: Autores, 2022)</figcaption>

### L27 - Tendência

| Léxico  | Noção | Impacto | Sinônimo | Classificação |
| ------  | ----- | ------- | -------- | ------------- |
|Tendência|Categoria que exibe quais as tendência do momento.|O usuário poderá visualizar títulos em tendência no momento.</br>O usuário poderá assistir títulos em tendência no momento.|Em alta   |     Verbo       |
<figcaption style="font-size: 15px" align="center">Tabela 29: Léxico 27. (Fonte: Autores, 2022)</figcaption>

## 4. Bibliografia

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. 1º/2022. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

HABITICA - Gamify your Life. Disponível em: https://requisitos-habitica.netlify.com/. Acesso em: 05 dezembro 2022.

## 5. Histórico de versão

| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 07/12/2022 | Criação dos léxicos | [Josué Teixeira](https://github.com/zjosuez)  | [Gabriel Roger](https://github.com/GabrielRoger07) |
| 1.1 | 08/12/2022 | adiciona novos léxicos; corrige legenda de tabelas; | [Josué Teixeira](https://github.com/zjosuez)  | [Gabriel Roger](https://github.com/GabrielRoger07) |
| 1.2 | 09/12/2022 | correção ortográfica | [Josué Teixeira](https://github.com/zjosuez)  | [Gabriel Roger](https://github.com/GabrielRoger07) |
