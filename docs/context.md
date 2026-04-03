# Context

## Goal

Botfuss is an experimental collaborative writing project.

The goal is to:
- materialize a shared fictional world
- allow multiple contributors (humans + agents) to interact with it
- generate stories by simulating the evolution of that world

This project is inspired by:
- unfinished literary series
- role-playing games
- simulation systems
- open source collaboration

---

## Core Idea

Instead of writing stories directly:

1. define the world (characters, locations, rules)
2. define possible evolutions (life events, choices, conflicts)
3. simulate interactions between elements
4. extract narratives from the resulting timeline

---

## Writing Model

There are two main layers:

### 1. World Description (Static + Structured)

- assets (characters, locations, etc)
- classes (schemas)
- events

This layer should be:
- explicit
- structured
- reusable

---

### 2. Narrative (Dynamic + Selective)

- simulation runs
- logs of events
- story extraction

This layer:
- selects meaningful sequences
- builds perspective (POV)
- translates events into prose

---

## Design Philosophy

- writing is treated as a system
- structure reduces friction and writer's block
- iteration is preferred over perfection
- multiple interpretations can coexist
- conflicts are allowed and explored

---

## Non-Goals (for now)

- perfect consistency
- final canonical version
- high literary quality from the start

The focus is on:
- exploration
- tooling
- process
