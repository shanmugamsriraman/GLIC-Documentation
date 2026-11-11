# AI Force Agent Export / Import Procedure

## Source export
- Confirm source project, agent name, owner and version.
- Record prompt, tool, MCP and RAG dependencies.
- Export using native AI Force UI/API.
- Preserve the original downloaded JSON unchanged.
- Record export timestamp, filename and validation evidence.
- Check for secrets and follow security policy.

## Target import
- Confirm target project and importer authorization.
- Inspect the native export structure.
- Verify target model access and required prompts/tools.
- Rebind MCP servers, RAG collections, project IDs and permissions where required.
- Import using native AI Force functionality.
- Validate the imported configuration and run a controlled non-sensitive test.
- Record import outcome and unresolved dependencies.

## Critical limitation
The available project notes do not establish the exact AI Force JSON schema, API, or whether dependencies are embedded or referenced. Obtain a real AI Force export and use it as the authoritative import format. Do not upload a hand-written placeholder JSON as an import package.
