---
title: Shared kernel
ring: hold
quadrant: methods-and-patterns
tags:
  - architecture
  - ddd
---

Sorcerer ADR 0002 forbids a shared kernel between slices while the domain is still being discovered, and prefers duplication. ADR 0008 later allows a small microkernel, which is the exception.
