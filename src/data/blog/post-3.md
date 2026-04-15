---
title: "RAG for Knowledge-Intensive NLP Tasks - Notes"
description: "A short walkthrough of Retrieval-Augmented Generation and why grounding improves factual outputs."
pubDate: 2026-04-08
category: "paper"
draft: false
---

# Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (2020)

## Why I picked this paper

RAG is foundational for building trustworthy assistants that can cite external knowledge.

## Core idea

The approach combines neural retrieval with sequence generation so the model conditions answers on retrieved passages.

## My key takeaways

- Retrieval quality is as important as generator quality.
- Grounded generation helps reduce hallucinations.
- RAG pipelines map well to production systems with vector databases.

## Link

- [Paper](https://arxiv.org/abs/2005.11401)
