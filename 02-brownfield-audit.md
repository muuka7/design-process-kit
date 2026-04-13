# Brownfield Audit

Use this when the app already exists.

## Audit Goals

- understand the current structure before redesign
- capture current UX, layout, and data-display issues
- produce a route/screen inventory grounded in code

## Audit Checklist

### Product Structure

- identify app packages
- identify web/mobile separation
- identify route directories or screen registries
- identify shared layout, navigation, shell, and theme files

### Current UI

- collect screenshots
- map screenshots to route files
- identify inconsistent button, form, table, card, and filter patterns
- identify mobile layout breakpoints or navigation issues

### Current Data Usage

- inspect data layer and API clients
- list which endpoints each page calls
- identify raw fields or internal values leaking into the UI
- identify missing data required for a better user-facing design

### Current Screen Inventory

- list every page/screen
- define each screen's job
- define current actions and states
- mark which screens are redesign priorities

## Brownfield Deliverables

- project intake doc
- current screen inventory
- wireframes for priority pages
- prototypes for priority flows
- page contracts for finalized pages
