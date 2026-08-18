# From Job Search to Employment Intelligence

A Systems Paper on Constraint-First AI Work Discovery, Evidence Matching, and Human-Gated Career Decisions

AI Employment Radar - Public GitHub Edition v1.2

> Core claim: A high-noise search problem improves when the system stops treating retrieval as the main task. Feasibility is tested before nuanced interpretation, evidence is kept separate from aspiration, and consequential action remains human-approved. The result is a repeatable decision architecture rather than a larger list of jobs.

Purpose statement. This paper demonstrates a tested systems-design approach to AI-assisted employment intelligence. It is a public proof-of-work artifact, not a replication specification. Implementation details, exact operating rules, detailed scoring mechanics, search configuration, candidate-specific constraints, and private working documents are intentionally withheld.

## Abstract

Generic job-search systems often optimize for retrieval volume and keyword similarity. For specialized AI work, that can produce a predictable failure mode: technically relevant listings are mixed with roles that are operationally unsuitable, titles are inconsistent, employer requirements are unevenly expressed, and semantic similarity can hide practical impossibility. The AI Employment Radar was developed as a constraint-first alternative. Its public architecture combines an early feasibility gate, domain interpretation, evidence matching, deep reading, human approval, and feedback from both rejection and success. Sequential prototyping materially changed the system before formalization. The resulting design illustrates broader principles for AI-assisted decision systems: reject impossibility early, keep semantic fit separate from operational viability, learn vocabulary from the environment, map claims to evidence, preserve human authority, and allow complexity only after practical value has been demonstrated.

> Paper map: Problem -> public architecture -> validation -> evidence -> transferable principles -> controls -> limits -> broader applications -> conclusion.

## 1. The Problem Is Not Finding Jobs

The visible problem appears simple: find paid work involving AI. The harder problem is deciding which nominally relevant opportunities are actually usable. A search engine can return hundreds of matches while leaving the most expensive work - interpretation, feasibility, evidence, and decision quality - to the person.

**Four forms of noise are especially important:**

- Label noise: a listing uses AI language even though the core work is materially different from the target domain.
- Title noise: similar work appears under inconsistent or unfamiliar role names.
- Feasibility noise: a role may be intellectually suitable but operationally unavailable because of non-negotiable constraints.
- Requirement noise: employer wish lists often blur the distinction between true barriers and negotiable preferences.

A ranking system can therefore be semantically correct and practically useless. The system objective must be larger than retrieval: it must support defensible decisions.

## 2. Design Objective

> Objective: Reduce a large, inconsistent market to a small set of opportunities that are relevant, feasible, evidence-supported, and worth human attention.

The system treats search results as candidates for evaluation, not recommendations. A listing earns deeper attention only by surviving increasingly expensive stages of analysis.

## 3. Public System Architecture

The public architecture is deliberately sequential. Cheap, decisive constraints come first; nuanced interpretation comes later. This protects attention and prevents semantic similarity from overriding practical reality.

| Stage | Purpose | Public question | Public output |
| --- | --- | --- | --- |
| Feasibility gate | Eliminate impossible candidates early | Can this opportunity realistically exist for the person? | Continue / stop |
| Domain interpretation | Separate real target work from label noise | What would the person actually be doing? | Working description of the role |
| Evidence alignment | Connect requirements to truthful proof | What can be demonstrated rather than merely asserted? | Evidence-supported fit picture |
| Human decision | Preserve accountability and personal tradeoffs | Is this opportunity worth consequential action? | Human-approved decision |
| Feedback loop | Learn from outcomes and errors | What should the next version remember? | Vocabulary, rule, or evidence update |

### 3.1 Gate Zero: feasibility before relevance

Gate Zero is the central architectural idea. Before detailed role interpretation, the system checks whether a hard practical condition makes further analysis pointless. The exact internal checks are private, but the public principle is simple: a conceptually perfect opportunity that cannot be taken is not a strong match.

