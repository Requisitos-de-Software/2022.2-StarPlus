# Cenários

## Introdução
  Um cenário nada mais é do que uma história curta ou uma descrição de como um evento (ou eventos futuros) pode impactar as operações de uma empresa. Cenários são criados tanto para o ambiente interno quanto para o externo (ou seja, para todos os riscos corporativos que impactam uma organização). Os cenários são exemplos da vida real em que o sistema é ou será utilizado. Sendo assim, os cenários podem ser úteis para adicionar detalhes a uma descrição geral de requisito. Trata-se de descrições de iterações do usuário com o sistema. Portanto, cada cenário cobre um pequeno número de interações possíveis e, além disso, diferentes cenários são desenvolvidos, evidenciando diversos tipos de informação em variados níveis de detalhamento sobre o sistema. O objetivo desse artefato é registrar todos os cenários observados.

## Metodologia                               

   Ele descreve uma situação de uso do sistema. Utilizaremos a tabela 1 a seguir como modelo para os cenários representados pelas tabelas 2 a 14. Inclui informações como Nome do Cenário, Ator(es), Pré-condição, Fluxo normal, Fluxos alternativos e Pós-condição. Também é o espaço real ou virtual.

| Modelo |Cenários |
| --------- | -----------|
| Título | Título do Cenário |
| Objetivo |	  Objetivo/meta do cenarios |
| Contexto |      Local, Tempo, Pré-Condição |
| Ator/Atores |      envolvidos |
| Recursos |	 Recursos envolvidos |
| Episódios |	Detalhes do cenários |
| Restrições |	Descrição da retrição |
| Exceção |    	Descrição da exceção |


Tabela 1: Estrutura de um Cenário. Fonte: Thiago Vivan, Abdul Hannan


## Cenários:

### Cenário 1: Criar Conta

|Elementos|Respostas|
|--|--|
| Objetivo | Assinante Star+ poder usar a plataforma |
| Contexto | Local: Página inicial<br>Tempo: 5-10 minutos<br>Pré-Condição: - |
| Atores | Assinante Star+ |
| Recursos | Dispositivo com acesso a internet<br>Forma de pagamento válida<br>Email válido |
| Exceção | Perda da conexão com a internet<br>Dados fornecidos inválidos |
| Episódios | Acessar site ou aplicativo Star+<br>Clicar em Criar conta<br>Preencher os dados necessários<br>Confirmar e-mail |
| Rastreabilidade | RF1 |

Tabela 2: Cenario 1. Fonte: Thiago Vivan, Abdul Hannan


### Cenário 2: Realizar Login
|Elementos|Respostas|
|--|--|
| Objetivo | Assinante Star+ poder fazer login no Star+|
| Contexto |  Local: Tela inicial </br>Tempo: 1-5 minutos</br>Pré Condição: Ter conta ativa no Star+ |
| Atores |   Assinante Star+  |
| Recursos | Computador ou SmartPhone com Internet , Acesso a Star+ |
| Exceção | Sem Internet, Sem Assinatura |
| Episódios | Acessar site ou aplicativo Star+</br>Clicar em Criar conta</br>Preencher os dados necessários</br>Confirmar e-mail |
| Rastreabilidade |RF3|

Tabela 3: Cenario 2. Fonte: Thiago Vivan, Abdul Hannan


### Cenário 3: Cancelar Assinatura
|Elementos|Respostas|
|--|--|
| Objetivo | Não ser mais cliente do serviço|
| Contexto |  Local: Tela de Configurações da Star </br>Tempo: 1-5 minutos</br>Pré Condição: Ter conta ativa no Star , Estar logado  |
| Atores |   Assinante Star+  |
| Recursos | Computador ou SmartPhone com Internet ,Acesso a StarPlus |
| Exceção | Assinante desistir de cancelar a assinatura, Assinante esquecer a senha |
| Episódios |    Clicar em Configurações de conta</br>Clicar em apagar Conta</br>Selecionar motivo</br>Clicar em "tenho certeza" |
| Rastreabilidade |RF3|

