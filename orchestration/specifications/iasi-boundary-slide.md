# IASI Boundary Slide Specification

## Metadata

| Field | Value |
|---|---|
| Type | specification |
| Status | draft |
| Scope | Conceptual IASI system-boundary slide |
| Presentation | Introducing IASI |
| Sources | current IASI model decisions and approved prototype |

## Purpose

Explain the external shape of IASI in one conceptual slide.

The slide must show that IASI has a simple external contract while allowing adaptive internal engineering.

## Base Diagram

The base diagram must communicate:

`OUTSIDE → INPUTS → ENGINE → OUTPUTS → OUTSIDE`

`INPUTS`, `ENGINE` and `OUTPUTS` must be enclosed within a larger box labeled `IASI`.

The two `OUTSIDE` elements must remain outside that boundary.

The slide footer should communicate:

*One entry. One exit. The cycles are internal.*

## Interactive Detail

### External source / left OUTSIDE

Clicking the left `OUTSIDE` must open a white popup explaining that external material:

- originates outside IASI;
- may be information, documents, messages, images, data or other source material;
- enters in its original form;
- is not normalized.

The popup should visually show common source formats, including examples such as:

- PDF / Acrobat;
- Word;
- PowerPoint;
- Excel;
- email;
- image;
- other files.

Prefer recognizable icons over text-heavy cards.

### Inputs

Clicking `INPUTS` must open a white popup explaining that inputs are organized by provenance.

It must show the three input areas:

- `externals`;
- `internals`;
- `authored`.

Meaning:

#### externals

Material originating outside IASI and preserved as received.

#### internals

Knowledge and decisions created inside the IASI engineering process.

#### authored

Material deliberately authored or prepared as explicit project input.

The classification is based on provenance and engineering role, not on whether a human or an AI produced the file.

### Engine

Clicking `ENGINE` must open a white popup showing the engineering process:

`UNDERSTAND → SPECIFY → PLAN → EXECUTE → VERIFY → AUTHORIZE`

Meaning:

- **Understand**: interpret inputs and establish understanding.
- **Specify**: turn understanding into explicit requirements and contracts.
- **Plan**: determine the work required.
- **Execute**: perform the work and materialize results.
- **Verify**: determine whether the produced result satisfies its specification and acceptance criteria.
- **Authorize**: approve the verified result for delivery.

Authorization occurs after verification.

### Outputs

Clicking `OUTPUTS` must open a white popup explaining the distinction between output and deliverable.

The visual flow must be:

`OUTPUT → VERIFY → AUTHORIZE → DELIVERABLE`

Rules:

- Tasks materialize results in outputs.
- Outputs remain inside IASI.
- Verification determines whether an output satisfies its requirements.
- Authorization may be automatic or human.
- Only an authorized output becomes a deliverable.
- Only deliverables may leave IASI.

The popup should include the statement:

*Outputs are produced. Deliverables are authorized.*

### Delivery / right OUTSIDE

Clicking the right `OUTSIDE` must open a white popup explaining delivery targets.

It should show representative destinations such as:

- Human / Client;
- Repository;
- Deployment / Runtime;
- Publication;
- Communication;
- Package / distributable artifact.

The popup should communicate:

*Deliverables leave IASI. Outputs do not.*

## Interaction Requirements

- Every detail opens on the same slide.
- Only one detail popup should be open at a time.
- Popups must close through a visible close button and `Escape`.
- Slide navigation must close open detail panels.
- The base diagram must remain understandable without opening any popup.

## Constraints

- Do not turn the slide into a folder tree.
- `ENGINE` must be represented as process, not storage.
- `OUTPUTS` must not be confused with deliverables.
- External sources and delivery destinations must represent different semantics.
- The right `OUTSIDE` is destination, not another list of output formats.

## Acceptance Criteria

1. IASI boundary visibly contains `INPUTS`, `ENGINE` and `OUTPUTS`.
2. Both `OUTSIDE` elements remain visibly outside the IASI boundary.
3. The flow direction is immediately understandable.
4. Each of the five conceptual areas is interactive.
5. All five popups remain on the same slide.
6. `ENGINE` includes `AUTHORIZE` after `VERIFY`.
7. `OUTPUTS` distinguishes outputs from deliverables.
8. Authorization explicitly supports automatic and human approval.
9. Delivery targets are shown only after the deliverable concept.
10. The base slide remains understandable without interaction.

## Sources

- Current IASI working model.
- Approved interactive prototype.
- Human review decisions from the current task execution.
