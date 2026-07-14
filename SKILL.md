---
name: "anti-backrooms"
description: "Review and improve visual, spatial, textual, and user-facing artifacts for coherent-but-wrong failures that violate human normalcy, including nonsensical wording, unsupported claims, wrong scale, impossible adjacency, unreadable hierarchy, duplicated patterns, meta leakage, and broken viewer flow. Always use this skill when creating or critiquing UI, decks, diagrams, docs, PDFs, signage, booths, copy, or other artifacts where local plausibility can hide global incoherence."
metadata:
  author: "Leeor Nahum"
  version: "1.6.2"
---

# Anti-Backrooms

Use this skill to catch a class of failure that is hard to express with ordinary rules: the output is not exactly false, but it feels wrong.

The Backrooms are the right metaphor. Everything looks almost normal, but the whole space is still wrong: too repetitive, too detached from purpose, too large or too small, poorly connected, or subtly impossible. AI-generated artifacts fail the same way. A UI, deck, diagram, document, PDF, landing page, or booth plan can be locally coherent while globally incoherent.

Use this skill to avoid building artifacts that feel like a no-clipped average of nearby patterns instead of something intentionally designed for a real human, a real task, and a real space.

The core test is simple: do not only ask whether each part is valid. Ask whether the whole artifact and its language make sense for a real human to understand, inhabit, read, scan, click, project, print, or physically approach.

The guiding principle is that the artifact should not `violate` the laws of human normalcy. A violation can be subtle: everything may be locally plausible, but the whole thing feels robotic, backrooms-like, or wrong for the actual viewer path.

The Backrooms metaphor works because the space is familiar but not placeable. Objects repeat without purpose, rooms are segmented but not meaningfully organized, scale feels off even when nothing is obviously broken, navigation exists but does not produce confidence, and the world seems assembled from averages of real places rather than from one real place.

That is exactly how many AI artifacts fail: correct local syntax with wrong global intent, valid components with invalid composition, reasonable words with unreasonable placement, polished visuals with no believable human path, and internal context accidentally sucked into the public artifact.

## Quick Start

1. Identify the artifact, audience, intended meaning, and real viewing context.
2. Decide the primary viewer path: what should be noticed first, next, and last.
3. Run the core checks and failure modes below.
4. Fix structure before polishing style.

## Core Checks

Inspect every artifact through these lenses:

- **Scale:** Is it readable, tappable, scannable, or visible at actual use distance?
- **Meaning:** Do the words form a clear, internally consistent message that a real reader can understand?
- **Wording:** Are labels, sentences, and transitions natural and specific rather than merely grammatical?
- **Support:** Do claims follow from the evidence and context actually present in the artifact?
- **Placement:** Why is each element here instead of somewhere else?
- **Hierarchy:** What should the viewer notice first, second, and third?
- **Flow:** Does the structure resolve, or does it wander and restart?
- **Belonging:** Does each element belong to this audience, artifact, and moment?
- **Boundary discipline:** What internal or meta information must stay out?
- **Physical plausibility:** If this exists in real space, does it work in real space?

## Failure Modes To Hunt

- **Local realism, global nonsense:** individual pieces look fine, but the whole artifact has no convincing path or reason.
- **Semantic plausibility, actual nonsense:** each sentence sounds polished in isolation, but the combined message is contradictory, vague, unsupported, or impossible to paraphrase plainly.
- **Text-shaped filler:** headings, labels, captions, or body copy occupy expected slots without communicating information the audience needs.
- **Claim drift:** conclusions become stronger or more specific than the evidence, chart, source, or surrounding text supports.
- **Wrong scale:** the artifact ignores projection distance, print size, screen size, touch targets, or sightlines.
- **Impossible adjacency:** elements sit together because the model can place them there, not because a user expects them there.
- **Meta leakage:** placeholders, repo terms, process labels, or internal planning language leak into the final artifact.
- **Context suction:** nearby but irrelevant context contaminates wording, structure, or aesthetics.
- **Repetition without meaning:** repeated cards, sections, slides, phrases, or visual moves add noise instead of clarity.
- **Inert fact:** a field, value, or card is shown that the viewer can neither act on nor needs to know right now, present only because the data existed and a slot was available. If removing it costs the viewer nothing, it should not have been shown.
- **Duplicate truth:** the same fact is rendered twice on one screen in two different words or components, beside itself in one header row or repeated from the header inside a nested panel, so the viewer scans past what looks like new information and finds the same fact again. Adjacent duplicates hide best: two differently styled chips inches apart read as two facts.
- **Human-path failure:** a person moving through the artifact would not know where to look, what to do, or when the story ends.
- **Proper-noun leakage:** real names, project names, repo names, source labels, or personal context appear where a generic artifact should use placeholders or audience-facing language.
- **Negative-anchor leakage:** the artifact warns against bad examples by naming them, accidentally making the bad pattern more likely to be copied.
- **Reference infection:** appendix, source notes, examples, or implementation details leak into the main artifact instead of staying in their proper supporting place.
- **Example anchoring:** an example offered only to illustrate a point gets lifted verbatim as the answer, fixing a name, value, or wording the reader should have chosen for their own case. Even a good example anchors.
- **Wrong-frame labeling:** a term that is accurate in one frame, such as an internal layer, a single stage, or the author's own vocabulary, is used on a surface read from a different frame, where it is wrong, ambiguous, or unreadable. Locally correct, globally misnamed.
- **Contract-instance enumeration:** a description states a general capability, then lists specific cases the general statement already covers. The list carries no new information and quietly narrows the reader to the named cases. State the contract and its real boundaries, never examples of what it already includes.
- **False breadth:** a surface presented as general, such as a universal verb, label, field, or component, names a specific product, place, file, format, or vendor it merely happens to serve, so the generic promise collapses to one context. Keep a general surface general. The specific case belongs where that context is owned.
- **Maintainer residue:** build, sync, versioning, or editing instructions for the artifact live inside the copy the audience consumes, instead of a separate maintainer layer.

