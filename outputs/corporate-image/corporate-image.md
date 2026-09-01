# Introducing IASI — Corporate Image

## Metadata

| Field | Value |
|---|---|
| Type | materialized-output |
| Source specification | `B-engine/specifications/corporate-image.md` |
| Task | `B-engine/tasks/define-corporate-image.md` |
| Execution | v2 |
| Status | review |
| Scope | `Introducing IASI` |
| Renderer dependency | none |

## Design direction

The visual identity of **Introducing IASI** is based on one idea:

> **Engineering clarity before visual decoration.**

The presentation should feel editorial, technical and deliberate. It should use large amounts of space, strong hierarchy and simple geometric relationships. The visual system must make concepts easier to understand, not make slides look busy.

The identity is intentionally independent from HTMLSlides. HTMLSlides may later implement this system, but does not define it.

## Typography

The primary typographic family is **IBM Plex**.

### Primary

```text
IBM Plex Sans
```

Used for:

- cover titles;
- slide titles;
- body text;
- labels;
- narrative statements;
- diagram labels.

### Technical

```text
IBM Plex Mono
```

Used for:

- code;
- identifiers;
- file paths;
- commands;
- technical annotations where monospacing has semantic value.

### Fallbacks

```text
"IBM Plex Sans", system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif
```

```text
"IBM Plex Mono", ui-monospace, "Cascadia Code", "SFMono-Regular", Consolas, monospace
```

IBM Plex is part of the visual identity, but the presentation must remain usable if a renderer temporarily falls back to a system font.

For final materialization, the project must decide how IBM Plex is made available without creating an unwanted runtime dependency on an external service.

### Hierarchy

| Use | Size at 1920×1080 | Weight | Notes |
|---|---:|---:|---|
| Cover title | 76 px | 700 | Maximum two lines |
| Slide title | 56 px | 700 | Left aligned |
| Section title | 64 px | 700 | May be used alone |
| Key statement | 42 px | 600 | Short sentence or principle |
| Body | 30 px | 400 | Prefer short blocks |
| Diagram label | 24 px | 600 | Direct labels |
| Supporting label | 20 px | 600 | Uppercase only when useful |
| Code / technical | 24 px | 500 | IBM Plex Mono |

## Color system

| Token | Value | Purpose |
|---|---|---|
| `canvas` | `#F7F8FA` | Default background |
| `surface` | `#FFFFFF` | Cards or isolated areas when needed |
| `ink` | `#111827` | Primary text and dark sections |
| `muted` | `#5B6472` | Secondary text / OUTSIDE / context |
| `primary` | `#1F4FD1` | IASI, INPUTS, active conceptual focus |
| `secondary` | `#0A6F78` | OUTPUTS, validated/result state |
| `emphasis` | `#B54708` | Decision, warning, exception, tension |
| `line` | `#D7DDE8` | Rules and non-semantic borders |
| `soft` | `#E8EDF7` | Quiet grouping / secondary surfaces |

## Composition

The canonical canvas is **16:9**.

At 1920×1080:

- horizontal safe margin: `96 px`;
- vertical safe margin: `72 px`;
- preferred content width: no more than `1600 px`;
- base spacing unit: `8 px`;
- common large gaps: `32 / 48 / 64 / 96 px`.

Slides are predominantly left aligned. Centered compositions are reserved for deliberate moments such as section breaks or a single dominant statement.

## Graphic language

Use a deliberately small vocabulary:

- rectangle: system, stage, artifact, bounded concept;
- circle: actor, agent, source or external entity when appropriate;
- line / arrow: direction, transformation or dependency;
- thin rule: separation, never decoration.

Default corner radius: `14 px`.

Default border: `2 px`.

Shadows are avoided by default.

### IASI flow semantics

| Concept | Visual treatment |
|---|---|
| OUTSIDE | neutral / `muted` |
| INPUTS | `primary` |
| ENGINE | `ink` / structural treatment |
| OUTPUTS | `secondary` |
| decision / tension / exception | `emphasis` |

Canonical relationship:

```text
OUTSIDE → INPUTS → ENGINE → OUTPUTS → OUTSIDE
```

## Imagery

Photography and generated illustration are not part of the default identity.

The default visual language is:

```text
type + geometry + relationships + space
```

## Motion

Motion may reveal narrative order, but must never carry information that disappears when motion is unavailable.

## What to avoid

- gradients as decoration;
- large shadows;
- glass effects;
- stock presentation icons used as filler;
- dense card grids;
- excessive rounded containers;
- decorative arrows;
- copied documentation paragraphs;
- multiple competing accent colors;
- presentation-framework default styling.

## Review state

This is **execution v2** of `define-corporate-image`.

The specification has not changed.

The previous execution remains valid historical evidence but is not accepted as final because its typographic decision was reopened during human review.

This execution remains in **review** until the human reviewer accepts or requests further adjustment.
