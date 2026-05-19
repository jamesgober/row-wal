# row-wal - Project Prompt

## Priority order

1. `REPS.md` - SUPREME AUTHORITY
2. `.dev/DIRECTIVES.md`
3. This file (`.dev/PROMPT.md`)
4. `.dev/ROADMAP.md`

## What this crate is

Row-format write-ahead log primitive for Rust databases. Group commit, fsync coordination, sharded writers, crash recovery, replay. Backend-agnostic durability layer for traditional row-oriented storage engines. Conventional ARIES-style semantics.

## Why it exists

Conventional row-format WAL primitive. Group commit, fsync coordination, crash recovery, replay. Backend-agnostic durability.

## Skill areas

- WAL design
- group commit
- ARIES recovery
- crash safety

## Scope (1.0)

Defined in `.dev/ROADMAP.md`.

## Out of scope (always)

- Features requiring async runtime hard-dependency
- Features pulling in heavy framework dependency
- Features that violate REPS

## Pre-1.0 audit (mandatory)

See `.dev/ROADMAP.md` for the audit checklist. Must verify:

- Feature completeness vs. the roadmap
- API accuracy and stability
- Code cleanliness
- Error hardening
- Documentation completeness
- Test coverage
- Benchmark coverage
- Cross-platform CI passing

## Versioning

Fast-track. No slow-stepping:

- 0.1.0 - scaffold
- 0.2.0 - first real implementation
- 0.5.0 - most features in place
- 0.9.0 - feature-complete, hardening
- 0.9.x - audit findings
- 1.0.0 - stable