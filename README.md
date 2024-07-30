**Controle de Oficina**

*versão 1.0*

## Histórico das alterações

   Data    | Versão |    Descrição   | Autor(a)
-----------|--------|----------------|-----------------
03/07/2023 |  1.0   | Release inicial | Pedro H Sassi


## 1 - Introdução

O controle de qualidade de software é uma etapa fundamental no ciclo de vida de desenvolvimento de qualquer aplicação. Garantir que o software funcione corretamente e atenda às expectativas dos usuários é vital para o sucesso do produto. Este documento de plano de testes tem como objetivo principal delinear as estratégias e abordagens a serem adotadas para testar o sistema "Controle de Oficina", assegurando que todos os requisitos funcionais e não funcionais sejam atendidos de maneira eficaz.

O sistema "Controle de Oficina" é uma aplicação desenvolvida para gerenciar o fluxo de trabalho em uma oficina mecânica, abrangendo desde o cadastro de clientes e veículos até o controle de estoque de peças e a gestão dos serviços prestados. Devido à complexidade e à criticidade das funcionalidades envolvidas, é imprescindível que o sistema seja rigorosamente testado em todos os seus aspectos para evitar falhas que possam comprometer a operação da oficina.

Este plano de testes visa definir de maneira clara e detalhada os requisitos a serem verificados, os tipos de testes a serem realizados, os recursos necessários e o cronograma de execução dos testes. Assim, pretende-se proporcionar uma visão abrangente do processo de testes, facilitando a identificação e correção de eventuais problemas antes do lançamento do sistema.

Os testes serão conduzidos de forma meticulosa, utilizando técnicas manuais e automáticas, com foco tanto em testes de caixa branca quanto de caixa preta. As etapas de teste incluirão desde a verificação de métodos de classe individuais até testes de integração de componentes, persistência de dados, tempo de resposta, animações e efeitos sonoros.

Em suma, este documento é uma peça-chave para garantir a qualidade do sistema "Controle de Oficina", proporcionando uma base sólida para a execução de testes eficazes e eficientes, e assegurando que o produto final atenda aos padrões de qualidade esperados pelos usuários finais.

## 2 - Requisitos a Testar

### Casos de uso:

Identificador do caso de uso | Nome do caso de uso
-----------------------------|---------------------
UC1                          | Cadastro de Clientes
UC2                          | Controle de Peças
UC3                          | Cadastro de Serviços
UC4                          | Controle de Atendimentos

### Requisitos não-funcionais:

Identificador do requisito   | Nome do requisito
-----------------------------|---------------------
RNF1                         | Performance
RNF2                         | Segurança
RNF3                         | Usabilidade

## 3 - Tipos de teste

- Teste de interface de usuário;
- Teste de performance;
- Teste de carga;
- Teste de stress;
- Teste de segurança e controle de acesso;
- Teste de instalação;
- Entre outros.

### 3.1 - Métodos da Classe 

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar a funcionalidade e retorno esperado de cada método da classe.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.2 - Persistência de Dados

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se dados são mantidos após súbito desligamento do programa.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.3 - Integração dos Componentes

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar a integração e comunicação entre diferentes componentes do sistema.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.4 - Tempo de Resposta

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se o tempo de resposta das funcionalidades está dentro do esperado.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação (x)
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.5 - Animação

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se as animações são disparadas corretamente e seguem uma sequência lógica.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.6 - Efeitos Sonoros

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se os efeitos sonoros são disparados corretamente e seguem uma sequência lógica.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

## 4 - Recursos

### 4.1 - Ambiente de teste - Software e Hardware

- Hardware: Computadores com configurações mínimas de 8GB de RAM, processador i5, SSD de 256GB.
- Software: 
  - Sistema Operacional: Windows 10 ou superior
  - IDE: Visual Studio Code
  - Browsers: Google Chrome, Mozilla Firefox
  - Servidor Web: Node.js
  - Emuladores: Android Studio, Xcode (para testes em dispositivos móveis)
  - Banco de Dados: SQLite

### 4.2 - Ferramenta de teste

- Ferramentas de Automação: 
  - Selenium
  - Appium
- Ferramentas de Gerenciamento de Testes: 
  - JIRA
  - TestRail

## 5 - Cronograma

Tipo de teste      | Duração | data de início | data de término
-------------------|---------|----------------|-----------------
planejar teste     | 1 semana| 01/08/2024     | 07/08/2024
projetar teste     | 2 semanas| 08/08/2024    | 21/08/2024
implementar teste  | 2 semanas| 22/08/2024    | 04/09/2024
executar teste     | 2 semanas| 05/09/2024    | 18/09/2024
avaliar teste      | 1 semana| 19/09/2024    | 25/09/2024