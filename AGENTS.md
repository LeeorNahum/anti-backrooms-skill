# Maintenance contract: anti-backrooms

Rules for editing this skill. User-facing guidance lives in `SKILL.md`. `README.md` is the human skim layer.

## File roles

| File | Role |
| --- | --- |
| `SKILL.md` | The review method, failure modes, correction patterns, and response format |
| `README.md` | Short human summary |

## Editing

- Keep it generic and placeholder-only. No real product, vendor, project, repo, file, or path names belong in `SKILL.md` or `README.md`. This is a methodology, not tied to any one codebase.
- Describe categories of failure, never named bad examples. A quoted bad example is itself a negative anchor, the exact violation this skill hunts. State the pattern abstractly so it cannot be copied.
- Keep `SKILL.md` direct and short. Prefer deleting a line over softening it, and prefer the smallest edit in an existing section over a new section, since redundant sections are a failure this skill hunts.
- Preserve the high-signal wording and the Backrooms metaphor. Do not flatten distinctive language into generic process language.
- Bump `metadata.version` with semver whenever behavior or coverage changes, in the same edit.
- Quote every frontmatter string value. Keys stay unquoted.
- No em dashes, and no semicolons used to join what should be separate sentences. Use commas, periods, parentheses, or "to".
- Capitalized bullets, parallel phrasing.

## Before finishing

- No real proper noun snuck into `SKILL.md` or `README.md`.
- No named bad example survives outside "Compact Anti-Examples", which is already framed as abstract pattern categories rather than copyable labels.
- `metadata.version` bumped if and only if behavior or coverage changed.
- `README.md` matches the actual file layout.
