<h1 align="center">Vinicius Henrique</h1>
<h3 align="center">Back-end Developer (Java) & AI Engineer | Spring Boot · AI Agents · RAG · LLMs · MCP</h3>

<p align="center">
  <a href="mailto:vinipenido312@gmail.com">vinipenido312@gmail.com</a> •
  <a href="https://www.linkedin.com/in/viniciushenrique">LinkedIn</a> •
  <a href="https://github.com/vinipenido">GitHub</a> •
  (35) 9 9831-9379 • Poços de Caldas, MG
</p>

<p align="center">
  🟢 <b>Aberto a oportunidades</b> como Desenvolvedor Back-end Java ou Engenheiro de IA (remoto ou híbrido)
</p>

<br>

## 🧑‍💻 Sobre mim

Sou desenvolvedor back-end **Java** e **Engenheiro de IA**. Curso **Ciência da Computação na PUC Minas** (previsão de conclusão: dez/2027).

Há quase 2 anos coloco **agentes de IA em produção**. Já entreguei **mais de 30 agentes e sistemas multiagentes** para clientes B2B e B2C. Eles atendem consultórios médicos, operadoras de saúde e times de vendas pelo WhatsApp, 24h por dia, e processam texto, áudio, imagem e PDF.

Participo do ciclo inteiro: levantamento de requisitos com o cliente, arquitetura, implementação, deploy, monitoramento e manutenção.

**No que eu trabalho:**
- 🤖 **IA aplicada:** RAG com busca vetorial, function calling / tool use, sistemas multiagentes, MCP, guardrails, memória de conversa, engenharia de prompt e otimização de tokens e custos
- ☕ **Back-end:** APIs REST com Java, Spring Boot, Spring Security/JWT, Spring Data JPA, streaming via SSE e Spring AI / LangChain4j
- 🔌 **Integrações:** OAuth 2.0, webhooks, paginação por cursor, rate limiting, retries com backoff exponencial, AWS Lambda e Puppeteer para sistemas sem API

<br>

## 🧰 Stack

**Linguagens & Back-end**

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Bancos de Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**IA & LLMs**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-5A45FF?style=for-the-badge&logoColor=white)

**Cloud, Automação & Ferramentas**

