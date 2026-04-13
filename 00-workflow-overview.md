# Workflow Overview

## Outcome

Produce implementation-ready page contracts from either an existing app or a new product idea.

## Sequence

Use the foundational stages before discovery. For brownfield projects, these stages may be derived from the current product rather than invented from scratch.

### Stage 0: Idea Capture

- capture the raw problem, users, and desired feel
- define the one-sentence problem statement

### Stage 1: Mental Model

- define what the user believes they are doing
- define the strongest product metaphor
- define the most common user action

### Stage 2: Information Architecture

- define domains and entities
- define what belongs where
- define top-level vs nested structure

### Stage 3: Project Intake

- identify product type
- identify target platforms
- identify available backend/API docs
- identify whether the project is greenfield or brownfield

### Stage 4: Discovery

- brownfield: inspect current codebase, routes, navigation, shared layout, existing screens, and current design language
- greenfield: gather PRD, backend docs, domain model, and platform scope

### Stage 5: Screen Inventory

- list screens by job, route, platform, entry points, and exit points
- mark shared vs platform-specific screens

### Stage 6: Wireframes

- define information hierarchy before visual polish
- create low-fidelity desktop/mobile wireframes
- lock page structure and task flow

### Stage 7: Prototype

- create higher-fidelity interaction spec or clickable prototype
- test flow, state transitions, action placement, and responsive behavior

### Stage 8: Page Contracts

- define exact data contract for each page
- map backend fields to frontend display
- include sample backend values and display formatting
- specify actions, states, constraints, and platform rules

### Stage 9: Visual Direction

- define aesthetic vocabulary once structure is stable
- capture references, typography, spacing, density, and motion rules

### Stage 10: Implementation Handoff

- hand finalized contracts to engineering or AI agent
- implementation should not begin before the contract is frozen unless the work is intentionally exploratory

## Guiding Rules

1. Do not skip wireframes and jump straight to pixels.
2. Do not skip contracts and jump straight from prototype to code.
3. Separate product thinking, design thinking, and implementation thinking.
4. For brownfield projects, validate every complaint against real code.
5. For greenfield projects, validate every page against the domain model and data contracts.
6. Visual direction should refine structure, not replace it.
