# HTML Retrieval

Written by Tiger Li, Dec 19, 2023

## Abstract
As the Retrieval-Augmented Generation (RAG) technique on LLM advanced, it made use of the capacity to absorb external knowledge. Multimodal data sources like text, audio, and graphics have long been used by LLMs. However, HTML documents present a different opportunity and challenge for LLMs because of their rich content and distinctive structure. This study aims to improve the narrative qualities of LLMs by creating and assessing strategies for efficiently retrieving HTML content from queries.

## Preliminaries 
This repo explores various rich text embedding approaches for HTML documents. These are mainly transformer-encoder-based models: Sentense-Transformer, MarkupLM, and Dense Passage Retriever (DPR). The code implementations are derived from the HuggingFace model tutorial.

Briefly, we designed a simple experiment: given a Natural Language(NL) query, can we look up the relevant HTML pages based on the embedding vector? Testing results can be found in the `img` folder. The result reveals that more optimization spaces could be involved for better accuracy.

## Dev Env
Python(Jupyter) + Langchain - Retrieval Library + Transformers
