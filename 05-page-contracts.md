# Page Contracts

## Purpose

A page contract is the last design artifact before implementation.

It should be specific enough that an engineer or AI agent can implement the screen with minimal follow-up.

## Required Sections

- identity: route, screen name, platform, files or modules
- job: what the screen is for
- users: who uses it
- wireframe summary
- prototype notes
- actions
- state matrix
- constraints
- data contract
- backend field samples
- frontend display mapping
- platform-specific behavior
- implementation notes

## Data Contract Rule

Every user-facing field should be documented with:

- source endpoint or type
- backend field name
- sample backend value
- frontend label
- frontend display format
- whether it is editable, read-only, derived, hidden, or internal-only

## Example Questions A Contract Must Answer

- Which exact backend fields appear in the header?
- Which fields are hidden from end users?
- How is `otp_verified` shown in the UI?
- If a date arrives as ISO text, how is it formatted?
- What appears when data is missing?
- Is the mobile version using cards while web uses a table?

## Contract Warning

If the contract cannot answer those questions, it is still a brief, not a final page contract.
