20/08/2026 - Introdução à Análise e Projeto de Sistemas de Informação

Conceitos e elementos fundamentais da engenharia de software - definição, características e tipos de
modelagens. Ferramentas Case de apoio ao desenho dos diagramas UML

# Ficha de Requisitos — Aula 02

**Análise e Projeto de Sistemas — Unidade II**

---

## 2. Requisitos Funcionais

| Campo | Descrição |
|---|---|
| **Identificação** | RF01 — Cadastrar usuário |
| **Descrição** | O sistema deve permitir que o bibliotecário cadastre usuários da biblioteca. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Permitir nome, matrícula, e-mail e telefone; impedir cadastro sem nome e matrícula; confirmar cadastro. |
| **Exemplo** | Bibliotecário informa os dados do aluno e seleciona Cadastrar. |

### RF02 — Cadastrar livro

| Campo | Descrição |
|---|---|
| **Identificação** | RF02 — Cadastrar livro |
| **Descrição** | O sistema deve permitir cadastrar livros disponíveis na biblioteca. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Permitir título, autor, ISBN e quantidade; impedir título vazio; confirmar cadastro. |
| **Exemplo** | Bibliotecário cadastra um livro e seus dados. |

### RF03 — Realizar empréstimo

| Campo | Descrição |
|---|---|
| **Identificação** | RF03 — Realizar empréstimo |
| **Descrição** | O sistema deve permitir registrar o empréstimo de um livro para usuário habilitado. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Verificar usuário, disponibilidade, registrar datas e atualizar quantidade. |
| **Exemplo** | Bibliotecário seleciona aluno e livro e registra o empréstimo. |

### RF04 — Registrar devolução

| Campo | Descrição |
|---|---|
| **Identificação** | RF04 — Registrar devolução |
| **Descrição** | O sistema deve permitir registrar a devolução de um livro emprestado. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Localizar empréstimo, registrar devolução, atualizar disponibilidade e verificar atraso. |
| **Exemplo** | Bibliotecário registra a devolução e o sistema atualiza o estoque. |

### RF05 — Calcular multa

| Campo | Descrição |
|---|---|
| **Identificação** | RF05 — Calcular multa |
| **Descrição** | O sistema deve calcular multa quando houver devolução após o prazo. |
| **Prioridade** | Média |
| **Critérios de aceitação** | Comparar datas, calcular valor segundo regra definida e registrar multa. |
| **Exemplo** | Devolução atrasada gera cálculo de multa. |

### RF06 — Consultar disponibilidade

| Campo | Descrição |
|---|---|
| **Identificação** | RF06 — Consultar disponibilidade |
| **Descrição** | O sistema deve permitir consultar se determinado livro está disponível. |
| **Prioridade** | Média |
| **Critérios de aceitação** | Pesquisar por título, autor ou ISBN e informar quantidade disponível. |
| **Exemplo** | Pesquisa retorna dois exemplares disponíveis. |

---

## 3. Requisitos Não Funcionais

| Campo | Descrição |
|---|---|
| **Identificação** | RNF01 — Segurança |
| **Descrição** | Controlar acesso conforme perfil. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Autenticação e autorização para funções restritas. |
| **Exemplo** | Aluno não acessa cadastro de livros. |

### RNF02 — Usabilidade

| Campo | Descrição |
|---|---|
| **Identificação** | RNF02 — Usabilidade |
| **Descrição** | Interface clara e consistente. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Rótulos claros, mensagens orientativas e ações identificáveis. |
| **Exemplo** | Campo obrigatório vazio gera orientação. |

### RNF03 — Desempenho

| Campo | Descrição |
|---|---|
| **Identificação** | RNF03 — Desempenho |
| **Descrição** | Consultas comuns devem responder em tempo adequado. |
| **Prioridade** | Média |
| **Critérios de aceitação** | Consultas simples em até 3 segundos em condições normais. |
| **Exemplo** | Pesquisa de livro retorna em até 3 segundos. |

### RNF04 — Disponibilidade

| Campo | Descrição |
|---|---|
| **Identificação** | RNF04 — Disponibilidade |
| **Descrição** | Disponível durante o horário da biblioteca. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Acessível no horário definido, salvo manutenção programada. |
| **Exemplo** | Bibliotecário realiza empréstimos durante o atendimento. |

### RNF05 — Integridade dos dados

| Campo | Descrição |
|---|---|
| **Identificação** | RNF05 — Integridade dos dados |
| **Descrição** | Preservar consistência dos dados. |
| **Prioridade** | Alta |
| **Critérios de aceitação** | Bloquear livro inexistente, quantidade negativa e associações inválidas. |
| **Exemplo** | Empréstimo sem estoque é bloqueado. |

---

## 4. Modelo para preenchimento

| Campo | Requisito Funcional | Requisito Não Funcional |
|---|---|---|
| **Identificação** | RF__ | RNF__ |
| **Descrição** | | |
| **Prioridade** | Alta / Média / Baixa | Alta / Média / Baixa |
| **Critérios de aceitação** | | |
| **Exemplo** | | |

---

## 5. Orientações

Um bom requisito deve ser **claro, específico, verificável e relevante**.

O grupo deve verificar:

- Identificação
- Descrição
- Prioridade
- Critérios de aceitação
- Exemplo

---

## 6. Entregável

Entregar:

- A identificação do sistema
- Pelo menos **5 requisitos funcionais**
- Pelo menos **3 requisitos não funcionais**
- Prioridade
- Critérios de aceitação
- Exemplos
- Identificação dos integrantes
