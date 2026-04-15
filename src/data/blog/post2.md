---
title: "LoRA - Efficient Fine-Tuning Notes"
description: "A practical summary of Low-Rank Adaptation (LoRA) for fine-tuning large language models."
pubDate: 2026-03-30
category: "paper"
draft: false
---

# LoRA: Low-Rank Adaptation of Large Language Models (2021)

## Why it matters

LoRA makes fine-tuning large models much cheaper by freezing base weights and training low-rank adapters.

## Core idea

Instead of updating full weight matrices, LoRA injects trainable rank-decomposition matrices into attention layers.

## My key takeaways

- Big reduction in trainable parameters and GPU memory usage.
- Similar quality to full fine-tuning for many downstream tasks.
- Great fit for personal projects and rapid experimentation.

## Link

- [Paper](https://arxiv.org/abs/2106.09685)
