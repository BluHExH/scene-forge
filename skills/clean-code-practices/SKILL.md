---
name: clean-code-practices
description: Use when writing, reviewing, or refactoring code for quality. Triggers on clean code, refactoring, code smells, naming conventions, function design, and maintainable software practices.
---

# Clean Code Practices

Use when writing, reviewing, or refactoring code for quality. Triggers on clean code, refactoring, code smells, naming conventions, function design, and maintainable software practices.

## Core Principles

1. **Meaningful names** — Variables, functions, classes should reveal intent.
2. **Small functions** — Do one thing. Prefer < 20 lines when possible.
3. **Single Responsibility** — A module/class/function should have one reason to change.
4. **DRY** — Don't Repeat Yourself. Extract common logic.
5. **Prefer clarity over cleverness** — Code is read more than written.
6. **Avoid side effects** when possible; make them explicit when necessary.
7. **Error handling** — Fail fast, give clear messages, don't swallow exceptions.

## Naming

- Use intention-revealing names.
- Avoid abbreviations unless universal (e.g. `id`, `url`).
- Classes: nouns. Methods: verbs.
- Booleans: `is`, `has`, `can`, `should`.

## Functions

- Few arguments (ideally 0–2).
- No flag arguments if possible (prefer separate functions).
- Early returns to reduce nesting.
- Pure functions when feasible.

## Comments

- Prefer self-documenting code.
- Comment *why*, not *what*.
- Keep comments up to date or delete them.

## Refactoring checklist

- Extract method / class when a unit does too much.
- Rename for clarity.
- Remove dead code.
- Simplify complex conditionals (guard clauses, polymorphism).
- Introduce meaningful constants instead of magic numbers.
