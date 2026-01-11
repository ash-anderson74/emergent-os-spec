# Pattern: Hypothesis Backlog (Outcome-Led Roadmapping)

### Also known as

* Outcome Backlog
* Problem Portfolio
* Learning Roadmap
* Intent Map

***

### Context

This pattern is applicable when an organisation is:

* operating in a complex or partially unknown domain
* building or replacing a product where _what_ is required is known, but _how_, _how long_, and _what trade-offs_ are not
* transitioning from a legacy system to a new architecture or platform
* attempting to uphold **outcomes over outputs** without losing delivery focus

Typical signals that this pattern is needed:

* feature roadmaps drive false certainty
* estimates harden into commitments prematurely
* learning happens late, during delivery or integration
* PMs plan deterministically because “the features are obvious”
* delivery pressure suppresses discovery in migration programmes

***

### Problem

Feature roadmaps make uncertainty invisible.

When work is expressed as a sequence of features:

* learning is treated as optional or disruptive
* time uncertainty is misrepresented as scheduling variance
* architectural complexity is underestimated
* risk is back-loaded into delivery and integration phases

This is especially dangerous during **replacement and migration work**, where:

* functional requirements are known
* system behaviour, performance, and integration complexity are not
* legacy constraints distort assumptions
* new architectures invalidate old delivery heuristics

The organisation believes it is planning what it knows.\
In reality, it is committing to what it _assumes_.

***

### Solution

Replace feature roadmaps with a **Hypothesis Backlog**:\
a prioritised list of _problems to solve_, _outcomes to achieve_, and _assumptions to test_.

Each item represents:

* an intended outcome (problem displacement, risk reduction, migration success)
* a hypothesis about how that outcome will be achieved
* explicit uncertainty
* learning required before high-integrity commitment is justified

Features become **candidate experiments or delivery vehicles**, not planning units.

The roadmap ceases to be a promise of scope.\
It becomes a **map of learning intent**.

***

### Structure

A Hypothesis Backlog entry typically contains:

**Outcome statement**

> “If we do X, we believe Y outcome will occur for Z users/system”

**Why it matters**

* business value
* strategic intent
* migration dependency or risk

**Key assumptions**

* technical feasibility
* delivery complexity
* integration or data risk
* performance or scalability expectations

**Learning required**

* what must be true for this outcome to be viable
* what would invalidate the hypothesis

**Candidate approaches**

* possible feature slices
* architectural experiments
* spikes or probes\
  &#xNAN;_(explicitly non-binding)_

**Commitment boundary**

* what can be decided now
* what must wait for evidence

***

### Example (Migration Context)

#### Feature roadmap framing (anti-pattern)

> Q2: Build payment processing\
> Q3: Integrate with accounting platform\
> Q4: Decommission legacy billing system

This assumes:

* delivery duration is knowable
* integration complexity is bounded
* legacy behaviour is fully understood

***

#### Hypothesis backlog framing (pattern)

**Outcome**

> Customers can complete payments in the new system without increased failure rate or reconciliation cost.

**Hypotheses**

* The new payments architecture can handle peak load without legacy retry logic
* Accounting integrations can be simplified without downstream breakage

**Learning required**

* realistic failure modes under load
* hidden legacy coupling
* real customer retry behaviour

**Candidate actions**

* parallel run of payment flows
* limited cohort migration
* targeted performance probes

**Commitment**

* No full migration until failure characteristics are understood

Same destination.\
Radically different risk posture.

***

### Consequences

#### Benefits

* learning becomes first-class work
* estimation pressure reduces naturally
* PMs retain planning authority without pretending certainty
* delivery focus improves by removing false precision
* architectural risk is surfaced early
* flow improves by reducing late surprises

#### Trade-offs

* executives lose comforting delivery narratives
* planning artefacts feel “less concrete”
* requires disciplined sensemaking
* requires tolerance for provisional answers

This pattern replaces narrative certainty with _earned confidence_.

***

### Alignment with EOM Principles

This pattern directly upholds:

* **Outcomes Over Outputs**
* **Hypothesis Over Assumption**
* **Learning Over Certainty**
* **Flow as a System Signal**
* **Incremental and Reversible Commitment**

It prevents EOM from collapsing into outcome-labelled feature planning.

***

### Common Misuse

* Writing outcomes but still committing to full feature scope
* Treating hypothesis backlogs as discovery-only artefacts
* Forcing time estimates where evidence does not yet exist
* Rewarding teams for delivery instead of learning
* Running discovery _alongside_ immutable delivery plans

These reintroduce determinism under different language.

***

### When Not to Use This Pattern

* in low-uncertainty, repeatable delivery domains
* for regulatory or contractual work requiring fixed scope
* where solution complexity is genuinely minimal

EOM does not prohibit feature roadmaps.\
This pattern applies where **uncertainty is structural, not accidental**.

***

### Related Patterns and Essays

* _Why Feature Roadmaps Feel Safer Than They Are_
* _Seeking the Right Thing: Outcomes as Constraints in an Emergent Operating Model_
* _From Legacy Control to Learning Systems_
* _Flow First_

***

### In Summary

A Hypothesis Backlog replaces the illusion of certainty with a discipline of learning.

It does not weaken planning.\
It strengthens it by aligning commitments with evidence.

When problems, not features, define progress:

> learning accelerates\
> risk reduces earlier\
> flow improves naturally

This is not softer planning.

It is **more honest planning** — designed for complexity.
