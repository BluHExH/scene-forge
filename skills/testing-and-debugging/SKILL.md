---
name: testing-and-debugging
description: Use when writing tests, improving test coverage, or systematically debugging issues. Triggers on unit tests, integration tests, end-to-end tests, test strategy, debugging process, and fixing bugs methodically.
---

# Testing and Debugging

Use when writing tests, improving test coverage, or systematically debugging issues.

## Testing strategy

- Unit tests for pure logic and edge cases.
- Integration tests for boundaries (API, DB, auth).
- E2E for critical user flows only.
- Prefer fewer, high-value tests over coverage percentage alone.

## Debugging process

1. Reproduce reliably.
2. Isolate (binary search / bisect if needed).
3. Form a hypothesis.
4. Test the hypothesis with minimal change.
5. Fix root cause, not symptoms.
6. Add a regression test when appropriate.

## Practices

- Fail fast with clear errors.
- Use logging / breakpoints intentionally.
- Don’t change many things at once while debugging.
