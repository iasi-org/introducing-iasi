# Introducing IASI Visual Identity Specification

## Metadata

| Field | Value |
|---|---|
| Type | specification |
| Status | draft |
| Scope | Introducing IASI presentation |
| Template | visual |
| Sources | current approved prototype and design review conversation |

## Purpose

Define the visual identity currently accepted for **Introducing IASI**.

This specification captures the design decisions that have survived human review so far. It may evolve as the presentation grows.

## Requirements

### Base identity

- The current base background is dark.
- Primary background: near-black / deep green-black.
- Main text must use a very light neutral.
- Accent colors may use acid green and cyan.
- The visual tone must feel technical, editorial and deliberate.
- Avoid generic corporate presentation styling.

### Typography

Preferred typography:

- IBM Plex Sans for primary text and headings.
- IBM Plex Mono for technical labels, small annotations and system-like metadata.

Typography must remain legible at presentation distance.

### Cover

The cover must contain:

- `Introducing IASI`;
- subtitle: `Intelligent Assisted Software Engineering`;
- a circular `START` control;
- a short epigraph at the bottom.

The earlier phrase `A new layer for building software` must not appear.

The epigraph currently used is:

*Because when implementation costs less and less, knowledge becomes more and more valuable.*

It must behave visually like a book epigraph:

- italic;
- discreet;
- one line when viewport permits;
- placed as a footer-like element;
- slightly differentiated in color;
- no decorative rule or ornamental frame.

### Slides

- Current working background remains dark across slides until deliberately revised.
- Content should use generous spacing.
- Conceptual diagrams should use simple boxes, arrows and restrained accents.
- White detail popups may be used to contrast with the dark presentation background.

### Popups

Interactive detail panels should:

- use a white background;
- not blur the slide behind them;
- use clear visual hierarchy;
- prefer icons and short labels over dense explanatory cards;
- remain visually lighter than the base slide.

### Graphic language

- Boxes represent bounded concepts or system areas.
- Arrows represent flow.
- A larger enclosing box may represent the IASI boundary.
- Cloud imagery may represent the external world.
- Icons should be recognizable and functional rather than decorative.

## Constraints

- Do not use visual complexity simply because HTML/CSS allows it.
- Do not use decorative photography by default.
- Avoid overloading slides with effects.
- Dark styling is currently accepted as a working direction, not an immutable global brand rule for all IASI artifacts.

## Acceptance Criteria

1. Cover is recognizably distinct from a generic HTML page.
2. `START` is visually prominent and interactive.
3. Epigraph reads as editorial supporting text.
4. Dark base palette remains coherent across slides.
5. White popups remain readable over the dark slide.
6. Typography hierarchy is explicit and consistent.
7. Diagrams remain understandable at presentation distance.
8. The design can be described independently of HTMLSlides.

## Sources

- Current approved cover prototype.
- Current three-slide prototype.
- Human design review during task execution.
