# AI Claims Audit Stack

## Public System Paper v1.0

**Evidence-bounded auditing of claims made through, about, or with artificial intelligence.**

**Public GitHub Edition:** v1.0  
**Builder:** Roger Crosby  
**Project:** Paranoid People Live Longer  
**Status:** Public technical systems paper

> **Public disclosure boundary**  
> This public paper explains the purpose, principles, and high-level operating model of the AI Claims Audit Stack. Detailed internal prompts, routing logic, decision rules, audit worksheets, agent specifications, validation records, and other implementation material are intentionally withheld.

Version 1.0 | Public / Sanitized Edition

## Contents

Executive Summary

1. Why AI-Mediated Claims Need Auditing
2. What the Public Framework Examines
3. Evidence Access and Auditability
4. AI Context and Provenance
5. Consequential Decisions and Human Oversight
6. Quantitative Claims and Generalization
7. Public Operating Model
8. Findings and Accountability
9. What the Public Edition Does Not Disclose
10. Suitable Use Cases and Boundaries

Closing Position

## Executive Summary

The AI Claims Audit Stack is a structured framework for examining consequential claims that are produced by AI, supported by AI, evaluated with AI, or presented as if AI has independently established the conclusion. Its central premise is simple: the visible output is rarely the whole process.

AI systems operate inside human-built environments. People choose the question, data, model, configuration, threshold, evidence, workflow, review process, and presentation. Those choices can materially affect the result even when the final output appears technical, numerical, or objective.

The framework therefore works upstream. It asks what is actually being claimed, what evidence supports the claim, what information entered or was omitted, what AI context matters, who controls consequential decisions, what the numbers really measure, what recourse exists for affected people, and how far the available evidence permits a conclusion to travel.

> **Core public position**  
> The public edition is designed to communicate the method without disclosing the internal implementation. It is not a reconstruction manual for the in-house system.

## 1. Why AI-Mediated Claims Need Auditing

### AI can amplify authority without removing human judgment

A statement such as “the model found,” “AI identified,” or “multiple models agreed” can sound more independent than a human opinion. But AI-mediated conclusions still depend on upstream choices: the framing of the problem, the evidence supplied, the system used, the conditions under which it ran, and the way the result was selected and presented.

The framework does not assume those choices are improper. It treats them as auditable variables.

### The problem is often input, not output

Public discussion tends to focus on what an AI system said. A reliable audit also examines what the system received, what it did not receive, how the task was framed, what definitions were used, which sources were available, and what constraints shaped the analysis.

> **Why provenance matters**  
> A polished output can be completely authentic and still support a misleading public claim if the input conditions, selection process, or scope are materially different from what the audience is led to believe.

## 2. What the Public Framework Examines

The in-house implementation uses specialized internal components. The public edition describes the major functional domains only.

| **Functional domain** | **Public audit question** |
|---|---|
| Claim scope | What is actually being asserted, and which words carry hidden definitions or assumptions? |
| Evidence provenance | Where did the supporting information come from, what changed along the way, and what material information may be missing? |
| AI context | Which model, version, tools, date, environment, or prior state could materially affect interpretation of the result? |
| Institutional context | Who benefits, who has authority, who has practical leverage, and who controls consequential parts of the process? |
| Measurement integrity | What do the numbers measure, who is included, what is the comparator, and how uncertain is the estimate? |
| Human review and recourse | Can a person meaningfully review, override, challenge, correct, appeal, or obtain a remedy? |
| Auditability | How much of the process can be independently examined through lawful and legitimate evidence access? |
| Conclusion discipline | What does the evidence actually establish, and what remains unsupported, unknown, or bounded? |

### A claim is not a single object

A short sentence may contain multiple independent propositions. For example, a claim that “several leading AI systems independently identified the strongest candidate” contains assumptions about the systems, their independence, the meaning of “strongest,” the evidence they saw, and the decision process that followed. The framework separates those propositions before evaluating them.

## 3. Evidence Access and Auditability

A serious audit begins by asking what evidence would be needed to support the requested conclusion and whether that evidence can be obtained legitimately. This prevents a partial public-record review from being mislabeled as a full process audit.

| **Access class** | **Meaning** |
|---|---|
| Open evidence | Public records, published documentation, accessible technical material, direct public statements. |
| Restricted evidence | Material that exists but is paywalled, private, proprietary, privileged, contractually restricted, or controlled by another party. |
| Uncertain evidence | Material whose existence, completeness, or retention status cannot be established. |
| Unavailable evidence | Relevant information that is lost, deleted, not retained, or not lawfully obtainable within the audit scope. |