This generalizes well beyond employment. In any decision pipeline, test non-negotiable feasibility before spending significant computation, attention, or persuasion effort on softer ranking criteria.

### 3.2 Content fit and employment fit are separate variables

A role can closely resemble the desired work and still be a poor employment decision. The architecture therefore keeps semantic or content alignment separate from practical employability. This prevents attractive false positives from being promoted simply because the work sounds right.

> Design rule: Never allow conceptual similarity to silently substitute for operational viability.

### 3.3 Search the work, not only the title

Job titles are treated as unstable market labels rather than canonical identifiers. Useful roles and useful near misses can reveal new vocabulary, which is then fed back into future discovery. The public principle is vocabulary learning; the internal search vocabulary and source configuration are intentionally not disclosed.

## 4. Public Decision Logic

The public release does not disclose the internal scorecard, weights, thresholds, rejection codes, or application states. What matters externally is the order of reasoning and the integrity constraints placed around it.

**The decision logic follows five public rules:**

- Feasibility precedes nuanced ranking.
- Role interpretation is based on duties and constraints, not the title alone.
- Potential fit is compared against available evidence rather than enthusiasm or self-description.
- Deep reading is required before consequential action.
- The final action is explicitly human-approved.

### 4.1 Deep reading is mandatory

Titles and summaries are useful for triage, but they are insufficient for final decisions. Deep reading turns a listing from marketing language into an operational model: duties, constraints, hidden management load, technical depth, evidence requirements, and work conditions. This is where many superficially attractive candidates are correctly discarded.

### 4.2 Truth-preserving translation

The system may translate equivalent experience into the receiver's vocabulary. It may not invent titles, credentials, tools, outcomes, or history. The distinction is crucial: good positioning changes language, not facts.

> Integrity test: If a material application claim could not survive detailed follow-up, it does not belong in the application.

## 5. Validation by Sequential Prototyping

The architecture was not specified completely in advance. It was developed through three sequential prototype stages, with each stage allowed to expose flaws in the current design. The first market test used a deliberately mixed batch of 30 live job listings. Later stages deep-read surviving candidates and then tested the revised architecture against a constrained hunt for actionable opportunities. The public record preserves the learning while omitting named listings, candidate-specific material, internal scores, thresholds, detailed test files, and private datasets.

| Prototype stage | Question | Observed lesson | Design consequence |
| --- | --- | --- | --- |
| Stage A | Can a mixed market be filtered usefully? | Basic filtering reduced noise but practical constraints remained too weak. | Feasibility was promoted earlier in the pipeline. |
| Stage B | Do promising candidates survive deep reading? | Strong content matches could still be poor employment matches. | Content alignment and operational fit were explicitly separated. |
| Stage C | Can the revised system produce defensible action? | The revised architecture produced opportunities judged worthy of real application effort. | The prototype phase ended and the operating system was formalized internally. |

### 5.1 Failure is design evidence

Rejected candidates are not wasted retrieval. They reveal missing constraints, misleading labels, repeated requirement patterns, and vocabulary the search system may not yet know. In this architecture, false positives and near misses are part of the learning set.

### 5.2 Earned complexity

A common systems failure is to automate or document a weak idea before its decision logic has been tested. The Radar used a stop-testing rule: formalization was allowed only after the cheaper prototype demonstrated practical decision value. The exact internal stop criteria are not part of the public release.

> Complexity rule: A system earns documentation, automation, and scale only after a cheaper prototype demonstrates that the decision logic is useful.

## 6. Evidence Matching

The system does not ask only whether a person "has experience." It asks what evidence supports each material requirement. Evidence can come from formal roles, education, completed systems, public artifacts, documented workflows, or concrete demonstrations. Unsupported enthusiasm is not treated as proof.

