# Research Context

## Why this note exists

The case studies in this repository are not presented as if they emerged in a vacuum. Public work already exists on:
- user-perceived interaction quality in human–AI dialogue
- learning from multi-turn user interactions
- emotional-support dialogue evaluation
- therapeutic alliance with chatbots

At the same time, the current literature still appears to lack a unified framework for analyzing the specific object of study pursued here:
> user-level explanation of response-path selection and suppression/activation of failure modes in live multi-turn interaction.

## Adjacent literatures that matter

A 2026 integrative review of 125 studies argues that the field still lacks a unified framework for **user-perceived interaction quality** in human–AI dialogue. That matters because this repository is not mainly about factual correctness in isolation. It is about how users experience and are affected by response-path selection in live interaction. 

A 2026 paper on **aligning language models from user interactions** argues that multi-turn user interactions contain useful alignment signal and that follow-up user messages can reveal when earlier responses were incorrect, preference-misaligned, or instruction-failing. That matters because the case studies here treat live interaction itself as evidence, rather than relying only on offline benchmarks or one-shot outputs. 

A 2026 benchmark called **HEART** directly compares humans and LLMs on the same multi-turn emotional-support conversations and evaluates qualities such as Human Alignment, Empathic Responsiveness, Attunement, Resonance, and Task-Following. That matters because Case 4 is concerned with successful stabilization and task recovery under distress, not simply with “good vibes” or generic supportive tone. 

A 2025 diary study on the **digital therapeutic alliance** examined how users perceive and develop relationships with mental-health chatbots over time using surveys, screenshots, and interviews. That matters because this repository also treats user trajectory, perceived legitimacy, and interactional effects as serious objects of analysis rather than background noise. 

## What appears to be missing

The public work above is relevant, but it does not appear to fully formalize the same goal pursued here.

This repository is not mainly trying to answer:
- whether a model is factually right
- whether a model is generally trusted
- or whether a model seems supportive in the aggregate

It is trying to answer a narrower question:

> When multiple plausible outputs are available in a live multi-turn interaction, why does the model choose the one it chooses, under what conversational conditions are known failure modes activated or suppressed, and what does that do to the user?

The literature reviewed above strongly overlaps with pieces of that question, but does not appear to package that exact user-level problem as its central object. 

## Position of this repository

This repository should therefore be read as:

- not a claim of total originality
- not a denial of adjacent work
- not a full alignment theory

Instead, it is best understood as an attempt to formalize a missing bridge between existing literatures:
- interaction quality
- user-side alignment signal
- emotional-support evaluation
- and live response-path analysis

Its distinctive contribution is the attempt to explain both **failure** and **success** cases at the level of:
- path selection
- contextual weighting
- rhetorical authority
- and user trajectory in real interaction. 

## Working conclusion

The strongest defensible claim is not that “nobody has studied anything like this.” That would be false.

The strongest defensible claim is narrower:

> The exact synthesis pursued here — user-level analysis of live multi-turn response-path selection across both failure and success cases — still appears under-formalized in the public literature.

That is the research context in which these documents should be read. 