Restricted or unavailable evidence does not automatically count against the subject of an audit. It limits what the auditor can responsibly conclude.

> **Lawful acquisition rule**  
> The integrity of the acquisition method is part of the integrity of the evidence. The framework does not treat hacking, credential bypass, jailbreaking access controls, or other illegitimate acquisition methods as acceptable ways to fill an evidentiary gap.

## 4. AI Context and Provenance

“I asked AI” is not a reproducible technical description. Model families change, versions change, tools are added or removed, retrieval systems alter available evidence, and previous conversation state can condition later responses.

Relevant public questions include:

- the execution date or time window;
- the named AI system and model/version when disclosed;
- whether browsing, retrieval, memory, tools, or third-party software materially affected the run;
- whether the same question was asked under genuinely equivalent conditions;
- whether a published result reflects a single run, multiple attempts, or an undisclosed selection process.

The public paper intentionally does not publish the in-house procedure used to reconstruct or compare instruction stacks.

## 5. Consequential Decisions and Human Oversight

The presence of a human reviewer does not by itself prove meaningful human control. A person may formally sign the final decision while software controls the ranking, threshold, evidence display, or attention order that substantially shapes the outcome.

### Questions that matter publicly

- Can the human reviewer see enough underlying evidence to disagree intelligently?
- Can the reviewer change or override the AI-supported result in practice?
- Are overrides difficult, discouraged, penalized, or rarely exercised?
- Does the affected person receive meaningful notice of the decision and the information used?
- Can incorrect information be corrected before the consequence becomes irreversible?
- Can a challenge be initiated directly, or does it depend on another actor such as an employer, clinician, landlord, institution, or representative?
- Does a successful appeal restore the original opportunity, or only provide a later remedy?

> **Timing matters**  
> A right to appeal after the consequence has already occurred is not analytically equivalent to a process that can prevent the consequence before it occurs.

## 6. Quantitative Claims and Generalization

Numbers can create an appearance of precision while hiding definitional choices. The framework treats percentages, probabilities, rankings, risk scores, productivity claims, and performance comparisons as claims that require interpretation rather than as self-validating facts.

| **Check** | **Public question** |
|---|---|
| Measure | What exactly is being measured? |
| Unit | Time, rate, percentage, percentage points, probability, score, odds, cost, or another quantity? |
| Population | Who or what is included in the calculation, and who is excluded? |
| Comparator | Compared with what baseline, control, prior period, or alternative? |
| Uncertainty | What range, sensitivity, or error remains around the point estimate? |
| Proxy | Does the measured variable actually represent the concept used in the public claim? |
| Generalization | How far can the result legitimately travel beyond the tested population, technology, task, geography, and time? |

The framework also considers whether a metric still means the same thing when the underlying technology or workflow changes. A measurement that was useful in one operating environment may become ambiguous in another.

## 7. Public Operating Model

The internal system is recursive and routed, but its implementation is not published. At a public level, the method can be summarized in six stages.

1. Define the claim and separate the consequential propositions.
2. Establish the evidence needed and the level of access actually available.
3. Trace relevant evidence, AI context, institutional controls, and measurement choices.
4. Test whether alternative explanations, omissions, timing, or presentation materially change the interpretation.
5. Separate verified facts from allegations, assumptions, unresolved questions, and later evidence.
6. Issue a conclusion that is no stronger than the evidence and audit scope permit.

> **Evidence-bounded operation**  
> The framework is designed to narrow a claim when evidence is incomplete, not to fill missing information with assumptions.

## 8. Findings and Accountability

The public framework rejects a single “trust score.” Different dimensions can point in different directions: the evidence may be strong while the generalization is weak; the process may be transparent while the technical model is not reproducible; the quantitative result may be sound while the public headline overstates it.

| **Finding language** | **Public meaning** |
|---|---|
| Supported | Available evidence materially supports the claim within the stated scope. |
| Supported - bounded | The claim is supported only within important limits that must remain attached to the conclusion. |
| Partially supported | Some consequential elements are supported and others are not. |
| Not established | The evidence available to the audit is insufficient to support the claim. |
| Contradicted | Reliable evidence materially conflicts with the claim. |
| Unknown - material | A missing fact could materially change the conclusion and cannot responsibly be assumed. |
| Methodologically weak | The process has material design limitations even if the underlying conclusion might still be correct. |

The framework also distinguishes evidentiary posture. An allegation, preliminary court ruling, settlement, regulatory finding, admission, and final adjudicated finding are not interchangeable.

## 9. What the Public Edition Does Not Disclose