| Evidence class | Public meaning | Decision implication |
| --- | --- | --- |
| Direct evidence | The capability has been demonstrated in a closely matching context. | Strong support. |
| Analogous evidence | A comparable system or workflow demonstrates the underlying capability. | Potentially useful if the connection is explained truthfully. |
| Bridgeable gap | Evidence is missing, but the barrier may be practical to close if market demand justifies it. | Learn or build evidence selectively. |
| Structural gap | A non-negotiable requirement is unavailable or materially outside the target path. | Re-route or reject. |

The private operating system contains the detailed mapping method. The public paper retains only the principle: consequential claims should be anchored to inspectable evidence.

## 7. Transferable Systems Principles

**Constraint first.** Put hard feasibility checks before nuanced ranking. This reduces wasted reasoning and prevents high semantic similarity from masking impossibility.

**Two-axis fit.** Represent resemblance and operational suitability separately. Collapsing them encourages over-recommendation.

**Failure as architecture.** Treat false positives, false negatives, and near misses as evidence about the system, not merely bad outcomes.

**Vocabulary discovery.** Do not assume external labels are stable. Learn terminology from the environment and feed it back into retrieval.

**Evidence over biography.** Map requirements to proof rather than relying on titles, broad identity claims, or enthusiasm.

**Human-gated action.** AI can retrieve, classify, compare, and draft; consequential action remains explicitly human-approved.

**Earned complexity.** Prototype with the cheapest useful representation and formalize only after value appears.

**Truth-preserving translation.** Reframe equivalent experience into the receiver's language without changing the underlying facts.

## 8. Human / AI Division of Labour

The architecture is intentionally human-gated rather than autonomous. AI is well suited to high-volume and high-friction analysis such as retrieval, extraction, comparison, classification, vocabulary discovery, and requirement decomposition. The human retains authority over target definition, acceptable tradeoffs, truth claims, consequential submissions, and changes to governing rules.

> Boundary: The system may recommend attention or action. It does not get to redefine what a suitable life, acceptable risk, or worthwhile job means.

## 9. Failure Modes and Public Controls

| Failure mode | Public control |
| --- | --- |
| Recency drift | Keep the target stable enough that one interesting new listing does not silently redefine the mission. |
| Over-permissive recommendation | Allow hard feasibility constraints to override attractive semantic matches. |
| Over-narrow filtering | Sample rejected candidates and deliberately search for unfamiliar terminology. |
| Requirement inflation | Distinguish genuine barriers from employer preferences. |
| Optimization replacing truth | Require claims to survive evidence and interview-level scrutiny. |
| Automation before understanding | Test the decision loop manually before scaling it. |
| Stale market assumptions | Keep transient listings separate from durable design doctrine. |

## 10. Limitations

- The prototype demonstrates usefulness for a specific employment target; it does not establish population-level hiring effectiveness.
- The internal evaluation framework is heuristic. It is designed to allocate attention consistently, not predict interview or offer probabilities.
- The labor market changes quickly. Individual postings are temporary evidence, not permanent system components.
- The system cannot control employer behavior, hidden hiring criteria, applicant volume, or discrimination.
- Evidence matching depends on the quality and accessibility of the underlying proof-of-work portfolio.
- Human judgment remains a source of both value and bias, which is why disagreement review and version history matter.

## 11. Why This Is a Systems Problem

The visible task - "find relevant jobs" - is not the real system problem. The real problem is coordinating noisy labels, feasibility, incomplete evidence, changing market vocabulary, ranking, truthfulness, and consequential human action. Retrieval alone leaves those interactions unresolved.

The Radar therefore behaves more like a control system than a search box. Candidate opportunities enter a gated pipeline; impossible states are removed; surviving candidates are interpreted; claims are constrained by evidence; humans control consequential action; and outcomes update the next version. The value comes from the connected decision loop, not any single classification step.

## 12. Implications Beyond Employment

The same public architecture can be applied to other high-noise decision environments where semantic relevance is cheap but operational suitability is expensive. Examples include grant discovery, vendor screening, procurement, research opportunity matching, policy triage, partnership evaluation, and candidate sourcing.

**The transferable pattern is:**

