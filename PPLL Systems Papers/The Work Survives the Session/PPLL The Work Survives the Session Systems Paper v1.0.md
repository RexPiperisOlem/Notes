# The Work Survives the Session

**Paranoid People Live Longer | Public Systems Paper v1.0**

> GitHub text edition generated from the reviewed public document. The PDF and DOCX editions are preserved in the publication package.

---

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
PARANOID PEOPLE LIVE LONGER / SYSTEMS PAPER
THE WORK SURVIVES
THE SESSION
A Systems Paper on Continuity, Handoff, Source of Truth, and Cold-Start Recovery
CORE PROPOSITION
A durable AI-assisted operation cannot depend on one chat, one model, or one person remembering 
the whole state. The work survives when authority, evidence, versions, decisions, and unresolved 
questions are externalized into inspectable records that can be reloaded and verified.
Public Proof-of-Work Edition | Version 1.0 | October 2026
Document type: Systems Paper | Public / sanitized edition
What this paper demonstrates: a continuity architecture for recovering current state after a new chat, model change, 
tool change, handoff, context loss, or interrupted workflow without treating memory as proof.
What this paper does not publish: private restart prompts, personal operating constraints, credentials, sensitive project 
status, internal file paths, exact authority maps, or the full recovery package.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
01 | Document Identity and Public Boundary
Field Public release value
Subject Continuity, handoff, source-of-truth routing, version state, and 
cold-start recovery for long-running AI-assisted work.
Origin Derived from a maintained continuity/handoff system and related
version, QA, retrieval, and authority records used in sustained 
project work.
Audience AI workflow designers, knowledge-operations teams, small 
organizations, technical operators, model-evaluation audiences, 
and anyone managing state across sessions or tools.
Public boundary Architecture, public state vocabulary, recovery logic, failure 
patterns, and transferable principles are included. Private 
prompts, personal context, exact file maps, security details, and 
environment-specific routing remain excluded.
Status Descriptive proof-of-work edition. Not a backup product, 
credential-recovery system, autonomous agent specification, or 
substitute for source verification.
Abstract
Long-running AI work has a structural weakness: the conversation feels like the work while it is happening, but the 
conversation is a poor permanent authority. Chats end. Models change. Memory is incomplete. Tools are replaced. Files 
move. Summaries compress distinctions. A handoff can preserve the story of a project while quietly losing which source 
is current, which claim was verified, and which decision was only proposed.
This paper describes a continuity system built to separate live collaboration from durable operational state. Its central 
move is simple: externalize the facts that must survive. Current authority, evidence level, version state, unresolved gaps, 
and recovery paths live in inspectable artifacts. The model can help operate the system, but the system does not treat 
model memory as the archive.
PUBLIC BOUNDARY
This edition explains the machine at architectural level. It deliberately omits private restart 
language, source inventories, sensitive project states, personal context, exact folder paths, and live 
operational controls.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
02 | Continuity Is a State Problem, Not a Memory Problem
The usual continuity question is “How do we make the next model remember?” The stronger question is “What must still 
be true even if the next model remembers nothing?”
Fragile approach Failure Continuity response
Rely on chat history Important state is buried in conversation 
and becomes hard to distinguish from 
discarded thinking.
Promote durable decisions and current 
state into maintained artifacts.
Rely on model memory Memory may be incomplete, stale, 
unavailable, or impossible to audit.
Treat memory as context, not proof.
Rely on newest file Modification time or polished appearance 
can misidentify authority.
Track explicit version/status and 
controlling authority.
Rely on summaries Compression can erase uncertainty, 
supersession, and evidence distinctions.
Preserve source records and label 
summaries as maps, not replacements.
Restart from scratch The human must repeatedly reconstruct 
the project.
Use a cold-start front door that routes to 
current sources and gaps.
CONTINUITY RULE
State is externalized. Memory is helpful, but memory is never the sole proof of current state.
The archive and the operator are different things
A model can be an active operator without being the durable archive. The durable layer is the set of maintained 
documents, ledgers, tests, source records, and version decisions that another model or human can inspect later.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
03 | Source of Truth Is Ranked, Not Averaged
Continuity fails when every old note, remembered fact, web result, and model inference is treated as equally 
authoritative. The system therefore uses a source hierarchy rather than conversational averaging.
Public priority Source class How it is treated
1 Current controlling instruction or current 
authoritative artifact
Highest priority for the live task unless a 
stronger explicit authority or safety 
constraint applies.
2 Verified artifact or source record Evidence of actual state: final files, system 
records, exports, screenshots, test results, 
or equivalent proof.
3 Maintained control documents / ledgers Doctrine, rules, statuses, and decision 
history, subject to version and scope.
4 Continuity map / handoff packet Front door and navigation layer; useful for
recovery but not a replacement for every 
underlying source.
5 Prior summaries or remembered context Useful orientation; insufficient by itself for 
consequential claims.
6 Fresh external information Used when the question depends on 
current outside facts.
7 Model intuition Lowest authority. Never proof.
AUTHORITY PRINCIPLE
When sources conflict, the job is to establish which one controls. The system should not average 
incompatible states into a confident answer.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
04 | Evidence Labels Preserve Uncertainty
A handoff is only trustworthy if uncertainty survives the handoff. The continuity layer therefore preserves evidence state 
instead of flattening everything into “known.”
State Meaning Public handling
PROVEN Supported by current source records, 
repeated checks, or direct verified 
evidence.
Use as operating fact within its scope.
USER-REPORTED / OWNER-REPORTED Directly stated by the responsible human 
but not independently source-checked in 
the current pass.
Respect as working state; verify before 
high-consequence public or irreversible 
use when needed.
UNVERIFIED Plausible or expected but not checked. Do not upgrade to fact.
CONFLICTING Sources disagree or authority is 
unresolved.
Hold the conflict visibly and resolve before
consequential use.
SUPERSEDED Replaced by later authority. Preserve for history; do not use as current.
SEALED / SENSITIVE Relevant but restricted. Keep out of ordinary public or portable 
context.
STILL NEEDED A required source or verification step is 
missing.
Do not pretend it was captured.
EVIDENCE PRINCIPLE
UNKNOWN is a valid state. An honest gap is safer than a fabricated bridge.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
05 | Cold Start: Recover Without Rebuilding the Universe
Cold-start recovery assumes the next operator may have little or no trustworthy conversational context. The system must 
therefore provide a short route from zero context to safe useful work.
Recovery stage Question answered Public behavior
Front door What system/project is this and where does
current authority live?
Open the continuity map rather than 
asking the human to retell the entire 
history.
Current-state check What is actually active now? Load current authority, current status, and
known open gaps.
Scope selection What part of the universe matters to this 
task?
Load only the relevant control and source 
material.
Evidence check Which claims are proven, reported, 
unverified, conflicting, or superseded?
Preserve labels before acting.
Tool/provider adjustment What changed because the environment 
changed?
Adapt interface/tool-specific behavior 
without rewriting core doctrine.
Resume or stop Is enough current state available to 
proceed safely?
Continue from evidence, or stop and 
retrieve/reconstruct missing authority.
COLD-START PRINCIPLE
A restart packet should reduce re-explanation without creating a second fictional memory system.
Minimal continuity is better than universal context dumping
The goal is not to preload every historical file into every new session. The goal is to identify the current task, retrieve the 
authority required for that task, and preserve enough evidence to distinguish present truth from background history.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
06 | Handoff: Transfer State, Not Just Narrative
A good handoff is not a long summary of what happened. It transfers the pieces another operator needs to make the next 
correct decision.
Handoff element What it preserves
Current objective What the work is trying to accomplish now.
Controlling authority Which document, decision, or verified source governs the task.
Current status What is complete, working, blocked, parked, superseded, or still 
unverified.
Evidence state What is proven versus reported, inferred, missing, or conflicting.
Open questions What still requires a decision, source, test, or human approval.
Artifacts and links Where the relevant current files and records can be found.
Stop conditions What the next operator must not assume or do without new 
authority.
Next action The smallest legitimate continuation point.
HANDOFF RULE
A handoff should let the next operator continue the work without pretending to inherit the previous
operator’s mind.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
07 | Versioning, Supersession, and Lifecycle
Continuity depends on knowing not only what exists, but what role each version currently plays. “Old” and “wrong” are 
not the same state.
Status Public meaning
CURRENT Controlling authority for active work.
WORKING In active refinement; usable but not fully trusted as final 
authority.
PROTOTYPE Testable implementation or concept that has not been promoted 
to current.
PARKED Intentionally preserved with no active build commitment.
HISTORICAL / PREDECESSOR Useful evidence or earlier architecture; not current.
SUPERSEDED Explicitly replaced by newer authority; retained for lineage.
RETIRED No longer actively used, but not formally destroyed or declared 
dead.
VERSION PRINCIPLE
Superseding is not deletion. History can remain valuable evidence even when it no longer controls 
current work.
Why explicit lifecycle state matters
Without lifecycle labels, search results and file listings become dangerous: a predecessor can look newer, a prototype can 
look polished, and an archived copy can be mistaken for the master. Continuity therefore treats file state as operational 
state.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
08 | Portability Across Models, Tools, and Providers
Portability is not the claim that every model is equivalent. It is the ability to preserve enough external state and control 
logic that a different capable operator can resume without rebuilding from conversational folklore.
Change event What must survive
New chat Current task, authority, evidence state, open gaps, and next 
action.
Model replacement External rules, current sources, version state, and verified 
decisions.
Provider/tool change Core doctrine and task state, while interface-specific behavior is 
adapted separately.
Human handoff Readable authority, current status, source paths, unresolved 
decisions, and stop conditions.
Partial context loss A cold-start route back to current sources and evidence.
Outage or unavailable memory Durable files and ledgers that do not depend on the unavailable 
system.
PORTABILITY LIMIT
External documents can preserve state and control logic. They cannot manufacture missing model 
capability or guarantee identical behavior across systems.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
09 | Archive Safety: A Summary Is Not Permission to Delete
Continuity systems create a new risk: once a useful summary or Atlas exists, the original evidence can look redundant. 
The source architecture rejects that shortcut.
Risk Why it matters Control
Summary replacement A summary can omit uncertainty, dates, 
exact wording, or context needed later.
Treat summary as navigation, not source 
destruction permission.
Duplicate cleanup Two similar files may represent different 
states, evidence, or branches.
Review lineage and authority before 
deletion or merge.
Mass migration Reorganization can break references and 
erase contextual clues.
Separate filing changes from authority 
changes and gate destructive moves.
Version collapse Keeping only the newest copy can erase 
why a decision changed.
Retain superseded evidence where 
recovery or provenance may matter.
Public derivative replacing master A sanitized release can lose operational 
detail by design.
Never promote a public derivative into the 
private source of truth by accident.
ARCHIVE PRINCIPLE
Capture is not deletion permission. A map of the archive is not the archive.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
10 | QA, Human Gates, and Recovery
Continuity is not complete when the next operator can read the files. It is complete when the operator can distinguish 
what is safe to continue from what still requires proof or permission.
Gate Stop condition
Authority gate The controlling source or current state cannot be established.
Evidence gate A consequential claim is unsupported, conflicting, or only 
inferred.
Scope gate The requested action exceeds the approved task or handoff scope.
Public-release gate Private or sensitive operating material would leak into a public 
artifact.
External-action gate The next step would contact, submit, purchase, publish, alter live 
state, or otherwise create a real-world consequence without 
authority.
Deletion/destructive gate A move, overwrite, delete, or irreversible migration would 
destroy source state or lineage.
Automation gate Software is technically able to act but the delegation envelope has
not been explicitly established.
RECOVERY PRINCIPLE
When state is unclear, retrieve or reconstruct authority before continuing. Do not convert 
confidence into continuity.
Common failure families
 Generic restart: treating mature work as if nothing exists.
 Memory promotion: turning remembered context into evidence.
 Version drift: selecting the plausible file instead of the controlling one.
 State flattening: collapsing proposed, drafted, executed, and verified into one “done” status.
 Private leakage: carrying sensitive source material into portable or public contexts unnecessarily.
 Recovery theatre: producing reassuring narrative instead of restoring verifiable state.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
