# Olá, sou a Isabelle! 👋

Estudante de **Análise e Desenvolvimento de Sistemas (ADS)** com foco em **Engenharia de Dados (ETL/ELT) e Desenvolvimento de Software**. 

Minha trajetória é dedicada à construção de **pipelines de dados resilientes, arquitetura modular, camadas de qualidade de dados (Data Quality)** e sistemas back-end com código limpo e tratamento defensivo de exceções.

---

## 🛠️ Conhecimentos e Tecnologias

- **Linguagens & Back-End:** Python 3.10+ (Programação Modular, Type Hints, Tratamento Defensivo de Exceções, Manipulação de Estruturas de Dados).
- **Engenharia de Dados & Pipelines:** Pipelines ETL End-to-End, Ingestão Resiliente, Sanitização/Higienização de Bases, Regras de Negócio e Segregação de Quarentena.
- **Bancos de Dados:** SQL (PostgreSQL), Modelagem de Dados, Consultas e Manipulação de Tabelas.
- **Testes & Ferramentas:** Pytest (Testes Unitários Automatizados), Git, GitHub, VS Code.

---

## 📌 Projetos em Destaque

### 🚚 [Logistics Data Pipeline (ETL & Data Quality)](https://github.com/isa-amorim/pipeline-logistica)
> **Stack:** Python 3.10+ | Pytest | Arquitetura Modular | Data Quality | Pipeline ETL
- **O Problema Solucionado:** Ingestão de dados brutos corrompidos (documentos inválidos, CEPs mal formatados e fretes negativos) de sistemas legados.
- **Destaques de Engenharia:** 
  - Construção de um pipeline ETL do zero utilizando a biblioteca padrão do Python (`csv`, `pathlib`, `typing`), garantindo alta performance e zero dependências pesadas.
  - Hierarquia de exceções de domínio customizadas (`ValidationError`, `PipelineError`) com rastreamento da linha física do arquivo e campo afetado.
  - Arquitetura desacoplada em módulos (`ingestao`, `transformacao`, `armazenamento`).
  - Segregação de dados em **Processed** (prontos para consumo) e **Quarantine** (relatório detalhado de auditabilidade de erros).
  - Cobertura de testes unitários automatizados desenvolvidos com `Pytest`.

---

### 💰 [Gerenciador Financeiro CLI](https://github.com/isa-amorim/gerenciador-financeiro-cli)
> **Stack:** Python 3.10 | Desenvolvimento CLI | Tratamento Defensivo | Lógica Financeira
- **O Problema Solucionado:** Organização do fluxo de caixa pessoal com controle de erros em tempo de execução e prevenção contra interrupções de sistema (*crashes*).
- **Destaques Técnicos:**
  - Autenticação por PIN numérico com controle de tentativas e bloqueio de segurança.
  - Sanitização de strings e validação rigorosa de tipos numéricos usando `try/except`.
  - Módulo de simulação de rendimentos aplicando juros compostos.
  - Filtros dinâmicos de extrato por tipo de operação (Receita/Despesa).

---

## 📊 Estatísticas do GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=isa-amorim&show_icons=true&theme=radial&include_all_commits=true&count_private=true" alt="Estatísticas do GitHub de Isa Amorim" height="175"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=isa-amorim&layout=compact&theme=radial&hide=html,css" alt="Linguagens mais usadas por Isa Amorim" height="175"/>
</p>

---

## 📫 Vamos nos conectar?

- **LinkedIn:** [linkedin.com/in/isa-amorim](https://linkedin.com/in/isa-amorim)
- **GitHub:** [github.com/isa-amorim](https://github.com/isa-amorim)
