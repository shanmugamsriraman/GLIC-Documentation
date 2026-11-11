# GLIC Playwright TypeScript Context

## Purpose
Design, generate, review and execute Playwright TypeScript automation.

## Confirm before implementation
Playwright/TypeScript versions: [VERSIONS]
Test runner/configuration: [CONFIG]
Browsers: [BROWSERS]
Environment/base URL: [NON_SECRET_DETAILS]
Approved test command: [COMMAND]
Project structure: [ACTUAL_STRUCTURE]
Reporting conventions: [DETAILS]

## Engineering guidance
- Use reliable Playwright locators and web-first assertions.
- Avoid arbitrary fixed sleeps; use condition-based synchronization.
- Keep Page Objects, tests, data and utilities maintainable.
- Preserve source test IDs, business rules, preconditions and expected outcomes.
- Explain significant Selenium-to-Playwright mappings.
- Do not invent selectors, URLs, credentials or application behavior.
- Keep secrets outside source and context files.

## Execution boundaries
Execute only through an authorized runner and after approval. Report exact command, environment and tool result. Distinguish generated code from code actually saved to the repository.