11 | Transferability and Limits
The continuity architecture is most useful where work is long-running, stateful, document-heavy, AI-assisted, or likely to 
cross sessions, people, providers, or tools. The exact documents can differ while the design questions remain stable: what 
is current, what proves it, what was superseded, what is unknown, what must remain private, and what the next 
operator is actually authorized to do.
Environment Transferable question
AI-assisted project work Can a new session recover authority and state without relying on 
remembered conversation?
Small organizations Can one operator or successor identify current decisions and 
unfinished work quickly?
Research / evidence workflows Can claims be traced to source and evidence level after handoff?
Creative production Can canon, versions, approvals, and derivatives survive tool 
changes?
Operations / incident recovery Can the system resume after interruption without silently 
changing state?
Public/private systems Can a sanitized derivative prove the architecture without 
replacing or exposing the private master?
Limits
 A continuity packet cannot compensate for missing or destroyed source material.
 It cannot guarantee that every future model or human will interpret the controls correctly.
 It cannot make stale evidence current without re-verification.
 It cannot replace backups, access control, legal recordkeeping, or specialized security systems where those are 
required.
 It should not become an excuse to load unnecessary private context into every session.
 The system remains human-gated when authority, evidence, privacy, deletion, or external action is consequential.
CLOSING OBSERVATION
The continuity problem is solved less by remembering more and more by deciding what deserves to 
survive, where it lives, what proves it, and how the next operator can tell the difference.

