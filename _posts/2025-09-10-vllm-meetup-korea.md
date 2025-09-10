---
layout: post
title: "The First vLLM Meetup in Korea"
author: "Jeongin, Rebellions"
date: 2025-09-10
tags: [vllm, meetup, korea, inference, npu]
---

The first vLLM meetup in Korea was held on **August 19, 2025**, in Seoul, hosted by **Rebellions** and **Red Hat** with support from the **PyTorch Korea User Group** and **SqueezeBits**.

Here are the numbers that mattered:  
- 350+ signed up  
- Attendees from 75+ companies  
- 80% industry professionals, and 80% of those were software engineers and researchers  

A strong showing for vLLM’s debut in Korea.

---

## Highlights

### Intro to vLLM + llm-d and Deep dive into vLLM TPU Integration — *Nicolo Lucchesi*
Nicolo Lucchesi, Senior ML Engineer at Red Hat, highlighted the original innovation behind vLLM — solving challenges in KV caching and dynamic batching with a novel paged attention architecture.  
He introduced **llm-d**, a Kubernetes-native orchestration layer for distributed inference, and shared ongoing work to integrate AI accelerators like Google TPU.

---

### Building, Testing and Contributing to vLLM — *Daniele Trifirò*
Daniele Trifirò, Software Engineer at Red Hat, discussed how developers can build, test, and contribute to vLLM.  
He noted the need for hardware-specific compilation (CUDA, ROCm, TPU) and introduced vLLM’s **hardware plugin system** — making vLLM more device-agnostic and strengthening its role in scalable AI serving.

---

### Supercharging Rebellions NPU with vLLM — *Hong-seok Kim*
Hong-Seok Kim, Chief Software Architect at Rebellions, explained how vLLM’s plugin system enables seamless deployment on custom NPUs.  
Thanks to vLLM, engineers can now run **Mixture of Experts (MoE)** models directly on Rebellions’ NPU with parallelism and continuous batching — all without complex integration steps.

---

### Quantization and Evaluation with vLLM — *Hyungjun Kim*
Hyungjun Kim from SqueezeBits emphasized quantization as essential for LLM deployment.  
He introduced:
- **LLM Compressor** (for quantization integration)  
- **Fits on Chips** (for evaluating serving performance across throughput, latency, accuracy, hardware)

---

## Looking Ahead
The meetup also looked ahead to growing the vLLM community in Korea with regular meetups, workshops, and collaboration with groups like PyTorch Korea and Python Korea.  

This inaugural meetup marked an exciting step, reaffirming what matters most: **practical, scalable solutions for real-world AI serving**.  

Rebellions, Red Hat, and passionate engineers across the region are committed to supporting more community-driven events and contributions to the vLLM project.  

Thanks to everyone who joined and made this first gathering a success — **we’re just getting started.**
