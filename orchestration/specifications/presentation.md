# Introducing IASI Presentation Specification

## Metadata

| Field | Value |
|---|---|
| Type | specification |
| Status | draft |
| Scope | Introducing IASI presentation |
| Renderer | HTMLSlides |
| Sources | business case, HTMLSlides decision, current approved presentation prototype |

## Purpose

Define the presentation-level requirements for **Introducing IASI**.

The presentation must introduce IASI progressively, visually and with enough interaction to explain the model without becoming a technical manual.

## Requirements

### Presentation model

- The presentation must be materialized with HTMLSlides.
- It must behave as a presentation, not as a vertically scrolling web page.
- Exactly one slide must be visible at a time.
- Navigation must support the HTMLSlides presentation model.
- The `START` control on the cover must navigate to the next slide.
- Interactive elements inside a slide must not navigate away from that slide unless explicitly intended.

### Narrative

The presentation must progressively explain:

1. what IASI is;
2. why it exists;
3. the external shape of the system;
4. how inputs, engine and outputs work;
5. how outputs become deliverables;
6. how deliverables leave IASI.

The presentation should remain conceptual before becoming technical.

### Content density

- Slides should contain little text.
- Ideas should be expressed progressively.
- Diagrams and interaction should carry meaning, not decoration.
- Long explanations should be placed in speaker notes or interactive detail panels rather than on the base slide.

### Speaker notes

Every slide must include speaker notes with:

- title;
- spoken script;
- key points.

Speaker notes must describe what the presenter says, not implementation details.

### Interaction

- Popups must open on the same slide.
- Popups must be closable with a visible close control.
- Popups should also close with `Escape`.
- Opening a popup must not alter the current slide.
- Moving to another slide must close any open popup.

## Constraints

- The presentation must not depend conceptually on HTMLSlides styling defaults.
- HTMLSlides is the renderer, not the visual identity.
- The deck should remain understandable even if interactive details are not opened.
- Avoid turning the deck into a web application.

## Acceptance Criteria

1. One slide is visible at a time.
2. `START` navigates to slide 2.
3. Keyboard navigation works.
4. Slide-local interactions remain on the current slide.
5. Every slide contains speaker notes.
6. The deck can be understood as a coherent narrative without reading implementation code.
7. Visual identity is governed by the visual specification.
8. The IASI model slide is governed by its dedicated specification.

## Sources

- `A-inputs/externals/business-case.qmd`
- `A-inputs/internal/htmlslides.md`
- `EDR-20013`
