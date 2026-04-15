---
title: "Attention Is All You Need - Notes"
description: "A concise breakdown of the Transformer paper and why self-attention changed sequence modeling."
pubDate: 2026-03-22
category: "paper"
draft: false
---

# Attention Is All You Need (2017)

## Why I picked this paper

This paper introduced the Transformer architecture and removed recurrence from sequence modeling.

## Core idea

The model uses self-attention to let each token attend to all other tokens in parallel, improving both training speed and long-range dependency handling.

## My key takeaways

- Positional encoding is essential because attention alone has no sense of order.
- Multi-head attention helps the model learn different relation types at once.
- Removing recurrence allows much better parallelism on modern hardware.

## Link

- [Paper](https://arxiv.org/abs/1706.03762)