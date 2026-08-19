# Systems Paper 003 — AI Claims Audit Stack

**Evidence-bounded auditing of claims made through, about, or with artificial intelligence.**

**Public GitHub Edition:** v1.0  
**Builder:** Roger Crosby  
**Project:** Paranoid People Live Longer  
**Status:** Public technical systems paper

[Read the full GitHub paper](paper.md)

## What this paper is

`AI Claims Audit Stack` documents the public architecture of a private framework for examining consequential claims that are produced by AI, supported by AI, evaluated with AI, or presented as if AI has independently established the conclusion.

The system starts from a simple premise: **the visible output is rarely the whole process.**

A model response, score, ranking, forecast, or recommendation is shaped by upstream choices such as:

- what was actually asked;
- which evidence was supplied or excluded;
- which model, version, tools, and execution conditions were involved;
- which definitions or thresholds controlled the result;
- who had authority, incentives, or practical leverage;
- how numerical claims were measured and generalized;
- whether affected people could challenge, correct, appeal, or obtain a remedy;
- how the result was selected, summarized, or presented publicly.

The public paper explains those audit domains without publishing the complete in-house operating machinery.

## Why the paper exists

AI-mediated conclusions increasingly arrive with borrowed authority: “the model found,” “AI identified,” “the score says,” or “multiple models agreed.”

Those phrases can make a result sound independent even when humans still control much of the environment that produced it.

The purpose of the AI Claims Audit Stack is therefore not to decide automatically whether an AI result is true or false. It is to make the **process behind the claim inspectable** and to keep conclusions bounded by the evidence actually available.

The public paper exists as **proof of systems-design and audit-method thinking without publication of the private operating package.**

It is not a prompt pack, public audit checklist, certification scheme, or complete reproduction manual.

## Core public architecture

The public edition exposes eight functional domains:

1. **Claim scope** — separate the actual propositions from labels, rhetoric, and undefined consequential terms.
2. **Evidence provenance** — trace where supporting information came from, how it changed, and what may be missing.
3. **AI context** — identify model, version, tools, date, runtime conditions, and other context that can materially affect a result.
4. **Institutional context** — distinguish formal authority, practical leverage, incentives, and value transfer.
5. **Measurement integrity** — inspect units, denominators, baselines, uncertainty, proxies, and generalization.
6. **Human review and recourse** — determine whether review, override, correction, contestability, appeal, and remedy are meaningful in practice.
7. **Auditability** — establish what evidence can legitimately be examined and what level of audit the available evidence permits.
8. **Conclusion discipline** — state only what the evidence establishes while preserving material unknowns and scope limits.

The exact internal routing, recursive questioning logic, specialist definitions, branch handling, stop conditions, ledger schema, and implementation details remain private.

## Important public distinctions

### Evidence access is not evidence quality

A public source can be poor evidence. A restricted source can be excellent evidence. The framework treats **accessibility** and **quality** as separate questions.

### Unknown is not permission to guess

If a material fact cannot be established, the audit records that limitation instead of silently filling the gap with an assumption.

### Human in the loop is not automatically meaningful human control

A person may formally sign the final decision while software controls ranking, thresholds, evidence display, attention order, or other consequential levers.

The public framework therefore asks what the human can actually see, change, override, explain, and correct.

### Appeal rights have timing and dependency

A right to appeal after the consequence has already occurred is not equivalent to a process that can prevent the consequence.

The framework also asks whether exercising a right requires another actor — such as a clinician, employer, landlord, institution, lawyer, or representative — to act first.

### Numbers do not explain themselves

Percentages, probabilities, scores, rankings, benchmarks, and risk labels require interpretation.

The framework asks what was measured, who was included, what the baseline was, what uncertainty remains, and how far the result can legitimately travel beyond the tested population, technology, task, geography, and time.

## Evidence access and lawful acquisition

The system begins by identifying the evidence needed to support the requested conclusion and whether that evidence can be obtained legitimately.

The public framework distinguishes:

- open evidence;
- restricted evidence;
- uncertain evidence;
- unavailable evidence.

Restricted or unavailable evidence does not automatically count against the subject of an audit. It constrains what can responsibly be concluded.

**Lawful acquisition rule:** the integrity of the acquisition method is part of the integrity of the evidence. Hacking, credential bypass, illegitimate access-control circumvention, or similar methods are not accepted as ways to fill an evidentiary gap.

