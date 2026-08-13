---
theme: seriph
title: Slidev Fixture Roadmap
---

# Slidev Roadmap

<Counter :start="1" />

Notes:
Presenter notes should be collapsed below the slide.

---
layout: custom-hero
class: lead invert
background: /images/cover.png
transition: fade
---

# Implementation

- Detect Slidev metadata.
- Preserve readable Markdown.
- Avoid executing Vue.

---

# Dashboard Region

Activate visual annotation and select a specific dashboard panel.

![Fictional release operations dashboard](./assets/release-dashboard.png)

---

# Source-backed Workflow

![Release review workflow with highlighted rollback path](./assets/review-workflow.svg)

---

# Mermaid Region

```mermaid
flowchart LR
  Source --> Render --> Annotate --> Resolve
  Resolve -. rollback .-> Render
```

---

# Repeated Occurrence

![Repeated release review workflow](./assets/review-workflow.svg)

---

# Final Check

Anchors should remain stable across deck navigation.
