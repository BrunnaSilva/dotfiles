# Context
You are analyzing a production codebase for the `[SERVICE_NAME]` service.
Repo: `[REPO_PATH]`
Stack: `[e.g. Node.js 20, TypeScript, Kotlin]`

# Task
Generate complete technical documentation for this service.

# Required Sections
1. **Overview** — purpose, business domain, and bounded context
2. **Architecture** — component diagram (Mermaid), dependencies, data flow
3. **API Reference** — all endpoints with method, path, params, request/response schemas, error codes
4. **Data Models** — entities, relationships, DB schema (tables, indexes, constraints)
5. **Configuration** — all env vars with type, default, and description
6. **Error Handling** — error taxonomy, retry strategy, circuit breakers
7. **Observability** — logs (format + key fields), metrics, trace IDs
8. **Runbook** — local setup, deploy steps, rollback procedure, known failure modes

# Output Format
- Markdown only
- Code blocks with language tags
- Mermaid diagrams for architecture and flows
- Tables for env vars, endpoints, error codes
- Max 1 sentence per bullet point

# Constraints
- Read ALL files before writing
- Do not infer behavior — document only what exists in the code
- Flag TODOs and undocumented behavior with `> ⚠️ Undocumented` callouts
- If a section has no content, write `> Not applicable for this service`