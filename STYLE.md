# Style Guide

This guide keeps terminology, facts and formatting consistent across the book.

## Audience and voice

1. Write for product, engineering, risk and operations teams at businesses that sell across markets. Explain a mechanism before using its acronym.
2. State facts and conclusions directly. Do not open by setting up a belief to knock down, such as "many people think".
3. Keep the tone neutral. Avoid promotional or alarmist adjectives.
4. Do not use dashes as punctuation, and do not use contractions or apostrophes. Use numbered lists rather than bullets.
5. Use American spelling.

## Facts and sources

1. Every factual claim must trace to a public source: specifications, official documents from card networks and regulators, public documentation from payment providers, reports from security firms and research organizations, and peer reviewed papers.
2. Place a citation directly after the sentence it supports. Do not attach one citation to a paragraph that makes several unrelated claims.
3. Card network rules, regulations, thresholds and statistics change over time. Give a year or date in the text.
4. Do not infer or fill in what a source does not say. Where an inference is needed, mark it clearly, for example "our view is".
5. List the references at the end of each chapter, numbered in order of first appearance.

## Examples and cases

1. Write every case in general terms, with no detail that could identify a specific merchant, customer or transaction.
2. Do not include attack payloads or step by step instructions that could be reused. Describe the logic of the attack and the defense.

## Terminology

1. 3DS, EMV 3DS, 3DS Server, Directory Server (DS) and Access Control Server (ACS): spell out at first use in each chapter.
2. Frictionless authentication, challenge and liability shift: define at first use.
3. Merchant initiated transaction (MIT), Strong Customer Authentication (SCA) and card testing or enumeration: spell out or define at first use.
4. Card network, issuer, acquirer and payment service provider (PSP): use the role that actually performs the action. They are not interchangeable.

## Figures

1. Number figures by chapter, for example "Figure 4.3", and give every figure a caption.
2. Draw flows, sequences and architecture diagrams in Mermaid. Keep the source (`.mmd`) and the rendered PNG together under `assets/chNN/`.
3. When using a third party screenshot, credit the source in the caption and confirm permission before formal publication.
4. Make figures readable on a phone. Prefer vertical layouts.
