---
title: Vertical slicing
ring: "1+ years"
quadrant: methods-and-patterns
tags:
  - architecture
---

Vertical slicing means one feature is carried through from the test to the interface, instead of a layer at a time. [hotto-test](https://github.com/dukeofgaming/hotto-test), the survey app, is organized that way. [scriptorium](https://github.com/dukeofgaming/scriptorium/pull/7), the Markdown sync CLI, and [detent](https://github.com/dukeofgaming/detent/tree/cucumber), the BPMN converter, each keep one slice per pull request.
