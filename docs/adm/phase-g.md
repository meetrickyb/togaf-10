# Phase G: Implementation Governance

> Phase G provides **architectural oversight** of implementation projects to ensure they conform to the target architecture and deliver expected value.

---

## Purpose

Phase G ensures that:
- Implementation projects comply with the architecture
- Architecture decisions are properly enforced
- Deviations are identified, assessed, and managed
- Solutions deliver promised business value
- Lessons learned inform future architecture

This phase is the **"architecture police"** function — ensuring architecture integrity during implementation.

---

## Objectives

| Objective | Description |
|-----------|-------------|
| **Ensure compliance** | Verify implementations conform to architecture |
| **Perform governance** | Execute architectural oversight and reviews |
| **Manage dispensations** | Handle requests for exceptions to standards |
| **Support implementation** | Provide architectural guidance to project teams |
| **Monitor progress** | Track implementation against plan |
| **Resolve issues** | Address architectural problems and conflicts |
| **Capture lessons** | Document insights for future architecture work |

---

## Inputs

| Input | Source |
|-------|--------|
| **Request for Architecture Work** | Phase A |
| **Capability Assessment** | Phases A, E |
| **Organizational Model for EA** | Preliminary Phase |
| **Architecture Contract** | Phase F |
| **Implementation and Migration Plan** | Phase F |
| **Architecture Roadmap** | Phase F |
| **Implementation Governance Model** | Phase F |
| **Architecture Definition Document** | Phases B, C, D, E |
| **Architecture Requirements Specification** | Phases B, C, D |
| **Work packages** | Phase E |

---

## Steps

### 1. Confirm Scope and Priorities
- Review implementation projects in current cycle
- Confirm architecture requirements for each project
- Establish governance priorities
- Allocate architecture resources

### 2. Identify Deployment Resources and Skills
- Assess project team capabilities
- Identify gaps in architectural knowledge
- Provide training or architectural guidance
- Assign architecture support resources

### 3. Guide Development of Solutions Deployment
- Advise on architecture-compliant approaches
- Review design decisions
- Recommend patterns and standards
- Facilitate architectural problem-solving

### 4. Perform Enterprise Architecture Compliance Reviews
- Conduct compliance assessments at governance checkpoints
- Review architecture deliverables from projects
- Identify deviations from standards
- Document compliance status

### 5. Implement Business and IT Operations
- Support deployment to production
- Validate operational readiness
- Ensure architecture documentation is complete
- Confirm monitoring and management capabilities

### 6. Perform Post-Implementation Review
- Assess realized vs. expected benefits
- Evaluate architecture effectiveness
- Gather stakeholder feedback
- Identify improvement opportunities

---

## Outputs

| Output | Description |
|--------|-------------|
| **Architecture Contract (signed)** | Executed agreement between architects and implementers |
| **Compliance Assessments** | Results of architectural compliance reviews |
| **Change Requests** | Identified needs for architecture changes |
| **Architecture-compliant solutions** | Implemented systems conforming to architecture |
| **Recommendations for Phase H** | Identified architecture updates and improvements |
| **Architecture Repository updates** | New patterns, standards, lessons learned |

---

## Architecture Governance Activities

### 1. Governance Checkpoints

Implementation projects pass through **mandatory review gates**:

| Checkpoint | Timing | Review Focus |
|------------|--------|--------------|
| **Project Initiation** | Project start | Scope, requirements, compliance approach |
| **Architecture Design** | After design | Solution architecture conformance |
| **Build Review** | Mid-implementation | Standards adherence, pattern usage |
| **Pre-Production** | Before deployment | Final compliance check, operational readiness |
| **Post-Implementation** | 3-6 months after go-live | Benefits realization, lessons learned |

### 2. Compliance Review Process

For each checkpoint:

1. **Submit artifacts** — Project provides required documentation
2. **Review for compliance** — Architecture team assesses conformance
3. **Identify deviations** — Document any non-compliance
4. **Assess impact** — Evaluate significance of deviations
5. **Make decision** — Approve, approve with conditions, or reject
6. **Document outcome** — Record decision and rationale

### 3. Compliance Assessment Criteria

| Criteria | Assessment Questions |
|----------|---------------------|
| **Principles adherence** | Does solution follow architecture principles? |
| **Standards conformance** | Are technology and data standards met? |
| **Pattern usage** | Are approved patterns used appropriately? |
| **Integration approach** | Does integration follow architecture guidelines? |
| **Security compliance** | Are security requirements satisfied? |
| **Performance** | Will non-functional requirements be met? |
| **Maintainability** | Is solution supportable and evolvable? |

---

## Managing Dispensations

A **dispensation** is permission to deviate from architecture standards.

### When Dispensations Are Needed

- Urgent business need requires exception
- Technology constraint prevents standard approach
- Cost of compliance exceeds benefit
- Standard is inappropriate for specific case

### Dispensation Process

1. **Request submitted** — Project documents need and justification
2. **Impact assessed** — Architects evaluate consequences
3. **Alternatives explored** — Consider compliant options
4. **Decision made** — Architecture Board approves/rejects
5. **Conditions set** — Define scope and duration of exception
6. **Monitored** — Track dispensation and prevent proliferation

### Dispensation Documentation

| Element | Description |
|---------|-------------|
| **Requester** | Project requesting exception |
| **Standard affected** | Which architecture requirement |
| **Justification** | Why exception is needed |
| **Impact assessment** | Consequences of granting exception |
| **Conditions** | Scope, duration, constraints |
| **Approval** | Decision and authority |
| **Expiration** | When dispensation ends |

---

## Architecture Support Activities

Phase G provides **hands-on support** to implementation teams:

### 1. Architectural Guidance

| Activity | Description |
|----------|-------------|
| **Design reviews** | Advise on solution architecture decisions |
| **Pattern selection** | Help choose appropriate architecture patterns |
| **Problem-solving** | Resolve architectural challenges |
| **Trade-off analysis** | Evaluate design alternatives |

### 2. Knowledge Transfer

| Activity | Description |
|----------|-------------|
| **Training** | Educate project teams on architecture |
| **Documentation** | Provide standards, patterns, guidelines |
| **Workshops** | Facilitate architecture sessions |
| **Mentoring** | Pair architects with project teams |

### 3. Standards Interpretation

| Activity | Description |
|----------|-------------|
| **Clarification** | Explain architecture requirements |
| **Application** | Show how standards apply to specific cases |
| **Updates** | Refine standards based on practical experience |

---

## Compliance Assessment Outcomes

Possible results from compliance review:

| Outcome | Description | Follow-up Actions |
|---------|-------------|------------------|
| **Fully Compliant** | Meets all architecture requirements | Approve to proceed |
| **Compliant with Observations** | Minor issues noted | Approve with recommendations for improvement |
| **Conditionally Compliant** | Requires specific changes | Approve contingent on addressing conditions |
| **Non-Compliant** | Significant deviations | Reject; require remediation before approval |
| **Dispensation Granted** | Exception approved | Document dispensation; set conditions and monitoring |

---

## Change Management During Implementation

Implementation may reveal need for architecture changes:

### Types of Changes

| Change Type | Example | Handling |
|-------------|---------|----------|
| **Requirement change** | New business requirement emerges | Via Requirements Management to appropriate ADM phase |
| **Technology change** | Better technology becomes available | Evaluate impact; may trigger Phase D revision |
| **Constraint change** | Budget or timeline changes | Reassess roadmap; may trigger Phase F revision |
| **Lessons learned** | Better approach discovered | Document; update patterns and standards |

### Change Request Process

1. **Change identified** — During implementation or review
2. **Change documented** — Capture details and justification
3. **Impact assessed** — Evaluate effect on architecture and projects
4. **Decision made** — Architecture Board approves/defers/rejects
5. **Implemented** — If approved, execute change
6. **Communicated** — Inform affected stakeholders

---

## Architecture Contract Management

**Architecture Contracts** govern the relationship between architects and implementers.

### Contract Elements

| Element | Purpose |
|---------|---------|
| **Scope** | What is being delivered |
| **Architecture criteria** | Standards and requirements to meet |
| **Deliverables** | Architecture artifacts required from project |
| **Review schedule** | When governance checkpoints occur |
| **Acceptance criteria** | How compliance is measured |
| **Roles and responsibilities** | Who does what |
| **Escalation process** | How issues are resolved |

### Contract Lifecycle

1. **Drafted** — In Phase F during implementation planning
2. **Negotiated** — Finalized with project team in Phase G
3. **Signed** — Formal agreement executed
4. **Monitored** — Compliance tracked throughout project
5. **Closed** — Upon successful post-implementation review

---

## Lessons Learned Capture

Phase G documents insights for **continuous improvement**:

### What to Capture

| Category | Examples |
|----------|----------|
| **What worked well** | Patterns that proved effective, good collaboration |
| **What didn't work** | Standards that hindered progress, unrealistic assumptions |
| **Surprises** | Unexpected challenges or opportunities |
| **Better approaches** | Alternative solutions discovered during implementation |
| **Architecture updates needed** | Standards to revise, gaps to address |

### Lessons Learned Process

1. **Collect** — Throughout project via reviews and retrospectives
2. **Analyze** — Identify patterns and root causes
3. **Document** — Create lessons learned report
4. **Share** — Communicate to broader architecture community
5. **Act** — Update architecture repository, standards, processes
6. **Feed to Phase H** — Input to architecture change management

---

## Relationship to Other Phases

| Phase | Relationship |
|-------|-------------|
| **Phase F** | Provides implementation plan and governance model for Phase G to execute |
| **Phase H** | Receives lessons learned and change requests from Phase G |
| **Requirements Mgmt** | Manages requirement changes identified during implementation |
| **Phases B, C, D** | May be revisited if significant architecture changes needed |

Phase G **governs** the implementation of what was **planned** in Phase F.

---

## Common Governance Challenges

| Challenge | Mitigation |
|-----------|------------|
| **"Architecture ivory tower"** | Embed architects in project teams; provide practical guidance |
| **Delays due to reviews** | Streamline review process; empower project architects |
| **Overly rigid standards** | Allow justified dispensations; update unrealistic standards |
| **Insufficient authority** | Secure executive sponsorship; establish clear escalation |
| **Resource constraints** | Prioritize governance effort; leverage project architects |
| **Lack of engagement** | Demonstrate value; celebrate compliance successes |

---

## Exam Tips

- Phase G provides **Implementation Governance** — architectural oversight during execution
- Key activities: **Compliance reviews, dispensation management, architecture support**
- **Architecture Contracts** formalize agreements between architects and implementers
- **Compliance checkpoints** occur throughout project: initiation, design, build, pre-production, post-implementation
- **Dispensations** are approved exceptions to architecture standards
- Phase G ensures implementations **conform to architecture** and **deliver value**
- **Lessons learned** captured for continuous improvement
- **Change requests** generated when architecture updates needed
- Phase G **executes governance model** defined in Phase F
- Architecture support includes: **guidance, training, problem-solving**
- Compliance outcomes: **Fully compliant, conditional, non-compliant, dispensation**
- Phase G feeds insights to **Phase H** for architecture maintenance
