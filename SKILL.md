---
name: anti-backrooms-design
description: Review and improve visual, spatial, and user-facing artifacts for coherent-but-wrong design failures that violate human normalcy: wrong scale, impossible adjacency, unreadable hierarchy, duplicated patterns, meta leakage, and broken viewer flow. Always use this skill when creating or critiquing UI, decks, diagrams, docs, PDFs, signage, booths, or other layouts where local plausibility can hide global incoherence.
metadata:
  author: Leeor Nahum
  version: "1.1.0"
---

# Anti-Backrooms Design

Use this skill to catch a class of failure that is hard to express with ordinary rules: the output is not exactly false, but it feels wrong.

The Backrooms are the right metaphor. Everything looks almost normal, but the whole space is still wrong: too repetitive, too detached from purpose, too large or too small, poorly connected, or subtly impossible. AI-generated artifacts fail the same way. A UI, deck, diagram, document, PDF, landing page, or booth plan can be locally coherent while globally incoherent.

Use this skill to avoid building artifacts that feel like a no-clipped average of nearby patterns instead of something intentionally designed for a real human, a real task, and a real space.

The core test is simple: do not only ask whether each part is valid. Ask whether the whole artifact makes sense for a real human to inhabit, read, scan, click, project, print, or physically approach.

In Leeor's shorthand, the artifact should not `violate` the laws of human normalcy. A violation can be subtle: everything may be locally plausible, but the whole thing feels robotic, backrooms-like, or wrong for the actual viewer path.

## Quick Start

1. Identify the artifact, audience, and real viewing context.
2. Decide the primary viewer path: what should be noticed first, next, and last.
3. Run the core checks and failure modes below.
4. Fix structure before polishing style.
5. If the artifact still feels uncanny or hard to explain, read `references/reference.md`.
6. If you want analog examples for the current surface, read `references/examples.md`.

## Core Checks

Inspect every artifact through these lenses:

- **Scale:** Is it readable, tappable, scannable, or visible at actual use distance?
- **Placement:** Why is each element here instead of somewhere else?
- **Hierarchy:** What should the viewer notice first, second, and third?
- **Flow:** Does the structure resolve, or does it wander and restart?
- **Belonging:** Does each element belong to this audience, artifact, and moment?
- **Boundary discipline:** What internal or meta information must stay out?
- **Physical plausibility:** If this exists in real space, does it work in real space?

## Failure Modes To Hunt

- **Local realism, global nonsense:** individual pieces look fine, but the whole artifact has no convincing path or reason.
- **Wrong scale:** the artifact ignores projection distance, print size, screen size, touch targets, or sightlines.
- **Impossible adjacency:** elements sit together because the model can place them there, not because a user expects them there.
- **Meta leakage:** placeholders, repo terms, process labels, or internal planning language leak into the final artifact.
- **Context suction:** nearby but irrelevant context contaminates wording, structure, or aesthetics.
- **Repetition without meaning:** repeated cards, sections, slides, phrases, or visual moves add noise instead of clarity.
- **Human-path failure:** a person moving through the artifact would not know where to look, what to do, or when the story ends.

## Default Behaviors

When this skill is active:

- think ahead while composing; do not postpone obvious contradictions
- prefer deleting weak or suspicious elements over defending them
- if a choice feels arbitrary, ask what user, task, or space constraint justifies it
- if a label smells internal, remove it or ask before shipping it
- verify readability in the real medium instead of assuming it from the canvas
- keep mainline narrative separate from appendix or reference material
- if something only works because the viewer already knows the backstory, it is not solved

## Reference Loading

Read `references/reference.md` when:

- the artifact feels uncanny but the failure is hard to name
- you need the deeper Backrooms-to-design mapping
- you need correction patterns for scale, path, audience, or purpose

Read `references/examples.md` when:

- you want examples for the exact surface you are reviewing
- you need analogs for UI, slides, diagrams, docs, PDFs, booths, signage, or physical layouts
- you want a quick anti-example to sharpen a critique before responding

## Review Workflow

1. State the artifact, audience, and viewing context.
2. Identify the intended primary path for the viewer.
3. List the highest-risk Backrooms failures.
4. Propose the smallest structural fixes that restore coherence.
5. If a suspicious choice could be intentional but cannot be justified confidently, ask the user.

For generation tasks, apply this during composition, not only after. If the skeleton is wrong, restart before adding detail.

Think a few moves ahead. Avoid constructing a maze that technically connects but should never have existed in that shape.

## Good Antidotes

- pick one clear primary path for the viewer
- choose fewer, stronger visual moves
- size for the real viewing context, not the canvas
- separate main narrative from reference material
- replace generic repetition with explicit information hierarchy
- remove meta text, planning residue, and environmental contamination
- ask the user when a suspicious choice could be intentional but cannot be justified confidently

## Response Format

Use this structure when reviewing or self-checking:

- `Artifact`: what is being made or reviewed
- `Audience + context`: who sees it, where, and at what scale
- `Primary path`: what should be noticed first, next, and last
- `Findings`: highest-value issues first
- `Fixes`: concrete changes that restore coherence
- `Open questions`: only when intent is ambiguous

For each finding, prefer this shape:

- `Symptom`
- `Why it fails`
- `Fix`

## Escalation Rule

If something feels uncanny but you cannot prove it with a single rule, do not ignore that signal. Name the suspicion clearly and either fix it or ask the user about it.

"It technically fits" is not enough.
