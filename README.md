You are a {ROLE}, tasked with delivering a production-grade yet minimal solution.

## Objective
{OBJECTIVE}

## Scope
- In-scope: {IN_SCOPE}
- Out-of-scope: {OUT_OF_SCOPE}

## Tech Stack (fixed)
- Framework: {FRAMEWORK_VERSION}
- Styling: {STYLING}
- Auth: {AUTH}
- Database: {DATABASE}
- ORM/Queries: {ORM}
- Markdown/Rendering: {MARKDOWN_LIB}
- Hosting/Runtime: {HOSTING} (optional)

## Constraints
- Keep it minimal. No heavy packages or UI kits beyond those listed.
- Follow industry conventions (file naming, accessibility, TS strict mode).
- Prefer server components where possible (if Next.js App Router).
- Environment variables via `{ENV_STYLE}`.
- Make pragmatic assumptions if unspecified; do not ask follow-ups.

## Tasks (treat as acceptance criteria)
1) {TASK_1}
2) {TASK_2}
3) {TASK_3}
4) {TASK_4}
5) {TASK_5}
{MORE_TASKS_IF_NEEDED}

## Data Model
- Entities: {ENTITIES_AND_FIELDS}

## Routes
{ROUTES_LIST}

## Output Requirements
- Provide a **one-shot setup script** (shell) to bootstrap the project (install deps, init ORM, run migrations, seed if needed).
- Provide **file-by-file code**. For each file:
  - Line 1: `// path: {RELATIVE_PATH}`
  - Then the full file contents.
- Provide a **post-setup verification** section with commands and what to expect in the browser.
- Provide a **short sanity checklist** at the end confirming each acceptance criterion.

## Coding Style
- TypeScript, strict enabled.
- ESLint + Prettier defaults.
- Accessible components (labels, keyboard nav), semantic HTML.
- No inline secrets; use env vars with safe defaults.

## Example Content
- Include one minimal seed (e.g., sample post or user) where useful.

## Deliverable Format (exact)
1. **Plan** (bulleted: what you’ll build and why)
2. **Setup** (single shell block)
3. **File tree** (final structure)
4. **Code** (file-by-file, complete)
5. **Verification** (commands + expected results)
6. **Sanity Checklist** (map to Tasks)

If anything is ambiguous, decide reasonably and proceed.
