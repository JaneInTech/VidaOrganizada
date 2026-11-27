# VidaOrganizada API

## Sobre o projeto

O **VidaOrganizada API** é uma aplicação backend desenvolvida em Java com o objetivo de auxiliar na organização pessoal e financeira.

O projeto está sendo desenvolvido como parte de um processo de aprendizagem prática, aplicando conceitos de Programação Orientada a Objetos (POO), desenvolvimento de APIs REST, organização de código e integração com banco de dados.

## Objetivos do projeto

Desenvolver uma API REST que permita organizar diferentes áreas da vida cotidiana, centralizando informações sobre despesas, tarefas e compras.

## Funcionalidades planejadas

### 1. Despesas
- Cadastrar despesas.
- Consultar despesas.
- Atualizar informações.
- Excluir despesas.
- Organizar despesas por categoria.

### 2. Tarefas
- Cadastrar tarefas.
- Consultar tarefas.
- Atualizar tarefas.
- Excluir tarefas.
- Organizar tarefas por status.

### 3. Compras
- Criar listas de compras.
- Adicionar produtos.
- Consultar itens.
- Atualizar informações.
- Remover produtos.

## Tecnologias utilizadas

- Java
- Spring Boot
- Maven
- Git
- GitHub
- IntelliJ IDEA

## Estrutura do projeto

O projeto está organizado em módulos, utilizando separação de responsabilidades para facilitar a manutenção e evolução da aplicação.

```text
src/
├── main/
│   ├── java/
│   │   └── br/com/vidaorganizada/
│   │       ├── VidaOrganizadaApplication.java
│   │       ├── config/
│   │       ├── despesas/
│   │       │   ├── controller/
│   │       │   ├── service/
│   │       │   ├── repository/
│   │       │   ├── model/
│   │       │   └── dto/
│   │       ├── tarefas/
│   │       │   ├── controller/
│   │       │   ├── service/
│   │       │   ├── repository/
│   │       │   ├── model/
│   │       │   └── dto/
│   │       ├── compras/
│   │       │   ├── controller/
│   │       │   ├── service/
│   │       │   ├── repository/
│   │       │   ├── model/
│   │       │   └── dto/
│   │       └── shared/
│   └── resources/
│       └── application.properties
│
└── test/
    └── java/
        └── br/com/vidaorganizada/
```

## Pré-requisitos

Para executar o projeto, é necessário ter:

- Java instalado e configurado.
- IntelliJ IDEA ou outra IDE compatível.
- Git instalado (para versionamento e acesso ao repositório).

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acessar a pasta do projeto

```bash
cd vida-organizada-api
```

### 3. Compilar o projeto

No Windows, execute:

```powershell
.\mvnw.cmd clean compile
```

### 4. Executar os testes

```powershell
.\mvnw.cmd test
```

### 5. Iniciar a aplicação

```powershell
.\mvnw.cmd spring-boot:run
```

## Testes

Os testes automatizados serão organizados dentro de `src/test/java`, acompanhando a estrutura dos módulos da aplicação.

O objetivo é verificar o funcionamento das funcionalidades e garantir a qualidade do código durante o desenvolvimento.

## Status do projeto

🚧 **Em desenvolvimento.**

A estrutura inicial está sendo organizada e as funcionalidades serão implementadas gradualmente.

## Versionamento

O projeto utiliza Git para controle de versões e GitHub para hospedagem do código-fonte e acompanhamento da evolução do desenvolvimento.

## Autora

Desenvolvido por **Jane**, estudante de Análise e Desenvolvimento de Sistemas, como projeto de aprendizagem prática em desenvolvimento backend com Java.