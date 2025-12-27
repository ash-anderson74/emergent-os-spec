# ADR-0004: Rejection of Deterministic Planning as a Default

## Status

Accepted

## Context

Deterministic planning approaches assume that work can be decomposed, sequenced, estimated, and executed predictably. These approaches are effective in domains with stable requirements, repeatable processes, and low uncertainty.

In product and technology development, uncertainty is pervasive and knowledge emerges over time. Applying deterministic planning as a default response in such environments often creates an illusion of control while reducing adaptability.

EmergentOS explicitly targets complex, adaptive domains rather than deterministic delivery contexts.

---

## Decision

EmergentOS **rejects deterministic planning as the default planning approach**.

Deterministic techniques (such as fixed-scope planning and long-range predictive schedules):

- may be used selectively in low-uncertainty contexts
- are treated as situational tools, not governing assumptions
- are explicitly constrained by learning and feedback mechanisms

---

## Rationale

1. **Complex systems are not fully predictable**  
   Cause-and-effect relationships cannot be reliably known upfront, making detailed prediction fragile.

2. **Early certainty inhibits learning**  
   Strong upfront commitments reduce willingness to respond to emerging evidence.

3. **Prediction shifts focus from discovery to compliance**  
   Teams optimize to meet plans rather than to learn and adapt.

4. **Illusions of control increase systemic risk**  
   Predictive plans can mask underlying uncertainty and delay corrective action.

---

## Alternatives Considered

### 1. Deterministic Planning with Better Estimation

**Reasons Not Chosen:**

- Estimation accuracy does not overcome inherent uncertainty
- Increases planning overhead without reducing risk
- Reinforces false confidence

---

### 2. Rolling Predictive Planning

**Reasons Not Chosen:**

- Retains prediction as the primary control mechanism
- Often degenerates into re-baselining exercises
- Does not fundamentally change incentive structures

---

## Consequences

### Positive

- Increased responsiveness to change
- Reduced risk of large misaligned investments
- Stronger alignment between planning and learning
- Greater focus on hypotheses and outcomes

### Trade-offs and Risks

- Requires comfort with uncertainty
- Reduces apparent short-term predictability
- May trigger resistance from control-oriented cultures

These risks are mitigated through explicit cadence, transparency, and outcome-based governance.

---

## Related Spec Sections

- `/spec/03-operating-cadence.md`
- `/spec/04-governance-and-funding.md`

---

## Notes

Deterministic planning is not prohibited in EmergentOS, but its use must be justified by context and revisited when uncertainty increases.