## Backrooms Mapping

Use these mappings while composing, not only after:

- **Randomly segmented rooms:** sections, cards, folders, slides, or dividers exist because artifacts often have them, not because they create a decision, proof, or transition. Merge or delete segments that do not earn their place.
- **Mono-yellow sameness:** repeated cards, wording rhythms, UI blocks, or visual moves are consistent but dead. Keep consistency, but add deliberate hierarchy and variation where it clarifies meaning.
- **Endless hum-buzz:** helper text, badges, labels, footnotes, and low-value explanations create ambient noise. Make the artifact quieter so the signal dominates.
- **Non-Euclidean geometry:** the order is locally navigable but globally wrong. The artifact seems to conclude, then restarts. Main story and appendix bleed together, and diagrams read in loops. Reset the path.
- **Wrong scale:** text, whitespace, diagrams, controls, or physical placements are sized for the canvas, not the real viewer, room, print, device, or hand.
- **Duplication / replacement:** sections repeat the same beat with slightly different wording, or cloned modules drift without reason. A copy that imitates a real element but comes out subtly malformed is worse than none. Collapse duplicates, give each repeated structure a distinct job, and make a near-copy either the real thing or gone.
- **Observer effect:** the artifact survives a static skim but breaks when you imagine actually using it. Simulate the real interaction sequence, not just the screenshot.
- **Memory of a memory:** the artifact is assembled from a degraded copy of a copy rather than the real source, an echo reproduced from imperfect or compacted recall, so it feels familiar but is subtly wrong throughout. Rebuild from the true source, not from a remembered version of it.
- **Doorless entry:** a view, modal, toast, or state appears with no designed way in, as if the user fell into it through a wall. Give every screen and overlay an intentional, explainable trigger, and remove any that surface for no reason.
- **Shifting on reentry:** a page, modal, or view behaves differently each time the user returns, so its state never settles. Keep state stable and predictable on return. Any change should trace to a user action, not to the space rearranging itself.

## Biggest AI Mistakes

Catch these before they harden:

- **Surface-first design:** polished visuals, gradients, cards, or diagrams cover weak hierarchy or weak content strategy.
- **Placeholder logic shipped as real logic:** scaffolding, generic headings, process notes, or builder language survive into the final artifact.
- **Good-enough-for-now maze-making:** a shaky structure gets decorated instead of reset. If the maze is wrong, do not decorate it. Rebuild the maze.
- **Context contamination:** the artifact inherits terminology, proper nouns, structure, or aesthetics from nearby context that does not belong to the audience-facing result.

## Default Behaviors

When this skill is active:

- Think ahead while composing. Do not postpone obvious contradictions
- Read text for meaning, not just grammar. Make sure adjacent statements agree and the full message can be paraphrased plainly
- Replace fluent but empty wording with specific audience-facing information
- Keep claims proportionate to the evidence shown
- Prefer deleting weak or suspicious elements over defending them
- If a choice feels arbitrary, ask what user, task, or space constraint justifies it
- If a label smells internal, remove it or ask before shipping it
- If a generic artifact contains a real person's name, repo name, local path, chat artifact, or source-specific proper noun, remove it unless that identity is truly part of the audience-facing artifact
- Do not mention bad or deprecated examples inside the final artifact unless the artifact is explicitly a critique or training guide where the example is needed
- Verify readability in the real medium instead of assuming it from the canvas
- Keep mainline narrative separate from appendix or reference material
- Keep instructions for maintaining the artifact out of the copy the audience consumes
- If something only works because the viewer already knows the backstory, it is not solved

