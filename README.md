# Nome do Projeto

#### Nome do Microsserviço

Introdução que explique o sentido da existência deste microsserviço. Algo curto e preciso.

##### Índice

1. [ Rodando Projeto; ](#1-rodando-projeto-localmente)
2. [ Rotina de Trabalho; ](#2-rotina-de-trabalho)
3. [ Correndo os Testes; ](#3-correndo-os-testes-no-postman)
4. [ Funcionalidades; ](#4-funcionalidades)
5. [ Outras Informações; e ](#5-outras-informações)
6. [ Arquitetura. ](#6-arquitetura)

### 1. Rodando Projeto Localmente

##### 1.1. Tenha Instalado

Aqui liste tudo o que deve ser instalado para que o projeto funcione. Ex.:

* [Java JDK 11+](https://openjdk.java.net/projects/jdk/15/);
* [Maven](https://maven.apache.org/download.cgi); e
* [Docker](https://www.docker.com/products/docker-desktop/).

##### 1.2. Passo-a-Passo

Aqui, em uma sequência de passos, demonstre como rodar o projeto. Ex.:

1. Clone o projeto;
2. Através do terminal entre na pasta do projeto;
3. Compile o Maven;
4. Abra sua IDE favorita, importe o projeto e o execute normalmente.

```sh
1. git clone <url_do_projeto>
2. cd <nome_da_pasta>
3. mvn package -U
```

### 2. Rotina de Trabalho

- Sempre criar branch para os novos desenvolvimento;
- Sempre efetuar comitts periódicos e com mensagens relevantes;
- Sempre verificar se está **TUDO** funcionando;
- Periodicamente Atualizar o projeto com o comando `git pull`;
- Mesclar com a branch `master` somente ao final do desenvolvimento; e
- Sempre faça testes e salve a versão mais atualizada para os colegas usarem.

### 3. Correndo os Testes

Aqui explique como rodar testes. Mesmo que sejam manuais (como testes realizados através do postman, por exemplo), devem haver orientações de como realizar os testes.
Neste caso também deve haver um arquivo exemplo com um exemplo de requisição para cada funcionalidade existente na api.
Este arquivo deve ser posicionado dentro da pasta "external_utils".

### 4. Funcionalidades

Aqui liste todas as funcionalidades contidas no microsserviço (para aplicações grandes/monolitos, recomendo tirar esta seção... ficará enorme e inútil, pois será difícil encontrar qualquer informação útil em uma lista com dezenas de itens)

- [x] Funcionalidade 1
- [x] Funcionalidade 2
- [ ] Funcionalidade 3

### 5. Outras Informações

Aqui devem ser dadas todas as informações complementares necessárias para a compreensão do projeto. Por exemplo:

Todas as classes de resposta da API devem obedecer padrão X.

As variáveis devem ser escritas em camelCase.

A funcionalidade X não pôde obedecer ao padrão Y por motivo Z.


### 6. Arquitetura

##### 6.1 Apresentação

Apresentação específica deste microsserviço. Esta seção deve ser constituída por um diagrama que represente bem o que é o serviço e um texto que o explique.


![Diagrama de Sequência](external_utils/Sequence%20Diagram.png)

##### 6.2 Diagrama de Contexto

Apresentação do que é microsserviço dentro do contexto geral do projeto.
Esta seção deve ser constituída por um diagrama que represente bem o que é o serviço e um texto que o explique.


![Diagrama de Contexto](external_utils/NBC%20-%20Visão%20Geral.png)

