# Systems Papers

**Public proof-of-work papers about systems that were actually built, tested, revised, and used.**

The Systems Papers series sits between private operating machinery and public professional proof.

These papers are not product manuals, prompt packs, consulting playbooks, or complete reproduction kits. They exist to make a system legible without publishing the full machinery that runs it.

A Systems Paper answers questions such as:

- What problem existed?
- What kind of system was built in response?
- What architecture holds the system together?
- Which controls, gates, or state distinctions matter?
- What failed during development?
- How is drift, error, or recovery handled?
- What did the work demonstrate?
- What remains intentionally private?

The papers should reveal enough that a reader can inspect the thinking, system boundaries, and engineering discipline. They should stop before becoming a complete implementation recipe for the internal system or a substitute for project-specific consulting.

## Current papers

### [001 - Rebuilding the Room](001-rebuilding-the-room/)

**Behavioural continuity through external operating controls, state discipline, calibration, and human authority.**

This paper describes a system built after preferred large-language-model interaction behaviour changed across model versions. Instead of treating the problem as a request for imitation, the work treated it as an operating-systems problem: identify the interaction conditions that mattered, externalize them, make state and authority explicit, classify drift, and build recovery and calibration around the resulting control layer.

The public paper does **not** claim to modify model weights, restore a proprietary model, or reproduce private vendor internals.

**What it demonstrates:**

- model-agnostic behavioural control thinking;
- external operating-state design;
- failure and drift classification;
- human-authority boundaries;
- calibration as an operational discipline;
- documentation architecture;
- public-safe explanation of private systems work.

[Read the paper overview and PDF](001-rebuilding-the-room/)

### [002 - From Job Search to Employment Intelligence](002-ai-employment-radar/)

**Constraint-first AI work discovery, evidence matching, and human-gated career decisions.**

This paper documents an employment-intelligence system that began as a private response to a noisy AI job market. Instead of treating retrieval volume as success, the system puts feasibility before nuanced ranking, separates content fit from operational employability, maps claims to evidence, learns vocabulary from near misses, and keeps consequential action under human authority.

The underlying system was developed through sequential prototypes, beginning with a deliberately mixed batch of **30 live job listings**. The public edition preserves the validation story and architecture while withholding exact scoring mechanics, private constraints, candidate-specific evidence, search configuration, and operating documents.

**What it demonstrates:**

- constraint-first decision architecture;
- human-gated AI-assisted evaluation;
- evidence-backed capability translation;
- failure-to-infrastructure thinking;
- vocabulary and taxonomy learning;
- sequential prototyping and earned complexity;
- public/private system-boundary design;
- claims discipline and technical systems writing.

[Read the paper overview and GitHub edition](002-ai-employment-radar/)

### [003 - AI Claims Audit Stack](003-ai-claims-audit-stack/)

**Evidence-bounded auditing of claims made through, about, or with artificial intelligence.**

This paper documents the public architecture of a private AI-claims audit framework built to examine the process behind AI-supported conclusions rather than treating the visible output as self-explanatory. It separates claim scope, evidence provenance, AI context, institutional power, measurement integrity, human oversight and recourse, auditability, and conclusion discipline.

The public edition preserves the audit philosophy and major functional domains while withholding the internal agent specifications, detailed prompts, recursive routing logic, branch mechanics, field cards, ledger schema, validation archive, and other implementation material.

**What it demonstrates:**

- AI evaluation and claims auditing;
- evidence and provenance architecture;
- human oversight and contestability analysis;
- institutional power and incentive mapping;
- quantitative-claim discipline;
- lawful evidence-access design;
- bounded findings and accountability language;
- public/private system-boundary design;
- technical systems writing and human-gated AI governance.

[Read the paper overview and GitHub edition](003-ai-claims-audit-stack/)

## What qualifies for this series

Not every internal document deserves a Systems Paper.

A candidate should have:

- a real problem rather than an invented demonstration;
- an identifiable architecture;
- actual development history, use, testing, or failure evidence;
- meaningful controls or design decisions;
- known failure modes or boundaries;
- some method of evaluation, verification, or recovery;
- lessons that transfer beyond one private project;
- enough protected internal machinery that a public proof layer is useful.

If all that exists is a clever document or an interesting idea, it belongs somewhere else.

## Public proof versus private machinery

The series uses a deliberate boundary.

Public papers may show:

- the problem definition;
- architecture at a useful level;
- component relationships;
- control categories;
- failure classes;
- design rationale;
- representative examples;
- limitations;
- transferable lessons.

They do not automatically publish:

- private source archives;
- complete internal Bibles;
- exact implementation prompts;
- full calibration suites;
- personal operating material;
- reusable consulting procedures;
- hidden commercial mechanics;
- credentials, customer data, or live configuration;
- unreleased intellectual property.

The point is not secrecy for its own sake. The point is to distinguish **proof that a system exists** from **delivery of the system itself**.

## Relationship to other public work

The Systems Papers complement, rather than replace, the other repositories.

- [Human-Gated Agent System](https://github.com/RexPiperisOlem/human-gated-agent-system) is a working public reference architecture.
- [Published Documents](../) contains long-form manuals, analysis, creative work, and this Systems Papers series.
- [PPLL Signal Archive](https://github.com/RexPiperisOlem/PPLL-Signal-Archive) is the main public portfolio and index.
- [Roger Crosby's GitHub profile](https://github.com/RexPiperisOlem) provides the professional overview.

## Status

This is a growing document family. Numbering identifies the public series, not a promise that every internal PPLL system will be published.

The next papers are selected because the underlying system has earned an explanation, not because a publication quota needs filling.

## About the builder

Systems Papers are written from systems built by **Roger Crosby** through Paranoid People Live Longer and related private working environments.

The broader practice focuses on human-gated artificial intelligence, workflow governance, documentation architecture, failure analysis, provenance, public/private system boundaries, and the conversion of messy operating knowledge into inspectable structures.

Contact: [info@paranoidpeoplelivelonger.com](mailto:info@paranoidpeoplelivelonger.com)  
Portfolio: [PPLL Signal Archive](https://github.com/RexPiperisOlem/PPLL-Signal-Archive)  
Website: [Paranoid People Live Longer](https://paranoidpeoplelivelonger.com)
