---
layout: page
title: AEGIS
description: AEGIS artifacts
img: assets/img/publication_preview/aegis.png
importance: 1
category: research
---

AEGIS is a server-scale runtime scheduling system for controlled collocation of deep learning training workloads on shared multi-GPU servers. It separates memory feasibility from runtime-pressure eligibility, temporarily withholds GPUs after each placement until meaningful GPU activity is observed, and uses activity-anchored telemetry to decide when further collocation is appropriate. AEGIS supports configurable memory inputs and placement policies, and includes OOM-aware recovery that retries failed jobs under progressively safer memory conditions.

**Links:**  
[GitHub](https://github.com/ehsanyousefzadehasl/AEGIS)
