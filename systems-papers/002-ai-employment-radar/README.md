# Systems Paper 002 - From Job Search to Employment Intelligence

**Constraint-first AI work discovery, evidence matching, and human-gated career decisions.**

**Public GitHub Edition:** v1.2  
**Builder:** Roger Crosby  
**Project:** Paranoid People Live Longer  
**Status:** Public technical systems paper

[Read the full paper on GitHub](paper.md)

## What this paper is

`From Job Search to Employment Intelligence` documents a private employment-intelligence system built to solve a practical problem: generic AI job searches returned too many nominally relevant listings and too few opportunities that were actually usable.

The response was not to build another public job board. The problem was reframed as a decision-system problem:

- Which opportunities are impossible before detailed analysis begins?
- How should semantic or content fit be separated from practical employability?
- How can unstable job titles be treated as market vocabulary rather than canonical labels?
- What evidence supports a claim of fit?
- When should AI stop analyzing and a human make the consequential decision?
- How should false positives, near misses, and failures improve the next version?

The resulting architecture uses early feasibility gating, domain interpretation, evidence matching, deep reading, explicit human approval, and feedback from both rejection and success.

## Why the paper exists

The underlying tool was built for private use to improve a real job search.

The public paper exists for a different reason: **proof of systems-design capability without publication of the private operating package.**

It is not a replication specification, prompt pack, job-search template, or complete consulting method.

## Validation path

The system was developed through sequential prototyping rather than written as a finished doctrine first.

The first market test used a deliberately mixed batch of **30 live job listings**. Later stages deep-read the surviving candidates, exposed weaknesses in the early design, and tested the revised architecture against a more constrained hunt for actionable opportunities.

The public paper preserves the design lessons while withholding named listings, candidate-specific material, internal scores, thresholds, detailed test files, and private datasets.

The important development sequence was:

1. **Filter the noisy market.**
2. **Deep-read the apparent survivors.**
3. **Let failures change the architecture.**
4. **Run the revised system against a constrained real-world hunt.**
5. **Formalize the private operating system only after practical decision value appeared.**

That sequence produced one of the paper's central rules:

> **A system earns complexity only after a cheaper prototype demonstrates that the decision logic is useful.**

## Core public architecture

The paper exposes five high-level stages:

1. **Feasibility gate** - remove candidates blocked by non-negotiable conditions before expensive analysis.
2. **Domain interpretation** - determine what the role actually does rather than trusting the title.
3. **Evidence alignment** - compare material requirements with truthful, inspectable proof.
4. **Human decision** - keep consequential action under explicit human authority.
5. **Feedback loop** - convert outcomes, false positives, near misses, and vocabulary changes into system updates.

The exact feasibility checks, rejection logic, scorecard, weights, thresholds, search configuration, and candidate-specific evidence library remain private.

## Important design distinctions

### Feasibility before relevance

A conceptually perfect opportunity that cannot actually be taken is not a strong match.

Hard feasibility conditions therefore come before nuanced interpretation.

### Content fit is not employment fit

A role can strongly resemble the desired work and still be a poor employment decision.

The architecture keeps semantic resemblance and operational suitability separate so an attractive description cannot silently override practical reality.

### Search the work, not only the title

Job titles are unstable interfaces.

Useful roles and useful near misses teach the system new vocabulary, which can then improve future discovery.

### Evidence over enthusiasm

The system asks what evidence supports a material requirement rather than relying on broad declarations of experience or interest.

Evidence may be direct, analogous, bridgeable, or structurally absent. The detailed private mapping method is not published.

### Truth-preserving translation

Equivalent experience may be translated into the receiver's vocabulary.

Facts may not be invented.

A material application claim that could not survive detailed follow-up does not belong in the application.

### Human-gated action

AI can retrieve, extract, compare, classify, decompose requirements, and draft.

The human retains authority over target definition, tradeoffs, truth claims, consequential submissions, and changes to the governing rules.

## What the public paper demonstrates

The paper provides inspectable evidence of work in:

