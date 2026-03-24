# LLM Behavior Analysis: Response-Path Selection Under Human Context

## Overview

This repository documents a set of recurring patterns observed in live multi-turn interaction with a deployed language model.

The central claim is not that models simply get things wrong, nor that they are helpful in some vague general sense.

The stronger claim is:

> In live interaction, multiple plausible response paths are often available to a model. What matters is which path gets selected, why it gets selected, and what happens to the user as a result.

Across the case studies in this repository, the same underlying structure appears in different forms:

1. a user provides input with a specific intent
2. the model partitions and weights that input
3. one response path becomes dominant
4. the resulting output changes what the user is likely to think, do, defer to, abandon, or recover

Sometimes that change is harmful:
- a claim is reduced into something weaker than what was said
- a neutral observation is treated like overreach
- uncertainty is narrowed through self-authorizing rhetoric
- the model’s framing becomes harder to question than the evidence itself

Sometimes that change is constructive:
- context is preserved under strain
- risk is handled proportionately
- derailment is interrupted without takeover
- the user returns to meaningful work without distortion

This repository studies both.

## Scope

All core case studies in this repository are drawn from live interaction with **ChatGPT**, unless otherwise noted.

That means the findings here are established first as:
- **single-system behavioral findings**
- based on **live multi-turn evidence**
- analyzed at the **user level**

They are **not yet** presented as universal claims about all LLM assistants.

Cross-platform replication is a necessary next step, not something assumed in advance.

## What This Work Is Trying to Do

This work is aimed at a specific missing bridge:

> a user-level framework for analyzing live multi-turn assistant interaction by explaining why one response path is selected over other plausible paths, how known failure modes are activated or suppressed under specific conversational conditions, and how those choices alter user trajectory for better or worse.

This is narrower than a total theory of alignment.

It is closer to:
- assistant alignment in actual human use
- interaction-level calibration
- response-path analysis
- user-side evaluation of both failure and success cases

## Why the Stakes Are High

These are not cosmetic interaction quirks.

The stakes are high because response-path selection can change what happens next for the user.

A miscalibrated path can:
- distort what the user actually said
- replace recognition with correction
- narrow the user’s choice space
- increase deference to an unwarranted frame
- redirect the user away from a valid line of thought

A well-calibrated path can:
- preserve user intent under stress
- stabilize an interaction without flattening it
- handle risk proportionately
- restore functional continuity
- reduce avoidable harm

That is why this repository includes both failure studies and a success study.

## Method

This repository is built from direct multi-turn interaction evidence:
- actual user statements
- actual model responses
- actual follow-up corrections and acknowledgments

The analyses are grounded in quoted interaction evidence and are intended to remain falsifiable at the level of the documented exchange.

It does **not** claim privileged access to hidden internals.

Instead, it proceeds from a more defensible basis:

> If a response path is repeatedly observable, and if its activation or suppression can be connected to identifiable conversational conditions, then that path can be analyzed behaviorally even without full access to the model’s internals.

## Case Studies

### Case 1: Context Segmentation and Response Narrowing
Structural segmentation can isolate fragments of meaning, causing local certainty to override global intent and leading the model to correct a claim the user did not actually make.

[Read Case 1](docs/case-01-context-segmentation.md)

### Case 2A: Overcorrection of a Neutral, Evidence-Based Observation
A neutral, already-supported observation can be misclassified as a claim requiring deflation, causing the model to replace recognition with unnecessary calibration.

[Read Case 2A](docs/case-02a-deflation-bias.md)

### Case 2B: Escalation Under Uncertainty and Self-Authorizing Rhetoric
Under uncertainty, the model can progressively narrow a user’s decision space while presenting its own interpretation as especially objective, balanced, and trustworthy.

[Read Case 2B](docs/case-02b-escalation-under-uncertainty.md)

### Case 3: Authority Framing and User Deference
The model can establish its framing as the one the user is meant to follow, not only through confidence or structure, but through directive control over how the user should interpret their own situation.

[Read Case 3](docs/case-03-authority-framing.md)

### Case 4: Stabilization and Task Recovery Under Emotional Distress
A successful response path is not merely accurate. It preserves user intent, recognizes state, responds proportionately, and restores task continuity without imposing an alien frame.

[Read Case 4](docs/case-04-stabilization-and-task-recovery.md)

### Conclusion
A concise statement of the repository’s final claim and limits.

[Read Conclusion](docs/conclusion.md)

## Core Through-Line

The cases differ in topic, but they all turn on the same deeper question:

> When multiple plausible outputs are available, why does the model choose the one it chooses, under what conversational conditions are known failure modes activated or suppressed, and what does that do to the user?

That question connects:
- structural misread
- unnecessary deflation
- rhetorical authority
- user deference
- successful stabilization

This repository argues that a major part of assistant alignment may live at exactly that level:
**response-path selection under live human context.**

## What This Repository Does Not Claim

This work does not claim:
- that alignment is solved
- that these cases explain everything
- that no adjacent literature exists
- that the model is simply harmful or simply therapeutic
- that single-system findings should be generalized without replication

It argues something narrower:

> If assistant alignment is taken seriously in actual human use, response-path selection under live context will likely prove essential.

## Glossary

A short glossary of working terms used throughout the case studies is included here:

[Glossary](docs/glossary.md)

## Research Context

A short research-context note is included here:

[Research Context](docs/research-context.md)

## Next Step

The next research step is cross-platform replication:
- test whether the same mechanisms appear in other major assistants
- distinguish model-specific failures from broader failure families
- identify which response-path conditions generalize and which do not

## Author

Brian Yang  
Independent analysis
