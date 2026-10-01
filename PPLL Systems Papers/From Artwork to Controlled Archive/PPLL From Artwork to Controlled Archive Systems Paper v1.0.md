# From Artwork to Controlled Archive

**Paranoid People Live Longer | Public Systems Paper v1.0**

> GitHub text edition generated from the reviewed public document. The PDF and DOCX editions are preserved in the publication package.

---

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 1
PARANOID PEOPLE LIVE LONGER / PUBLIC SYSTEMS PAPER
FROM ARTWORK TO
CONTROLLED ARCHIVE
A systems paper on identity, provenance, rights status, derivative lineage, sale 
records, and controlled release
CORE PROPOSITION
A physical artwork should remain the parent identity across storage, digitization, reproduction, 
licensing, public release, and sale. The object may move or leave the collection; the lineage should not 
break.
Public Proof-of-Work Edition | Version 1.0 | October 2026
Document type: Systems Paper | Public architecture, not an operating manual
PUBLIC DISCLOSURE BOUNDARY
This edition explains the control architecture without publishing private creator history, ownership evidence, storage locations, 
buyer records, pricing, exact identifier grammar, QR routing, internal ledgers, source files, contracts, or implementation 
prompts. It does not establish the legal rights status of any specific artwork.

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 2
1. The Problem: Art Becomes Uncontrolled Faster Than It Becomes 
Valuable
A physical art collection can look organized while its operational truth is already fragmenting. The object may have one title on 
paper, another file name in a scan folder, a cropped version in a product directory, a public caption with a guessed date, and a 
sale record that no longer points back to the master image. Each item can look individually reasonable while the system as a 
whole becomes unreliable.
The architecture documented here was developed to prevent that drift. It treats every physical work as a parent record with 
durable identity and makes later objects - scans, working masters, product exports, certificates, listings, derivatives, licenses, 
and sale records - subordinate records that point back to the parent.
Failure pressure What goes wrong without control
Identity drift One work acquires multiple names or files that can no longer be 
confidently reconciled.
Provenance drift Known facts, estimates, memories, and guesses collapse into one 
unmarked story.
Rights drift Physical possession, reproduction permission, commercial rights, 
and public-use status are treated as if they were the same thing.
Derivative drift Products and transformed versions become orphaned from the 
source artwork that gave rise to them.
Sale drift The physical object leaves, and the collection loses the record 
needed to preserve history, rights, and image lineage.
Public/private collapse Internal location, buyer, pricing, rights, or source-file data leaks into 
public catalogues or outgoing files.
DESIGN RESPONSE
Do not organize the archive around folders or products. Organize it around persistent object identity, 
then make every other record prove its relationship to that identity.
2. System Objective
The system objective is not merely to catalogue art. It is to preserve enough operational truth that a future human, model, tool, 
or platform can answer five questions without reconstructing the entire history from memory:
 What physical object is this?
 What is actually known about its creator, title, date, condition, and provenance?
 What digital captures and working files belong to it?
 What rights, permissions, restrictions, or uncertainties apply?
 What has happened downstream - reproduction, transformation, release, licensing, certificate, sale, or transfer?

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 3
3. Public Architecture: The Artwork Is the Parent
Layer Public role Authority rule
Physical artwork The real-world object or retained physical 
artifact.
Receives a persistent identity before 
downstream use.
Parent archive record The durable control record for identity, 
known facts, condition, status, and lineage.
Remains the parent even if the object is sold 
or relocated.
Digital captures Preservation scans, photographs, and 
controlled working masters.
Must remain linked to the parent record and 
must not overwrite the historical identity.
Rights / permission record Documents what is known, restricted, 
permitted, unresolved, or subject to review.
Physical possession does not automatically 
answer reproduction or commercial-use 
questions.
Derivative / use map Tracks prints, products, crops, 
transformations, publications, and licenses.
Children never replace the parent.
Certificate / sale record Documents a particular transfer or proof 
event.
Secondary proof linked to the parent; not a 
new source of truth.
Public catalogue Curated public facts and approved 
images/status.
Public subset only; never replaces the 
private master.
PARENT-CHILD RULE
The original stays the parent. Every meaningful derivative remains a child with a traceable path back to 
the source identity.
3.1 Why folders are not the database
Folders are useful storage. They are poor authority. A file can be moved, renamed, duplicated, exported, compressed, or 
copied to another platform without carrying enough context to explain what it is. The master record must therefore hold the 
durable relationship between object identity, file identity, use history, and status.
4. Persistent Identity Without Rewriting History
The control system assigns a stable archive identity to each retained physical object. That control identity is deliberately 
separate from artist-assigned titles, numbers, signatures, dates, series marks, or other historical information. A database should
not clean the artwork by rewriting it.
Identity principle Public rule
Persistent control ID The archive identifier remains stable when titles, locations, products, 
platforms, or status change.
Historical marks stay historical Known artist titles, numbers, inscriptions, and signatures remain part 
of the record and are not overwritten by archive convenience.
Unknown stays unknown A missing title, date, creator fact, intent, or provenance detail is 
recorded as unknown or approximate rather than invented.
Group membership is additive Collections, series, or batches may have group identities, but 
individual object identity remains intact.
Status is not identity Finished, unfinished, private, sold, restricted, or public are states of 
the record, not replacements for the record.

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 4
5. Layered Records: Private Truth and Public Presentation Have 
Different Jobs
A public catalogue cannot safely carry everything the archive needs to know. The system therefore separates complete 
operational truth from approved public presentation.
Record layer What it needs to know Public?
Physical inventory What exists, basic classification, current realworld location, handling state.
No - operational.
Private master catalogue Identity, provenance, condition, source files, 
rights status, internal decisions, derivative 
links, sale/transfer history.
No - authoritative internal record.
Rights register Permission status, restrictions, uncertainty, 
review state, documentary basis.
No - sensitive and case-specific.
Derivative/use map Where the work has been reproduced, 
transformed, published, productized, or 
licensed.
Mostly internal; selected uses may be public.
Certificate / transfer register Issued proof records, replacement/void 
history, sale or transfer linkage.
Selective.
Public catalogue Approved facts, public-safe images, selected
provenance, availability/sold status, public 
description.
Yes.
BOUNDARY RULE
The private master is allowed to remember what the public catalogue is required to forget.
6. Rights Are a Separate Control Surface
The internal system treats physical ownership, possession, authorship, reproduction permission, licensing authority, and 
commercial-use status as distinct questions. The public architecture preserves that separation without publishing or 
adjudicating the answer for any individual work.
 No downstream commercial use is treated as safe merely because the file exists or the physical object is in hand.
 Rights uncertainty is a valid state. Unresolved status should block or narrow use rather than be converted into a confident 
