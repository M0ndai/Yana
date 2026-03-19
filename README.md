# Yana
Yet Another Note App

This is not a note-taking app.
It is a deterministic system for explicit knowledge transformation and decision tracking.

---

## Overview

Yana is a structured, filesystem-based note system.

Notes are stored as JSON files.

- One file per note
- Typed relations
- Schema validation
- Deterministic rebuild
- Explicit selection

It is a simple system.

If you are looking for a typical note app, this is not it.
---

## Design

- Source of Truth: filesystem
- No in-place overwrite
- No implicit selection
- No background canonization
- Clear separation of generation and commit

If a state becomes canonical, it was explicitly approved.

---

## Architecture

/knowledge_nodes/*.json  
→ Validator  
→ Projection (optional)  
→ API / UI  

Projection is disposable.  
Files are canonical.

---

## Non-Goals

- No autonomous agents
- No self-optimizing loops
- No AI authority
- No SaaS features
- No “second brain” positioning

Yana is infrastructure.

---

## Status

Local-first.  
Deterministic core.  
Experimental.
