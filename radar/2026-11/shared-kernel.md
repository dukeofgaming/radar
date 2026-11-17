---
title: Shared kernel
ring: "< 1 year"
quadrant: methods-and-patterns
tags:
  - architecture
  - ddd
---

A shared kernel, code that every feature imports, is something he has written down as a thing to avoid while a domain is still being discovered. A private knowledge notebook says slices should duplicate rather than share, and a later note allows a small kernel as the exception. [hotto-test](https://github.com/dukeofgaming/hotto-test), the survey app, keeps each slice's model inside the slice.
