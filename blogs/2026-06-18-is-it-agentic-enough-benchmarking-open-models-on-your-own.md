---
title: "Is it agentic enough? Benchmarking open models on your own tooling"
url: "https://huggingface.co/blog/is-it-agentic-enough"
date: "2026-06-18"
feed_url: "https://huggingface.co/blog/feed.xml"
---
This article introduces an evaluation framework that measures not just whether agents succeed but how much effort success requires, examining token usage, latency, error rates, and the paths agents take through libraries. Testing the harness on the transformers library across various open models revealed that improvements beneficial for large models sometimes created problems for smaller ones, a tradeoff invisible when only checking final answers.
