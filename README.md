# Marp Slide Rendering Fixture

This branch demonstrates Commentary's Marp preview support.

## Manual Commentary Routes

```text
/review/github/commentary-dev/commentary-markdown-slides-fixtures/pull/7?file=slides%2Fmarp-roadmap.md
/review/github/commentary-dev/commentary-markdown-slides-fixtures/pull/7?file=slides%2Fmarp-roadmap.md&render=marp
```

## Feature Coverage

- `marp: true` frontmatter detection.
- Theme and pagination metadata.
- Global and local header/footer directives.
- Speaker notes.
- Slide navigation controls and list view toggle.
- Embedded PNG, source-backed SVG, and Mermaid visual review surfaces.
- Repeated SVG occurrences with slide-specific markers.

Activate visual annotation in the rendered deck, select a rectangle, and submit the normal comment composer. Use the dashboard for zoom and pan. Public viewing is read-only; writes require authentication.
