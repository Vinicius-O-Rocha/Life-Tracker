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