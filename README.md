<h1 align="center">Vinicius Henrique</h1>
<h3 align="center">AI Engineer & Java Back-end Developer | AI Agents · RAG · LLM Integration · MCP</h3>

<p align="center">
  <a href="mailto:vinipenido312@gmail.com">vinipenido312@gmail.com</a> •
  <a href="https://www.linkedin.com/in/viniciushenrique">LinkedIn</a> •
  <a href="https://github.com/vinipenido">GitHub</a> •
  (35) 9 9831-9379
</p>

<br>

## 🧑‍💻 Sobre mim

Desenvolvedor back-end **Java** e **Engenheiro de IA**, com foco em **Spring Boot** e IA aplicada. Curso **Ciência da Computação na PUC Minas**.

Há mais de 1,5 ano crio **agentes de IA e automações em produção**: foram **mais de 30 agentes entregues** para clientes B2B e B2C, que hoje atendem consultórios médicos, operadoras de saúde e empresas de vendas 24h por dia pelo WhatsApp, sem intervenção humana, processando texto, áudio, imagem e PDF.

Trabalho em tudo o que faz um agente ser confiável: **RAG** com busca vetorial, **function calling e tool use**, sistemas **multiagentes**, **MCP (Model Context Protocol)**, guardrails, memória de conversa e engenharia de prompt. Também construo o back-end em volta: APIs REST, webhooks, funções serverless na **AWS Lambda** e serviços em **Java com Spring Boot e Spring AI**.

<br>

## 🧰 Stack Principal

**Linguagens & Backend**

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Banco de Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**IA & LLMs**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-5A45FF?style=for-the-badge&logoColor=white)

**Automação, Cloud & Ferramentas**