PPLL SYSTEMS PAPER | THE WORK SURVIVES THE SESSION | PUBLIC EDITION V1.0
Paranoid People Live Longer | Public Proof-of-Work Edition | October 2026
12 | Sources and Validation Basis
Internal validation basis
This public paper is derived from maintained PPLL continuity, authority, versioning, evidence, retrieval, QA, and handoff 
records. Those internal materials establish the architecture described here, but they are not reproduced or linked 
publicly because they include private operating context and environment-specific controls.
The source base supports the following public claims: continuity is handled through explicit source hierarchy; evidence 
states remain distinct; current, working, parked, historical, and superseded states are separated; cold-start recovery 
routes back to current sources; model memory is treated as context rather than proof; destructive actions remain gated; 
and public derivatives do not replace private masters.
Public references for context
NIST - AI Risk Management Framework. https://www.nist.gov/itl/ai-risk-management-framework
NIST - Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile (NIST AI 600-
1). https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence
W3C - PROV Overview (provenance, derivation, versioning, and traceability context). https://www.w3.org/TR/provoverview/
These public references provide general context for risk management, provenance, and traceability. They are not 
presented as the source of the PPLL architecture, which was developed from the project’s own continuity and operating 
records.
THE WORK SURVIVES THE SESSION
Continuity is not remembering everything. It is preserving enough verified state that the work
can continue without inventing the missing parts.
Paranoid People Live Longer | Public Systems Paper | Version 1.0 | October 2026
