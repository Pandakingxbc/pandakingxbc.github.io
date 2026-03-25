---
layout: page
title: InfoNav
description: VLM-driven Embodied Navigation System
img: assets/img/infonav.jpg
importance: 1
category: research
---

## InfoNav: A Unified Value Framework Integrating Semantics Value and Information Gain for Navigation

**Duration:** Nov 2025 - Mar 2026
**Status:** IROS 2026 Under Review

### Overview

InfoNav is a zero-shot Object Navigation system for indoor environments that enables robots to navigate based on natural language instructions without prior training on specific environments.

### Key Features

- **Fast-Slow Dual-System Architecture**: Decouples VLM inference from robot control loops, achieving 20x speedup (from 10s to 0.5s decision latency)
- **LLM Agent Decision Module**: Utilizes DeepSeek-V3 for high-level semantic reasoning and exploration strategy generation
- **VLM Semantic Perception**: Integrates Qwen3-VL / BLIP2 for environment semantic understanding

### Technical Highlights

1. Unified value framework combining semantic value and information gain
2. Language-conditioned navigation without environment-specific training
3. Validated on HM3D / MP3D datasets and real robot platforms

### Links

- [GitHub Repository](https://github.com/Pandakingxbc/InfoNav)
- Paper: Under Review at IROS 2026