Tabela 4: Cenario 3. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 4: Remover titulo
|Elementos|Respostas|
|--|--|
| Objetivo | Remover titulo da Lista |
| Contexto |  Local: página</br>Tempo:30segundos</br>Pré-Condição: estar logado  |
| Atores |   Assinante Star+  |
| Recursos | Computador ou SmartPhone com Internet ,Acesso a StarPlus |
| Exceção | Perda de conexão com a internet |
| Episódios | Na página principal apos login</br>clique em Minha lista e selecione um título </br>E em seguida, selecione a marca de seleção |
| Rastreabilidade |RF8|

Tabela 5: Cenario 4. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 5: Buscar ajuda
|Elementos|Respostas|
|--|--|
| Objetivo | Acessar página de ajuda |
| Contexto |  Local:   Página principal</br>Tempo: 10-30 segundos</br>Pré-Condição: estar logado |
| Atores | Assinante Star+ |
| Recursos | Dispositivo com acesso a internet e compatível com Star+ |
| Exceção | Perda de conexão com a internet |
| Episódios | Acessar Configurações</br>Clicar em Ajuda |
| Rastreabilidade | RF10 |

Tabela 6: Cenario 5. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 6: Passar para o proximo episódio
|Elementos|Respostas|
|--|--|
| Objetivo | Passar para o próximo episódio ainda na reprodução do atual  |
| Contexto | Local: Tela de Reprodução</br>Tempo: 1-10 segundos</br>Pré-Condição: Estar logado</br>Estar assistindo a um título |
| Atores | Assinante Star+ |
| Recursos | Dispositivo com acesso a internet e compatível com Star+</br>Conta Star+ Ativa |
| Exceção | Perda de conexão com a internet |
| Episódios | Clicar em botão de próximo episodio |
| Rastreabilidade | RF11 |

Tabela 7: Cenario 6. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 7: Escolher temporada
|Elementos|Respostas|
|--|--|
| Objetivo | Poder escolher a qual temporada de um titulo assistir |
| Contexto | Local: Página Principal</br>Tempo: 1-2 minutos</br>Pré-Condição: Estar Logado |
| Atores | Assinante Star+ |
| Recursos | Dispositivo com acesso a internet e compatível com Star+</br>Conta Star+ Ativa |
| Exceção | Perda de conexão com a internet |
| Episódios | Clicar no titulo a qual quer assistir |
| Rastreabilidade | RF17 |

Tabela 8: Cenario 7. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 8: Acessar histórico
|Elementos|Respostas|
|--|--|
| Objetivo | Assinante Star+ deseja saber quais títulos já foram assistidos |
| Contexto | Local: Página de Configurações Star+</br>Tempo: 10-30 segundos |
| Atores | Assinante Star+ |
| Recursos | Dispositivo com acesso a internet e compatível com Star+</br>Conta Star+ Ativa |
| Exceção | Perda de conexão com a internet </br>Histórico está vazio |
| Episódios | Clicar em Histórico de Reprodução |
| Rastreabilidade | RF19 |

Tabela 9: Cenario 8. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 9: Realiza busca
|Elementos|Respostas|
|--|--|
| Objetivo | Realizar busca pelo filme/série ou programa no star+ |
| Contexto | Local: Barra de pesquisa na tela principal </br>Tempo:30segundos</br>Pré-Condição: estar logado  |
| Atores | Assinantes Star+ |
| Recursos | Dispositivo com acesso a internet e compatível com Star+ |
| Exceção | Perda de conexão com a internet |
| Episódios | o usuário clica na barra de pesquisa na página principal,</br>o usuário escolhe a opção de digitação ou comando pelo microfone,</br>o usuário clica no botão de pesquisa |
| Rastreabilidade | RF21 |