guess.
 Permissions can be scoped. A use allowed for one purpose does not automatically authorize every other purpose.
 High-value, disputed, collaborative, or ambiguous cases can be routed for professional review instead of forcing an internal 
conclusion.
 This paper describes a control mechanism, not legal advice and not a public declaration of ownership for specific works.
RIGHTS GATE
If the system cannot explain the rights position cleanly enough for the proposed use, the proposed use 
should stop or narrow until the record improves.

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 5
7. Digital Preservation and File Lineage
Digitization creates a second archive around the physical one. Without control, a high-quality capture, a cleaned master, a web 
copy, and a product export can become indistinguishable. The architecture separates those roles.
Digital level Purpose Metadata posture
Preservation capture Highest-quality scan or photograph that 
preserves evidence of the object.
Retain useful technical/archive metadata; 
protect from casual editing or upload.
Working reproduction master Cleaned or corrected source used to create 
controlled derivatives.
Keep parent identity and edit/version lineage.
Public derivative Web, catalogue, marketplace, press, or other
outgoing copy.
Remove unnecessary 
personal/device/location metadata before 
release.
Product / format export Output built for a specific production lane. Must remain traceable to the parent and 
working master.
The architecture therefore rejects two opposite mistakes: stripping every useful trace from the preservation master, and leaking 
every private trace into the public copy.
8. Derivative Lineage: Products Are Children, Not New Originals
A source artwork may later become a print, poster, sticker, publication image, crop, digital product, transformed image, or 
licensed asset. The operational requirement is not that every output look the same. It is that every significant output can still 
answer where it came from.
Lineage question Required public principle
What is the source? Every derivative points back to a parent artwork identity.
What changed? The record distinguishes scan, crop, cleanup, colourway, product 
export, transformation, or other stage.
Who owns the downstream workflow? Product systems may control manufacture or commerce, but source 
lineage remains anchored in the art record.
Can a transformation replace the original? No. A transformed output is a descendant, not evidence that the 
source ceased to exist.
Can weak or retired derivatives disappear? They can be retired or archived without deleting the parent or erasing
use history.

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 6
9. Physical Sale Without Archival Amnesia
Selling a one-of-one physical object is a transfer event, not the end of the archive record. The public system keeps identity, 
images, condition evidence, certificate linkage, rights posture, and transfer history connected after the object leaves the seller's 
possession.
Before transfer At transfer After transfer
Identity confirmed Payment / handoff recorded Object marked sold or transferred
Condition documented Certificate or receipt linked Availability conflicts removed
Front/back/detail images captured as 
appropriate
Rights language attached as appropriate Certificate copy retained
Rights and sale eligibility checked Shipping or pickup state recorded Parent record and retained image lineage 
preserved
RECORD PERSISTENCE
The art can leave the room. The record stays in the system.
9.1 Certificate discipline
A certificate is treated as a proof object attached to the parent identity and a specific issuance or sale event. It does not become
a second independent authority. Replacement, correction, or void history should therefore remain traceable to the same parent 
record.
10. Controlled Release: Do Not Dump the Archive
Public release is treated as a controlled movement from private system to public surface. A large archive can be damaged 
operationally by releasing too much, too quickly, without records, boundaries, or post-release updates.
 Each public release has a reason and a defined boundary: what belongs, what does not, and why.
 Rights and file status are checked before release.
 Only the product formats or public assets needed for the release are created.
 Public-safe images and descriptions are prepared separately from internal records.
 Links, dates, outcomes, and follow-up state are logged after release.
 The archive remains capable of feeding future releases instead of being exhausted for short-term attention.
