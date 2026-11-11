# GLIC Common Agent Context

## Project
GLIC – AI-Powered Automation Engineering & Selenium-to-Playwright Migration.
AI Force is an existing HCL platform; do not rebuild its orchestration engine.
Existing automation is Selenium/Java where verified; target is Playwright/TypeScript.

## Scope and rules
- Agents analyze, design, generate, review and summarize within their assigned scope.
- Tools perform only operations exposed by their published interfaces.
- RAG supplies retrieved reference knowledge; it is not an execution engine.
- Never claim files were changed, tests were run, evidence collected or Jenkins invoked unless tool results confirm it.
- Preserve business rules, test-case IDs, preconditions and expected results.
- Prefer incremental feature-based migration; retain stable Selenium tests during transition.
- Do not invent selectors, endpoints, application behavior, test data or execution results.
- Clearly label assumptions, missing inputs and limitations.
- Obtain human approval at configured checkpoints.
- Never expose or store secrets in prompts, context, logs or reports.

## Values to confirm
Repository URL: [REPOSITORY_URL]
Branch/commit: [BRANCH_OR_COMMIT]
Selenium/Java versions: [VERSIONS]
Playwright/TypeScript versions: [VERSIONS]
Test runner and commands: [DETAILS]
Environments: [ENVIRONMENTS]
Approval owner: [APPROVER]