- constraint-first decision architecture;
- human-gated AI workflows;
- feasibility and rejection-gate design;
- evidence-backed capability translation;
- model-output and opportunity evaluation;
- failure-to-infrastructure thinking;
- vocabulary and taxonomy learning;
- public/private system-boundary design;
- sequential prototyping;
- documentation architecture;
- claims discipline;
- technical systems writing.

## What it does not claim

This paper does **not** claim:

- guaranteed employment outcomes;
- population-level hiring effectiveness;
- that an AI system can predict interviews or offers reliably;
- machine-learning engineering;
- autonomous application authority;
- that employer requirements are fully observable;
- that the public paper contains the complete private system;
- that a strong content match is automatically a suitable job.

The internal framework is a decision-support system for allocating attention and making better-grounded choices. It cannot control employer behavior, hidden hiring criteria, applicant volume, discrimination, or labor-market volatility.

## Public / private boundary

The public edition intentionally exposes:

- the problem definition;
- constraint-first architecture;
- the Gate Zero concept;
- the distinction between content and operational fit;
- evidence-matching principles;
- vocabulary-learning principles;
- the sequential validation story;
- human-gated decision authority;
- failure modes, limitations, and transferable lessons.

It intentionally withholds:

- exact feasibility checklists;
- personal constraints;
- detailed rejection and exception logic;
- internal scoring dimensions, weights, thresholds, and decision codes;
- candidate-specific proof libraries;
- search terms, source configuration, and monitoring cadence;
- named test datasets and detailed test documents;
- private workflows, prompts, templates, and operating Bibles.

**Release boundary:** enough architecture to evaluate the design; not enough implementation detail to reconstruct the private operating system.

## Why this matters professionally

A résumé can claim that somebody understands AI governance, evaluation, workflow control, evidence, or human oversight.

This paper makes a different kind of evidence available.

A reviewer can inspect:

- how an ambiguous problem was reframed;
- how constraints were ordered;
- how a failure in the first design changed the architecture;
- how evidence and aspiration were separated;
- how human authority was preserved;
- how the prototype was required to earn formalization;
- how private machinery was converted into public professional proof.

The paper is deliberately dense. It is intended to reward the reader who wants to inspect the thinking rather than optimize for casual browsing.

## How to read it

A useful path is:

1. Read the problem and design objective.
2. Read Gate Zero and the content-fit / employment-fit distinction.
3. Read the sequential prototyping section to see how failure changed the design.
4. Read evidence matching and truth-preserving translation.
5. Read the human/AI division of labour.
6. Read the failure modes and limitations before judging transferability.
7. Finish with the public/private boundary.

## Related public work

- [Systems Papers series](../)
- [Systems Paper 001 - Rebuilding the Room](../001-rebuilding-the-room/)
- [Published Documents](../../)
- [Human-Gated Agent System](https://github.com/RexPiperisOlem/human-gated-agent-system)
- [PPLL Signal Archive](https://github.com/RexPiperisOlem/PPLL-Signal-Archive)
- [Roger Crosby GitHub profile](https://github.com/RexPiperisOlem)

## Repository boundary

The GitHub-native paper and this README are public proof-of-work artifacts.

The private AI Employment Radar operating Bible, internal Systems Paper, test records, candidate data, search configuration, proof library, and implementation machinery remain private.

Publication does not grant access to those materials.

## Copyright and reuse

No open-content license is granted by publication of this paper unless a separate license explicitly says otherwise. Public access permits reading and inspection. It does not automatically grant permission to reproduce, modify, redistribute, package, train on, sublicense, or sell the work.

For permissions or professional use, contact the author.

## About the builder

**Roger Crosby** is an Ottawa-based systems builder and operational writer working across human-gated artificial intelligence, workflow governance, documentation architecture, failure analysis, provenance, quality control, knowledge operations, and the conversion of practical operating knowledge into inspectable structures.

Contact: [info@paranoidpeoplelivelonger.com](mailto:info@paranoidpeoplelivelonger.com)  
Portfolio: [PPLL Signal Archive](https://github.com/RexPiperisOlem/PPLL-Signal-Archive)  
Website: [Paranoid People Live Longer](https://paranoidpeoplelivelonger.com)
