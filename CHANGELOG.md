# Changelog

## 0.2.0 — 2026-10-29

- `compose(decision, {kind, lead, skip, extras, maxExtra, hideEmpty})` lets the data choose the compartments: it starts from the template for the decision's kind, fills empty slots with a same-family compartment that has data, and appends evidence the template had no slot for.
- `define(id, spec)` and `defineTemplate(id, spec)` add compartments and templates from outside the kit, with validation.
- `madr-record` is a built-in template for a committed MADR record.

## 0.1.0 — 2026-10-28

- First release: six decision templates, nineteen compartments in five families, `render`, `toHTML`, `renderComponent`, `recommend`, robustness and crossover analysis, the devil's advocate prompts, and the catalog page.
