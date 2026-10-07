# Life Tracker

Sistema para acompanhamento de hábitos, metas e evolução pessoal.

## Objetivo

O Life Tracker tem como objetivo ajudar usuários a registrar hábitos, acompanhar metas pessoais e visualizar sua evolução ao longo do tempo.

## Tecnologias

- Java 21
- Spring Boot 4.1.1
- Spring Security
- Spring Data JPA
- PostgreSQL
- Flyway
- Maven

## Status do Projeto

🚧 Em desenvolvimento

## Primeira Versão (MVP)

- Cadastro de usuários
- Autenticação JWT
- Gerenciamento de hábitos
- Registro diário de hábitos
- Gerenciamento de metas
- Dashboard simples de acompanhamento

## Decisões Arquiteturais

### ADR-001 — Desenvolvimento em GitHub Codespaces

**Contexto**

Necessidade de desenvolver em diferentes computadores, inclusive ambientes sem permissão para instalação de software.

**Decisão**

Utilizar GitHub Codespaces como ambiente principal de desenvolvimento.

**Consequências**

- Ambiente padronizado.
- Desenvolvimento acessível de qualquer lugar.
- Menor dependência da máquina local.
- Necessidade de conexão com internet.

---

### ADR-002 — PostgreSQL via Docker Compose

**Contexto**

O projeto utiliza PostgreSQL e será desenvolvido em diferentes ambientes, incluindo GitHub Codespaces.

**Decisão**

Executar o banco de dados PostgreSQL através de Docker Compose.

**Consequências**

- Ambiente reproduzível.
- Inicialização simplificada do banco.
- Menor dependência de instalações locais.
- Necessidade de Docker disponível.