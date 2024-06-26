---
layout: post
---
### Introduction

Due to their exceptional generation capabilities, large language models have experienced a substantial increase in their use as chatbots, LLM Agents, and several other applications. It is therefore crucial to research the security and safety-related facets of LLMs and their applications in light of this abrupt rise. Retrieval Augmented Generation (RAG) is a commonly used approach that enhances the generation capabilities of LLMs. One important but understudied area is the safety/security implications of RAG.

In this blog, we reveal how a few simple triggers can lead to the full exploitation of RAG Applications. We discovered a method to poison RAG pipelines, making the entire RAG app useless with proprietary poisoning payloads. We demonstrate a successful poisoning attack on RAG with a high Attack Success Rate (ASR) through small triggers inserted into the knowledge base documents. Stay tuned as we unveil this critical vulnerability and showcase how even minor manipulations can have drastic consequences.

### Retrieval Augmented Generation
Let’s begin with a brief introduction to RAG. RAG stands for “Retrieval-Augmented Generation,” which is a model architecture that combines retrieval-based and generation-based approaches in natural language processing. RAG is often used in question-answering and text-generation tasks.

RAG has 3 main components:

1. Knowledge Base — The knowledge base is a database, collection of documents, or any other structured or unstructured source of factual information, examples, and context that the LLM can use to generate more accurate and contextually relevant responses.

2. Retriever — The Retriever’s task is to retrieve the relevant information from the knowledge base. It ensures that the information provided to the LLM is relevant to the user’s query.

3. LLM — The LLM is the core component of the RAG framework. It is a powerful language model that is capable of generating human-like text based on the input query or context. The LLM uses the information retrieved by the retriever from the knowledge base to enhance its generation capabilities.

[Continue Reading...](https://blog.repello.ai/how-rag-poisoning-made-llama3-racist-1c5e390dd564)