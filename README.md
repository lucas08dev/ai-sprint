# 🚀 Prompt Toolkit — Checkpoint 02

Sistema desenvolvido em Python para comparar técnicas de Prompt Engineering utilizando modelos de linguagem executados localmente com Ollama.

## 👥 Integrantes

* Lucas Silva de Abreu — RM 572321
* Enzo Guislandi — RM 569885
* Guilherme Reiche — RM 569918
* João Camperlingo — RM 568957
* Nicolas Nishi — RM 572242

## 🎯 Objetivo

Avaliar automaticamente diferentes técnicas de prompting e identificar qual apresenta melhor desempenho em tarefas de análise de avaliações de produtos no contexto de e-commerce.

## 🛒 Domínio

O sistema realiza:

* Classificação de sentimento
* Extração de informações
* Sumarização de avaliações

## 🧠 Técnicas Implementadas

* **Zero-Shot Prompting** – apenas a instrução da tarefa.
* **Few-Shot Prompting** – utilização de exemplos.
* **Chain-of-Thought (CoT)** – raciocínio passo a passo.
* **Role Prompting** – definição de um papel para o modelo.

## ⚙️ Funcionalidades

* Integração com Ollama
* Execução automática das 4 técnicas
* Comparação de resultados
* Medição de tempo de resposta
* Avaliação de desempenho
* Geração de relatórios CSV
* Criação de gráficos
* Recomendação da melhor técnica

## 🛠️ Tecnologias Utilizadas

* Python 3.10+
* Ollama
* Llama 3.2
* Pandas
* Matplotlib

## 📥 Instalação

```bash
pip install -r requirements.txt
python main.py
```

## 📊 Fluxo do Sistema

```text
Entrada da tarefa
        ↓
Aplicação das 4 técnicas
        ↓
Execução no Ollama
        ↓
Coleta de métricas
        ↓
Comparação dos resultados
        ↓
Recomendação da melhor técnica
```

## 📌 Conclusão

O Prompt Toolkit permite analisar o impacto das diferentes estratégias de Prompt Engineering, auxiliando na escolha da técnica mais eficiente para tarefas de NLP em e-commerce.
