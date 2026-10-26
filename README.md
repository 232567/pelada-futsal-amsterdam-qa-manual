# ⚽ Pelada Futsal Amsterdam — Projeto de QA Manual

## 📌 Sobre o projeto

Este repositório apresenta um projeto prático de **Quality Assurance (QA Manual)**, desenvolvido para aplicar conhecimentos de planejamento, documentação e organização de testes funcionais.

O projeto utiliza como cenário um sistema de inscrições para partidas de futsal, denominado **Pelada Futsal Amsterdam**.

O objetivo é simular atividades realizadas por um **Analista de QA Manual Júnior**, utilizando ferramentas e práticas empregadas no desenvolvimento de software.

> **Importante:** Este é um projeto de estudo. Os casos de teste foram documentados, mas ainda não foram executados em uma aplicação real.

## 🎯 Objetivos

- Compreender o processo de testes manuais funcionais.
- Documentar histórias de usuário e critérios de aceitação.
- Elaborar casos de teste positivos e negativos.
- Planejar a execução de testes.
- Criar cenários BDD utilizando Gherkin.
- Compreender o ciclo de vida de defeitos.
- Organizar a documentação utilizando Jira, Confluence e GitHub.

## 🛠️ Ferramentas utilizadas

| Ferramenta | Finalidade |
|---|---|
| Jira | Organização da história de usuário e dos casos de teste |
| Confluence | Documentação do plano de testes e dos cenários BDD |
| GitHub | Organização e apresentação do projeto |
| Markdown | Documentação do repositório |
| Gherkin | Descrição de cenários BDD |

## 📋 História de usuário

**Identificação:** PFA-1

**Título:** Jogador pode realizar sua inscrição na pelada.

Como jogador, desejo realizar minha inscrição em uma partida de futsal para participar dos jogos organizados.

### Regras de negócio consideradas

- O nome do jogador é obrigatório.
- A posição do jogador deve ser informada.
- O nível de jogabilidade permitido é de 6 a 8.
- A fotografia é opcional.
- O limite é de 12 jogadores de linha.
- O limite é de 2 goleiros.
- Os goleiros não precisam realizar pagamento.
- Os jogadores de linha precisam pagar para confirmar a inscrição.
- As inscrições devem respeitar os períodos de abertura e encerramento.
- O sistema deve impedir novas inscrições quando as vagas estiverem esgotadas.

## 🧪 Casos de teste

Foram documentados **16 casos de teste funcionais** no Jira.

| ID | Identificação Jira | Descrição |
|---|---|---|
| CT-001 | PFA-2 | Validar inscrição com dados válidos |
| CT-002 | PFA-3 | Validar inscrição sem informar o nome |
| CT-003 | PFA-4 | Validar seleção da posição do jogador |
| CT-004 | PFA-5 | Validar nível de jogabilidade permitido |
| CT-005 | PFA-6 | Validar
## 📚 Documentação do Projeto

A documentação do projeto Pelada Futsal Amsterdam foi organizada utilizando Jira e Confluence.

### 📋 Documentos disponíveis

- **Plano de Testes:** objetivos, escopo, estratégia e critérios de execução.
- **Cenários BDD:** dois cenários escritos em Gherkin, contemplando testes positivos e negativos.
- **Ciclo de Vida de um Defeito:** etapas de identificação, registro, correção e reteste, incluindo um exemplo hipotético.
- **Casos de Teste:** 16 casos de teste funcionais documentados no Jira.

### 🔗 Links da documentação

- [Plano de Testes](https://jeversonborges.atlassian.net/wiki/spaces/PFAQM/pages/17760257)
- [Cenários de Teste BDD](https://jeversonborges.atlassian.net/wiki/spaces/PFAQM/pages/17858563)
- [Ciclo de Vida de um Defeito](https://jeversonborges.atlassian.net/wiki/spaces/PFAQM/pages/17662179)
- [História de Usuário PFA-1](https://jeversonborges.atlassian.net/browse/PFA-1)

### 📊 Status do projeto

- Casos de teste documentados: **16**
- Cenários BDD documentados: **2**
- Casos executados: **0**
- Status: **Documentação concluída; execução pendente**

> Este projeto tem finalidade educacional. Os testes ainda não foram executados em uma aplicação real.