![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white)
![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=for-the-badge&logo=puppeteer&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<br>

## 🚀 Projetos em destaque

### 🎓 CodeMentor.java: tutor de programação com IA
> Java 21 · Spring Boot 4 · LangChain4j · Claude API · PostgreSQL · pgvector · ONNX Runtime · Spring Security · JWT · Docker

- Agente que **ensina** programação: prioriza a explicação didática em vez de entregar a resposta pronta
- **RAG** sobre uma base de livros técnicos, com ingestão de PDFs, busca semântica e respostas fundamentadas em conteúdo real
- **Embeddings locais** (ONNX Runtime + AllMiniLM-L6-v2), sem custo de API de embeddings
- Memória de conversa por aluno e reformulação de perguntas de follow-up com base no histórico
- Endpoints protegidos com JWT, documentação Swagger/OpenAPI e ambiente 100% Dockerizado

🔗 [Repositório](https://github.com/vinipenido/codementor-java)

---

### 💬 Claude Clone: API de chat com IA em streaming
> Java 25 · Spring Boot 4.1 · Spring Data JPA · PostgreSQL · Server-Sent Events · Anthropic API · Docker Compose

- Respostas em **streaming token a token via SSE**, com processamento assíncrono usando `@Async`
- Consumo do stream SSE da Anthropic com o **`HttpClient` nativo do Java**, sem dependências reativas
- Histórico de conversas persistido em PostgreSQL, com o contexto completo reenviado a cada mensagem
- Arquitetura em camadas (Controller → Service → Repository), DTOs com `records` e erros centralizados via `@RestControllerAdvice` (400, 404, 502)

🔗 [Repositório](https://github.com/vinipenido/claude-clone)

---

### 🎬 Catálogo de Filmes: API REST segura
> Java 25 · Spring Boot 4.1 · Spring Security · JWT · Spring Data JPA · PostgreSQL 16 · Swagger · Docker

- 7 endpoints: cadastro e login públicos que emitem **JWT stateless** e 5 rotas de filmes protegidas
- CRUD completo com **3 filtros combináveis** (título, gênero e ano), paginação e ordenação configurável
- Tratamento centralizado de erros (401, 404, 500), documentação Swagger e PostgreSQL em container

🔗 [Repositório](https://github.com/vinipenido/catalogo-filmes)

---

### ⚙️ n8n Automations: portfólio de agentes e automações em produção
> n8n · GPT-4.1 / GPT-5 · LangChain · MCP · Supabase pgvector · Redis · PostgreSQL · Python

- **19 automações de produção** documentadas em 5 categorias: agentes, RAG, pipelines, integrações e utils
- **Servidor MCP** que expõe operações de agenda como capacidade reutilizável, separando o provedor de agenda de cada agente
- Ingestão vetorial incremental com reindexação delete-then-insert e checkpoint por lote
- Sanitizador em Python que remove credenciais e dados pessoais antes de versionar os workflows

🔗 [Repositório](https://github.com/vinipenido/n8n-automations)

---

### 🎙️ API de Orçamento por Voz: Spring AI
> Java · Spring Boot · Spring AI

- API de orçamento operada por comandos de voz, integrando Spring AI a um back-end Java

<br>

## 🏭 Sistemas que construí em produção

<details>
<summary><b>Sistema de Vendas Multiagente (WhatsApp, 24/7)</b></summary>

> n8n · GPT-4.1 · GPT-5 · Supabase · Redis · Chatwoot · Airtable · WhatsApp API

- **Agente SDR** (80 nós): qualifica leads, agenda reuniões no Google Calendar via MCP e atualiza o CRM
- **Agente Vendedor** (92 nós): conduz negociações e gera propostas. O próprio modelo move o lead pelo funil usando 8 ferramentas de CRM
- **Agente Suporte** (66 nós): RAG sobre a base de conhecimento (OpenAI Embeddings + pgvector), com entrada multimodal
- **Buffer em Redis** que junta mensagens fragmentadas do cliente antes de chamar o modelo
- **Follow-up automático** em D+7, D+10 e D+15, orquestrado por sub-workflows agendados
</details>

<details>
<summary><b>Agente de Agendamento Médico</b></summary>

> n8n · API 4Medic

- Integração com o sistema médico 4Medic via API REST
- Verifica pacientes por CPF, valida convênios e cria ou cancela agendamentos
- Cadastra o paciente automaticamente quando ele ainda não existe na base
</details>

<details>
<summary><b>Agente de Atendimento: Operadora de Saúde</b></summary>

> Make · WhatsApp API

- Consulta de cobertura por bairro, envio de imagens das unidades e tabelas de planos
- Qualificação geográfica: o lead informa o bairro e recebe as opções da região
</details>

<details>
<summary><b>Lambda de Integração com Sistemas Fechados</b></summary>

> AWS Lambda · Node.js · Express · Puppeteer

- API REST que autentica e navega em sistemas externos sem API pública e devolve JSON estruturado
- Permite que agentes de IA leiam e registrem dados em sistemas legados como um usuário faria
- Trata falhas de login com `401` e `{ success: false, error: "..." }`
</details>

<details>
<summary><b>Relatório Automático de Representante</b></summary>

> n8n · PostgreSQL

- 4 queries SQL em paralelo (vendas, clientes inativos, ranking e ruptura de estoque)
- Relatório consolidado entregue via webhook sob demanda, sem extração manual
</details>

<br>

## 💼 Experiência

**Analista Júnior de Implantação de Sistemas: Agentes de IA e Integrações** · Pipelora · fev 2026 – set 2026 · Poços de Caldas, MG
- Entreguei **mais de 10 agentes de IA** em produção para clientes B2B e B2C (agendamento, vendas, SDR, qualificação de leads e suporte)
- Desenvolvi funções serverless em **AWS Lambda + Node.js** que dão aos agentes acesso aos sistemas internos dos clientes
- Integrei sistemas legados sem API usando **Puppeteer** e web scraping, eliminando etapas manuais
- Estruturei os agentes com RAG, tool calling, guardrails e memória de conversa em PostgreSQL, e validei cada entrega com baterias de testes e casos de borda

**Engenheiro de IA e Automações** · TOP IA · nov 2024 – fev 2026 · Poços de Caldas, MG
- Entreguei **mais de 20 agentes de IA** em produção, incluindo sistemas multiagentes de vendas, SDR e suporte rodando 24/7 no WhatsApp
- Construí pipelines de **RAG** com semantic chunking e busca vetorial por limiar no Supabase pgvector, e depurei alucinações até o nível do chunk
- Implementei **function calling e tool use** com OpenAI e Anthropic Claude para os agentes executarem ações reais
- Deixei as integrações mais resilientes com OAuth 2.0, webhooks bidirecionais, paginação por cursor, rate limiting e backoff exponencial
- Mantive a infraestrutura de produção com Docker, VPS (DigitalOcean, Hetzner) e EasyPanel, e resolvi incidentes com análise de logs e de causa raiz

<br>

## 🎓 Formação & Certificações

- **Bacharelado em Ciência da Computação**, PUC Minas (ago/2022 – previsão dez/2027)
- Building with the Claude API · Claude Academy
- Claude with Amazon Bedrock · Claude Academy
- Claude with Google Cloud's Vertex AI · Claude Academy
- Bootcamp Java com Inteligência Artificial · Itaú e DIO

## 🌎 Idiomas

Português (nativo) · Inglês (intermediário-avançado, B2)
