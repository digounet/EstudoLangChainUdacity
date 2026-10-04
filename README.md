# Estudo LangChain (Udacity)

Notebooks do curso de LangChain/LangGraph, rodando contra o Azure OpenAI. Cada notebook e um tema; a ordem e a do curso.

| Notebook | Tema |
|---|---|
| 01_langchain | Setup, mensagens e primeiro chat com `AzureChatOpenAI` |
| 02_chatbot | Chatbot com historico |
| 03_outputs | Saidas estruturadas e parsers |
| 04_LCEL | LangChain Expression Language (pipes) |
| 05_multi_step_workflow | Workflow em varias etapas |
| 06_tools | Tools e function calling |
| 07_graph | LangGraph: nos, arestas e estado |
| 08_router | Roteamento condicional no grafo |
| 09_state_management_demo | Gerenciamento de estado |
| 10_library_assistant | Assistente de biblioteca (exercicio integrador) |
| 11_memory_checkpoint | Memoria e checkpoint no LangGraph |

## Rodar

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt jupyter
cp .env.example .env     # credenciais do Azure OpenAI
jupyter lab
```

O `.env` nao e versionado. Os notebooks leem as variaveis com `dotenv`.

## Relacionados

Os projetos `Python/WorkDayAgent` e `IA/study/hr-agent-lab` partem do que esta aqui.
