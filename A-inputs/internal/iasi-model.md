# IASI External Model

## Metadata

| Field | Value |
|---|---|
| Type | internal input |
| Status | accepted |
| Scope | IASI conceptual model |
| Provenance | Engineering decisions produced inside IASI |

## External shape

IASI has a simple external shape:

`OUTSIDE → INPUTS → ENGINE → OUTPUTS → OUTSIDE`

`INPUTS`, `ENGINE` and `OUTPUTS` belong inside the IASI boundary.

The external world remains outside that boundary.

A useful summary is:

*One entry. One exit. The cycles are internal.*

## External inputs

Anything entering IASI from outside may arrive in its original form.

Examples include:

- documents;
- PDF;
- Word;
- PowerPoint;
- Excel;
- email;
- images;
- data;
- other source material.

External material is not normalized in place.

It is preserved as received.

## Input provenance

IASI inputs are organized according to provenance.

The current input areas are:

### externals

Material originating outside IASI.

External material is preserved as received and is treated as immutable/read-only from the IASI process.

### internals

Knowledge and decisions created inside the IASI engineering process.

This includes decisions produced through conversation, reasoning, analysis and engineering work.

### authored

Material deliberately written or prepared as explicit input for the project.

`authored` describes its engineering role as intentional source material.

The classification is about provenance and role, not whether a human or an AI physically wrote the file.

## Engine

The ENGINE represents activity rather than storage.

The current engineering flow is:

`UNDERSTAND → SPECIFY → PLAN → EXECUTE → VERIFY → AUTHORIZE`

### Understand

Interpret available inputs and establish explicit understanding.

### Specify

Turn understanding into requirements, constraints, contracts and acceptance criteria.

### Plan

Determine the work needed to satisfy the specification.

### Execute

Perform the work and materialize results.

### Verify

Determine whether the produced result satisfies the relevant specification, rules and acceptance criteria.

Verification may include automatic checks and human judgement.

### Authorize

Authorization occurs after verification.

Authorization decides whether a verified result is approved to leave IASI.

Authorization may be automatic or human depending on the rules and responsibility involved.

## Outputs

Tasks materialize their results in outputs.

An output is a result of execution.

An output may exist even when it is:

- intermediate;
- rejected;
- failed;
- auxiliary;
- awaiting verification;
- awaiting authorization.

Therefore an output is not automatically something that can be delivered.

## Deliverables

A verified and authorized output becomes a **deliverable**.

The conceptual flow is:

`OUTPUT → VERIFY → AUTHORIZE → DELIVERABLE`

A useful distinction is:

*Outputs are produced. Deliverables are authorized.*

Only deliverables may cross the IASI boundary toward the outside.

## Delivery

Deliverables may leave IASI toward different destinations, including:

- a human or client;
- a repository;
- a deployment or runtime environment;
- a publication;
- a communication channel;
- a package or distributable artifact.

A useful summary is:

*Deliverables leave IASI. Outputs do not.*

## Sources

- Current IASI engineering conversation
- Current implementation of Introducing IASI as a practical application of IASI
