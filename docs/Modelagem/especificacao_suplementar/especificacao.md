# Especificação Suplementar

## 1. Introdução
&emsp;&emsp;A Especificação Suplementar é um documento que é feito em linguagem natural, aonde os requisitos não funcionais são descritos. Nesse sentido, juntamente com o Modelo de Casos de Uso, as Especificações Suplementares capturam todos os requisitos de software que precisam ser descritos, para que seja possível servir como uma Especificação de Requisitos De Software.

&emsp;&emsp;A Especificação Suplementar é complementar aos casos de uso, tendo em vista que ela pega os requisitos do sistema que não foram prontamente capturados nos casos de uso do modelo de caso de uso. Assim, é possível citar os seguintes requisitos incluídos:

- Outros requisitos, como aqueles para os sistemas e ambientes operacionais, compatibilidade com outro software e restrições de design.
- Atributos de qualidade do sistema a ser criado, incluindo requisitos de  usabilidade, confiabilidade, desempenho e suportabilidade;
- Requisitos legais e de regulamentação e padrões de aplicativo;

## 2. Metodologia
&emsp;&emsp; Para definir as categorias dos requisitos não funcionais nesse projeto, usaremos a metodologia FURPS+. Esse acrônimo irá descrever as principais categorias de requisitos com subcategotias, a exemplo do que será mostrado a seguir.

### 2.1 F - Funcionality (Funcionalidade)

&emsp;&emsp;Os requisitos funcionais podem incluir:

- Segurança.
- Conjuntos de recursos;
- Recursos;

### 2.2 U - Usability (Usabilidade)
&emsp;&emsp;Os requisitos de utilidade podem incluir:

- Estética
- Fatores humanos
- Assistentes e agentes
- Documentação do usuário
- Materiais de treinamento
- Ajuda on-line e sensível ao contexto
- Consistência na interface com o usuário

### 2.3 R - Reliability (Confiabilidade)
&emsp;&emsp;Os requisitos de confiabilidade podem incluir:

- Tempo médio entre falhas (MTBF)
- Freqüência e gravidade de falhaossibilidade de recuperação
- Previsão
- Precisão

### 2.4 P - Performance (Performance)
&emsp;&emsp;Um requisito de performance ,ou, desempenho, pode incluir:

- Produtividade
- Eficiência
- Disponibilidade
- Tempo de resposta
- Velocidade
- Tempo de recuperação
- Uso de recurso

### 2.5 S - Suportability (Suportabilidade)
&emsp;&emsp;Os requisitos de suportabilidade, que pode ser utilizado em sistemas android a partir da versão 5 e ios a partir da versão 14, podem incluir:

- Possibilidade de instalação
- Possibilidade de localização (internacionalização)
- Possibilidade de teste
- Possibilidade de serviço
- Extensibilidade
- Compatibilidade
- Possibilidade de configuração
- Possibilidade de adaptação
- Possibilidade de manutenção

### 2.6 +
&emsp;&emsp;O "+" em FURPS+ é para lembrá-lo de incluir requisitos como:

- Requisitos de Design
    - Frequentemente chamado de restrição de design, especifica ou restringe o design de um sistema. 
- Requisitos de implementação
    - Um requisito de implementação especifica ou restringe o código ou a construção de um sistema.
- Requisitos de interface
    - Um requisito de interface especifica: 
        - Um item externo com o qual o sistema deve interagir 
        - Restrições de formatos, tempos ou outros fatores utilizados por tal interação 
- Requisitos físicos
    - Esse tipo de requisito pode ser utilizado para representar requisitos de hardware, como as configurações físicas de rede obrigatórias.

## 3. Resultado
&emsp;&emsp; Tendo como base os requisitos não funcionais levantados na fase de elicitação de requisitos, chegamos nos seguintes resultados:

Fonte: João

<center>

| Sigla | Categoria | Requisitos                                      |
|:------: | :------: | :--------------------------------------------------: |
| F | Funcionalidade   | RNF1 (técnica: brainstorm), RNF3 (técnica: brainstorm), RNF5 (técnica: brainstorm), RNF9 (técnica: introspecção)|
| U | Usabilidade | RNF4 (técnicas: brainstorm, questionário) 
| R | Confiabilidade | - |
| P | Performance | RNF6 (técnicas: observação e brainstorm), RNF8 (técnica: introspecção)|
| S | Suportabilidade | RNF2 (técnicas: brainstorm, introspecção e questionário) |
| + | Outros | RNF7 (técnicas: observação e questionário) |

<figcaption>Tabela 1: Categorização dos requisitos não funcionais pelo modelo FURPS+</figcaption>

</center>

## 4. Referências

> - https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/concepts/requirements_62E28784.html
> - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13;
> - https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html

## 5. Histórico de versão

| Versão | Data       | Descrição                      | Autor        |Revisor        |
| ------ | ---------- | ------------------------------ | ------------ |------------ |
| 0.1    | 06/12/2022 | Criação do documento | João Pedro de Camargo Vaz | Vinicius  |
