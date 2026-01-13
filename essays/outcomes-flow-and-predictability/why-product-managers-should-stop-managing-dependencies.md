---
description: (and start provoking them)
---

# Why Product Managers Should Stop “Managing Dependencies”

Product managers are often expected to answer impossible questions early:

* _What are the dependencies?_
* _How risky is this plan?_
* _Can we commit with confidence?_

These questions are reasonable — but the way organisations expect them to be answered is not.

In complex product environments, dependencies do not behave like items on a checklist. They behave like **relationships**, **queues**, **decisions**, and **delays** — none of which can be fully understood without interaction.

***

### Why Dependency Identification Fails PMs

The traditional approach assumes that:

* dependencies are stable
* risk can be enumerated
* effort can be inferred
* confidence precedes action

This puts PMs in a bind.

If they surface uncertainty honestly, they appear unprepared.\
If they present a polished plan, they absorb risk personally.

Dependency lists become a coping mechanism.

They create the appearance of due diligence while silently transferring uncertainty into the future.

***

### What PMs Actually Control

PMs do not control most dependencies.

They _do_ control:

* where attention is placed
* what gets tested first
* how uncertainty is framed
* whether learning is legitimised
* when the organisation commits

The mistake is treating dependencies as coordination problems rather than **learning problems**.

***

### A Better Question to Ask Early

Instead of:

> _“What are all the dependencies?”_

Ask:

> **“Which assumption, if wrong, would most damage our ability to proceed?”**

That question reframes planning from reassurance to discovery.

***

### Learning Before Commitment Is the PM Skill

In EOM terms, PMs create value early by:

* articulating assumptions explicitly
* identifying where confidence is borrowed
* designing cheap experiments to reduce uncertainty
* sequencing work to collapse risk first
* resisting false certainty

This is not indecision.\
It is disciplined risk management.

***

### Why “Provoking” a Dependency Is a Product Responsibility

When PMs hear _“provoke dependencies”_, it can sound reckless — as if the suggestion is to create instability or force conflict between teams.

That is not what is meant.

Provoking a dependency does **not** mean:

* interrupting other teams
* ignoring coordination
* starting work prematurely
* creating artificial blockers

It means doing something more fundamental:

> **Deliberately forcing a dependency to reveal what it does not yet know about itself.**

This is not chaos.\
It is disciplined exposure.

***

### The Hidden Problem with “Managing” Dependencies

When dependencies are “managed”, they are typically:

* catalogued
* sequenced
* owned by someone
* deferred to the right point in the plan

This creates the appearance of safety.

But from an EOM perspective, it does something dangerous:

> **It converts uncertainty into scheduling logic.**

The dependency still exists.\
The risk still exists.\
But discovery is postponed until delivery is already underway.

PMs feel productive because the dependency is _accounted for_.\
The system becomes fragile because it is not _understood_.

***

### What Dependencies Actually Represent

A dependency is not a thing to be waited on.

It is a signal that:

* assumptions cross team boundaries
* knowledge is incomplete
* feedback loops are too long
* ownership is fragmented
* risk is being displaced rather than reduced

From this perspective, a dependency is not a coordination problem.\
It is a **learning problem**.

And learning problems are squarely within the PM’s domain.

***

### What “Provoking” a Dependency Really Means

To provoke a dependency is to **interact with it early, cheaply, and deliberately** in order to answer questions like:

* What assumptions does this dependency rely on?
* What would break if those assumptions are wrong?
* Where would learning surface fastest?
* How reversible are we right now?

Examples of provocation include:

* testing an integration path with a minimal spike
* migrating a single workflow before committing to a full cutover
* validating data contracts with real payloads
* exercising edge cases long before feature completeness
* exposing cross-team coupling through partial use, not negotiation

What matters is not the technique, but the intent:

> **Expose reality before the plan depends on it.**

***

### Why This Is a PM Job (Not an Engineering Detail)

Engineers can build experiments.\
Architects can anticipate failure modes.\
Teams can coordinate execution.

But **PMs are uniquely positioned to decide where uncertainty must collapse first**.

This is because PMs operate at the intersection of:

