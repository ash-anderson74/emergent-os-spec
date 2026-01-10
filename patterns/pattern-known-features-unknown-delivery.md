# Pattern: Known Features, Unknown Delivery

### Context

An organisation is building a new product to replace or displace a legacy system.

The existing system is well understood. Core functionality, integrations, regulatory requirements, and workflows are known. This creates a strong sense of certainty.

Product managers and stakeholders therefore conclude:

* the required features are known
* the scope can be enumerated
* delivery can be planned deterministically
* timelines can be committed upfront

Despite this confidence, the work takes place in a **new context**:

* a new architecture
* new integration surfaces
* new teams and skills
* new operational constraints
* new user behaviours and migration paths

***

### Problem

Although the **features** are known, the **work is not**.

Teams cannot reliably predict:

* how long the work will take
* where complexity will surface
* which integrations will prove brittle
* what quality thresholds will emerge
* how much refactoring or rework will be required
* where unexpected coupling will appear

When delivery is treated as predictable:

* estimates harden into commitments
* uncertainty is hidden rather than explored
* pressure favours optimistic plans
* learning arrives too late to change decisions
* progress narratives replace evidence
* “slippage” is explained externally rather than structurally

The system behaves as if certainty exists — even when it does not.

***

### Forces at Play

* **Familiarity bias**: “We’ve built this before.”
* **Feature gravity**: Lists feel concrete; outcomes feel abstract.
* **Replacement anxiety**: Pressure to prove the new system is “on track”.
* **Architectural novelty**: Hidden complexity in new platforms.
* **Governance expectations**: Desire for timelines in the absence of learning.
* **Reward structures**: Progress measured by planned completion, not insight.

These forces make deterministic planning feel rational — even when it isn’t justified.

***

### Pattern

**Treat features as known requirements, but treat delivery as a hypothesis.**

Separate certainty about _what must exist_ from uncertainty about _how it will be built, integrated, and operated_.

Anchor goals above the feature layer, while allowing delivery to remain adaptive.

***

### How This Manifests in EOM

#### Outcome-Oriented Framing

Instead of OKRs that imply delivery certainty:

❌ **Anti-pattern OKR**

> **Objective:** Deliver replacement payments platform\
> **KR1:** Complete payments integration by Q3\
> **KR2:** Migrate all payment flows by Q4

This encodes:

* scope certainty
* schedule certainty
* outcome assumption

***

#### EOM-aligned OKRs (example)

**Objective**

Enable safe, reliable migration to the new payments platform with minimal service disruption

**Key Results**

* 90% of live transactions processed through the new platform without manual intervention
* Legacy payment system run-cost reduced by 50%
* Mean time to recover from payment incidents reduced by 30%
* Time-to-change for payment-related updates reduced from weeks to days

**Delivery Implication**\
The required features still exist — but success is judged on **system behaviour**, not checklist completion.

***

#### Delivery Framing

Features are planned as:

* necessary enablers
* time-boxed bets
* reversible investments
* staged commitments

Estimates are used to inform sequencing and risk awareness — **not to guarantee timelines**.

***

### Consequences

#### When Applied Well

* Teams surface architectural risk earlier
* Progress conversations shift from “are we on plan?” to “what did we learn?”
* Governance focuses on readiness and risk, not promises
* Delivery adapts without trust erosion
* Feature work remains grounded but not weaponised

***

#### When Ignored

* Timelines become emotional commitments
* Optimism bias compounds
* WIP grows to maintain the plan illusion
* Quality erodes under schedule pressure
* Migration pain is discovered late
* Confidence collapses suddenly rather than adjusting gradually

***

### Key Insight

> **Knowing&#x20;**_**what**_**&#x20;must exist does not mean knowing&#x20;**_**how long**_**&#x20;it will take to make it exist.**

Replacement work reduces _problem_ uncertainty, not _delivery_ uncertainty.

EOM exists to prevent organisations from collapsing those two ideas into one.

***

### Related Patterns

* Outcome Over Output
* High-Integrity Commitments
* Incremental and Reversible Commitment
* Flow as a Diagnostic, Not a Target
