<h1 align="center">Vinicius Henrique</h1>
<h3 align="center">Desenvolvedor Backend Java | Spring Boot | IA & Automações</h3>

<p align="center">
  <a href="mailto:vinipenido312@gmail.com">vinipenido312@gmail.com</a> •
  <a href="https://www.linkedin.com/in/viniciushenrique">LinkedIn</a> •
  <a href="https://github.com/vinipenido">GitHub</a> •
  (35) 9 9831-9379
</p>

<br>

## 🧑‍💻 Sobre mim

Estou cursando **Ciência da Computação na PUC Minas**, com foco em **Java e Spring Boot** para atuação como **Desenvolvedor Backend**. Tenho conhecimento também em HTML, CSS, JavaScript, React, Python, C, C# e .NET, além de banco de dados MySQL, e já participei de projetos acadêmicos envolvendo análise de dados e visualizações com Grafana.

Antes de migrar para o backend Java, atuei por mais de um ano criando **agentes de IA e automações em produção** — sistemas que hoje atendem consultórios médicos, operadoras de saúde e empresas de vendas 24h por dia sem intervenção humana. Também desenvolvi funções serverless (Lambda) em Node.js, usando Puppeteer para integrar sistemas corporativos fechados, sem API pública.

Hoje busco oportunidades como **Desenvolvedor Backend Java**, aplicando essa bagagem prática em automação, integração de sistemas e IA à construção de sistemas corporativos robustos.

<br>

## 🧰 Stack Principal

**Backend & Linguagens**

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Banco de Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**IA, Automação & Cloud**

![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

**Ferramentas**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<br>

## 🚀 Projetos

### Catálogo de Filmes — API REST
> Java · Spring Boot · PostgreSQL · JWT · Swagger

- Primeiro projeto backend em Java, construído do zero com CRUD completo (entidade, repository, service, controller)
- Autenticação e autorização via JWT, paginação e filtros de busca
- Documentação de endpoints com Swagger, banco PostgreSQL rodando em container Docker

---

### Sistema de Vendas Multiagente
> n8n · GPT-4.1 · GPT-5 · Supabase · Chatwoot · WhatsApp API

Sistema completo com três agentes trabalhando em conjunto:

- **Agente SDR** — qualifica leads via WhatsApp, agenda reuniões com Google Calendar (MCP) e atualiza o CRM automaticamente
- **Agente Vendedor** — conduz negociações, gera propostas e gerencia o pipeline completo (conexão → qualificação → proposta → ganho/perdido)
- **Agente Suporte** — resolve dúvidas pós-venda com RAG sobre base de conhecimento (OpenAI Embeddings + Supabase vetorial), processando texto, áudio e imagem
- **Follow-up automático** em 3 etapas (7º, 10º e 15º dia), com delay humanizado e registro no Google Sheets

---

### Agente de Agendamento Médico
> n8n · GPT Maker · API 4Medic

- Integração completa com sistema médico 4Medic via API REST
- Verifica pacientes por CPF, valida convênios e cria/cancela agendamentos automaticamente
- Fluxo inteligente: cadastra o paciente automaticamente caso ele não exista na base

---

### Agente de Atendimento — Operadora de Saúde
> Make · WhatsApp API

- Consulta de cobertura por bairro, envio de imagens das unidades e apresentação de planos com tabelas de preços
- Qualificação geográfica automática: o lead informa o bairro e recebe as opções disponíveis na região

---

### Chat RAG com Base de Estoque
> n8n · OpenAI Embeddings · Supabase Vetorial · Discord

- Agente conversacional com memória de histórico e RAG sobre base de estoque
- Integrado ao Discord, com suporte a threads e modelo de raciocínio (think) antes de responder

---

### Relatório Automático de Representante
> n8n · PostgreSQL

- Pipeline que executa 4 queries SQL em paralelo (vendas, clientes inativos, ranking e ruptura de estoque)
- Entrega relatório consolidado via webhook sob demanda, eliminando extração manual

---

### Lambda de Integração com Sistema Fechado
> Node.js · Express · Puppeteer

- API REST que recebe login/senha e acessa sistemas externos sem API pública
- Usa Puppeteer para autenticar, navegar e extrair dados, retornando JSON estruturado
- Trata erros de login com status `401` e `{ success: false, error: "..." }`

<br>

## 💼 Experiência

**Implantação de Sistemas Junior** · Pipelora · fev 2026 – mai 2026 · Poços de Caldas, MG
- Desenvolvimento de tools e funções serverless (Lambda) em Node.js para automação de agentes de IA na plataforma Pipelora
- Uso de Puppeteer para automação de interfaces e integração com sistemas corporativos fechados, sem API, viabilizando automações que conectam IA a ambientes que normalmente não permitem integração direta
- Implementações que otimizam processos e eliminam tarefas repetitivas, melhorando a eficiência operacional

**Desenvolvedor de Agentes de I.A e Automações** · Top IA Empresas · jan 2025 – fev 2026 · Poços de Caldas, MG
- Desenvolvimento de agentes de IA e automação de fluxos inteligentes com n8n, Make e Webhooks
- Criação de soluções voltadas à consulta, tratamento e retorno automatizado de dados a partir de bancos de dados e planilhas
- Integração de APIs para automação de atendimento, notificações e operações personalizadas

<br>
