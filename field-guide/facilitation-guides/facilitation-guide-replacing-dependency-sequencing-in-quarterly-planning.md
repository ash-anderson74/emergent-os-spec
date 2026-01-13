# Facilitation Guide: Replacing Dependency Sequencing in Quarterly Planning

#### Purpose

To help teams plan without pretending dependencies are predictable.

#### Participants

* Product Managers
* Tech Leads / Architects
* Dependent teams where relevant
* A governance or portfolio representative

***

#### Step 1: Replace the Question

> “What do we deliver, in what order, by when?”

with:

> **“What must be learned before we can safely commit?”**

***

#### Step 2: Build a Risk & Learning Map (see section 5)

Capture:

* key assumptions
* untested dependencies
* integration unknowns
* confidence gaps

Do **not** assign dates yet.

***

#### Step 3: Order by Risk Collapse

Ask:

* Which assumption, if wrong, would invalidate the most work?
* Which dependency has never been exercised?
* Where is confidence borrowed from history that no longer applies?

Sequence **learning work**, not delivery work.

***

#### Step 4: Define Evidence Thresholds

For each learning item:

* What evidence would make this safe to proceed?
* What evidence would cause us to stop or change direction?

This creates **decision points**, not deadlines.

***

#### Step 5: Commit Incrementally

Only commit to:

* work that reduces uncertainty
* work that preserves reversibility

Everything else remains provisional.

***

#### Step 6: Review on Learning, Not Progress

Governance asks:

* What did we learn?
* What risks collapsed?
* What options opened or closed?
* What changed as a result?

***

## 5. What a Risk & Learning Map Actually Is

A **risk & learning map** is a planning artefact that replaces timelines with **assumptions and evidence**.

#### Structure

| Assumption / Risk                   | Why It Matters       | How We Learn          | Evidence Needed        | Decision Impact     |
| ----------------------------------- | -------------------- | --------------------- | ---------------------- | ------------------- |
| API X will support load             | Affects architecture | Spike + load test     | Sustained throughput   | Enables scale work  |
| Payment provider integration effort | Core feature         | Thin vertical slice   | Successful transaction | Unlocks migration   |
| Team B availability                 | Dependency risk      | Early joint prototype | Working interface      | Confirms sequencing |

#### Key Characteristics

* No dates
* No estimates
* No task ordering
* Clear learning intent
* Explicit confidence thresholds

#### How It Evolves

Early:

* many unknowns
* few commitments

Later:

* fewer unknowns
* stronger commitments
* safer sequencing

This is **how certainty is earned**, not declared.
