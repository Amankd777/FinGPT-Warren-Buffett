# Finance Chatbot with GPT-3 using ADA-002 Embeddings

## Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [Technologies](#technologies)
- [Data Collection](#data-collection)
- [Customized Prompts](#customized-prompts)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)

## Introduction

Welcome to FinanceChatbot, an AI-powered assistant crafted using OpenAI's advanced GPT-3 model enhanced with ADA-002 embeddings. This chatbot serves as a knowledgeable companion for financial discussions, offering insightful advice and answers. It taps into the wisdom of renowned investors Warren Buffet and Charlie Munger, drawing from transcribed interviews sourced from YouTube audio files.

## Key Features

- **Natural Language Understanding:** FinanceChatbot harnesses the capabilities of GPT-3, enabling seamless interaction through natural language inputs and generating human-like responses.
- **Empowered by ADA-002 Embeddings:** The chatbot is empowered by ADA-002 embeddings, ensuring the responses it generates are contextually rich and coherent.
- **Informed Financial Insights:** Drawing from the wisdom shared in interviews with Warren Buffet and Charlie Munger, the chatbot offers advice rooted in their vast experience and expertise.

## Technologies

The FinanceChatbot integrates the following technologies:

- [OpenAI GPT-3](https://openai.com): The backbone of the chatbot's language understanding and response generation.

- ADA-002 Embeddings: Leveraging ADA-002's capabilities, the chatbot provides responses that are more contextually accurate and relevant.

- [YouTube-DL](https://github.com/ytdl-org/youtube-dl): The tool employed for downloading audio files from YouTube interviews.

## Data Collection

Our chatbot's training data was carefully curated from YouTube interviews featuring Warren Buffet and Charlie Munger. Utilizing YouTube-DL, audio files were obtained and subsequently transcribed to assemble the training dataset.

## Customized Prompts

To optimize the chatbot's responses and ensure relevance to financial queries, we meticulously engineered custom prompts. This approach ensures that the chatbot generates meaningful and contextually precise answers.

## Installation

To deploy the FinanceChatbot locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Amankd777/fFinGPT-Warren-Buffett.git
   cd finance-chatbot
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```


4. Obtain API keys for GPT-3 and ADA-002 embeddings, and add them to the designated configuration files.

5. Launch the chatbot:

```python
python app.py

```

##Usage
Once the chatbot is up and running, engage with it by entering your financial queries or seeking investment advice. The chatbot will provide insightful responses based on its training data.

##Contribution
We welcome contributions to enhance the chatbot's knowledge base, improve responses, and expand its financial expertise.

Please note that the FinanceChatbot is designed as a prototype and for illustrative purposes, and may not be actively developed further.
