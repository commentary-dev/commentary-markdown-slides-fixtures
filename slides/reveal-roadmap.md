reveal: true

<!-- .slide: data-background="cover.png" class="center" -->

# Reveal Roadmap

Rendered as a Reveal.js deck in Commentary.

Notes:
Presenter notes should be collapsed below the slide.

---

# Horizontal Slide

- First item
<!-- .element: class="fragment fade-in" data-fragment-index="1" -->

- Second item
<!-- .element: class="fragment fade-in" data-fragment-index="2" -->

--

# Dashboard Region

Activate visual annotation and select a specific dashboard panel.

![Fictional release operations dashboard](../assets/release-dashboard.png)

--

# Source-backed Workflow

![Release review workflow with highlighted rollback path](../assets/review-workflow.svg)

--

# Mermaid Region

```mermaid
flowchart LR
  Source --> Render --> Annotate --> Resolve
  Resolve -. rollback .-> Render
```

--

# Repeated Occurrence

![Repeated release review workflow](../assets/review-workflow.svg)

--

# Vertical Child

This slide verifies vertical slide labels.

---

# Attribute Fallback

<!-- .slide: data-background="cover.png" {bad} -->

This slide intentionally includes invalid attribute syntax for warning coverage.