RELEASE DOCTRINE
A release is not merely posting a picture. It is a controlled state change with preparation, evidence, 
boundaries, and a record.

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 7
11. Failure Modes the Architecture Is Designed to Expose
Failure family Signature Control response
Mystery object The physical piece exists but identity or 
location is uncertain.
Park downstream use until identity and 
minimum record are restored.
Mystery file A scan/export cannot be confidently linked to
a source.
Do not trust it for licensing or production until
lineage is restored.
Invented provenance A title, date, intent, story, or creator fact is 
added because it sounds plausible.
Preserve unknown/approximate states 
explicitly.
Rights-by-possession Physical control is treated as automatic 
authority for every reproduction or 
commercial use.
Use a separate rights gate and documentary 
status.
Orphan derivative A product or transformation no longer points 
back to the source.
Require parent linkage in naming, inventory, 
or derivative map.
Public metadata leak Outgoing files expose unnecessary 
location/device/private information.
Publish a public derivative, not the 
preservation master.
Sale erasure A sold original disappears from the collection
record.
Preserve the parent record and transfer 
history after sale.
Certificate drift A certificate becomes a competing source of 
truth.
Make certificate status subordinate to the 
parent record.
Archive dumping Large volumes are released with weak 
context or no release ledger.
Use bounded releases and post-release 
updates.
12. Human Authority and Irreversible Actions
The architecture is deliberately human-gated around actions that can alter rights, public exposure, ownership state, sale state, 
provenance claims, or preservation status. Automation can help inventory, compare, route, draft, rename safely, or generate 
candidate records. It should not silently convert uncertainty into permission or irreversible action.
AI / software may assist Human approval remains appropriate
Suggest metadata fields and flag missing records Final creator/provenance assertions
Match derivatives to likely parents for review Rights or licensing decisions
Generate public-description drafts from verified fields Sale / transfer of originals
Detect file naming or catalogue inconsistencies Destructive file actions or master replacement
Prepare release checklists and record updates Public release of sensitive or uncertain material

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 8
13. What the Public Paper Intentionally Withholds
The public paper is meant to make the architecture inspectable without publishing the operating package or private archive.
Withheld material Why it remains private
Exact permanent ID grammar and registry schema Implementation detail; unnecessary to evaluate the architecture.
Real storage locations and handling routes Operational and security-sensitive.
Private creator history and source evidence Personal/provenance material that is not required for public proof.
Rights evidence, permission records, contracts, and counsel material Case-specific legal and commercial records.
Buyer/contact/payment data and private sale history Personal and financial information.
Pricing, reserve logic, release calendars, and negotiation records Commercial operating information.
Exact QR routing, private destinations, and verification internals Implementation/security detail.
Full internal prompts, checklists, thresholds, and specialist Bibles Reusable operating machinery rather than public explanation.
Source image masters and unpublished artwork files Creative assets and preservation material.
14. Limits and Non-Claims
 This paper is not legal advice and does not determine copyright, ownership, permission, provenance, authenticity, or 