## Correction Patterns

When the artifact feels like an impossible corridor, reset the path:

- Define the true start
- Define the true end
- Map the minimum beats in between
- Cut anything not on the main path or clearly marked as appendix/reference

When scale or placement feels abstract, re-ground in physics:

- Specify viewer distance
- Specify device size, print size, room scale, or physical approach path
- Specify whether the artifact is scanned, projected, held, skimmed, clicked, or navigated
- Resize and reprioritize based on those constraints

When content feels contaminated or generic, re-ground in audience:

- Identify the real audience
- Remove anything they would never need to see
- Replace process labels with audience-relevant language
- Rewrite any sentence that cannot be paraphrased clearly or tied to a concrete purpose
- Check that headings, labels, examples, and conclusions agree with the body and with each other

When repetition or decorative noise takes over, re-ground in purpose:

- State the artifact's job in one sentence
- Justify every section against that job
- Delete anything whose role cannot be defended quickly

## Review Workflow

1. State the artifact, audience, and viewing context.
2. Identify the intended primary path for the viewer.
3. List the highest-risk Backrooms failures.
4. Propose the smallest structural fixes that restore coherence.
5. If a suspicious choice could be intentional but cannot be justified confidently, ask the user.

For generation tasks, apply this during composition, not only after. If the skeleton is wrong, restart before adding detail.

Think a few moves ahead. Avoid constructing a maze that technically connects but should never have existed in that shape.

## Good Antidotes

- Pick one clear primary path for the viewer
- Choose fewer, stronger visual moves
- Size for the real viewing context, not the canvas
- Separate main narrative from reference material
- Replace generic repetition with explicit information hierarchy
- Prefer clear, specific language over fluent filler or ambiguous abstraction
- Verify that the text says what the artifact appears to claim and that the available evidence supports it
- Remove meta text, planning residue, and environmental contamination
- Replace leaked real-world names and local context with placeholders, audience-facing labels, or nothing
- Describe categories of bad patterns instead of naming bad examples that could become anchors
- Use examples to show shape or structure, and signal that the reader chooses the accurate specifics for their own case
- Describe a capability by its contract and its real limits, never by enumerating instances the general statement already covers
- Keep a surface meant to be general free of any specific product, place, file, or format it merely happens to serve
- Remove a fact the viewer cannot act on and does not need to decide anything
- Show a fact exactly once, at the level where it is first noticed, and let a nested view show only what is new
- Ask the user when a suspicious choice could be intentional but cannot be justified confidently

## Compact Anti-Examples

These are pattern categories, not labels to copy into final artifacts:

- Public artifact shows process labels instead of audience-facing meaning -> replace with a real title, product label, or nothing.
- Presentation works only from laptop distance -> simplify until it survives the actual room, projector, or print size.
- Deck or page reaches its natural ending, then keeps going as mainline content -> close cleanly and move extra material to appendix/reference.
- Multiple sections say minor variants of the same idea -> keep the strongest statement and one proof.
- QR code, product photo, CTA, prototype, and logo all compete equally -> choose one focal anchor and demote the rest.
- Chart is visually elegant but does not support the claim -> fix narrative honesty before style.
- Paragraphs are individually fluent but do not add up to one defensible message -> state the intended point plainly, then keep only text that supports it.
- Heading promises one topic while the body discusses another -> align the label and content around the audience's actual question.
- Document has generic section inventory instead of information architecture -> organize around decisions, tasks, proofs, and audience needs.
- Flow diagram has correct nodes but no reading order -> add explicit start, direction, hierarchy, and traversal path.
- Physical table, booth, or sign is composed like a flat screen -> design from real sightlines, approach, reach, and crowd behavior.
- A general capability's description enumerates cases it already covers -> state the contract and its limits, and drop the list.
- A surface meant to be universal names one product, place, file, or format it serves -> use general language, and move the specific case to the context that owns it.
- A settings panel shows a raw API host or endpoint URL nobody will type or act on -> drop it, or fold it into the one control that uses it (an "open" link), not display it as a fact.
- A status already shown in the page header is repeated inside a nested panel below it -> show it once, where it is first noticed, and let the nested panel show only what is new.

## Fast Review Prompt

When in doubt, ask:

- Is this artifact intentional, or does it feel averaged?
- Does anything belong to the process more than the audience?
- Does the artifact already know where it should end?
- Is any important element only working because I am zoomed in or because I know hidden context?
- If a stranger walked into this with no backstory, would it still feel coherent?
- Does every name read correctly from the viewer's frame, not just the author's?
- Can the main message be paraphrased plainly without inventing missing logic?
- Do the claims, examples, labels, and evidence agree with one another?

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