The public system paper is intentionally incomplete at the implementation level. The following material is retained in the in-house system and is not part of this GitHub edition.

| **Withheld implementation material** | **Public disclosure position** |
|---|---|
| Internal agent specifications | Detailed specialist responsibilities, prompt/instruction sets, internal decision authorities, and handoff rules. |
| Routing and recursion logic | The mechanism used to choose the next question, prioritize branches, stop investigation paths, and reopen issues. |
| Operational protocols | Internal checklists, thresholds, decision matrices, field cards, and case-handling procedures. |
| Audit ledger design | Detailed evidence-record schema, branch records, state codes, and internal provenance controls. |
| Validation archive | Crash-test cases, internal findings, design failures, revisions, and development history used to harden the system. |
| Scoring and comparison mechanics | Any internal formulas, weighting, confidence handling, branch prioritization, or implementation-specific metrics. |
| Private examples and working hypotheses | Internal case notes, unfinished reasoning, experimental material, and non-public research. |

> **IP boundary**  
> The omission of these materials is intentional. The GitHub edition is meant to demonstrate the system concept and audit discipline without publishing the operational machinery used to reproduce the in-house implementation.

## 10. Suitable Use Cases and Boundaries

### Where the public framework is useful

- AI-supported research, reports, forecasts, rankings, and public claims.
- Claims that multiple AI systems independently reached the same conclusion.
- AI-assisted hiring, screening, benefits, healthcare, insurance, education, finance, housing, or other consequential decisions.
- Productivity and performance claims expressed through percentages, scores, probabilities, or benchmarks.
- Public claims of neutrality, fairness, safety, accuracy, relevance, risk, qualification, or “best” performance.
- Situations where the process is only partially visible and the audit must state what cannot be verified.

### What it is not

- It is not a detector for identifying whether text was written by AI.
- It is not a guarantee that a model output is true or false.
- It is not a substitute for jurisdiction-specific legal advice, clinical judgment, financial advice, or domain-specific scientific review.
- It does not claim access to hidden model reasoning or proprietary internals that have not been legitimately disclosed.
- It is not a method for bypassing access controls, passwords, paywalls, authentication, or other legal and technical restrictions.
- It is not a public certification mark or an automatic label of fraud, bias, corruption, or bad faith.

### Public design principles

- Audit the process, not just the output.
- Define consequential terms before treating them as measurements.
- Treat unknown as unknown rather than as permission to guess.
- Keep evidence quality separate from evidence accessibility.
- Separate formal authority from practical influence over outcomes.
- Keep conclusions no stronger than the evidence and audit scope.
- Preserve the distinction between weak methodology, misleading presentation, and intentional deception.

## Closing Position

The AI Claims Audit Stack is built around a simple idea: accountability improves when claims can be traced back through the evidence, conditions, decisions, measurements, and human institutions that produced them. AI does not make that chain disappear. In many cases it makes the chain more important.

The public edition documents the philosophy and scope of the system while deliberately withholding the operational machinery of the in-house implementation. Its purpose is to show what responsible AI-claim auditing should examine, what it should refuse to assume, and why auditability must be treated as part of accountability.

> **Public principle:** When the evidence cannot support the desired conclusion, change the scope - not the evidence.

---

## Public / private boundary

This GitHub paper is a public proof-of-work artifact. It explains the purpose, major audit domains, design principles, evidence-access rules, human-oversight questions, quantitative discipline, and findings vocabulary of the AI Claims Audit Stack.

It does **not** publish the private operating package, internal agent specifications, detailed prompts, routing and recursion logic, branch-priority mechanics, field cards, audit-ledger schema, validation archive, internal thresholds, or implementation-specific decision rules.

Publication demonstrates that the system exists and makes its reasoning boundaries inspectable. It does not deliver the private system itself.

## Copyright and reuse

No open-content license is granted by publication of this paper unless a separate license explicitly says otherwise. Public access permits reading and inspection. It does not automatically grant permission to reproduce, modify, redistribute, package, train on, sublicense, or sell the work.

For permissions or professional use, contact the author.

## About the builder

**Roger Crosby** is an Ottawa-based systems builder and operational writer working across human-gated artificial intelligence, workflow governance, documentation architecture, evidence and provenance, failure analysis, and the conversion of practical operating knowledge into inspectable structures.

Contact: [info@paranoidpeoplelivelonger.com](mailto:info@paranoidpeoplelivelonger.com)  
Portfolio: [PPLL Signal Archive](https://github.com/RexPiperisOlem/PPLL-Signal-Archive)  
Website: [Paranoid People Live Longer](https://paranoidpeoplelivelonger.com)