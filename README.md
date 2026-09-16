# QA Test Strategy — E-commerce

Projeto de Quality Assurance desenvolvido para demonstrar, de forma prática e documentada, a aplicação de técnicas de **análise, planejamento e estratégia de testes** em um contexto de e-commerce.

O projeto utiliza uma aplicação Web de terceiros como **System Under Test (SUT)** e tem como objetivo demonstrar o processo de QA desde a análise do produto até a definição dos cenários, casos de teste, riscos e estratégias de execução.

---

## 🎯 Objetivo

Demonstrar a aplicação prática de um processo de Quality Assurance baseado em:

* análise de requisitos;
* critérios de aceitação;
* identificação de regras de negócio;
* análise de riscos;
* definição de escopo;
* elaboração do mapa de testes;
* definição de cenários;
* elaboração de casos de teste;
* definição de massa de dados;
* estratégia de execução;
* identificação de candidatos à automação;
* registro de defeitos;
* evidências;
* análise dos resultados.

A proposta é demonstrar **como as decisões de teste são construídas antes da implementação da automação**.

---

## 🛒 Aplicação de referência

### Sauce Demo / Swag Labs

A aplicação Web utilizada como referência neste projeto é a **Sauce Demo**, uma aplicação de demonstração baseada no domínio de e-commerce.

A aplicação é de terceiros e **não foi desenvolvida por Rodrigo Cardoso**.

Ela será utilizada exclusivamente como **sistema sob teste (SUT)** para a realização das análises e demonstrações de Quality Assurance deste portfólio.

> A aplicação utilizada neste projeto é de terceiros e foi selecionada como aplicação de referência para demonstrar, de forma prática, conhecimentos e experiência em Quality Assurance, testes e automação.

---

## 🔎 Abordagem

A estratégia será construída progressivamente a partir da análise da aplicação.

```text
Aplicação
    ↓
Requisitos
    ↓
Critérios de aceitação
    ↓
Regras de negócio
    ↓
Análise de riscos
    ↓
Escopo de testes
    ↓
Mapa de testes
    ↓
Cenários
    ↓
Casos de teste
    ↓
Massa de dados
    ↓
Execução
    ↓
Defeitos
    ↓
Evidências
    ↓
Relatório
    ↓
Candidatos à automação
```

A automação não será definida previamente.

Os cenários candidatos à automação serão identificados a partir da estratégia e posteriormente poderão ser implementados utilizando diferentes tecnologias.

---

## 📋 Escopo

O escopo será definido durante a análise da aplicação e poderá contemplar funcionalidades relacionadas ao fluxo de e-commerce, como:

* Login;
* Produtos;
* Busca e ordenação;
* Carrinho;
* Checkout;
* Pedidos;
* Navegação;
* Outras funcionalidades identificadas durante a análise.

A inclusão de cada funcionalidade no escopo será baseada na análise realizada durante o projeto.

---

## ⚠️ Riscos

A identificação e classificação dos riscos será realizada durante a análise do produto.

Os riscos identificados serão utilizados como um dos critérios para:

* definição de prioridades;
* seleção de cenários;
* profundidade dos testes;
* necessidade de testes negativos;
* identificação de candidatos à automação.

---

## 🧪 Estratégia de testes

A estratégia poderá contemplar diferentes abordagens de validação, de acordo com os riscos e objetivos identificados.

Entre elas:

* testes funcionais;
* testes positivos;
* testes negativos;
* testes exploratórios;
* testes de regressão;
* testes de integração, quando aplicável;
* testes de API, quando aplicável;
* automação Web;
* execução manual;
* validação de regras de negócio.

A definição final será feita após a análise do produto.

---

## 🔗 Projetos relacionados

Este projeto faz parte de um portfólio integrado de Quality Assurance.

A estratégia desenvolvida aqui servirá como referência para a evolução dos projetos de automação e testes existentes no portfólio.

### 🌐 Automação Web — Cypress

[QA Automation Cypress](https://github.com/Rodrigopca42/qa-automation-cypress)

Projeto de automação Web utilizando Cypress.

### 🔌 API Testing — Postman

[QA API Testing — Postman](https://github.com/Rodrigopca42/qa-api-testing-postman)

Projeto de testes de API utilizando Postman.

### 🐍 Automação Web — Python / Selenium / Pytest

[Estudo Automacao Python](https://github.com/Rodrigopca42/Estudo_Automacao_Python)

Projeto de automação Web utilizando Python, Selenium e Pytest.

> Os projetos relacionados poderão ser posteriormente ajustados para refletir os cenários, riscos e decisões definidos nesta estratégia de testes.

---

## 🔄 Relação entre os projetos

```text
                     QA TEST STRATEGY
                            │
                            ▼
                  Requisitos / Regras
                            │
                            ▼
                       Riscos
                            │
                            ▼
                   Cenários de teste
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
          Selenium       Postman       Cypress
           Python          API           E2E
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                          CI/CD
```

A estratégia de testes representa a **origem do raciocínio de QA**.

As diferentes tecnologias serão utilizadas posteriormente de acordo com os objetivos e cenários definidos para cada abordagem.

---

## 📁 Estrutura do projeto

A estrutura do repositório será construída progressivamente conforme a estratégia for desenvolvida.

```text
qa-test-strategy-ecommerce/
│
├── README.md
│
├── documentation/
│
├── test-cases/
│
├── bdd/
│
├── defects/
│
└── evidence/
```

As pastas serão preenchidas conforme cada etapa do projeto for concluída.

---

## 📌 Transparência e autoria

### Recursos de terceiros

Este projeto utiliza recursos externos, incluindo:

* aplicação Web;
* ferramentas;
* bibliotecas;
* APIs, quando utilizadas;
* outros materiais externos eventualmente necessários.

Cada recurso externo será identificado e, quando aplicável, acompanhado das respectivas informações de utilização.

### Trabalho desenvolvido neste projeto

O trabalho de QA apresentado no repositório compreende:

* análise;
* estratégia;
* identificação de requisitos;
* regras de negócio;
* análise de riscos;
* cenários;
* casos de teste;
* documentação;
* execução;
* evidências;
* análise dos resultados;
* automação eventualmente derivada da estratégia.

Nenhum recurso de terceiros será apresentado como sendo de autoria própria.

---

## ✅ Definition of Done

Um projeto de QA não será considerado concluído apenas porque os testes foram executados.

A estratégia deverá permitir responder:

* O que foi testado?
* Por que foi testado?
* Qual era o risco?
* Quais cenários foram definidos?
* Como foram executados?
* Qual abordagem foi utilizada?
* Qual foi o resultado?
* Existem evidências?
* Existem registros dos defeitos encontrados?
* A documentação permite que outra pessoa compreenda o trabalho realizado?

---

## 🚧 Status do projeto

**Em desenvolvimento**

O projeto será construído progressivamente, começando pela análise da aplicação de referência e evoluindo até a definição da estratégia de testes.

---

## 👤 Autor

**Rodrigo Cardoso**

QA Analyst | Quality Assurance | Testes | Automação

Este repositório faz parte de um portfólio pessoal desenvolvido para demonstrar conhecimentos e práticas de Quality Assurance.
