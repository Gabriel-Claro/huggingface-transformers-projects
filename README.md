# 🤗 Hugging Face Transformers Projects

Coleção de projetos práticos de **Inteligência Artificial** utilizando modelos pré-treinados do **Hugging Face Transformers** para aplicações de Processamento de Linguagem Natural (NLP), Visão Computacional e IA Conversacional.

O projeto explora diferentes pipelines e modelos de Machine Learning por meio de aplicações práticas desenvolvidas em Python.

---

## 🎯 Objetivo

Explorar a utilização de modelos pré-treinados do Hugging Face em diferentes tarefas de Inteligência Artificial, compreendendo desde o uso de pipelines até a criação de aplicações interativas com Gradio.

---

## 📚 Projetos desenvolvidos

### 📊 1. Sentiment Analysis

Análise automática de sentimentos em avaliações de produtos.

O modelo classifica avaliações como **POSITIVE** ou **NEGATIVE** e os resultados são organizados e analisados utilizando Pandas e ferramentas de visualização de dados.

**Modelo utilizado:**

`distilbert-base-uncased-finetuned-sst-2-english`

**Conceitos aplicados:**

- Hugging Face Pipeline
- Sentiment Analysis
- Pandas
- Visualização de dados
- WordCloud

---

### 🏷️ 2. Zero-Shot Classification

Classificação automática de produtos em categorias sem necessidade de treinamento específico do modelo.

O sistema recebe descrições de produtos e utiliza categorias pré-definidas para determinar automaticamente a classificação mais provável.

**Modelo utilizado:**

`facebook/bart-large-mnli`

**Conceitos aplicados:**

- Zero-Shot Classification
- Candidate Labels
- Scores de confiança
- Hugging Face Pipeline

---

### 🖼️ 3. Background Removal

Aplicação de Visão Computacional para remoção automática do fundo de imagens.

Foi desenvolvida uma interface utilizando **Gradio**, permitindo enviar uma imagem e obter como resultado a imagem processada sem o fundo.

**Modelo utilizado:**

`briaai/RMBG-1.4`

**Conceitos aplicados:**

- Image Segmentation
- Background Removal
- Hugging Face Pipeline
- Gradio

---

### ❓ 4. Question Answering — FAQ Automation

Sistema de perguntas e respostas capaz de localizar informações automaticamente dentro de um contexto fornecido.

Como exemplo, foi desenvolvido um FAQ no qual o usuário pode realizar perguntas relacionadas às informações de uma loja.

**Modelo utilizado:**

`distilbert-base-cased-distilled-squad`

**Conceitos aplicados:**

- Question Answering (QA)
- Context
- Question
- Score de confiança
- Gradio

---

### 🤖 5. Conversational AI

Desenvolvimento de um chatbot utilizando o modelo **DialoGPT** da Microsoft.

O projeto trabalha com tokenização, geração de texto e manutenção do histórico da conversa para permitir interações entre usuário e modelo.

**Modelo utilizado:**

`microsoft/DialoGPT-small`

**Conceitos aplicados:**

- AutoTokenizer
- AutoModelForCausalLM
- Tokenização
- Decodificação
- Geração de texto
- Histórico de conversa
- Chatbot conversacional

---

## 🛠️ Tecnologias utilizadas

- Python
- Hugging Face Transformers
- PyTorch
- Pandas
- Matplotlib
- Plotly
- WordCloud
- Gradio
- Google Colab

---

## 🧠 Principais conceitos praticados

- Processamento de Linguagem Natural (NLP)
- Hugging Face Pipelines
- Sentiment Analysis
- Zero-Shot Classification
- Question Answering
- Conversational AI
- Image Segmentation
- Modelos pré-treinados
- AutoTokenizer
- AutoModelForCausalLM
- Interfaces de IA com Gradio

---

## 📂 Estrutura do repositório

```text
.
├── HuggingFace_Transformers_Projects.ipynb
├── README.md
├── requirements.txt
└── .gitignore
