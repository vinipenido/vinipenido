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

Cada vez mais estudantes aprendem programação conversando com IA. Só que um LLM genérico costuma entregar a resposta pronta sem ensinar o raciocínio, pode inventar informação e esquece o que o aluno já perguntou. O CodeMentor resolve isso assim:

- Agente com comportamento **didático**: guia o aluno pela explicação em vez de entregar o código pronto
- **RAG** sobre uma base de livros técnicos (ingestão de PDFs e busca semântica com pgvector), para as respostas se basearem em conteúdo real
- **Embeddings locais** com ONNX Runtime + AllMiniLM-L6-v2, sem custo de API de embeddings
- **Memória por aluno** e reformulação de perguntas de follow-up com base no histórico
- Endpoints protegidos com JWT, documentação Swagger/OpenAPI e ambiente 100% Dockerizado

🔗 [Repositório](https://github.com/vinipenido/codementor-java)

---

### 💬 Claude Clone: API de chat com IA em streaming
> Java 25 · Spring Boot 4.1 · Spring Data JPA · PostgreSQL · Server-Sent Events · Anthropic API · Docker Compose

Em um chat com IA, esperar a resposta inteira do modelo deixa a experiência lenta. Além disso, a API do LLM não guarda estado, então é o back-end que precisa manter o histórico para a conversa fazer sentido. Construí este back-end do zero para resolver as duas coisas:

- **Streaming token a token via SSE**, com processamento assíncrono usando `@Async`
- Consumo do stream da Anthropic com o **`HttpClient` nativo do Java**, sem adicionar dependências reativas
- Histórico persistido em **PostgreSQL** e reenviado a cada mensagem para manter o contexto
- Arquitetura em camadas (Controller → Service → Repository), DTOs com `records` e erros centralizados via `@RestControllerAdvice` (400, 404, 502)

🔗 [Repositório](https://github.com/vinipenido/claude-clone)

---

### 🎬 Catálogo de Filmes: API REST segura
> Java 25 · Spring Boot 4.1 · Spring Security · JWT · Spring Data JPA · PostgreSQL 16 · Swagger · Docker

Uma API de catálogo aberta permite que qualquer pessoa altere os dados, e, sem filtros nem paginação, a consulta fica pesada conforme o catálogo cresce. Por isso a API foi construída com:

- **JWT stateless** com Spring Security: cadastro e login públicos, e as 5 rotas de filmes protegidas
- CRUD completo com **3 filtros combináveis** (título, gênero e ano), paginação e ordenação configurável
- Tratamento centralizado de erros (401, 404, 500), documentação Swagger e PostgreSQL em container Docker

🔗 [Repositório](https://github.com/vinipenido/catalogo-filmes)

---

### ⚙️ n8n Automations: portfólio de agentes e automações em produção
> n8n · GPT-4.1 / GPT-5 · LangChain · MCP · Supabase pgvector · Redis · PostgreSQL · Python

As automações que construí para clientes rodavam em produção, dentro das instâncias de cada um. Exportar os workflows do jeito que estavam vazaria credenciais e dados pessoais, e parte da lógica, como a de agenda, estava duplicada em vários agentes. Este repositório organiza tudo isso:

- **19 automações** documentadas em 5 categorias: agentes, RAG, pipelines, integrações e utils
- **Sanitizador em Python** que remove credenciais, dados de execução e dados pessoais antes de versionar
- **Servidor MCP** que expõe operações de agenda como capacidade reutilizável, separando o provedor de agenda de cada agente
- Ingestão vetorial incremental com reindexação delete-then-insert e checkpoint por lote

🔗 [Repositório](https://github.com/vinipenido/n8n-automations)


## 🏭 Sistemas que construí em produção

<details>
<summary><b>Sistema de Vendas Multiagente (WhatsApp, 24/7)</b></summary>

> n8n · GPT-4.1 · GPT-5 · Supabase · Redis · Chatwoot · Airtable · WhatsApp API

Empresas que vendem pelo WhatsApp recebem leads a qualquer hora, e o atendimento manual não dava conta de responder, qualificar e acompanhar todos a tempo. Os clientes ainda mandam várias mensagens picadas, o que confunde um bot comum. A solução foi um sistema com três agentes trabalhando juntos:

- **Agente SDR** (80 nós): qualifica leads, agenda reuniões no Google Calendar via MCP e atualiza o CRM
- **Agente Vendedor** (92 nós): conduz a negociação, gera propostas e move o lead pelo funil usando 8 ferramentas de CRM
- **Agente Suporte** (66 nós): RAG sobre a base de conhecimento (OpenAI Embeddings + pgvector), com entrada de texto, áudio, imagem e PDF
- **Buffer em Redis** que junta as mensagens fragmentadas antes de chamar o modelo
- **Follow-up automático** em D+7, D+10 e D+15, orquestrado por sub-workflows agendados
</details>

<details>
<summary><b>Agente de Agendamento Médico</b></summary>

> n8n · API 4Medic

Nas clínicas que usam o 4Medic, a recepção conferia manualmente cadastro, convênio e agenda a cada pedido de consulta pelo WhatsApp. O agente automatiza esse fluxo:

- Integração com a API REST do 4Medic: busca do paciente por CPF, validação do convênio e criação ou cancelamento de agendamentos
- Cadastro automático do paciente quando ele ainda não existe na base
</details>

<details>
<summary><b>Agente de Atendimento: Operadora de Saúde</b></summary>

> Make · WhatsApp API

A cobertura e os planos da operadora mudam conforme a região, e a equipe repetia as mesmas respostas para cada lead. O agente assume essa parte:

- O lead informa o bairro e recebe as opções disponíveis na região (**qualificação geográfica**)
- Envio de imagens das unidades e apresentação dos planos com tabela de preços
</details>

<details>
<summary><b>Lambda de Integração com Sistemas Fechados</b></summary>

> AWS Lambda · Node.js · Express · Puppeteer

Muitos sistemas internos dos clientes eram legados e não tinham API, então os agentes de IA não conseguiam acessá-los. Esta função serverless faz a ponte:

- API REST que recebe as credenciais, autentica com **Puppeteer**, navega no sistema e devolve JSON estruturado
- Permite que os agentes leiam e registrem dados como um usuário faria
- Trata falhas de login com `401` e `{ success: false, error: "..." }`
</details>

<details>
<summary><b>Relatório Automático de Representante</b></summary>

> n8n · PostgreSQL

Os representantes comerciais extraíam dados de vendas e estoque manualmente, em várias consultas separadas. O pipeline junta tudo em um relatório só:

- **4 queries SQL em paralelo** (vendas, clientes inativos, ranking e ruptura de estoque)
- Relatório consolidado entregue via webhook, sob demanda
</details>

<br>

## 💼 Experiência

### Analista Júnior de Implantação de Sistemas: Agentes de IA e Integrações
**Pipelora** · fev 2026 – set 2026 · Poços de Caldas, MG

A Pipelora oferece uma plataforma de agentes de IA para automatizar operações de clientes. Esses agentes precisavam acessar sistemas internos, muitos legados e sem API, e por isso vários processos ainda dependiam de trabalho manual. Meu trabalho foi dar esse acesso aos agentes:

- Funções serverless em **AWS Lambda + Node.js** conectando os agentes aos sistemas dos clientes
- **Puppeteer** e web scraping para integrar aplicações sem API
- Agentes estruturados com RAG, tool calling, guardrails e memória de conversa em PostgreSQL, validados com baterias de testes e casos de borda
- Mais de **10 agentes em produção** (agendamento, vendas, SDR, qualificação de leads e suporte), com menos etapas manuais

### Engenheiro de IA e Automações
**TOP IA** · nov 2024 – fev 2026 · Poços de Caldas, MG

A TOP IA desenvolve agentes de IA e automações para empresas B2B e B2C, com foco em atendimento via WhatsApp. Os clientes perdiam tempo com atendimento manual, tarefas repetitivas e sistemas que não se comunicavam, o que deixava a operação lenta e difícil de escalar. Meu papel foi construir os agentes e as integrações que resolviam isso:

- Sistemas multiagentes de vendas, SDR e suporte rodando 24/7, com entrada multimodal
- Pipelines de **RAG** com semantic chunking e busca vetorial no pgvector, com alucinações depuradas até o nível do chunk
- **Function calling e tool use** (OpenAI e Claude) para os agentes executarem ações reais: agendar, consultar e atualizar registros
- Integrações resilientes com OAuth 2.0, webhooks, paginação por cursor, rate limiting e backoff exponencial
- Infraestrutura própria com Docker, VPS (DigitalOcean, Hetzner) e EasyPanel
- Mais de **20 agentes de IA em produção**, automatizando atendimentos que antes eram manuais

<br>

## 🎓 Formação & Certificações

- **Bacharelado em Ciência da Computação**, PUC Minas (ago/2022 – previsão dez/2027)
- Building with the Claude API · Claude Academy
- Claude with Amazon Bedrock · Claude Academy
- Claude with Google Cloud's Vertex AI · Claude Academy
- Bootcamp Java com Inteligência Artificial · Itaú e DIO

## 🌎 Idiomas

Português (nativo) · Inglês (intermediário-avançado, B2)