Tabela 10: Cenario 9. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 10: Adicionar filtro de busca
|Elementos|Respostas|
|--|--|
| Objetivo | Assinante Star+ deseja buscar um título utilizando Filtros |
| Contexto | Local: Barra de pesquisa na tela principal</br>Tempo: 1-3 minutos |
| Atores | Assinante Star+ |
| Recursos | Dispositivo com acesso a internet e compatível com Star+</br>Conta Star+ Ativa |
| Exceção | Perda de conexão com a internet  |
| Episódios |O usuário Clica na barra de pesquisa na página principal</br>O usuário clica em Filtros</br>O usuário seleciona os Filtros desejados</br>O usuário clica em Aplicar filtros |
| Rastreabilidade | RF22 |

Tabela 11: Cenario 10. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 11: Alterar meios de pagamento
|Elementos|Respostas|
|--|--|
| Objetivo | Assinante Star+ Alterar Forma de pagamento cadastrada |
| Contexto | Local: Tela de configurações Star+ </br>Tempo: 3-10 minutos </br>Pré-condição: Usuário ter uma conta na Star+ |
| Atores | Assinante Star+ |
| Recursos | Dispositivo com acesso a internet e compatível com Star+</br>Conta Star+ Ativa |
| Exceção | Perda de conexão com a internet</br>Nova forma de pagamento inválida  |
| Episódios | Clicar no botão Conta Star+</br>Clicar em Assinatura</br>Clicar em Detalhes de Assinatura</br>Inserir novos dados</br>Clicar em Salvar |
| Rastreabilidade | RF23 |

Tabela 12: Cenario 11. Fonte: Thiago Vivan, Abdul Hannan

### Cenário 12: Baixar Título
|Elementos|Respostas|
|--|--|
| Objetivo | Assinante Star+ deseja baixar um titulo para reprodução offline |
| Contexto | Local: Página de informações do Titulo</br>Tempo: 1-30 minutos</br>Pré-Condição: Conta Star+ ativa |
| Atores | Assinante Star+  |
| Recursos |Dispositivo móvel com acesso a internet e compatível com Star+</br>Conta Star+ Ativa |
| Exceção | Perda da conexão com a internet durante o download |
| Episódios | Clicar em Baixar titulo/episodio |
| Rastreabilidade | RF24 |

Tabela 13: Cenario 12. Fonte: Thiago Vivan, Abdul Hannan


### Cenário 13: Mudar idioma, audio,Retirar legenda    
|Elementos|Respostas|
|--|--|
| Objetivo | Mudar idioma, audio,Retirar legenda de um titulo  |
| Contexto | Local:   Durante Assistindo o título</br>Tempo: 1 minuto</br>Pré-Condição:Assistindo título  |
| Atores | assinante |
| Recursos | Dispositivo com acesso a internet e compatível com Star+</br>Conta Star+ Ativa |
| Exceção |  título sem legendas ou sem dublagem idioma  |
| Episódios | Abra o StarPlus.</br>Selecione um programa de TV ou filme.</br>Comece a jogar e execute a ação listada para o seu dispositivo:</br>Na parte superior ou inferior da tela, selecione Áudio e legendas . Nas TVs, as opções de idioma podem aparecer na parte inferior sem o ícone. Você pode escolher entre os idiomas mostrados ou selecionar Outros para ver todas as opções de idioma.</br>Faça alterações nas seleções de áudio ou legenda. |
| Rastreabilidade | RF25,RF28 |

Tabela 14: Cenario 13. Fonte: Thiago Vivan, Abdul Hannan


## 4. Bibliografia

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. 1º/2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## 5. Histórico de versão

| Versão | Data | Descrição | Autor | Revisor |
| :----: | :--: | :-------: | :---: | :-----: |
| 1.0 | 08/12/2022 | Criação dos cenários | [Thiago Vivan Bastos](https://github.com/thiago-vivan)  | [Abdul Hannan](https://github.com/hannanhunny01) |
| 1.1 | 13/12/2022 | correção ortográfica | [Josué Teixeira](https://github.com/zjosuez) | [Thiago Vivan Bastos](https://github.com/thiago-vivan)