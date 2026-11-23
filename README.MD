# Large Language Model from Scratch

## References: 

#### Build a Large Language Model from Scratch by Sebastian Raschka
#### Attention is all you need by Ashish Vaswani
#### Raj Abhijit Dandekar from Vizuara

AI is at the forefront of modern technology, driving innovation across many industries. While companies and consumers use AI products from OpenAI and Anthropic, it's important to understand how these systems work and why they're built the way they are. Large Language Models are the foundation of many of today's AI products, and that's what I wanted to learn. Using an article, a book, and a creator, I built this repo to show the individual parts of an LLM and to understand the model beyond simply using it.

Raschka divides LLMs into 3 stages:

#### Stage 1: Implementing LLM architecture and data preperation

Data Preprocessing: First stage of building an LLM is the data and processing it for a model to work with

    -> llm_BPE: Byte Pair Encoding, a type of tokenization in which words are broken down into subwords and those are used as tokens
    -> llm_positional_embedding: vector embedding for token IDs with addition of awareness of position for context
    -> llm_tokenizer: initial tokenization (words to tokens to token IDs)
    -> token_embedding: embedding of tokens
    -> the-verdict: text file for data

Attention models: The evolution of attention mechanism

    -> simple_attention: usage of raw token embeddings with no trainable params
    -> self_attention_tw: simple attention + 3 learned weight matrices: query, key, value
    -> causal_self_attention: usage of causal mask and dropout
    -> multi-head: utilizes multiple causal attention mechanisms

GPT Architecture: Process

    -> 



#### Stage 2: Pretraining an LLM to create a foundation model
#### Stage 3: Finetuning the foundation model 

Environment:

LLMTKN: Virtual environment with necessary imports

Runs on python 3.11.9

