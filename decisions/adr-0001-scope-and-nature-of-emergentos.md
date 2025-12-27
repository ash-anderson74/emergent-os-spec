# ADR-0001: Defining the Scope and Nature of EmergentOS

## Status

Accepted

## Context

Organizations operate across a spectrum of uncertainty.

Some domains are:

- repeatable
- predictable
- governed effectively by deterministic planning and control

Others are:

- complex
- adaptive
- characterized by unknowns that only emerge through action and feedback

Many operating models, frameworks, and methodologies fail by applying deterministic assumptions uniformly across all contexts.

EmergentOS is intended to address a specific class of problems but must explicitly define that scope to avoid misuse and misinterpretation.

---

## Decision

EmergentOS is defined as a **socio-technical operating system for organizations operating in complex, high-uncertainty product environments**.

It is explicitly designed for contexts where:

- customer needs cannot be fully known upfront
- solutions emerge through experimentation
- cause-and-effect relationships are not reliably predictable
- learning is required to reduce uncertainty over time

EmergentOS:

- is not a delivery methodology
- is not a prescriptive framework
- does not define team practices or ceremonies
- does not assume homogeneity of work across the organization

Deterministic approaches may coexist with EmergentOS **only where uncertainty is demonstrably low**.

---

## Rationale

1. **Context matters more than practice**  
   The effectiveness of any operating model depends on the nature of the work being performed.

2. **Complex systems behave differently than mechanical systems**  
   Prediction, optimization, and centralized control lose effectiveness as uncertainty increases.

3. **Misapplication creates harm**  
   Applying adaptive models in deterministic domains (or vice versa) introduces unnecessary risk.

4. **Learning must be first-class**  
   In complex contexts, learning—not execution efficiency—is the primary means of progress.

---

## Alternatives Considered

### 1. Universal Operating Model

**Description:**  
Treat EmergentOS as applicable to all work, regardless of uncertainty.

**Reasons Not Chosen:**

- Ignores domain differences
- Encourages dogmatic adoption
- Increases risk of misapplication
- Weakens conceptual rigor

---

### 2. Delivery-Focused Operating Model

**Description:**  
Scope EmergentOS primarily around software delivery.

**Reasons Not Chosen:**

- Reduces DevOps to pipelines
- Excludes discovery and learning
- Fails to address systemic decision-making

---

## Consequences

### Positive

- Clear applicability boundaries
- Reduced risk of ideological misuse
- Stronger internal coherence across the spec
- Easier justification of later decisions

### Trade-offs and Risks

- Some stakeholders may find scope limiting
- Requires leadership judgment to classify work
- Reduces promise of universal applicability

These trade-offs are accepted to preserve integrity.

---

## Related Spec Sections

- `/spec/00-introduction.md`
- `/spec/03-operating-cadence.md`
- `/spec/04-governance-and-funding.md`

---

## Notes

This ADR acts as the **interpretive lens** for all subsequent EmergentOS decisions.

Any future change to this decision would require a major revision of the specification.
