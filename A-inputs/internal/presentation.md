# Introducing IASI Presentation

## Metadata

| Field | Value |
|---|---|
| Type | internal input |
| Status | accepted |
| Scope | Introducing IASI |
| Provenance | Decisions produced inside the IASI engineering process |

## Decision

**Introducing IASI** will be materialized as an HTMLSlides presentation.

HTMLSlides is the renderer and presentation infrastructure. It does not define the visual identity, narrative, content or engineering model of IASI.

## Presentation behaviour

The deck must behave as a presentation rather than as a vertically scrolling web page.

The current interaction model is:

- exactly one slide visible at a time;
- keyboard navigation between slides;
- mouse-wheel navigation changes slide instead of scrolling a document;
- `START` on the cover begins the presentation;
- interactive details may open inside the current slide;
- opening detail must not navigate to another slide;
- leaving a slide closes its open detail.

## Narrative approach

The presentation should introduce IASI progressively.

It should prefer:

- little text on the base slide;
- strong conceptual statements;
- diagrams where structure matters;
- interaction where progressive explanation helps;
- speaker notes for presenter detail.

The presentation is not intended to be:

- a repository catalogue;
- a technical manual;
- a projected web document.

## Speaker notes

Speaker notes are part of the presentation artifact.

They should contain what the presenter would actually say and the essential talking points.

They should not describe how the HTML, CSS or JavaScript was implemented.

## Current direction

The presentation will be developed incrementally.

A slide may first establish a simple concept and then expose detail through interaction rather than placing all information on screen at once.

## Sources

- EDR-20013
- HTMLSlides documentation
- Current Introducing IASI engineering conversation
