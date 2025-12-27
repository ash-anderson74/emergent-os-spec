# ADR-0005: Use of Flow Metrics as Signals Rather than Targets

## Status

Accepted

## Context

Flow metrics such as lead time, cycle time, throughput, and deployment frequency provide valuable insight into how work moves through a system.

However, when metrics are treated as targets or performance objectives, they are prone to distortion, gaming, and unintended consequences. This behavior is well-documented in socio-technical systems.

EmergentOS emphasizes learning and systemic improvement over local optimization.

---

## Decision

EmergentOS treats **flow metrics as diagnostic signals**, not performance targets.

Flow metrics are used to:

- observe system behaviour
- detect constraints and bottlenecks
- inform improvement decisions
- evaluate trends over time

They are not used to:

- set quotas
- compare teams competitively
- evaluate individual performance
- enforce delivery commitments

---

## Rationale

1. **Metrics influence behavior**  
   Targets incentivize optimization toward the metric rather than the system.

2. **Flow metrics describe, not prescribe**  
   Their value lies in revealing patterns, delays, and constraints.

3. **Trend analysis is more meaningful than point targets**  
   System health is better assessed through direction and stability over time.

4. **Local optimization degrades system performance**  
   Isolated metric improvement can worsen overall flow and learning.

---

## Alternatives Considered

### 1. Metric-Based Targets and Incentives

**Reasons Not Chosen:**

- Encourages gaming and metric manipulation
- Reduces psychological safety
- Obscures root causes of systemic issues

---

### 2. Metric-Free Governance

**Reasons Not Chosen:**

- Removes valuable feedback mechanisms
- Increases reliance on anecdote and intuition
- Reduces transparency at scale

EmergentOS balances visibility with restraint.

---

## Consequences

### Positive

- More accurate system diagnostics
- Reduced metric gaming
- Improved learning and improvement focus
- Better alignment between metrics and intent

### Trade-offs and Risks

- Metrics may be misinterpreted without context
- Leaders accustomed to targets may feel loss of control
- Requires coaching to build metric literacy

These risks are addressed through governance cadence and shared interpretation of signals.

---

## Related Spec Sections

- `/spec/03-operating-cadence.md`
- `/spec/04-governance-and-funding.md`

---

## Notes

Flow metrics must always be interpreted within context. Any use of a metric as a target should be treated as a risk signal.
