# Oficina de Arquitetura de LLMs

Esta monitoria acompanha a construção de um único sistema de IA ao longo de seis aulas. Em cada encontro, o projeto ganha uma capacidade nova: primeiro uma chamada de API, depois contexto, ferramentas, MCP, um loop de agente e recuperação de documentos.

## LLMs, Context Engineering, Tool Calling, Agents, MCP, SDKs e RAG

O objetivo não é construir seis exercícios independentes. O objetivo é entender como as peças se conectam dentro de uma aplicação real.

## Estrutura da monitoria

A monitoria é organizada em **6 aulas** e será orientada no desenvolvimento de um **único projeto evolutivo**.

Em vez de construir aplicações independentes em cada aula, o mesmo sistema é desenvolvido progressivamente. Cada encontro adiciona uma nova capacidade à arquitetura.

| Aula   | Eixo                | Evolução                                  | Projeto |
| ------ | ------------------- | ------------------------------------------- | ------- |
| Aula 1 | LLM APIs            | Chamada simples de LLM                      | v1.0    |
| Aula 2 | Context Engineering | Contexto externo selecionado                | v2.0    |
| Aula 3 | Tool Calling        | Chamadas de ferramentas                     | v2.1    |
| Aula 4 | MCP + SDKs          | Ferramentas disponibilizadas via MCP Server | v2.2    |
| Aula 5 | Agents              | Agente com loop de decisão                 | v3.0    |
| Aula 6 | RAG + Fechamento    | Recuperação de documentos com RAG         | v3.1    |

## Conceitos de apoio

Ao longo das aulas, alguns conceitos aparecem transversalmente:

- **Tokens e context window [🔗](https://www.ibm.com/br-pt/think/topics/context-window)**
- **Mensagens `system`, `user` e `tool` [🔗](https://platform.openai.com/docs/guides/conversation-state)**
- **Structured outputs e schemas [🔗](https://platform.openai.com/docs/guides/structured-outputs)**
- **Function calling [🔗](https://platform.openai.com/docs/guides/function-calling)**
- **Embeddings e retrieval [🔗](https://www.ibm.com/think/topics/embedding)**
- **Agent loop [🔗](https://www.anthropic.com/research/building-effective-agents)**
- **Estado e histórico [🔗](https://learn.microsoft.com/en-us/agent-framework/concepts/agents/conversations/?pivots=programming-language-csharp)**
- **Memória [🔗](https://www.ibm.com/br-pt/think/topics/ai-agent-memory)**
- **Observabilidade [🔗](https://www.ibm.com/think/topics/ai-observability)**
- **Avaliação [🔗](https://platform.openai.com/docs/guides/evals)**
- **Guardrails [🔗](https://www.ibm.com/think/topics/ai-guardrails)**

Esses conceitos ajudam a conectar as diferentes camadas da arquitetura e entender não apenas **como utilizar uma LLM**, mas como construir sistemas ao redor dela.

## Resultado esperado

Ao final da monitoria, espera-se que o participante seja capaz de:

- Consumir modelos de linguagem por API;
- Estruturar e controlar contexto;
- Definir e executar ferramentas;
- Entender o funcionamento de agentes;
- Reconhecer o papel de MCP e SDKs;
- Compreender os fundamentos de RAG;
- Integrar essas diferentes capacidades em uma aplicação;
- Acompanhar a evolução de uma arquitetura de IA de ponta a ponta.
- Criar um sistema capaz de realizar o fluxo abaixo:

> LLM, contexto, ferramentas, MCP, agentes e RAG formam camadas diferentes de um mesmo sistema.