1. Define non-negotiable feasibility constraints.
2. Reject impossible candidates before nuanced analysis.
3. Interpret the survivors using a small number of explainable dimensions.
4. Deep-read only candidates that earn attention.
5. Map consequential claims to evidence.
6. Require human authorization for consequential action.
7. Feed outcomes and failures back into the next version.

## 13. Conclusion

The AI Employment Radar began as a response to an ordinary frustration: too many nominally relevant jobs and too few realistic ones. Its useful contribution is not a new job board or a larger search engine. It is a decision architecture that makes feasibility, evidence, learning, and human authority explicit.

Sequential prototyping changed the architecture materially before formalization. Basic filtering was not enough. Deep reading revealed that semantic alignment and practical employability could diverge. Moving feasibility forward in the pipeline corrected that defect. The revised system then demonstrated enough real decision value to justify a durable internal operating framework.

The broader lesson is simple: systems improve when failure is allowed to rewrite the architecture. Search is retrieval. Decision intelligence begins when the system knows what to discard, what to inspect, what must be proved, what should be learned, and when a human must decide.

> Closing principle: Build the cheapest useful decision loop first. Let reality decide whether it deserves a larger machine.

## 14. Public Release and Professional Engagement

This edition is designed for public inspection on GitHub and related portfolio surfaces. Its purpose is to make the system architecture, validation path, control philosophy, and claims discipline legible to employers, collaborators, and technical reviewers without publishing the private operating package.

Professional discussion can go deeper than the public paper where appropriate, but access to private implementation material is not implied by publication. Interested readers may contact info@paranoidpeoplelivelonger.com.

## Appendix A. Public Architecture Diagram

> INPUT - Candidate opportunities + public target definition + available evidence

↓

> FEASIBILITY GATE - Remove candidates blocked by non-negotiable constraints

↓

> INTERPRET + ALIGN - Understand actual work and compare it with the target domain

↓

> EVIDENCE + HUMAN REVIEW - Constrain claims to proof and make the consequential decision

↓

> FEEDBACK - Learn vocabulary, failure patterns, and validated design changes

## Appendix B. Public Claims

| Claim | Statement |
| --- | --- |
| Claim 1 | Early feasibility gates reduce wasted downstream analysis. |
| Claim 2 | Semantic fit and operational fit should be represented separately. |
| Claim 3 | Near misses and false positives can improve retrieval vocabulary and decision rules. |
| Claim 4 | Evidence-matched claims are more defensible than generic declarations of fit. |
| Claim 5 | Human-gated action preserves accountability while AI handles high-volume analysis. |
| Claim 6 | A system should earn complexity through successful low-cost tests before formalization or automation. |

## Appendix C. Public / Private Boundary

This paper intentionally exposes the design ideas necessary to evaluate the system while withholding operational details that would reproduce the private implementation.

| Public in this paper | Intentionally private |
| --- | --- |
| Constraint-first architecture | Exact feasibility checklist and personal constraints |
| Gate Zero concept | Detailed rejection rules and exception logic |
| Content fit versus operational fit | Internal scoring dimensions, weights, thresholds, and decision codes |
| Evidence-matching principle | Candidate-specific proof library and requirement mappings |
| Vocabulary-learning principle | Search terms, source configuration, monitoring cadence, and internal market taxonomy |
| Sequential validation story | Named test datasets, internal test documents, and transient market examples |
| Human-gated decision model | Private workflows, templates, prompts, and operating documentation |

> Release boundary: Enough architecture to evaluate the design. Not enough implementation detail to reconstruct the private operating system.

## Appendix D. Version Note

v1.1 established the sanitized public edition and formalized the public/private publication boundary. v1.2 is the GitHub release edition. It adds explicit purpose framing, states the 30-listing validation fact without publishing the private dataset or decision mechanics, adds a professional engagement path, and clarifies release history. The core architecture and system claims are unchanged.

The private operating Bible and internal Systems Paper remain separate archival artifacts. This public edition is the proof layer.
