# Backlog - Life Tracker

## Visão Geral

Objetivo do MVP:

Permitir que um usuário acompanhe hábitos e metas pessoais através de uma aplicação web com autenticação própria.

---

# Sprint 0 - Infraestrutura

Status: ✅ Concluída

## Entregas

- [x] Repositório GitHub criado
- [x] GitHub Codespaces configurado
- [x] Projeto Spring Boot criado
- [x] PostgreSQL configurado via Docker Compose
- [x] Flyway configurado
- [x] Aplicação inicial funcionando
- [x] Primeiro commit realizado

---

# Sprint 1 - Usuários e Autenticação

Status: 🔄 Planejada

## História LT-001

Como visitante,
quero criar uma conta,
para acessar o sistema.

### Critérios de Aceite

- Usuário deve informar nome.
- Usuário deve informar e-mail.
- Usuário deve informar senha.
- E-mail deve ser único.
- Senha deve ser armazenada criptografada.

---

## História LT-002

Como usuário,
quero realizar login,
para acessar minhas informações.

### Critérios de Aceite

- Login por e-mail e senha.
- Retorno de token JWT.
- Credenciais inválidas devem ser rejeitadas.

---

# Sprint 2 - Hábitos

Status: 📋 Futura

## História LT-003

Como usuário,
quero cadastrar um hábito,
para acompanhar meu desenvolvimento.

### Critérios de Aceite

- Informar nome do hábito.
- Informar descrição opcional.
- Hábito deve ficar vinculado ao usuário.

---

## História LT-004

Como usuário,
quero editar um hábito,
para manter minhas informações atualizadas.

---

## História LT-005

Como usuário,
quero desativar um hábito,
para não utilizá-lo mais.

---

## História LT-006

Como usuário,
quero visualizar meus hábitos,
para acompanhar minha rotina.

---

# Sprint 3 - Registros Diários

Status: 📋 Futura

## História LT-007

Como usuário,
quero registrar a conclusão de um hábito,
para acompanhar minha evolução diária.

---

## História LT-008

Como usuário,
quero visualizar meu histórico de registros,
para acompanhar meu progresso.

---

# Sprint 4 - Metas

Status: 📋 Futura

## História LT-009

Como usuário,
quero criar metas pessoais,
para organizar meus objetivos.

---

## História LT-010

Como usuário,
quero acompanhar o progresso de uma meta,
para saber o quanto falta para concluí-la.

---

# Sprint 5 - Dashboard

Status: 📋 Futura

## História LT-011

Como usuário,
quero visualizar um resumo das minhas atividades,
para acompanhar minha evolução.

### Indicadores

- Hábitos concluídos hoje.
- Sequência atual.
- Metas ativas.
- Progresso geral.

# Ideias Futuras (Fora do MVP)

- Controle financeiro
- Controle de estudos
- Controle de candidaturas
- Dashboard avançado
- Notificações
- Integração com calendário