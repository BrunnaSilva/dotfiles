# Code Review Request

## Context
- **Project**: <nome do projeto / serviço>
- **Language/Stack**: <ex: Python 3.11 / Kotlin / TypeScript>

## Review Focus
Prioritize your feedback in this order:
1. **Correctness** — Logic errors, edge cases, off-by-one, null/None handling
2. **Security** — Injection risks, exposed secrets, insecure dependencies
3. **Performance** — N+1 queries, unnecessary allocations, blocking I/O
4. **Maintainability** — Naming clarity, function length, DRY violations
5. **Tests** — Missing coverage for critical paths or edge cases

## What I've Already Considered
<descreva brevemente decisões que você já pensou, para evitar feedback repetitivo>
Ex: "Escolhi polling ao invés de webhooks porque o parceiro não suporta."

## Constraints
- Must stay within the existing architecture (no new services)
- Response time budget: <ex: p95 < 200ms>
- <qualquer outra restrição relevante>

## Output Format
For each issue found:
- **Location**: file:line or function name
- **Severity**: critical / major / minor / nit
- **Issue**: what's wrong and why it matters
- **Suggestion**: concrete fix or alternative, with code snippet if helpful

End with a **Summary** section: overall assessment + top 3 priorities if the list is long.

-----
# Fast Code Review Request 

Review this <linguagem> code for correctness, security, and performance issues.
Context: <1 linha de contexto>.
Flag only major/critical issues. For each: location, what's wrong, suggested fix.