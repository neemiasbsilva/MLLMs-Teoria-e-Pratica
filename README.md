# MLLMs-Teoria-e-Pratica

Neste repositório se encontram os _notebooks_ desenvolvidos como exemplo prático para o minicurso apresentado durante o _WebMedia 2025_.

Os _notebooks_ foram desenvolvidos para ser executados pela plataforma [_Google Colab_](https://colab.google/).

## Classificação de Sentimentos

Em [Classify_Sentiment_DeepseekVL](use-cases\Classify_Sentiment_DeepseekVL.ipynb) é apresentado um breve tutorial sobre o uso de MLLMs para a inferência de sentimentos em imagens utilizando o modelo de MLLM DeepseekVL.

![Classificação de Sentimentos](imagens/SentimentAnalysis.png)

O tutorial aborda a configuração do ambiente, carregamento do modelo e inicialização do tokenizer, para então realizar um teste de inferência e um teste de inferência em _Batch_.

## Fine-tuning

O _notebook_ [FineTuning_ModernBERT](use-cases\FineTuning_ModernBERT.ipynb) oferece um guia para o processo de fine-tuning de LLMs Multimodais a partir do uso do modelo ModernBERT para a tarefa de classificação de sentimento. 

![Fine Tuning](imagens/FineTuning.png)

Neste _notebook_ são tratados os temas de configuração de ambiente, criação de arquivo de configuração, carregamento e preparação de dados setup do modelo e definição de funções para treinamento, para finalmente executar o _fine-tuning_ do modelo.

## Identificação de objetos

![Image Classification](imagens/ImageClassification.png)