---
marp: true
theme: default
paginate: true
title: Marp Fixture Roadmap
description: Commentary Marp fixture deck
---

<!-- header: Commentary fixture -->
<!-- footer: Marp preview -->

# Marp Roadmap

Rendered as a Marp deck in Commentary.

<!-- Presenter note
Use this slide to verify speaker notes collapse correctly.
-->

---

<!-- _footer: Local footer -->

# Review Flow

- Open fixture PR.
- Confirm slide controls work.
- Toggle list view.

---

# Dashboard Region

Activate visual annotation and select the blocked timeline item, a risk cell, or a chart segment.

![Fictional release operations dashboard](../assets/release-dashboard.png)

---

# Source-backed Workflow

![Release review workflow with highlighted rollback path](../assets/review-workflow.svg)

---

# Mermaid Region

```mermaid
flowchart LR
  Source --> Render --> Annotate --> Resolve
  Resolve -. rollback .-> Render
```

---

# Repeated Occurrence

The same SVG appears on another slide. Markers must remain occurrence-specific.

![Repeated release review workflow](../assets/review-workflow.svg)

---

# Final Check

The final slide keeps anchors and source-line metadata stable.
