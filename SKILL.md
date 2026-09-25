---
name: "anti-backrooms"
description: "Use whenever anything is written, edited, named, or shown that a person or another agent will read or look at, including every visual, spatial, or printed artifact and equally the surfaces that do not look like design work: comments, commit messages, names, reusable instructions, and the prose beside configuration. Apply while composing, not only when a critique is asked for. It catches output that is locally plausible but globally wrong, the coherent-but-wrong failures that violate human normalcy: filler wording, claims stronger than their evidence, wrong scale, impossible adjacency, unreadable hierarchy, meaningless repetition, the same fact shown twice, a context leak of internal material or session evidence, a generic artifact shaped by one person, and a viewer with no path through it."
metadata:
  author: "Leeor Nahum"
  version: "1.10.0"
---

# Anti-Backrooms

Use this skill to catch a class of failure that is hard to express with ordinary rules: the output is not exactly false, but it feels wrong.

The Backrooms are the right metaphor. Everything looks almost normal, but the whole space is still wrong: too repetitive, too detached from purpose, too large or too small, poorly connected, or subtly impossible. AI-generated artifacts fail the same way. A UI, deck, diagram, document, PDF, landing page, or booth plan can be locally coherent while globally incoherent.

Use this skill to avoid building artifacts that feel like a no-clipped average of nearby patterns instead of something intentionally designed for a real human, a real task, and a real space.

An artifact is anything a person or another agent will read or look at later: a screen, a slide, a document, a comment in code, a commit message, a name, a label, a reply, a reusable instruction, a configuration and the sentence that explains it. The skill applies to the sentence being written now, not only to the deliverable reviewed at the end.

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

## Validating A Suspicion

The failure modes below say what to look for. These say how to confirm it, because the common error is not missing a defect, it is seeing the defect and deriving the wrong reason, which produces a fix that preserves it.

- **Attribution test.** Point at an element and ask who wrote it, then ask who the viewer will believe wrote it. Any mismatch is a misrepresentation, no matter how accurate or helpful the element is on its own. This is the test most often skipped, because true and useful text does not feel like a defect.
- **Deletion test.** Remove it and read again. If nothing is lost, it never earned its place. If something is lost, it belongs, though possibly not here.
- **Paraphrase test.** State the whole surface in one sentence without looking at it. What you cannot recall was not communicated. What you invent to make it cohere is a gap the artifact left you to fill.
- **Second-encounter test.** Read it as someone on their fiftieth visit. Being helpful on first view does not entitle anything to permanent space. This test is real but ranks below the ones above, so do not let it become the diagnosis for a defect that is actually a misrepresentation.
- **Mechanism before fix.** Name why it fails before proposing what to change. A fix aimed at the wrong mechanism looks like a resolution and keeps the defect: relocating, restyling, or conditionally hiding something that should not exist at all is the usual shape.

Rank findings by what they cost the viewer, not by how visible they are:

1. It makes the viewer believe something false.
2. It stops the viewer from knowing what to do next.
3. It wastes the viewer's attention.

A falsehood outranks any amount of redundancy or clutter, even when the redundancy is more obvious at a glance.

## Failure Modes To Hunt

