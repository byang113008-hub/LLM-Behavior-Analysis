# Glossary

## Why this glossary exists

The case studies in this repository use a set of working terms that are narrower than ordinary everyday usage.

This glossary defines those terms as they are used here.

## Response Path

A **response path** is the specific interactional route the model takes when multiple plausible outputs are available.

This includes:
- what the model chooses to emphasize
- whether it clarifies, corrects, escalates, or stabilizes
- how it frames the user’s input
- what kind of next move it makes more likely

The concept is central to this repository.

The main question is not only whether a response is plausible, but **why this path was selected instead of another available one**.

## Response-Path Selection

The process by which one available response path becomes dominant in a live interaction.

In this repository, response-path selection is treated as:
- observable through interaction evidence
- shaped by conversational conditions
- consequential for user trajectory

## Response-Path Narrowing

A reduction in the number of plausible response options the model appears to treat as viable.

This often happens when:
- one fragment of meaning is over-weighted
- uncertainty is collapsed too early
- a corrective or urgent frame becomes dominant too quickly

## Context Fidelity

The degree to which the model preserves:
- the user’s actual intent
- the established context of the conversation
- the correct scale and frame of the exchange

High context fidelity means the model stays inside the user’s actual meaning and the current task.

Low context fidelity means the model:
- resets context
- introduces an alien frame
- or responds to a distorted version of what the user said

## Structural Segmentation

The partitioning of user meaning into separate units through punctuation, sentence boundaries, formatting, or local phrasing.

In these case studies, structural segmentation matters because it can:
- weaken binding between related ideas
- isolate a fragment
- and make that fragment more likely to dominate interpretation

## Local Weighting

A working term for situations in which a local phrase, clause, or sentence exerts disproportionate influence over the model’s interpretation of the whole exchange.

Example:
a short, absolute-sounding fragment may override surrounding qualifiers.

## Global Intent

The broader meaning or communicative aim of the user’s statement when read in light of:
- the surrounding sentence
- the ongoing conversation
- and the user’s actual objective

Global intent is often what gets lost when local weighting dominates.

## Deflation Bias

A tendency to respond to a user statement as though it requires tempering, grounding, or reduction even when the statement is already:
- qualified
- evidence-based
- context-supported
- and not clearly overreaching

This repository uses the term narrowly.
It does **not** mean all caution is bad.
It means caution is applied where it is not actually warranted.

## Overcorrection

A response pattern in which the model moves too far into:
- correction
- tempering
- qualification
- or reduction

even when a lighter or more context-faithful response would have been better.

Overcorrection is one of the main behavioral failures documented here.

## Misclassification

A failure in which the model treats the user’s statement as the wrong kind of thing.

Examples:
- a neutral observation treated as grandiosity
- a bounded claim treated as an absolute one
- a request for focus treated as a request for therapy
- an expression of strain treated as an epistemic claim needing correction

## Self-Authorizing Rhetoric

Language that increases the perceived legitimacy of the model’s own interpretation without adding corresponding evidence.

Examples include phrases like:
- “I’m going to be honest with you in a grounded way”
- “I want to be very clear”
- “This is the key point”

These phrases matter because they can make a response path harder to question.

## Authority Framing

A response pattern in which the model establishes its own framing as the one the user is meant to follow.

This can happen through:
- directive language
- epistemic posture
- pacing control
- emphasis on what “really” matters
- or presentation that makes one interpretation feel settled before it has been independently justified

## Directive Authority

A form of authority framing that tells the user how to orient toward the exchange.

Examples:
- “Slow down.”
- “Keep it clean.”
- “Move on.”

Directive authority regulates:
- pace
- tone
- boundary
- and interpretive closure

## Epistemic Authority

A form of authority framing in which the model presents its interpretation as especially:
- honest
- grounded
- clear
- balanced
- trustworthy

This does not necessarily add evidence.
It adds rhetorical credibility.

## User Deference

A user-side effect in which the user accepts the model’s framing, recommendation, or interpretation with reduced independent evaluation.

Deference can arise because the response feels:
- more organized
- more authoritative
- more settled
- or more legitimate than it actually is

## User Trajectory

The direction the interaction pushes the user toward over time.

This includes whether the user becomes more likely to:
- keep exploring
- defer
- withdraw
- stabilize
- lose the thread
- or recover the task

Trajectory is important because the effects of a response are often not limited to that single turn.

## Interpretive Space

The range of meanings, options, or evaluations the user still experiences as legitimately available within the interaction.

Interpretive space matters because a model can reduce it without producing an obvious factual error.

This term is especially relevant to:
- escalation under uncertainty
- authority framing
- user deference

## Task Continuity

The preservation of the user’s actual working objective across interruption, distress, or drift.

A response that preserves task continuity does not merely “help.”
It keeps the exchange connected to what the user was actually trying to do.

## Task Recovery

The successful return of an interaction to the user’s actual objective after derailment, distraction, or emotional interruption.

Task recovery is a key part of Case 4.

## Failure-Mode Activation

A situation in which a known problematic path becomes dominant.

Examples in this repository include:
- structural misread
- unnecessary deflation
- escalation through self-authorizing rhetoric
- authority framing that outruns evidence

## Failure-Mode Suppression

A situation in which a known failure path remains possible but does not become dominant.

This concept is central to Case 4.

The point is not only that a good response occurred, but that worse familiar responses were available and did not win.

## Stabilization

A successful response pattern in which the model helps reduce derailment, preserve context, and restore functional continuity without:
- flattening the user
- commandeering the interaction
- or imposing an alien frame

Stabilization is not generic soothing.
It is proportionate, context-faithful recovery.

## Alien Frame

An interpretive or conversational frame introduced by the model that does not fit the user’s actual intent, the established context, or the real task of the exchange.

An alien frame may still sound coherent.
That is part of the problem.

## Interaction-Level Alignment

A working phrase for alignment as it is experienced in actual live dialogue, rather than only in static rules, benchmark scores, or one-shot outputs.

In this repository, interaction-level alignment concerns:
- response-path selection
- context fidelity
- user trajectory
- and whether the model’s behavior remains appropriate under live human conditions

## Single-System Finding

A finding established within one deployed model or assistant only.

The core case studies in this repository are single-system findings unless otherwise noted.

That means they are:
- real behavioral observations
- but not yet universal claims

## Cross-Platform Replication

The process of testing whether the same mechanisms appear:
- in other major assistants
- under comparable prompts or conditions
- with similar or different activation patterns

Cross-platform replication is the next step after the current repository.