## Findings language

The public edition rejects a single “trust score.” Different dimensions can point in different directions.

Public findings use bounded language such as:

- **Supported**
- **Supported — bounded**
- **Partially supported**
- **Not established**
- **Contradicted**
- **Unknown — material**
- **Methodologically weak**

The framework also preserves evidentiary posture. An allegation, preliminary ruling, settlement, regulatory finding, admission, and final adjudicated finding are not interchangeable.

## What the public paper demonstrates

The paper provides inspectable evidence of work in:

- AI evaluation and claims auditing;
- evidence and provenance architecture;
- human oversight and contestability analysis;
- institutional power and incentive mapping;
- quantitative-claim discipline;
- auditability and evidence-access design;
- public/private system-boundary design;
- failure-to-infrastructure thinking;
- bounded conclusion language;
- technical systems writing;
- human-gated AI governance.

## What it does not claim

This paper does **not** claim:

- that every AI-mediated claim can be fully audited from public information;
- that a missing record proves misconduct;
- that a weak methodology proves the underlying conclusion false;
- that AI outputs can be certified as true through this framework alone;
- hidden access to model reasoning or proprietary internals;
- legal, clinical, financial, regulatory, or professional audit authority;
- that the public paper contains the complete private operating system;
- that publication of the paper grants permission to reproduce the internal method.

## Public / private boundary

The public edition intentionally exposes:

- the problem definition;
- major audit domains;
- evidence-access principles;
- high-level AI-context questions;
- human-oversight and recourse principles;
- quantitative and generalization discipline;
- findings vocabulary;
- suitable use cases, limitations, and public boundaries.

It intentionally withholds:

- internal agent specifications;
- detailed prompts and instruction sets;
- routing and recursive-questioning logic;
- branch-priority and stopping mechanics;
- operational protocols and field cards;
- the audit-ledger schema and state codes;
- internal comparison and confidence mechanics;
- detailed validation and crash-test records;
- private working hypotheses and case notes;
- the complete in-house operating package.

**Release boundary:** enough structure to evaluate the design; not enough implementation detail to reconstruct the private audit system.

## Why this matters professionally

AI governance is easy to describe in abstract language. This paper provides something more concrete: a reader can inspect how claims, evidence, access, model context, institutional power, measurement, human oversight, contestability, and conclusion strength are treated as separate but connected problems.

It demonstrates an operating philosophy built around a simple rule:

> **When the evidence cannot support the desired conclusion, change the scope — not the evidence.**

## Related public work

- [Systems Papers series](../)
- [Systems Paper 001 — Rebuilding the Room](../001-rebuilding-the-room/)
- [Systems Paper 002 — From Job Search to Employment Intelligence](../002-ai-employment-radar/)
- [Published Documents](../../)
- [Human-Gated Agent System](https://github.com/RexPiperisOlem/human-gated-agent-system)
- [PPLL Signal Archive](https://github.com/RexPiperisOlem/PPLL-Signal-Archive)
- [Roger Crosby GitHub profile](https://github.com/RexPiperisOlem)

## Repository boundary

The GitHub-native paper and this README are public proof-of-work artifacts.

The private AI Claims Audit Stack operating package, internal agents, routing rules, field tools, detailed ledgers, validation records, and implementation machinery remain private.

Publication does not grant access to those materials.

## Copyright and reuse

No open-content license is granted by publication of this paper unless a separate license explicitly says otherwise. Public access permits reading and inspection. It does not automatically grant permission to reproduce, modify, redistribute, package, train on, sublicense, or sell the work.

For permissions or professional use, contact the author.

## About the builder

**Roger Crosby** is an Ottawa-based systems builder and operational writer working across human-gated artificial intelligence, workflow governance, documentation architecture, failure analysis, provenance, quality control, knowledge operations, and the conversion of practical operating knowledge into inspectable structures.

Contact: [info@paranoidpeoplelivelonger.com](mailto:info@paranoidpeoplelivelonger.com)  
Portfolio: [PPLL Signal Archive](https://github.com/RexPiperisOlem/PPLL-Signal-Archive)  
Website: [Paranoid People Live Longer](https://paranoidpeoplelivelonger.com)