* customer impact
* strategic intent
* investment decision-making
* narrative commitment

When PMs sequence work to “manage” dependencies, they often do so to protect:

* roadmaps
* stakeholder confidence
* quarterly commitments
* perceived momentum

When PMs provoke dependencies, they deliberately risk _local discomfort_ to prevent _systemic failure_.

That trade-off is a product decision, not a delivery one.

***

### Why Provocation Feels Unsafe — and Why That Matters

Provoking a dependency usually produces:

* bad news earlier
* awkward conversations sooner
* partial invalidation of plans
* visible uncertainty

In many organisations, this is personally risky.

Which is exactly why dependency provocation is rare — and why dependency management dominates instead.

EOM does not assume PMs lack insight.

It assumes the system makes **deferral safer than exposure**.

This essay exists to name that reality — not to judge it.

***

### Reframing the PM Role Under EOM

Under EOM, PMs create value early not by sequencing certainty, but by collapsing uncertainty.

They do this by:

* choosing exposure over coordination
* learning before committing narrative
* turning dependencies into discovery mechanisms
* making risk visible while it is still cheap

This does not eliminate planning.

It prevents planning from standing in for learning.

***

### A Final Reframe

A useful shift for PMs is to stop asking:

> “How do we plan around this dependency?”

And start asking:

> **“What would we need to learn for this dependency to stop being scary?”**

That question changes the work.

And when the work changes early enough,\
the plan often becomes simpler — without anyone having to manage it.

***

### A Worked Example: Migration Without Deterministic Sequencing

**Context**

An organisation is building a new product to replace a legacy system.

The strategic intent is displacement, not coexistence.\
Much of the required functionality is known:

* payments must work
* customer data must migrate
* downstream integrations must remain stable
* regulatory obligations must still be met

On the surface, this appears predictable.

As a result, the initial planning approach looks familiar:\
features are identified, sized, sequenced, and assigned to teams, with dependencies mapped between them.

From an EOM perspective, this is where risk quietly accumulates.

***

#### The “Managed Dependency” Approach

In a traditional plan, dependencies are handled by coordination:

* Team A builds the new payment service
* Team B migrates customer accounts
* Team C updates reporting integrations
* Each dependency is scheduled in the right order
* Risks are recorded and reviewed
* Confidence is derived from the completeness of the plan

Nothing in this is obviously wrong.

The problem is that **most of the risk has been translated into time**, not eliminated.

Key questions remain unanswered:

* Will the new payment flow behave correctly under real load?
* Are data assumptions between systems actually compatible?
* Do regulatory edge cases behave the same in the new architecture?
* How reversible is the migration if something subtle breaks?

These uncertainties are acknowledged — but deferred.

***

#### The Provoked Dependency Approach

Under EOM, the PM reframes the problem.

Instead of asking:

> “How do we sequence all this work safely?”

They ask:

> **“Which dependency contains the most uncertainty — and how can we expose it cheaply?”**

In this case, the riskiest dependency is not _building_ payments.

It is **running real customer transactions across both systems safely**.

So instead of sequencing features, the PM designs an early exposure:

* one payment path
* one customer cohort
* one integration
* strict blast-radius limits
* explicit reversal conditions

This forces several dependencies to surface immediately:

* architectural coupling
* data compatibility assumptions
* operational behaviour under real use
* organisational response to partial migration

Importantly, none of this requires “finishing” the system.

Learning arrives before commitment.

***

#### What Changes Systemically

This provocation produces uncomfortable outcomes early:

* estimates become obviously unreliable
* sequencing assumptions unravel
* some planned work is no longer relevant
* new constraints become visible
* confidence becomes conditional rather than performative

From the outside, this can look like chaos.

From the system’s perspective, it is risk collapsing while it is still cheap.

***

#### The PM’s Role in This Shift

The PM did not:

* abandon planning
* let teams act independently
* ignore dependencies

They did something more difficult:

* resisted the false safety of complete roadmaps
* chose exposure over reassurance
* treated dependencies as learning surfaces, not scheduling artefacts
* protected the organisation from narrative debt

The result is not less control.

It is **control grounded in evidence rather than assumption**.

