# Maintenance contract: anti-backrooms

Rules for editing this skill. User-facing guidance lives in `SKILL.md`. `README.md` is the human skim layer.

## File roles

| File | Role |
| --- | --- |
| `SKILL.md` | The review method, failure modes, correction patterns, and review table |
| `README.md` | Short human summary |

## Editing

- The description is the trigger, not a summary. Keep it as wide as the skill's real scope, name the surfaces and signals an agent would otherwise not connect to this skill, and never narrow it to the artifact types that happened to prompt the last edit.
- Keep it generic and placeholder-only. No real product, vendor, project, repo, file, or path names belong in `SKILL.md` or `README.md`. This is a methodology, not tied to any one codebase.
- Describe categories of failure, never named bad examples. A quoted bad example is itself a negative anchor, the exact violation this skill hunts. State the pattern abstractly so it cannot be copied.
- Keep `SKILL.md` direct and short. Prefer deleting a line over softening it, and prefer the smallest edit in an existing section over a new section, since redundant sections are a failure this skill hunts.
- State each failure once, in Failure Modes To Hunt, with its fix. Every other section adds what that statement lacks, never an echo of it.
- Preserve the high-signal wording and the Backrooms metaphor. Do not flatten distinctive language into generic process language.
- Bump `metadata.version` by the release-versioning skill's rules for skills.
- Quote every frontmatter string value. Keys stay unquoted.
- No em dashes, and no semicolons used to join what should be separate sentences. Use commas, periods, parentheses, or "to".
- Capitalized bullets, parallel phrasing.

## Where edits come from

- Most edits to this skill begin with something the user saw in a visible review table: a false positive to narrow, or a miss to add. Treat each as a detection to sharpen, stated as a category of failure, and keep the review table format stable so the user keeps seeing what fired.
- Detections stay textual. This skill is judgment an agent applies while writing, never a script, a linter, or a tool, because the failures it hunts are ones a rule cannot express.
- Never soften the skill's voice or narrow its trigger to reduce how often it fires. Wide triggering is the point.

## Before finishing

- No real proper noun snuck into `SKILL.md` or `README.md`.
- No named bad example survives outside "Compact Anti-Examples", which is already framed as abstract pattern categories rather than copyable labels.
- `metadata.version` bumped as the release-versioning skill requires.
- `README.md` matches the actual file layout.
