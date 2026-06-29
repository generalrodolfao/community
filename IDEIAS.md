# 💡 Idéias de Projetos

> Lista viva. Novas idéias entram toda semana.

---

## 🔥 Prioridade alta

| Projeto | Descrição | Por que |
|---|---|---|
| **OpenRoute** | Roteador inteligente de LLMs — cache semântico, fallback automático, custo mínimo | Já citei no LinkedIn, é meu diferencial |
| **spec-to-code** | Template de spec-driven dev: PRD → código (front, back, docs, testes) | Mostra metodologia, vira lead magnet |
| **agent-debate** | Multi-agente com debate: duas IAs discutem até consenso | Conteúdo viral + case técnico |
| **prompt-arena** | A/B testing de prompts com LangFuse + estatística | Ferramenta prática para times de IA |
| **llm-cost-tracker** | Dashboard de custo por query, modelo, usuário | Problema real de todo time de IA |

## 📋 Média prioridade

| Projeto | Descrição |
|---|---|
| **eval-harness** | Suite de avaliação RAG + agentes (RAGAS, LangFuse, testes customizados) |
| **data-observability** | Template de observabilidade de dados com OpenMetadata + Great Expectations |
| **social-poster** | Agente que cria calendário editorial, gera imagens e publica |
| **secret-audit** | CLI que varre repositórios git atrás de segredos expostos |
| **prompt-injection-lab** | Guia + exemplos de ataques e defesas de injeção de prompt |

## 🧪 LangGraph Recipes — Aplicações Reais

| Projeto | Descrição | Stack |
|---|---|---|
| **langgraph-recipes** | Coleção de exemplos práticos de LangGraph: agentes, fluxos condicionais, human-in-the-loop, multi-agent orchestration | LangGraph, LangFuse |
| **feature-engine-agent** | Pipeline de feature engineering com agentes LangGraph: ingestão → validação → transformação → feature store. Inclui point-in-time correctness e time travel. | LangGraph, DuckDB, Feast |
| **ml-pipeline-agent** | Agente que orquestra pipeline ML end-to-end: split treino/teste, treinamento, avaliação, deploy. Com checkpoints para retomada de falhas. | LangGraph, scikit-learn, MLflow |
| **data-quality-agent** | Squad de agentes que audita qualidade de dados: um agente por dimensão (completude, frescor, unicidade, consistência). Gera relatório e alertas. | LangGraph, Great Expectations, OpenMetadata |
| **etl-orchestrator** | Agente que recebe spec de ETL em linguagem natural e gera/monitora DAG no Airflow. Ex: "Ingerir CSV de vendas, limpar nulos, agregar por mês, salvar no PostgreSQL" | LangGraph, Airflow, OpenAI |

## 💭 Baixa prioridade / Ideias soltas

| Ideia | Notas |
|---|---|
| **llm-router-benchmark** | Comparar roteadores (OpenRoute, OpenRouter, etc) |
| **airflow-llm-provider** | Provider do Airflow para chamar LLMs |
| **mcp-server-brasil** | MCP servers para serviços brasileiros (CNPJ, CEP, etc) |
| **git-story** | CLI que gera release notes a partir do git log com IA |
| **agent-dashboard** | Dashboard Pixi.js para visualizar agentes em tempo real |
| **data-squad-cli** | CLI para scaffold de projetos Data Squad |

---

## 🎯 Repositórios alvo para PRs

| Repo | Issues boas para começar |
|---|---|
| [LangChain](https://github.com/langchain-ai/langchain/issues?q=is%3Aissue+is%3Aopen+label%3Adoc) | Issues de documentação |
| [LangGraph](https://github.com/langchain-ai/langgraph/issues) | Issues de exemplo/bug |
| [CrewAI](https://github.com/crewAIInc/crewAI/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) | Good first issues |
| [RAGAS](https://github.com/explodinggradients/ragas/issues) | Issues abertas |
| [LangFuse](https://github.com/langfuse/langfuse/issues) | Issues de integração |
| [MCP Servers](https://github.com/modelcontextprotocol/servers/issues) | Novos servidores |

---

<p align="center">
  <i>Sugestões são bem-vindas — abre uma issue!</i>
  <br/>
  <a href="https://github.com/generalrodolfao/community">← Voltar ao README</a>
</p>
