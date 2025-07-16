# README.md

# DataCamp Prática 2 - Este repositório com uma aplicação prática com a API da [Groq](https://groq.com/) Modelo LLaMA3

## Funcionalidades

Conectar com a API Groq via chave (`GROQ_API_KEY`);
Utilizar o modelo **LLaMA3-70b-8192**;
Criar um agente interativo com histórico de mensagens;
Realizar ações personalizadas considerando o prompt de sistema;
Cálculo e busca de capitais.

## Estrutura

- `DataCamp_Pratica_2.ipynb` — Notebook com todo o código.
- Ferramentas implementadas:
  - `calculate`: Executa operações matemáticas.
  - `simon_blog_search`: Retorna respostas simuladas sobre capitais de países.

## Exemplo

python
agent = Agent(client, system=system_prompt)
print(agent("What is the capital of Germany?"))
