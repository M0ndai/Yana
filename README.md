# Yana

Yet Another Note App.  
A generic one too.

---

## Overview

Yana is a structured, filesystem-based note system.

It stores notes as JSON files.

- One file per note
- Typed relations
- Schema validation
- Deterministic rebuild
- Explicit selection

Nothing more.  
It is a simple system.

---

## Design Principles

- Source of Truth = filesystem
- No in-place overwrite
- No implicit selection
- No hidden scoring
- No background canonization
- Separation of generation and commit

If something becomes canonical,
it was explicitly approved.

---

## Architecture

/knowledge_nodes/*.json  
→ Validator  
→ Projection (optional graph)  
→ API / UI  

The projection is disposable.  
The files are canonical.

---

## Non-Goals

- No autonomous agents
- No self-optimizing loops
- No AI authority
- No SaaS narrative
- No “second brain”

Yana is infrastructure.

---

## Status

Local-first.  
Deterministic core.  
Intentionally average.

---

It is just a note system.
