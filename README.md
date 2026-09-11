# Grandes Modelos de Linguagem Multimodais (MLLMs): Da Teoria à Prática

[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?&style=flat&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-%F0%9F%A4%97-yellow)](https://huggingface.co/)
[![LangGraph](https://img.shields.io/badge/LangGraph-black?style=flat&logo=langchain&logoColor=white)](https://langchain-ai.github.io/langgraph/)

## Sobre o Evento (WebMedia 2025)

Realizado anualmente pela Sociedade Brasileira de Computação (SBC), o Simpósio Brasileiro de Sistemas Multimodais e Web (WebMedia) é o principal evento do tema no Brasil e uma excelente oportunidade de intercâmbios científico e técnico entre alunos, pesquisadores e profissionais das áreas de Multimídia, Hipermídia e Web.

Em 2025, especialmente, estaremos celebrando a 31ª edição do WebMedia, com organização da Pontifícia Universidade Católica do Rio de Janeiro (PUC-Rio) e do Instituto Militar de Engenharia (IME).

---

Este repositório contém os *notebooks* desenvolvidos como exemplos práticos para o minicurso "MLLMs: Teoria e Prática", apresentado durante o **[WebMedia 2025](https://webmedia.org.br/2025/)** na PUC-RIO.

O objetivo é fornecer guias práticos sobre como aplicar Modelos de Linguagem Multimodais (MLLMs) em diferentes tarefas, como classificação de sentimentos e *fine-tuning*.

## Como Executar

Todos os *notebooks* foram desenvolvidos para execução direta na plataforma [Google Colab](https://colab.google/). Basta clicar no emblema "Open in Colab" correspondente ao caso de uso que você deseja explorar.

## Notebooks Práticos

### 1. Classificação de Sentimentos com DeepseekVL

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neemiasbsilva/MLLMs-Teoria-e-Pratica/blob/main/use-cases/Classify_Sentiment_DeepseekVL.ipynb)

* **Arquivo:** `use-cases/Classify_Sentiment_DeepseekVL.ipynb`
* **Descrição:** Um tutorial sobre o uso de MLLMs para inferência de sentimentos em imagens. Aborda a configuração do ambiente, carregamento do modelo (DeepseekVL), inicialização do *tokenizer*, e testes de inferência (única e em *batch*).

![Classificação de Sentimentos](imagens/SentimentAnalysis.png)

### 2. Fine-tuning de MLLMs com ModernBERT

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neemiasbsilva/MLLMs-Teoria-e-Pratica/blob/main/use-cases/FineTuning_ModernBERT.ipynb)

* **Arquivo:** `use-cases/FineTuning_ModernBERT.ipynb`
* **Descrição:** Um guia para o processo de *fine-tuning* de MLLMs (usando o modelo ModernBERT) para a tarefa de classificação de sentimento. Cobre a criação de arquivos de configuração, preparação de dados, *setup* do modelo e a execução do treinamento.

<img src="imagens/mllmsent.png" title="MLLMSent"/>
<img src="imagens/FineTuning.png" title="Fine Tuning"/>

### 3. Identificação de Objetos (Adaptação de Prompt)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neemiasbsilva/MLLMs-Teoria-e-Pratica/blob/main/use-cases/IdentifyFeatures.ipynb)

* **Arquivo:** `use-cases/IdentifyFeatures.ipynb`
* **Descrição:** Este *notebook* introduz uma simples adaptação da tarefa de classificação para a identificação de objetos. A diferença principal está na estruturação do *prompt*, que busca obter uma saída estruturada para facilitar o processamento.

<figure>
<img src="imagens/ImageClassification.png" title="Classificação de Imagens"/>
<figcaption>Crédito: Imagem de Sebastian Raschka</figcaption>
</figure>

### 4. RAG com LangGraph

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neemiasbsilva/MLLMs-Teoria-e-Pratica/blob/main/use-cases/agent_rag_langgraph.ipynb)

* **Arquivo:** `use-cases/agent_rag_langgraph.ipynb`
* **Descrição:** Um *notebook* demonstrando a implementação de um pipeline de RAG (Retrieval-Augmented Generation) utilizando a biblioteca LangGraph para orquestrar o fluxo de dados e estados.

![Pipeline RAG com LangGraph](imagens/pipeline-mllm.png)

---

## Paper e Citação

Caso faça uso deste trabalho, por favor cite o [capítulo]([https://arxiv.org/abs/2602.12302](https://books-sol.sbc.org.br/index.php/sbc/catalog/view/208/934/2001)):

```
@incollection{dasilva2025mllms,
  author    = {da Silva, Neemias and Scholz, J{\'u}lio C. W. and Harrison, John and Borges, Marina and {\'A}vila, Paulo and Santos, Frances A. and Delgado, Myriam and Minetto, Rodrigo and Silva, Thiago H.},
  title     = {Grandes Modelos de Linguagem Multimodais ({MLLMs}): Da Teoria {\`a} Pr{\'a}tica},
  booktitle = {Minicursos do WebMedia 2025},
  editor    = {Viana de Carvalho, Windson and Goularte, Rudinei and Willrich, Roberto and Barr{\'e}re, Eduardo and Colcher, Sergio and Duarte, Julio Cesar and da Veiga, {\'A}lvaro},
  chapter   = {1},
  publisher = {Sociedade Brasileira de Computa{\c{c}}{\~a}o},
  address   = {Porto Alegre, RS, Brasil},
  year      = {2025},
  isbn      = {978-85-7669-679-7},
  doi       = {10.5753/sbc.20879.7.1},
  url       = {https://books-sol.sbc.org.br/index.php/sbc/catalog/view/208/935/2002},
  language  = {Portuguese}
}
```
