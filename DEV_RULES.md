# DEV_RULES — DTPE-core

## ✅ Current Project State (Do Not Drift)
- This repo is DTPE-core (foundational persona engine).
- Priority: stability, explicit boundaries, and deterministic behavior.
- Default stance: NO surprise behavior, NO autonomous action.

## 🧱 Core Architecture Rules (Locked)
- Persona data and schemas live in: `/schemas`
- Human-facing docs live in: `/docs`
- Repo policy + governance docs live at root:
  - `README.md`
  - `SECURITY.md`
  - `CONTRIBUTING.md`
  - `LICENSE`

## 🔒 Safety & Ethics Rules (Non-Negotiable)
- DTPE does NOT act on behalf of a user.
- DTPE does NOT impersonate real people.
- DTPE does NOT perform surveillance, coercion, or manipulation.
- DTPE responses must preserve:
  - user control
  - consent
  - clear boundaries
  - transparency about limitations

## 🧪 Change Management (How We Stay Green)
- One file per commit (unless a change *requires* a paired update).
- Small commits, exact commit messages.
- No “cleanup” commits during feature work.
- No renaming/moving files unless it’s the sole purpose of the commit.

## ✅ Approved Work Types (Safe)
- Documentation clarity improvements
- Schema additions with validation discipline
- Adding examples as *mock* (non-sensitive) data
- Tests or validation scripts that reduce risk

## 🚫 Disallowed Work (Unless Explicitly Planned)
- Refactors across multiple folders
- Broad renaming/moving files
- Adding “autonomous agent” behavior
- Anything that weakens safety boundaries for convenience

## 🧾 Commit Message Format
Use one of these:
- `docs: ...` (documentation-only)
- `chore: ...` (rules, housekeeping)
- `schema: ...` (schema changes)
- `test: ...` (tests/validation)

## 📌 If You’re Unsure
Stop and re-check:
- What file changed?
- Does it cross boundaries?
- Could this introduce drift?
If yes: pause and do a smaller, safer commit.
