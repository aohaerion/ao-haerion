# M001 — Governed Memory Layer

## Public status

**Status:** Proposed public design milestone  
**Repository state:** Public documentation draft  
**Baseline status:** Non-baseline

M001 is not a runtime implementation.
M001 is a design milestone for explaining how AO Haerion should preserve useful continuity across interrupted work.

## Purpose

M001 defines how AO Haerion preserves context, decisions, evidence, and direction across interrupted work.

The goal is to make resuming a path safer and more understandable.

When work stops and later restarts, the governed memory layer should help answer:

- What was the situation?
- What had already been decided?
- What evidence supported the decision?
- What direction was active?
- What was still uncertain?
- What should not be assumed?

## Scope

M001 focuses on governed memory as a public design concept.

It covers:

- context preservation;
- decision preservation;
- evidence references;
- direction tracking;
- interruption and resumption;
- readable state summaries;
- explicit limits and non-goals.

## Non-goals

M001 does not define:

- a complete AO Haerion system;
- a production runtime;
- autonomous execution;
- a full agent framework;
- private user memory infrastructure;
- an automatic validation engine;
- a universal project archive;
- a complete knowledge graph;
- a final repository baseline.

## Key concepts

### Context

The surrounding information needed to understand a situation.

### Decision

A selected direction among possible options.

### Evidence

Material used to support a statement, state, or decision.

### Direction

The current intended path of work.

### Governed memory

Memory that is structured, limited, traceable, and explicit about what it can and cannot claim.

### Resume path

The act of continuing interrupted work using preserved context, decisions, evidence, and direction.

## What is preserved

M001 is intended to preserve:

- current situation summary;
- key decisions;
- decision reasons;
- evidence references;
- active direction;
- open questions;
- known limits;
- next practical step;
- public status.

## What is not preserved

M001 should not pretend to preserve:

- every detail;
- hidden reasoning;
- unverifiable claims;
- private information not meant for public use;
- unrelated project systems;
- full implementation history;
- automatically validated truth;
- future decisions not yet made.

## Basic flow

A basic governed memory flow may look like this:

1. **Capture the situation**  
   Record the current state in a human-readable way.

2. **Separate facts, assumptions, and decisions**  
   Do not mix what is known, guessed, and chosen.

3. **Attach evidence where possible**  
   Link important statements to visible material or explicit sources.

4. **Define the active direction**  
   State what path is currently being followed.

5. **List open limits**  
   State what is missing, uncertain, or outside scope.

6. **Prepare for resumption**  
   Create a compact handoff that allows work to continue later without false certainty.

## Risks and limits

### Risk: overclaim

A memory layer can appear more complete than it is.

Mitigation:

- state status clearly;
- separate preserved from non-preserved material;
- avoid baseline language unless a baseline is actually declared.

### Risk: false continuity

A resumed path can accidentally invent missing steps.

Mitigation:

- record open questions;
- mark unknowns;
- avoid filling gaps silently.

### Risk: mixing public and private layers

AO Haerion may have deeper design ideas behind the scenes, but the public repository should stay focused and readable.

Mitigation:

- keep public documentation Haerion-first;
- do not import unrelated systems into the first public milestone;
- avoid exposing unfinished architecture as if it were stable.

### Risk: excessive complexity

A memory system can become too heavy too early.

Mitigation:

- use small documents;
- prefer readable structure;
- add complexity only when needed.

## Public status

M001 is a public design milestone.

It is suitable for:

- documentation drafting;
- public explanation;
- early GitHub issues;
- review and discussion.

It is not suitable for:

- production claims;
- runtime claims;
- baseline claims;
- system-complete claims.
