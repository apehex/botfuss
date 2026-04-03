# Decisions

Record of important architectural and conceptual decisions.

---

## [v0] File-Based Layering

Assets are structured as directories with incremental layers.

Example:

drafts/assets/characters/kvothe/
- 0.birth
- 1.childhood.happy/
- 1.childhood.trauma/

Rationale:
- easier for humans to read and contribute
- avoids large monolithic files
- aligns with incremental storytelling

---

## [v0] YAML as Base Format

All structured data is stored in YAML.

Rationale:
- readable
- easy to edit
- compatible with LLMs
- diff-friendly

---

## [v0] Multiple Variants Allowed

Conflicting versions of events or states are allowed.

Rationale:
- supports multiple interpretations
- avoids early locking of canon
- enables branching narratives

---

## [open] Timeline Representation

To be defined:
- how to normalize time across assets
- how to resolve ordering conflicts

---

## [open] Simulation Engine

To be defined:
- how to "run" the world
- how to resolve conflicts between agents
- how to select events

---

## [open] Narrative Extraction

To be defined:
- how to select meaningful events
- how to build story arcs
- how to generate prose
