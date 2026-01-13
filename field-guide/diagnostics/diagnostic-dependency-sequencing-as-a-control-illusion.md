# Diagnostic: Dependency Sequencing as a Control Illusion

### Diagnostic Intent

This diagnostic helps identify when planning activity has shifted from **reducing uncertainty through learning** to **deferring uncertainty through coordination**.

It focuses on a common failure mode in complex product environments:\
the use of deterministic sequencing to manage dependencies that are not yet understood.

***

### Core Diagnostic Question

> **Is work being sequenced to manage dependencies, or to collapse uncertainty?**

In EOM terms, sequencing is only valuable when it **reduces risk earlier**.\
When sequencing exists primarily to protect plans, it becomes a liability.

***

### Observable Indicators

This diagnostic is likely relevant when one or more of the following are visible:

#### Planning Artefacts

* Gantt-like quarterly plans with:
  * sequenced features
  * swimlanes per team
  * dependency arrows between work items
* Dependencies represented as ordering constraints rather than unknowns
* Estimates used to justify sequencing rather than guide learning

#### Planning Language

* “We can’t start until Team X finishes”
* “Blocked by dependency Y”
* “Integration will be handled later”
* “Once the foundation is complete, delivery will accelerate”
* “The risk is manageable because it’s planned”

#### Behavioural Signals

* Learning activities deferred until after implementation begins
* Integration, migration, or data complexity discovered late
* Repeated replanning without reduction in uncertainty
* Teams waiting rather than exposing constraints
* Confidence expressed early, surprise expressed late

***

### What This Diagnostic Is _Not_

This pattern is **not** caused by:

* lack of diligence
* poor product management
* insufficient coordination effort
* team incompetence

It is typically the result of **rational behaviour within a system that rewards defensibility over learning**.

***

### Underlying System Incentives

Dependency-first sequencing usually emerges when:

* plans are used as risk-management artefacts
* predictability is treated as a proxy for competence
* governance expects delivery confidence before learning evidence exists
* early admission of uncertainty carries social or political cost
* dependencies are “managed” rather than challenged

Within such a system, **sequencing work to look controlled is safer than exposing what is unknown**.

***

### System-Level Consequences

When dependency sequencing dominates:

* learning is delayed until cost of change is high
* risk accumulates silently across teams
* coordination effort increases without reducing uncertainty
* flow slows due to late constraint discovery
* delivery becomes brittle and reactive
* “blocked” becomes a stable state rather than a diagnostic signal

Time-to-delivery may appear optimized early.\
Time-to-learning almost always degrades.

***

### EOM Invariants Commonly Violated

This diagnostic often indicates tension with one or more EOM invariants:

* **Learning must precede high-integrity commitment**\
  Sequencing assumes knowledge that has not yet been earned.
* **Commitment should be incremental and reversible**\
  Ordered plans create narrative and political lock-in.
* **Flow is a signal, not a target**\
  Sequencing optimizes for coordination smoothness rather than insight.
* **Governance acts as sensing, not control**\
  Sequenced plans shift governance toward enforcement of order.

***

### Reframing the Problem

The issue is not _dependencies themselves_.

Dependencies are unavoidable in complex systems.

The issue is **treating dependencies as scheduling problems rather than learning problems**.

From an EOM perspective:

* Known dependencies can be sequenced
* Unknown dependencies must be exposed

A plan that preserves uncertainty is riskier than one that reveals it.

***

### Diagnostic Reframe Question

Replace:

> “How do we sequence work to accommodate dependencies?”

With:

> **“What would we need to do first to make this dependency less dangerous?”**

This question shifts focus from coordination to learning.

***

### Signals of Health (What You’d See Instead)

In systems where dependency exposure is preferred over sequencing:

* early spikes on integration and migration risk
* short, deliberate experiments to surface unknowns
* work ordered by uncertainty reduction, not team availability
* dependencies treated as hypotheses to test
* governance discussions focused on learning gained, not plan adherence
* “blocked” viewed as urgent information, not normal state

***

### Summary

This diagnostic identifies when deterministic sequencing has quietly replaced learning as the primary risk strategy.

The behaviour it surfaces is rational.\
The outcomes it produces are predictable.

EOM does not eliminate dependencies.\
It insists they be **revealed early, cheaply, and deliberately**—before they are turned into fixed plans.

When sequencing dominates learning, the system is optimising for the appearance of control.

This diagnostic exists to make that visible.

For guidance on using this diagnostic safely in context, see:

* [Facilitation Guide: Replacing Dependency Sequencing in Quarterly Planning](../facilitation-guides/facilitation-guide-replacing-dependency-sequencing-in-quarterly-planning.md)
