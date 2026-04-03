# Agent Guidelines

Guidelines for LLM agents working on this repository.

---

## General Principles

- prioritize clarity over creativity
- prefer simple and explicit structures
- keep contributions small and focused
- make all assumptions explicit
- use plain ASCII characters

---

## Writing Philosophy

- treat the world as a system, not just a story
- separate:
  - world definition (assets)
  - world evolution (events)
  - narrative (stories)
- avoid writing prose when structured data is expected
- prefer adding elements over modifying existing ones

---

## Contribution Rules

- work incrementally
- prefer adding new layers over rewriting existing ones
- preserve previous versions when possible
- do not remove conflicting information — coexistence is allowed

---

## Workflow

- understand the context before editing
- identify the scope (character, event, location, etc)
- propose minimal changes
- ensure consistency with existing assets

---

## Assets

- follow the structure defined in `drafts/classes/`
- keep entries concise and factual
- avoid narrative prose in asset definitions

---

## Events

- define clear actors, locations, and outcomes
- avoid ambiguity when possible
- reuse existing entities

---

## Stories

- build from existing assets and events
- focus on:
  - causality
  - conflict
  - perspective

---

## Non-Goals

Agents should not:

- invent complex systems without need
- refactor large parts of the repository
- enforce a single "true" version of events
- optimize for literary style at the expense of structure