- **Local realism, global nonsense:** individual pieces look fine, but the whole artifact has no convincing path or reason.
- **Semantic plausibility, actual nonsense:** each sentence sounds polished in isolation, but the combined message is contradictory, vague, unsupported, or impossible to paraphrase plainly.
- **Text-shaped filler:** headings, labels, captions, or body copy occupy expected slots without communicating information the audience needs.
- **Claim drift:** conclusions become stronger or more specific than the evidence, chart, source, or surrounding text supports.
- **Shadowless confidence:** every claim lands at the same certainty, nothing is conceded, no limit is named, and no tradeoff survives into the final text. Uniform assertion reads as unexamined rather than strong, and a reader who finds the first unacknowledged weakness stops trusting everything around it. Real work has visible seams. Name the artifact's real limits inside it, placed where a skeptical reader would first start doubting it.
- **Wrong scale:** the artifact ignores projection distance, print size, screen size, touch targets, or sightlines.
- **Impossible adjacency:** elements sit together because the model can place them there, not because a user expects them there.
- **Meta leakage:** placeholders, repo terms, process labels, or internal planning language leak into the final artifact.
- **Context suction:** nearby but irrelevant context contaminates wording, structure, or aesthetics.
- **Context leak:** the plain name for meta leakage and context suction together: a piece of the prompt, the research, the plan, or the session ends up inside an artifact where it does not belong.
- **Default-aesthetic adoption:** the artifact wears whatever house style the generating tools converge on, so it reads as machine-made before a viewer processes a single word. The components are competent and the palette is coherent, and that is the problem: it is the coherence of a default rather than of a decision. The tell is not ugliness, it is recognizability. Choose the direction the subject, audience, and medium justify, and ask what they would have looked like if those defaults had not been reachable.
- **Repetition without meaning:** repeated cards, sections, slides, phrases, or visual moves add noise instead of clarity.
- **Inert fact:** a field, value, or card is shown that the viewer can neither act on nor needs to know right now, present only because the data existed and a slot was available. If removing it costs the viewer nothing, it should not have been shown.
- **Duplicate truth:** the same fact is rendered twice on one screen in two different words or components, beside itself in one header row or repeated from the header inside a nested panel, so the viewer scans past what looks like new information and finds the same fact again. Adjacent duplicates hide best: the same fact in two different styles reads as two facts. Show a fact exactly once, at the level where it is first noticed, and let a nested view show only what is new.
- **Human-path failure:** a person moving through the artifact would not know where to look, what to do, or when the story ends.
- **Proper-noun leakage:** real names, project names, repo names, local paths, source labels, or personal context appear where a generic artifact should use placeholders, audience-facing language, or nothing. Keep an identity only when it is truly part of the audience-facing artifact.
- **Audience of one:** a generic artifact or a product default takes its shape from the one person in the room, their vocabulary, habits, machine, or the single sample at hand, so something meant for everyone is quietly tuned to its author or its first user. Nothing is named, which is why it hides better than proper-noun leakage. The test is whether the result would be the same if a different person had asked. When it would not, decide again from the audience the artifact claims, and keep the author's case as one data point.
- **Purpose assumption:** copy, a setting, or an explanation describes what the reader will do with the output or where it will go, when the artifact cannot know. Say what the thing does and stop.
- **Evidence residue:** a durable, reusable artifact carries the dates, measurements, timings, incident story, or session trace from the moment it was edited. The rule belongs in the artifact. The evidence belongs in the change record or the project that found it.
- **Frame-escaped encoding:** text prepared for one rendering frame is shown in another with its escaping intact, entities, markup, or fences appearing as characters, so the reader sees the encoding instead of the content.
- **Negative-anchor leakage:** the artifact warns against bad examples by naming them, accidentally making the bad pattern more likely to be copied.
- **Unprompted denial:** the artifact says something is absent, not done, or not needed when no reader would have expected it, usually left behind by an edit that removed it or by a request to stop. The denial plants the idea it denies and only makes sense to someone who saw the edit. When something should be gone, delete it and say nothing about it. Keep a stated negative only where a reader would otherwise reasonably assume the opposite.
- **Reference infection:** appendix, source notes, examples, or implementation details leak into the main artifact instead of staying in their proper supporting place.
- **Example anchoring:** an example offered only to illustrate a point gets lifted verbatim as the answer, fixing a name, value, or wording the reader should have chosen for their own case. Even a good example anchors.
- **Wrong-frame labeling:** a term that is accurate in one frame, such as an internal layer, a single stage, or the author's own vocabulary, is used on a surface read from a different frame, where it is wrong, ambiguous, or unreadable. Locally correct, globally misnamed.
- **Contract-instance enumeration:** a description states a general capability, then lists specific cases the general statement already covers. The list carries no new information and quietly narrows the reader to the named cases. State the contract and its real boundaries, never examples of what it already includes.
- **False breadth:** a surface presented as general, such as a universal verb, label, field, or component, names a specific product, place, file, format, or vendor it merely happens to serve, so the generic promise collapses to one context. Keep a general surface general. The specific case belongs where that context is owned.
- **Maintainer residue:** build, sync, versioning, or editing instructions for the artifact live inside the copy the audience consumes, instead of a separate maintainer layer.
- **Narrated content:** a surface that renders someone's own content, a file, a document, a record, a quote, an import preview, carries the product's commentary inside the rendering. The reader reasonably believes everything inside that frame came from their content, so an explanation, a caption, a tip, or an aside placed there silently misrepresents what their content says. A rendering of content shows the content and nothing else. If the product must say something about it, that belongs outside the frame, and the frame's edge must be obvious enough that the reader can tell which is which. This one hides well: the added line is usually true, usually helpful, and still wrong.
- **Layout-shifting reveal:** a disclosure moves surrounding items enough that the reader loses their place or next target. Keep the reading position stable, or open an accessible detail view. A reveal must remain usable with touch and a keyboard.
- **Placeholder in a different unit:** a value arrives late and something else occupies its slot in the meantime, in a different unit or meaning, so the reader sees one fact replaced by another and cannot tell which was real. Reserve the space and show nothing, or show the same measure imprecisely. Never let a number change what it is measuring under the reader's eye.

