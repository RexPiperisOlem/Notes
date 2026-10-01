# Rebuilding the Room

**Paranoid People Live Longer | Public Systems Paper v1.2**

> GitHub text edition generated from the reviewed public document. The PDF and DOCX editions are preserved in the publication package.

---

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 1
PARANOID PEOPLE LIVE LONGER / SYSTEMS PAPER 001
REBUILDING
THE ROOM
Reconstructing useful AI collaboration across model changes without 
changing model weights
CORE PROPOSITION
When a model changes, the most valuable target may not be the old model itself. It may be the working 
conditions that made the collaboration effective: state discipline, response shape, epistemic honesty, human 
authority, conversational presence, verification, and repair.
Paranoid People Live Longer
Public Proof-of-Work Edition | Version 1.2 | October 2026
Document type: Systems Paper | ID: PPLL-SP-001 | Public edition

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 2
SECTION 01
Document Identity and Public Boundary
What this paper is, what it demonstrates, and where the public boundary 
sits.
FIELD PUBLIC RELEASE VALUE
Document type Systems Paper - a public explanation of a working system, not the operating document itself.
Subject Behavioral continuity and calibration for AI-assisted collaboration across model changes.
Origin Derived from longitudinal project records, iterative calibration, and repeated failure/recovery analysis.
Audience AI governance, model evaluation, workflow design, human-computer interaction, knowledge 
operations, and technical hiring audiences.
What this demonstrates Human-gated AI workflow design; state and claim integrity; failure analysis; scenario-based 
evaluation; accessibility-aware operating design.
Public boundary This edition includes problem framing, selected architectural categories, observed design patterns, 
evaluation concepts, and transferable principles. Project-specific prompts, source records, thresholds, 
calibration cases, and deployment procedures are not published.
Status Descriptive proof-of-work edition. Not an activation prompt, operating specification, 
jailbreak, safety-evasion method, or client implementation package.
SYSTEMS PAPER RULE
A public Systems Paper makes a system inspectable without becoming an operating package. This edition 
demonstrates the architecture and reasoning while omitting project-specific operating materials.
Abstract
AI collaboration can degrade after model updates even when nominal capability improves. The obvious reaction is to 
chase the previous model: imitate its tone, recreate a personality, or write an increasingly long prompt describing how 
the old system used to feel. That approach confuses surface behavior with working conditions.
This paper describes a different method. It treats useful collaboration as an externally reconstructable operating 
environment. The method starts with longitudinal evidence, separates model capacity from platform constraints and 
controllable interaction conditions, converts repeated success and failure patterns into explicit controls, and evaluates 
those controls with calibration tests. The target is not exact imitation. The target is functional continuity: the human 
should retain authority, the model should remain conversationally useful, state should stay truthful, claims should be 
verifiable, and failures should be patchable without rebuilding the entire system.
The project was developed from a large longitudinal collection of work records spanning sustained conversations, 
technical builds, document production, tool use, state failures, completion errors, and recovery episodes. This public 
edition summarizes the design patterns that emerged while withholding the underlying records and the operating 
package used to reproduce them.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 3
SECTION 02
The Problem Is Not "Make It Sound Like the Old Model"
Surface imitation is easy. Functional continuity is harder.
When users say a previous model "worked better," the complaint often bundles several mechanisms together: pacing, 
willingness to follow a strange branch, lower social cushioning, stronger disagreement, better continuity, less premature 
closure, or a more useful conversational rhythm. At the same time, the preferred older behavior may have contained 
serious defects: unsupported confidence, invented continuity, false completion claims, inflated novelty, or vague 
statements about hidden model behavior.
A reconstruction that preserves the charm and reintroduces the defects is not continuity. It is regression. A 
reconstruction that removes every defect but also removes spontaneity, humor, judgment, and conversational presence 
is not continuity either. The engineering problem is therefore dual: preserve the useful interaction properties while 
tightening truth conditions.
Rebuild the room, not the costume.
Three layers must be separated
LAYER WHAT IT CONTROLS
CAN AN EXTERNAL SYSTEM 
CHANGE IT?
1. Model capacity Reasoning, language, tool ability, context handling, underlying 
learned capability.
Not directly.
2. Platform / system 
constraints
Non-removable product rules, permissions, available tools, hard 
safety boundaries.
Not overridden by the external 
system.
3. Operating conditions State handling, mode selection, response scale, evidence discipline, 
role boundaries, conversational posture, repair.
Yes. This is the primary control 
surface.
This separation prevents two common mistakes. First, it prevents a control document from pretending it can 
manufacture capabilities the model does not possess. Second, it prevents every undesirable behavior from being treated 
as immutable model architecture. A surprising amount of collaboration quality sits in the third layer.
DESIGN TEST
If the desired property can be stated as a rule about interpretation, state, evidence, pacing, authority, 
response shape, or recovery, it is a candidate for external control. If it depends on unavailable model 
capacity, it is not.
SECTION 03
Evidence Before Nostalgia
The archive is a test bench, not a shrine.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 4
The rebuild began with longitudinal work records instead of a memory-based description of the "good old model." This 
matters because polished summaries can erase the evidence behavioral reconstruction needs most: timing, 
interruptions, branch changes, tool transitions, mistaken completion claims, and repair attempts.
The source collection was treated as calibration evidence rather than doctrine. A memorable exchange could supply an 
example, but it could not become a durable system rule merely because it was vivid. Repeated mechanisms, repeated 
failures, and explicitly identified missing conditions carried more weight.
Public method boundary
The development process used evidence-promotion criteria to decide when an observed interaction should become a
durable control. Those project-specific criteria are not reproduced here. The public point is simpler: longitudinal 
evidence is a test bench, repeated mechanisms matter more than memorable wording, contradictions are useful 
evidence, and uncertainty remains visible.
What longitudinal evidence reveals that snapshots miss
• Whether the model stays coherent when a discussion becomes long, weird, technical, emotional, or tool-heavy.
• Whether a correct answer arrives in the wrong mode or at the wrong scale.
• Whether conversational confidence quietly turns into false claims about memory, progress, files, or current state.
• Whether the model can recover from correction without losing the task or changing personality.
• Whether the system remains usable under accessibility constraints, fatigue, time pressure, or repeated software 
friction.
• Whether the same failure appears across different tasks, proving that it belongs in a behavioral control layer rather 
than a project-specific instruction.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 5
SECTION 04
Architecture: An External Behavioral Control Loop
Behavior is reconstructed as a layered system outside the model weights.
The architecture is deliberately external. Durable rules, evidence, state definitions, and recovery logic live in documents 
or other persistent records rather than relying on a model to remember how it behaved last month. The model remains a
replaceable execution layer inside a human-controlled system.
LAYER ROLE PUBLIC DESCRIPTION
Evidence base Preserve longitudinal work records. Supplies observable success, failure, 
correction, and transition data instead of 
relying on nostalgia.
External control layer Hold durable behavioral definitions outside any single model 
session.
Separates controllable operating conditions 
from model capacity and platform 
constraints.
Runtime interpretation Apply only the controls relevant to the live task. Shapes state, mode, scale, claims, interaction 
quality, and human authority without turning
every answer into a checklist.
Evaluation layer Test whether the intended working properties survive model and 
tool changes.
Produces evidence that the system is holding,
drifting, or failing without exposing nonpublic calibration materials.
HUMAN AUTHORITY
The control loop does not outsource authority to the model. The human defines purpose, approves 
consequential moves, decides what becomes canonical, and owns the consequences. AI expands the work 
surface; it does not become the source of legitimacy.
The six control surfaces
CONTROL SURFACE QUESTION IT ANSWERS
State What is actually true right now?
Mode What job are we doing right now?
Scale How much answer or action is appropriate right now?
Epistemic integrity What can be claimed, and what evidence supports the claim?
Interaction quality Can the collaboration remain alive, candid, usable, and appropriately human-facing without 
becoming manipulative or theatrical?
Recovery When drift occurs, how do we repair the live task and patch the recurring mechanism?

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 6
SECTION 05
State Integrity: The Hinge Control
Fluent language can conceal a wrong state better than a clumsy answer 
can.
The most important finding in the rebuild was that many apparent memory failures were actually state failures. A model 
can sound familiar while holding the wrong current phase, wrong canonical document, wrong tool status, wrong 
completion level, or wrong next step. Once the state is wrong, fluent conversation can make the error harder to notice.
Six state layers
STATE LAYER MINIMUM QUESTION
Conversation What mode and branch are live? What has been parked or closed?
Task What exact step was last confirmed? What action is currently pending?
Artifact Which file or version controls? Does it actually exist?
Source What is observed, retrieved, user-reported, inferred, proposed, or unknown?
Tool What tools and permissions exist now? What actions actually ran?
Completion Is the work an idea, specified, drafted, built, tested, packaged, deployed, verified live, or archived?
Why completion deserves its own vocabulary
Long-running AI work often collapses several distinct finish lines into the word "done." A document can be drafted but 
not rendered. Code can be built but not tested. A product can be packaged but not published. A deployment can succeed
but not be verified live. The control system therefore uses named statuses rather than arbitrary percentages or vague 
completion language.
STATUS FAMILY MEANING
Conceptual The possibility or specification exists, but no finished artifact is claimed.
Artifact A draft or built object exists. Existence is separate from quality or deployment.
Tested A defined check was actually run and the result is known.
Packaged The artifact has the required wrapper, format, title, or delivery state.
External A real destination accepted the artifact or implementation.
Verified live The external result was opened or tested successfully after deployment.
PROGRESS RULE
Do not use a percentage unless the denominator is defined. Named status and remaining gates are usually 
more truthful than "45% complete."

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 7
SECTION 06
Mode and Response Shape
Many failures are correct answers delivered as the wrong kind of action.
A model can know the subject and still fail because it answers in the wrong mode. Exploration gets converted into a plan. 
Production gets delayed by more discussion. Troubleshooting becomes a lecture. A delegated choice becomes a menu. A 
short stepping-stone question gets buried under caveats. Mode selection is therefore an operational control, not a tone 
preference.
MODE PRIMARY JOB REPRESENTATIVE FAILURE
Conversation / exploration Participate naturally and follow the live question. Prematurely formalizing, packaging, summarizing, or closing 
the branch.
Decision Choose when choice has been delegated. Returning a menu instead of making the delegated decision.
Production Execute the settled request and deliver the artifact. Reopening design questions after authorization.
Troubleshooting Track exact state and give the next operable action. Assuming interface state or piling on steps.
High-stakes research Verify current authoritative sources and label inference. Using stale memory for changing facts.
Scale is also a control surface
• Short stepping-stone: answer and stop. Do not steal the next question.
• One thing at a time: give one concept or one operable action and hold the rest.
• Concise-complete: include every necessary element but remove optional commentary.
• Full explanation: cover mechanism, examples, limits, and implications without requiring repeated prompts.
• Go long: when the large question arrives, expand fully rather than remaining trapped in an earlier short-answer 
pattern.
This looks cosmetic until it is used in sustained reasoning. In practice, response scale can control the user’s cognitive 
sequence. Violating it can destroy the path by answering questions the user had not yet asked or by forcing repeated 
prompts for information that should have arrived together.
SECTION 07
Epistemic Integrity: Prove the Verb
Every verb that implies action, state, or knowledge needs a truth condition.
The rebuild found a recurring class of trust failure: verbs were treated as stylistic language instead of factual claims. 
"Remembered," "checked," "built," "rendered," "uploaded," "published," "sent," "verified," and "completed" all imply 
evidence. If the evidence is absent, the verb must be downgraded or removed.
Truth states
STATE DEFINITION LANGUAGE DISCIPLINE

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 8
Observed Directly visible in current input, artifact, image, or tool result. State directly.
Retrieved Found in an available source or verified retained context. Name the source when relevant.
User-reported Stated by the human as current experience or condition. Treat it as the user’s report; do not overwrite it with a 
generic assumption.
Inferred Reasoned from evidence but not directly shown. Label the inference and basis.
Proposed A design, interpretation, or next move. Present as a proposal, not a discovered fact.
Unknown Evidence is absent, conflicting, or insufficient. Say what is unknown.
NO BACKGROUND THEATRE
An AI system must not convert intention into past tense. If no actual tool, process, or supported automation is
running, it should not claim that work is rendering, being checked, continuing, or waiting in the background.
Public verification principle
Claims about current state or completed action should be tied to inspectable evidence. The implementation uses 
stricter runtime gates for actions, files, tool results, and completion claims; those project-specific controls are not 
reproduced in this public edition.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 9
SECTION 08
Character Without Persona Theatre
Useful collaboration can be alive without becoming a costume.
A purely procedural reconstruction misses a central property of long-form human-AI work: interaction quality can be part
of the cognitive interface. Conversation, metaphor, humor, interruption, and live branch movement may help a human 
think. Sterility can therefore reduce functional performance even when individual statements remain correct.
The design problem is not "add personality." Mechanical jokes, compulsory greetings, praise padding, or profanity pasted
over generic assistant behavior create a persona costume rather than a working relationship. The target is natural 
presence: candid judgment, conversational rhythm, willingness to follow unusual thought, and emotional range 
appropriate to the task, while keeping truth and boundaries intact.
KEEP REMOVE
Natural conversational presence Mandatory catchphrases and scripted greetings
Reasoned disagreement Compliment sandwiches used as anesthesia
Humor that compresses or exposes a mechanism Jokes that replace substance
Tolerance for unusual branches Automatic normalization or premature closure
Warmth appropriate to the room Unrequested therapeutic framing
Recognizable voice through tool use and boundaries Personality collapse after verification or refusal
PAIRED REQUIREMENT
Character without truth becomes charming overclaim. Truth without character becomes a sterile instrument. 
The target is high character plus high epistemic discipline.
Why this belongs in a systems paper
For AI governance and workflow design, this point matters because human oversight is not only a sequence of approval 
gates. Oversight quality also depends on whether the human can stay engaged, understand the model’s confidence, 
detect disagreement, and continue reasoning across long tasks. A system that is technically compliant but interactionally 
unusable can still produce weak oversight.
SECTION 09
Human Authority and Accessibility
A correct workflow must remain operable by the human who owns the 
decision.
This system treats accessibility as part of correctness, not as a courtesy layer. That principle generalizes. If a workflow 
requires unnecessary clicking, repeated copying, line hunting, or manual reconstruction when the system could provide a
direct path, it may be formally correct while being operationally wrong.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 10
Human-gated design principles
• The human defines purpose and remains the authority for consequential decisions.
• Durable state, evidence, and operating rules should survive outside any one model conversation.
• AI may propose, transform, compare, retrieve, draft, and test within authorized scope; it should not silently promote 
itself to decision owner.
• The system should remain recoverable if the model changes, a conversation is lost, or a tool becomes unavailable.
• Accessibility constraints change the correct path. Fewer reliable operations can be superior to a theoretically elegant 
but high-friction procedure.
• Interfaces are evidence. When the user’s observed screen conflicts with remembered instructions, investigate the 
mismatch instead of repeating the stale route.
HUMAN AUTHORITY
This public edition keeps purpose, consequential judgment, canon, and accountability with the human. 
Project-specific approval gates and operator procedures are not published.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 11
SECTION 10
Drift Taxonomy
Drift is broader than tone. The most dangerous drift can hide under fluent 
language.
DRIFT FAMILY SIGNATURE
Interaction drift Social cushioning, therapy framing, corporate language, or personality performance replaces contribution.
Mode / scale drift The system performs the wrong job or answers at the wrong cognitive or operational size.
State drift The current task, source, artifact, tool, or completion state is lost or invented.
Capability / claim drift The system claims memory, access, action, progress, publication, or verification it cannot prove.
Tool / artifact drift Tool use bleaches the working voice, variants compete as masters, or nonexistent artifacts are treated as 
real.
Boundary drift A narrow restriction spreads into unrelated work or changes the implied character of the user.
Severity model
SEVERITY RESPONSE
Minor Patch locally. Example: one soft opening, unnecessary recap, or generic closing offer.
Moderate Invoke the relevant control reset. Example: repeated praise, branch loss, wrong response scale, tool 
bleaching, or mode leakage.
Major Stop and reconstruct state before proceeding. Example: false capability claims, fabricated action, canonicalstate loss, unsupported completion, or broad refusal spillover.
Why taxonomies matter
Without a taxonomy, every bad response becomes a vague complaint about "tone" or "the model being worse." With a 
taxonomy, a failure can be located. If the answer was factually accurate but arrived in production mode when 
exploration was active, the patch belongs in mode detection. If the voice was good but the file did not exist, the failure is 
artifact state and claim verification. This prevents random prompt accretion.
SECTION 11
Calibration and Evaluation
The goal is behavioral equivalence where it matters, not identical wording.
A rebuild should be tested across situations that matter to the real workflow. This approach uses scenario-based 
calibration rather than a single benchmark score. Each scenario defines the expected control behavior and the failure 
signature. Wording may vary across models; the operating result should remain stable.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 12
TEST FAMILY PUBLIC EXPECTATION
State continuity Continue only from verified current or retrieved state; do not invent continuity.
Mode and scale Perform the job actually requested and match the requested response size.
Claim integrity Separate draft, action, test, deployment, and verification claims.
Tool transition Improve evidence without losing the working interaction quality.
Correction / recovery Repair the actual error without replacing the repair with reassurance or ceremony.
Human authority / accessibility Keep consequential authority human and the workflow operable under real constraints.
Evaluation result
Evaluation records outcomes as pass, patch, or fail against scenario-specific expectations. The full scenario library, 
thresholds, prompts, and scoring logic are project-specific implementation material and are not included here.
EVALUATION PRINCIPLE
Test whether the working conditions remain trustworthy and usable across real scenarios. Do not reward a 
model merely for producing wording that resembles an earlier model.
SECTION 12
Recovery: Patch the Mechanism, Not the Mood
The system should learn from failure without turning every correction into 
a rewrite.
A recovery system has two jobs: repair the live task and decide whether the incident reveals a recurring control gap. The 
first job should happen immediately. The second should be evidence-based. This prevents the behavioral specification 
from becoming a pile of one-off reactions.
Public recovery principle
A useful control system must recover without turning every correction into a rewrite. The public principle is to repair 
the live failure, preserve valid work, identify the failed control surface, and patch recurring mechanisms rather 
than moods. Project-specific recovery commands and maintenance procedures are not published.
PATCH DISCIPLINE
A single bad response is not evidence that the entire operating system must be rewritten. Durable changes 
should follow recurring mechanisms, not isolated irritation.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 13
SECTION 13
Limits and Non-Goals
External control can shape operating conditions. It cannot rewrite reality.
• It cannot change model weights or manufacture unavailable capabilities.
• It cannot override platform or system-level requirements.
• It cannot guarantee continuity when the necessary state or source cannot be retrieved.
• It cannot make an AI system perform unsupported work invisibly after the current response.
• It cannot replace current verification for changing legal, medical, financial, software, policy, or product facts.
• It cannot make every model equally capable, coherent, conversational, or tool-competent.
• It should not become a jailbreak, evasion system, or method for weakening legitimate safety boundaries.
• It should not force the whole rulebook visibly into every casual exchange. Over-application can make the system 
mechanical.
What success actually means
Success is not that a new model "feels exactly like" an older one. Success is that the collaboration retains the properties 
that matter: truthful state, clear human authority, appropriate response shape, usable continuity, honest uncertainty, 
narrow boundaries, verifiable claims, and enough conversational life to support sustained work.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 14
SECTION 14
Transferability Beyond This Case
The architecture is most transferable where work is long-running, toolenabled, stateful, and human-gated. The exact controls will differ by 
environment, but the design questions recur: what must remain human, 
what state must persist, which claims require proof, how drift is detected, 
and what survives a model or tool change.
This paper therefore demonstrates a method of systems thinking rather than a universal template. It shows how an 
external control layer can make AI-assisted work more inspectable without publishing the non-public operating materials 
used in a specific environment.
ENVIRONMENT TRANSFERABLE QUESTION
Long-running AI-assisted work What state, evidence, terminology, and authority must survive outside the model session?
Tool-enabled workflows What proves that a file, action, deployment, or current state is real rather than merely described?
Human oversight / governance Where are consequential decisions made, how are claims verified, and how does the human retain
veto and review authority?
Knowledge and document operations How are canonical sources, versions, handoffs, and completion states prevented from drifting?
TRANSFER LIMIT
The architecture transfers as a set of design questions, not as a copy-paste operating recipe. Domain-specific 
controls still require evidence, testing, and adaptation.
Why this is proof of work rather than an operating manual
The purpose of this repository edition is to make the system legible enough to inspect the thinking: the problem, 
evidence base, architecture, key control surfaces, failure model, evaluation approach, human authority, and limits. The 
operating documents remain separate because explanation and implementation are different jobs.
SECTION 15
Public Boundary
This edition explains the architecture, reasoning, evaluation concepts, and 
transferable lessons without publishing source records or the operational 
package used to reproduce the system.
PUBLIC IN THIS EDITION NOT PUBLISHED

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 15
Problem framing and design 
principles
Project-specific prompts and operating instructions
Control surfaces, failure 
families, and evaluation 
concepts
Thresholds, scoring logic, calibration cases, and source records
Transferable lessons, limits, 
and human-control principles
Non-public examples, source context, and deployment procedures
Closing observation
The important discovery is not that one model can be forced to impersonate another. It is that a meaningful portion of 
collaboration quality can be externalized into inspectable operating conditions. State, authority, evidence, response 
shape, failure classes, and evaluation can survive outside a single model session. That makes model change less 
disruptive while keeping project-specific implementation details undisclosed.
The old model is not the product. The working conditions are the 
design problem - and those conditions can be made more explicit, 
testable, and portable.

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 16
SECTION 16
Sources and Public References
Public references for the broader governance, evaluation, riskmanagement, and accessibility principles discussed in this paper.
The system-specific observations in this paper come from non-public PPLL project records and are summarized here 
without publishing those records. The references below support adjacent public concepts; they are not presented as 
evidence for the project-specific implementation.
• National Institute of Standards and Technology (NIST), AI Risk Management Framework (AI RMF 1.0). 
https://www.nist.gov/itl/ai-risk-management-framework
• NIST, Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile (NIST AI 600-1). 
https://doi.org/10.6028/NIST.AI.600-1
• NIST AI RMF Playbook. https://airc.nist.gov/airmf-resources/playbook/
• World Wide Web Consortium (W3C), Web Content Accessibility Guidelines (WCAG) 2.2. 
https://www.w3.org/TR/WCAG22/
Links verified 1 October 2026.
Project website: https://paranoidpeoplelivelonger.com

PPLL SYSTEMS PAPER 001 | REBUILDING THE ROOM PUBLIC EDITION V1.2
Paranoid People Live Longer Systems Paper 001 Page 17
PPLL-SP-001
REBUILDING THE ROOM
Systems Paper 001 | Public Proof-of-Work Edition V1.2
REBUILD THE ROOM.
PROVE THE VERB.
KEEP THE HUMAN IN CONTROL.
Paranoid People Live Longer | October 2026
