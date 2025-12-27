# ADR-0003: Adoption of Outcome-Based Planning over Output-Based Planning

## Status

Accepted

## Context

Many organizations plan and assess progress through outputs such as features delivered, scope completed, or milestones achieved. This approach assumes that outputs are reliable proxies for value and impact.

In complex product environments, this assumption frequently fails. Outputs may be delivered as planned while customer outcomes, business impact, or system health fail to improve.

EmergentOS is designed for environments where value is uncertain at the outset and must be discovered through interaction, feedback, and learning.

---

## Decision

EmergentOS adopts **outcome-based planning** as the default approach for strategic and portfolio planning.

Plans are framed in terms of:

- intended outcomes
- hypotheses about value creation
- measurable signals of change

Outputs are treated as potential means to an end, not as success criteria in themselves.

---

## Rationale

1. **Value is not directly controllable**  
   While teams can control outputs, they cannot directly control outcomes. Treating outcomes as primary focuses attention on learning and adaptation rather than compliance with plans.

2. **Outputs can misrepresent progress**  
   High delivery volume can coexist with poor customer impact, degraded system health, or strategic misalignment.

3. **Outcomes encourage hypothesis-driven thinking**  
   Framing work around outcomes requires teams to articulate assumptions and test them explicitly.

4. **Outcome framing reduces local optimization**  
   Teams are incentivized to optimize for real-world impact rather than activity completion.

---

## Alternatives Considered

### 1. Output-Based Planning

**Reasons Not Chosen:**

- Encourages delivery-focused behavior without regard to value
- Delays feedback until after investment is committed
- Reinforces fixed-scope thinking in uncertain contexts

---

### 2. Hybrid Output/Outcome Planning

**Reasons Not Chosen:**

- Maintains ambiguity about what constitutes success
- Allows output metrics to dominate under pressure
- Weakens accountability for impact

EmergentOS allows outputs to be tracked but not used as primary success measures.

---

## Consequences

### Positive

- Improved alignment between strategy and execution
- Faster detection of ineffective investments
- Increased emphasis on learning and customer impact
- Reduced incentive to deliver low-value work

### Trade-offs and Risks

- Outcomes can lag outputs, creating perceived ambiguity
- Requires stronger telemetry and measurement discipline
- May be uncomfortable for stakeholders accustomed to certainty

These risks are mitigated through explicit cadence, guardrails, and transparent learning signals.

---

## Related Spec Sections

- `/spec/03-operating-cadence.md`
- `/spec/04-governance-and-funding.md`

---

## Notes

Outcome-based planning is foundational to EmergentOS. Reversion to output-based planning is considered a systemic risk in high-uncertainty contexts.
