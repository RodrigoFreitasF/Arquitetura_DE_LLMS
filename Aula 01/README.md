# Aula 01 - LLM APIs

Esta pasta contém a primeira versão do projeto da monitoria: uma aplicação Python que envia uma requisição para uma LLM e observa a resposta.

## Preparação

No terminal, dentro desta pasta:

```bash
python -m venv .venv
```

Ative o ambiente virtual e instale as dependências:

```bash
pip install -r requirements.txt
```

Copie o arquivo de exemplo e preencha a chave da Groq:

```bash
copy env.example .env
```

No macOS ou Linux, use `cp env.example .env`.

Depois, abra `aula1_llm_apis_template.ipynb` no VSCode ou no Jupyter e execute as células em ordem.

## Arquivos

- `aula1_llm_apis.ipynb`: notebook da v1.0;
- `env.example`: variáveis de ambiente esperadas;
- `requirements.txt`: dependências Python;
- `README.md`: este documento de configuração do ambiente.

**Nunca faça commit do arquivo `.env`.**
