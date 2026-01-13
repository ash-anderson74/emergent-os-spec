# Pattern: From Dependency Mapping to Dependency Exposure

### Context

In complex product environments, teams are routinely asked to identify dependencies and risks upfront in order to support planning, sequencing, and confidence-building.

This typically results in:

* dependency lists
* risk registers
* integration plans
* escalation paths

These artefacts are intended to reduce uncertainty.\
In practice, they often **create the illusion of control without reducing risk**.

***

### Problem

Dependencies in complex systems are rarely:

* static
* fully knowable in advance
* independent of context
* equally consequential

Lists of dependencies describe _assumptions_ about future interactions.\
They do not reveal whether those assumptions are valid.

As a result:

* the most dangerous dependencies remain untested
* confidence is based on completeness of documentation, not evidence
* real risk emerges late, when it is most expensive to respond
* teams are rewarded for planning sophistication, not learning speed

***

### Forces

* Organisations want early confidence and coordination
* Teams are penalised for uncertainty but rewarded for apparent control
* Upfront dependency identification feels responsible and professional
* Exercising dependencies early is perceived as disruptive or premature
* Governance forums prefer artifacts to ambiguity

These forces make **mapping** safer than **exposing**, even when exposure would be more useful.

***

### Solution

Shift the objective from **documenting dependencies** to **actively exposing them**.

Instead of asking:

> “What are all the dependencies?”

Ask:

> **“Which dependencies are most likely to invalidate our plan — and how can we provoke them cheaply?”**

Dependency exposure means deliberately triggering interactions early in order to learn:

* whether the dependency responds as expected
* how long it actually takes
* where friction or delay exists
* who truly owns the decision
* what happens when assumptions are wrong

***

### How Dependency Exposure Works

Rather than producing a single artefact, teams:

1. **Identify the riskiest dependencies**, not all dependencies\
   Focus on those with the highest potential to block learning, flow, or delivery.
2. **Form explicit assumptions**\
   Example:\
   &#xNAN;_“We assume team X can support integration within two weeks.”_
3. **Design a low-cost test**
   * make a real request
   * attempt a trivial integration
   * submit a compliance query
   * deploy a minimal slice end-to-end
4. **Observe the response**\
   Time taken, friction encountered, ambiguity revealed, decisions delayed.
5. **Update plans based on evidence**\
   Sequencing, scope, commitment, and funding are adjusted _before_ large investment.

Dependency exposure converts hidden risk into visible signals.

***

### Resulting Context

When dependency exposure replaces dependency mapping:

* uncertainty is surfaced earlier
* commitments become more credible
* plans adapt to reality rather than defend assumptions
* teams gain confidence through evidence, not optimism
* governance discussions shift from blame to design

Dependencies no longer “surprise” the system — they inform it.

***

### Anti-Patterns

This pattern is violated when teams:

* maintain detailed dependency registers without testing any of them
* escalate dependencies rather than exercising them
* treat documentation as mitigation
* defer integration “until later”
* accept verbal assurances as evidence
* equate coordination with control

***

### Relation to EOM

This pattern upholds EOM invariants by:

* treating learning as a prerequisite for commitment
* using flow and response time as signals
* reducing reliance on predictive planning
* legitimising uncertainty
* shaping behaviour through system design, not instruction

Dependency exposure is a concrete expression of **learning over certainty**.

***

### Summary

> Dependencies cannot be managed if they are not experienced.

Mapping creates plans.\
Exposure creates understanding.

In complex systems, **only the latter reduces risk**.