![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<br>

## 🚀 Projetos

### CodeMentor.java — Agente de IA para Ensino de Programação
> Java 21 · Spring Boot 4 · LangChain4j · Claude · pgvector · ONNX Runtime · Docker

- Agente de IA que ensina programação priorizando explicação didática em vez de resposta pronta
- RAG sobre base de livros técnicos: ingestão de PDFs, embeddings locais (ONNX, AllMiniLM-L6-v2, sem custo de API) e busca semântica
- Memória de conversa por aluno, com reformulação de perguntas de follow-up com base no histórico
- Endpoints protegidos com JWT, documentação via Swagger/OpenAPI e ambiente 100% Dockerizado

🔗 [Repositório](https://github.com/vinipenido/codementor-java)

---

### Claude Clone — Chat com IA e Streaming
> Java 25 · Spring Boot 4.1 · PostgreSQL · Server-Sent Events · API da Anthropic · Docker Compose

- Back-end de chat com respostas em streaming token a token via SSE e processamento assíncrono com `@Async`
- Consumo do stream SSE da Anthropic com o `HttpClient` nativo do Java, sem dependências reativas
- Histórico de conversas persistido em PostgreSQL, com o contexto completo reenviado a cada mensagem
- Arquitetura em camadas (Controller → Service → Repository), DTOs com records e erros padronizados via `@RestControllerAdvice` (400, 404, 502)

🔗 [Repositório](https://github.com/vinipenido/claude-clone)

---

### API de Orçamento por Voz — Spring AI
> Java · Spring Boot · Spring AI

- API de orçamento operada por comandos de voz, integrando Spring AI ao back-end Java

---

### Catálogo de Filmes — API REST Segura
> Java 25 · Spring Boot 4.1 · Spring Security · JWT · PostgreSQL 16 · Swagger · Docker

- API REST construída do zero com 7 endpoints: cadastro e login públicos emitindo JWT e 5 rotas de filmes protegidas
- CRUD completo com 3 filtros combináveis (título, gênero e ano), paginação e ordenação configurável
- Tratamento centralizado de erros (401, 404, 500), documentação com Swagger e PostgreSQL em container Docker

🔗 [Repositório](https://github.com/vinipenido/catalogo-filmes)

---

### n8n Automations — Portfólio de Agentes e Automações
> n8n · GPT-4.1 · GPT-5 · LangChain · MCP · Supabase pgvector · Redis · PostgreSQL · Python

- Portfólio documentado com **19 automações de produção** em 5 categorias: agentes, RAG, pipelines, integrações e utils
- Servidor **MCP** que expõe operações de agenda como capacidade reutilizável por qualquer agente
- Ingestão vetorial incremental com reindexação delete-then-insert e checkpoint por lote
- Sanitizador em Python que remove credenciais, dados de execução e dados pessoais antes de versionar os workflows

🔗 [Repositório](https://github.com/vinipenido/n8n-automations)

---

### Sistema de Vendas Multiagente
> n8n · GPT-4.1 · GPT-5 · Supabase · Redis · Chatwoot · WhatsApp API

Sistema completo com três agentes trabalhando em conjunto, rodando 24/7 em produção:

- **Agente SDR** (80 nós): qualifica leads via WhatsApp, agenda reuniões com Google Calendar (MCP) e atualiza o CRM automaticamente
- **Agente Vendedor** (92 nós): conduz negociações, gera propostas e gerencia o pipeline completo (conexão → qualificação → proposta → ganho/perdido), com o modelo conduzindo as transições de etapa via tools
- **Agente Suporte** (66 nós): resolve dúvidas pós-venda com RAG sobre base de conhecimento (OpenAI Embeddings + Supabase pgvector), processando texto, áudio, imagem e PDF
- **Buffer em Redis** que junta mensagens fragmentadas do cliente antes de chamar o modelo
- **Follow-up automático** em 3 etapas (7º, 10º e 15º dia), com delay humanizado e registro no Google Sheets

---

### Agente de Agendamento Médico
> n8n · GPT Maker · API 4Medic

- Integração completa com o sistema médico 4Medic via API REST
- Verifica pacientes por CPF, valida convênios e cria/cancela agendamentos automaticamente
- Fluxo inteligente: cadastra o paciente automaticamente caso ele não exista na base

---

### Agente de Atendimento — Operadora de Saúde
> Make · WhatsApp API

- Consulta de cobertura por bairro, envio de imagens das unidades e apresentação de planos com tabelas de preços
- Qualificação geográfica automática: o lead informa o bairro e recebe as opções disponíveis na região

---

### Relatório Automático de Representante
> n8n · PostgreSQL

- Pipeline que executa 4 queries SQL em paralelo (vendas, clientes inativos, ranking e ruptura de estoque)
- Entrega relatório consolidado via webhook sob demanda, eliminando extração manual

---

### Lambda de Integração com Sistema Fechado
> AWS Lambda · Node.js · Express · Puppeteer

- API REST que recebe login/senha e acessa sistemas externos sem API pública
- Usa Puppeteer para autenticar, navegar e extrair dados, retornando JSON estruturado
- Trata erros de login com status `401` e `{ success: false, error: "..." }`

<br>

## 💼 Experiência

**Analista de Implantação de Sistemas Júnior** · Pipelora · fev 2026 – mai 2026 · Poços de Caldas, MG
- Entreguei **mais de 10 agentes de IA** em produção para clientes B2B e B2C: agendamento, vendas, SDR, qualificação de leads e suporte
- Desenvolvi tools e funções serverless na AWS Lambda com Node.js para orquestrar agentes de IA na plataforma Pipelora
- Usei Puppeteer e web scraping para integrar sistemas corporativos fechados, sem API, conectando IA a ambientes que normalmente não permitem integração direta
- Validei cada agente antes da entrega com baterias de conversas de teste e casos de borda

**Desenvolvedor de IA e Automação** · TOP IA · jan 2025 – fev 2026 · Poços de Caldas, MG
- Entreguei **mais de 20 agentes de IA** em produção, incluindo sistemas multiagentes de vendas, SDR e suporte rodando 24/7 no WhatsApp
- Construí pipelines de RAG com chunking semântico e busca vetorial no Supabase pgvector, depurando alucinações até o nível do chunk
- Implementei function calling e tool use com OpenAI e Anthropic Claude para os agentes executarem ações reais (agendar, consultar e atualizar registros)
- Tornei as integrações resilientes com OAuth 2.0, webhooks, paginação, rate limiting e retentativas com backoff exponencial

<br>

## 🎓 Formação & Certificações

- **Bacharelado em Ciência da Computação**, PUC Minas (em andamento)
- Building with the Claude API · Claude Academy
- Claude with Amazon Bedrock · Claude Academy
- Claude with Google Cloud's Vertex AI · Claude Academy
- Bootcamp Java com Inteligência Artificial · Itaú e DIO