***

#### Why This Matters

Had the dependencies been “managed”, the organisation would have learned the same things — later, under higher pressure, with fewer options.

By provoking them, the PM changed **when** the organisation learned — and therefore **how much freedom it retained**.

This is the difference EOM cares about.

***

### Which Teams Do What and When?

The question:

> _“Which teams do what and when?”_

exists because traditional planning assumes two things:

1. Work can be decomposed cleanly into independent slices
2. Dependencies should be minimised by sequencing work over time

In **complex product systems**, both assumptions are often false **early on**.

EOM’s claim is not that teams shouldn’t coordinate — it’s that **sequencing uncertainty doesn’t remove it; it postpones it**.

***

### What EOM is _not_ suggesting

Let’s rule out misunderstandings first.

EOM is **not** suggesting:

* permanent team overlap
* everyone working on everything
* abandoning team boundaries
* dissolving accountability
* “just collaborate more”

That _would_ be chaos.

***

### What is actually being suggested

#### 1. Temporary convergence is sometimes the _cheapest_ way to learn

When a dependency is both:

* high-risk, **and**
* highly uncertain

…then trying to sequence it cleanly often _increases_ cost.

Why?

Because sequencing assumes knowledge that doesn’t yet exist.

In those cases, EOM prefers **deliberate, time-boxed convergence**:

* multiple teams focus on the _same thin slice_
* long enough to expose reality
* short enough to avoid structural drift

This is not a delivery model.\
It is a _**learning intervention**._

> _The objective of early convergence is not speed, but reversibility — learning cheaply enough that future sequencing decisions remain optional._

_but_

> **If convergence becomes the default rather than the exception, it is a signal that system-level constraints are forcing learning too late.**

***

#### 2. Teams still have roles — but not queue positions

In your example:

* Team A (payments)
* Team B (migration)
* Team C (integrations)

Under deterministic planning:

* Team A “goes first”
* Team B “waits”
* Team C “prepares”

Under an EOM learning-first move:

* Team A brings deep domain knowledge
* Team B brings data and customer transition concerns
* Team C brings operational and downstream risk awareness

They **co-own the learning**, not the output.

This doesn’t dissolve accountability — it **temporarily re-centres it around the risk**.

***

#### 3. After learning, teams _diverge again_

This is critical.

Once the risky dependency is exposed:

* assumptions harden into knowledge
* architecture boundaries clarify
* estimates improve
* sequencing becomes meaningful

At that point:

* teams split back into coherent ownership
* work becomes parallel again
* roadmaps become _earned_, not speculative

**Convergence is a phase, not a state.**

***

### Why this feels wrong (and why that matters)

Most organisations optimise for:

* utilization
* predictability
* clean swimlanes
* no “duplication of effort”

But in uncertainty:

* utilization hides risk
* predictability is performative
* clean swimlanes delay truth
* some “duplication” is actually shared sense-making

EOM is explicit about this trade-off:

> **You either pay for learning with overlap early, or with rework and failure later.**

Sequencing often chooses the second — quietly.

***

### A useful reframing for PMs

Instead of asking:

> _“Which team should do this first?”_

EOM encourages PMs to ask:

> **“Which teams must be present for this decision to be reversible later?”**

If the answer is “more than one”, early convergence is a signal — not a planning failure.

***

### In Closing

Dependencies do not become manageable when they are documented.

They become manageable when they are **experienced early, cheaply, and deliberately**.

In high-uncertainty work, the goal is not to assign tasks cleanly, but to **concentrate the right expertise around risk early**, then return teams to clear ownership once learning makes sequencing meaningful.

When PMs are allowed to shift from dependency management to dependency exposure:

* plans improve
* confidence becomes earned
* surprises shrink
* and delivery accelerates — not because people try harder, but because reality is faced sooner

That is not weaker planning.

It is **planning that respects complexity**.

***

### How To Diagnose This Pattern

* [Diagnostic: Dependency Sequencing as a Control Illusion](https://app.gitbook.com/s/wVqEs2cuXgPu222Kt8eP/diagnostics/diagnostic-dependency-sequencing-as-a-control-illusion)