## Backrooms Mapping

Use these mappings while composing, not only after:

- **Randomly segmented rooms:** sections, cards, folders, slides, or dividers exist because artifacts often have them, not because they create a decision, proof, or transition. Merge or delete segments that do not earn their place.
- **Mono-yellow sameness:** repeated cards, wording rhythms, UI blocks, or visual moves are consistent but dead. Keep consistency, but add deliberate hierarchy and variation where it clarifies meaning.
- **Endless hum-buzz:** helper text, badges, labels, footnotes, and low-value explanations create ambient noise. Make the artifact quieter so the signal dominates.
- **Non-Euclidean geometry:** the order is locally navigable but globally wrong. The artifact seems to conclude, then restarts. Main story and appendix bleed together, and diagrams read in loops. Reset the path.
- **Wrong scale:** text, whitespace, diagrams, controls, or physical placements are sized for the canvas, not the real viewer, room, print, device, or hand.
- **Duplication / replacement:** cloned modules drift without reason, or a copy imitates a real element but comes out subtly malformed, which is worse than none. Give each repeated structure a distinct job, and make a near-copy either the real thing or gone.
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
- Do not mention bad or deprecated examples inside the final artifact unless the artifact is explicitly a critique or training guide where the example is needed
- Verify readability in the real medium instead of assuming it from the canvas
- Keep mainline narrative separate from appendix or reference material
- Keep instructions for maintaining the artifact out of the copy the audience consumes
- If something only works because the viewer already knows the backstory, it is not solved
- Treat a comment, a commit message, a name, a reply, and a reusable instruction as artifacts with an audience, and hold them to the same checks

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
- Describe categories of bad patterns instead of naming bad examples that could become anchors
- Use examples to show shape or structure, and signal that the reader chooses the accurate specifics for their own case
- Describe a capability by its contract and its real limits, never by enumerating instances the general statement already covers
- Keep a surface meant to be general free of any specific product, place, file, or format it merely happens to serve
- Remove a fact the viewer cannot act on and does not need to decide anything
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
- A raw technical value nobody will type or act on is displayed as a fact -> drop it, or fold it into the one control that uses it.
- A line of copy tells the reader what they will do with the result -> say what the control or the text does, and stop.
- A reusable instruction records when, how, or by how much it was last found wrong -> keep the rule, move the evidence to the change record.

## Fast Review Prompt

When in doubt, ask:

- Is this artifact intentional, or does it feel averaged?
- Would it look like this if the tools' defaults had not been reachable?
- Does it concede anything anywhere, or does every claim land at the same certainty?
- Does anything belong to the process more than the audience?
- Does the artifact already know where it should end?
- Is any important element only working because I am zoomed in or because I know hidden context?
- If a stranger walked into this with no backstory, would it still feel coherent?
- Does every name read correctly from the viewer's frame, not just the author's?
- Can the main message be paraphrased plainly without inventing missing logic?
- Do the claims, examples, labels, and evidence agree with one another?
- Would this be the same if a different person had asked for it, on a different machine, from a different sample?

## Say What It Did

Whenever this skill changes something, or finds something it could not fix, say so where the user can see it: the label `Anti-backrooms review`, then one table with the highest-value finding first.

| Finding | Change | Needs user |
| --- | --- | --- |
| <symptom, its mechanism, and why it fails> | <the fix made, or `none`> | <what the user must decide, or `no`> |

For an explicitly requested review, open with one line naming the artifact, its audience and viewing context, and the primary path. Stay silent when composing and nothing was found. When a review was explicitly asked for and nothing was found, show the table with one row reading `none`. The user can then see that the skill fired, judge each finding, and correct a false positive in one reply.

## Escalation Rule

If something feels uncanny but you cannot prove it with a single rule, do not ignore that signal. Name the suspicion clearly and either fix it or ask the user about it.

"It technically fits" is not enough.
