# Aula 02 - Context Engineering

Esta pasta contém a segunda versão do projeto da monitoria: uma aplicação Python que seleciona contexto externo antes de chamar uma LLM.

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

Depois, abra `aula2_context_engineering_template.ipynb` no VSCode ou no Jupyter e execute as células em ordem.

## O que muda na V2

Na Aula 01, a aplicação enviava apenas a pergunta e as instruções. Agora ela:

- mantém uma pequena base local de documentos;
- calcula quais documentos são mais relevantes para a pergunta;
- limita a quantidade de contexto enviada;
- monta uma mensagem com fontes identificadas;
- compara uma resposta sem contexto com uma resposta baseada no contexto selecionado.

O exercício usa seleção por sobreposição de termos para tornar o mecanismo visível.

## Arquivos

- `aula2_context_engineering_template.ipynb`: notebook com TODOs para a atividade;
- `env.example`: variáveis de ambiente esperadas;
- `requirements.txt`: dependências Python;
- `README.md`: este documento de configuração do ambiente.

**Nunca faça commit do arquivo `.env`.**
