LLMTKN: Virtual environment with necessary imports

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
    -> multi-head
