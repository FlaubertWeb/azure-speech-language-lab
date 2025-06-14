# Laboratório: Análise de Fala e Linguagem com Azure Speech Studio e Language Studio

Repositório criado para o desafio prático do bootcamp DIO/Suzano.

---

## Passo a passo realizado no laboratório

### 1. Criação do projeto no Azure AI Foundry portal

- Acesse o [Azure AI Foundry portal](https://ai.azure.com) e faça login com sua conta Azure.
- No menu de recursos, clique em **Create** para criar um novo recurso.
- No assistente, dê um nome ao seu projeto, escolha assinatura, grupo de recursos e região (East US, France Central, Korea Central, West Europe ou West US).
- Aguarde a criação do projeto e acesse a página de **Overview**.

---

### 2. Speech Studio: Transcrição de fala para texto

- No menu à esquerda, clique em **Playgrounds** e selecione o tile **Speech playground**.
- Escolha **Real-time transcription** em "Try out Speech capabilities".
- Baixe o arquivo de exemplo `speech.zip` pelo link [https://aka.ms/mslearn-speech-files](https://aka.ms/mslearn-speech-files).
- Faça upload do arquivo de áudio `WhatAICanDo.m4a` para transcrever em tempo real.
- Acompanhe a transcrição automática gerada e avalie a precisão do reconhecimento.

---

### 3. Language Studio: Análise de texto

- No menu à esquerda, acesse **Playgrounds** e selecione **Language playground**.
- Teste as principais capacidades de NLP (Processamento de Linguagem Natural):

#### a) Extração de entidades nomeadas (Named Entities)
- Clique em **Extract information** > **Extract named entities**.
- Cole o texto de exemplo fornecido (review de hotel).
- Execute a análise e observe entidades extraídas e as pontuações de confiança.

#### b) Extração de frases-chave (Key Phrase Extraction)
- Em **Extract information**, selecione **Extract key phrases**.
- Cole o segundo texto de review de hotel.
- Veja as frases-chave identificadas pelo serviço.

#### c) Sumarização de texto (Summarization)
- Em **Summarize information**, selecione **Summarize text**.
- Cole o terceiro texto de review de hotel.
- Observe a síntese automática das informações principais do texto.

---

### 4. Limpeza de recursos

- Para evitar custos, acesse o [Azure Portal](https://portal.azure.com), encontre o grupo de recursos criado, selecione e exclua os recursos do laboratório.

---

## Principais aprendizados

- Como criar projetos e hubs no Azure AI Foundry portal.
- Uso do Speech Studio para transcrição automática de áudio para texto.
- Aplicação do Language Studio para análise de sentimentos, extração de entidades e frases-chave, e sumarização de textos.
- Compreensão prática das ferramentas de NLP e reconhecimento de fala da Microsoft Azure.
- Importância da limpeza de recursos para evitar custos indesejados.

---

## Links úteis

- [Azure Speech Studio (Speech to Text e Text to Speech)](https://aka.ms/ai900-speech)
- [Azure Language Studio (Análise de Texto)](https://aka.ms/ai900-text-analysis)

---

*Material produzido como parte do desafio prático do bootcamp Python Fundamentals – DIO/Suzano.*
