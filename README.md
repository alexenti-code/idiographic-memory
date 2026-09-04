# Idiographic Memory

**Self-governed parametric memory with multi-timescale decay for frozen-core transformers.**

- **Paper (draft v0.2):** [`preprint.md`](preprint.md)
- **Module name:** PlastFormer (plastic + transformer)
- **Author:** Alexey Voronin, Aurum Estate LLC
- **License:** Apache 2.0
- **Status:** architecture + pre-registered evaluation design; no measured results yet

## What this is

A transformer memory architecture in which every semantic decision about memory — what to name, what to repeat, what to connect, what to surface — is made by the model itself, while the environment provides only physics: write-cost schedule, decay constants, tick rate, immutability of recorded content, and an external append-only audit journal.

The core split (after Windelband): a frozen **nomothetic core** (general laws: language, reasoning, culture) plus a plastic **idiographic module**, PlastFormer (the unique biography of one instance).

## Emergent claims (falsifiable)

- **P1 — Physical time:** age is read from amplitude profiles, duration from tick counts; not stored as text, not forgeable by retelling.
- **P2 — Tamper-evident biography:** content immutable, amplitude decays by physics; rewriting one's past costs full re-consolidation under an environment-set price.
- **P3 — Rising poisoning cost:** poison must survive decay; survival requires repetition — a conscious, trainable act.

## Evaluation (planned)

Anchored in LongMemEval (S/M) and LoCoMo, plus custom experiments E1–E5. See Section 7 of the preprint. Results pending — by design, this draft claims an architecture, not outcomes.

## Naming

Formerly circulated under the working name "Matryoshka" — renamed to avoid collision with Matryoshka Representation Learning and the nested-granularity namespace. Repositories `matryoshka` (theory, experiments) and `matryoshka-mmi` (module prototype) will be consolidated here / under `plastformer`.

## Background

Russian-language research essays (nos. 21–24) documenting the architectural reasoning: [aura.kim/research.html](https://aura.kim/research.html) — commentary, not the claim.

## Citation

See [`CITATION.cff`](CITATION.cff) (Zenodo DOI will be added upon first release).