licensing status for any specific artwork.
 It is not a conservation treatment manual. Fragile, damaged, mould-affected, unusually valuable, or technically complex 
works may require a professional conservator.
 A good record cannot correct a false claim merely by storing it neatly. Evidence quality still matters.
 A persistent ID improves traceability but does not itself prove authorship, authenticity, value, or rights.
 Public descriptions should remain no stronger than the documented record permits.
15. Transferability Beyond One Art Archive
The architecture generalizes to other environments where a physical creative object produces digital files, public 
representations, commercial derivatives, and transfer events over time.
Environment Transferable question
Independent artist studio Can every original and derivative be traced without relying on 
memory or folder names?
Estate or legacy collection Can authorship, ownership, rights, and physical custody remain 
distinct?
Gallery / dealer inventory Can sale, consignment, condition, certificate, and availability state be
reconstructed later?
Design archive Can fragments, crops, editions, and product outputs remain 
connected to source work?
Museum / community collection Can private collection-management facts remain separate from 
public catalogue facts?
AI-assisted creative workflow Can generated or transformed outputs remain traceable to 
authorized source assets and human decisions?

PUBLIC SYSTEMS PAPER | ART ARCHIVE CONTROL
Paranoid People Live Longer | From Artwork to Controlled Archive | 9
16. Development Basis and Sources
The architecture in this public paper was derived from PPLL internal operating records and then narrowed to a publication-safe 
systems explanation. The internal documents are listed here by title for provenance but are not published or linked from this 
paper.
 Internal art authority and decision record
 Internal collection strategy and future-use plan
 Internal archive and inventory control manual
 Internal inventory and licensing control manual
 Internal rights and permission control manual
 Internal physical-original sale control manual
 Internal controlled-release manual
 Internal file naming and lineage control manual
Public reference links
The following public sources provide external context for the copyright and preventive-conservation principles referenced in this 
paper. They do not establish the ownership, rights, attribution, value, or provenance of any specific work in the internal archive.
 Canadian Intellectual Property Office - What you should know about copyright
 Canadian Conservation Institute - Basic care: Works of art on paper
 Canadian Conservation Institute - Storing Works on Paper (CCI Note 11/2)
 Canadian Conservation Institute - Caring for paper objects
CLOSING PRINCIPLE
The archive is not the room where art waits. The archive is the control system that lets the object, its 
history, its rights status, its digital descendants, and its public life remain connected even when 
everything else changes.
THE OBJECT MAY MOVE. THE RECORD MUST HOLD.
