# Governance & Compliance

> **Architecture Governance** is the practice and orientation by which enterprise architectures are managed and controlled, ensuring alignment with business strategy, compliance with standards, and delivery of value.

---

## Purpose

Architecture Governance ensures:
- **Alignment** — Architecture supports business strategy
- **Compliance** — Implementations follow architecture standards
- **Value delivery** — Architecture investments deliver benefits
- **Risk management** — Architecture risks are identified and mitigated
- **Accountability** — Clear responsibility for architecture decisions
- **Traceability** — Architecture decisions are documented

---

## What is Architecture Governance?

Architecture Governance is:
- **Framework** for decision-making and oversight
- **Processes** for reviewing and approving architecture
- **Controls** ensuring compliance with standards
- **Mechanisms** for managing exceptions
- **Culture** of architectural accountability

---

## Architecture Governance Framework

### Framework Components

| Component | Purpose |
|-----------|---------|
| **Governance structure** | Bodies and roles responsible for governance |
| **Governance processes** | How architecture is reviewed and approved |
| **Governance checkpoints** | When reviews occur in project lifecycle |
| **Decision rights** | Who makes which decisions |
| **Escalation procedures** | How conflicts are resolved |
| **Compliance mechanisms** | How conformance is verified |
| **Metrics and reporting** | How governance effectiveness is measured |

---

## Architecture Board

The **Architecture Board** is the **primary governance body** for enterprise architecture.

### Composition

| Member | Role |
|--------|------|
| **CIO or Chief Architect** | Chair, overall accountability |
| **Domain Architects** | Business, Data, Application, Technology expertise |
| **Business Representatives** | Represent business unit interests |
| **IT Leadership** | Infrastructure, operations, development leaders |
| **Subject Matter Experts** | Security, compliance, as needed |

### Board Responsibilities

| Responsibility | Description |
|----------------|-------------|
| **Approve architectures** | Review and endorse Architecture Vision, definition, roadmap |
| **Set standards** | Define and update architecture standards and principles |
| **Review compliance** | Assess project conformance to architecture |
| **Grant dispensations** | Approve exceptions to standards with conditions |
| **Resolve conflicts** | Arbitrate architecture disputes |
| **Prioritize initiatives** | Guide architecture work priorities |
| **Monitor performance** | Track architecture value delivery |
| **Set strategy** | Define architecture strategic direction |

### Board Meetings

| Meeting Type | Frequency | Purpose |
|--------------|-----------|---------|
| **Regular meetings** | Monthly or bi-monthly | Routine governance decisions |
| **Project reviews** | Per governance checkpoint | Compliance assessments |
| **Strategic sessions** | Quarterly | Architecture strategy and planning |
| **Emergency meetings** | As needed | Critical issues requiring immediate decision |

---

## Governance Processes

### 1. Architecture Development Process

How architectures are created and approved:

```
Request → Vision (Phase A) → Approval → Development (B,C,D) →
Approval → Planning (E,F) → Approval → Implementation (G) →
Monitoring (H)
```

**Approval gates** at key milestones ensure architecture aligns with governance.

### 2. Compliance Review Process

How project compliance is assessed:

| Step | Activity |
|------|----------|
| **1. Initiate** | Project requests architecture review |
| **2. Submit** | Project provides architecture artifacts |
| **3. Review** | Architecture team assesses compliance |
| **4. Report** | Compliance assessment documented |
| **5. Decide** | Architecture Board approves/rejects/conditions |
| **6. Follow-up** | Track remediation if needed |

### 3. Dispensation Process

How exceptions to architecture standards are handled:

| Step | Activity |
|------|----------|
| **1. Request** | Project requests exception with justification |
| **2. Assess** | Architects evaluate impact |
| **3. Explore alternatives** | Consider compliant options |
| **4. Recommend** | Architects provide recommendation |
| **5. Decide** | Architecture Board approves/rejects |
| **6. Document** | Dispensation recorded with conditions |
| **7. Monitor** | Ensure dispensation scope and duration are respected |

### 4. Change Management Process

How architecture changes are managed:

| Step | Activity |
|------|----------|
| **1. Identify** | Change need identified |
| **2. Document** | Change request submitted |
| **3. Assess** | Impact analysis performed |
| **4. Prioritize** | Change prioritized in backlog |
| **5. Approve** | Architecture Board reviews and approves |
| **6. Implement** | Change executed (may trigger ADM phase) |
| **7. Communicate** | Stakeholders notified |

---

## Governance Checkpoints

Governance reviews occur at **key points** in project lifecycle:

### Mandatory Checkpoints

| Checkpoint | Timing | Review Focus |
|------------|--------|--------------|
| **Project Initiation** | Project start | Scope, approach, architecture requirements |
| **Architecture Design** | After design phase | Solution architecture compliance |
| **Build Review** | Mid-implementation | Standards adherence, progress |
| **Pre-Production** | Before go-live | Final compliance check, operational readiness |
| **Post-Implementation** | 3-6 months post-launch | Benefits realization, lessons learned |

### Optional Checkpoints

| Checkpoint | When Used |
|------------|-----------|
| **Proof of Concept** | High-risk technology decisions |
| **Vendor Selection** | Selecting major technology or product |
| **Architecture Decision Records** | Significant architectural decisions |

---

## Compliance Assessment

### Assessment Criteria

| Criterion | Assessment Questions |
|-----------|---------------------|
| **Principles adherence** | Does solution follow architecture principles? |
| **Standards conformance** | Are approved technologies and patterns used? |
| **Integration compliance** | Does integration follow architecture guidelines? |
| **Security compliance** | Are security requirements satisfied? |
| **Data compliance** | Does data handling meet governance standards? |
| **Performance** | Will non-functional requirements be met? |
| **Supportability** | Can the solution be maintained and operated? |

### Compliance Levels

| Level | Description | Action |
|-------|-------------|--------|
| **Fully Compliant** | Meets all requirements | Approve to proceed |
| **Compliant with Observations** | Minor issues noted | Approve with recommendations |
| **Conditionally Compliant** | Specific changes needed | Approve contingent on addressing issues |
| **Non-Compliant** | Significant deviations | Reject; require remediation |
| **Dispensation Required** | Exception needed | Grant dispensation with conditions |

---

## Architecture Contracts

**Architecture Contracts** formalize the governance relationship.

### Contract Purpose

| Purpose | Description |
|---------|-------------|
| **Set expectations** | Clear architecture requirements |
| **Define deliverables** | Architecture artifacts expected from project |
| **Establish accountability** | Who is responsible for what |
| **Enable oversight** | Governance checkpoints and review process |
| **Manage exceptions** | How dispensations are handled |

### Contract Contents

| Section | Content |
|---------|---------|
| **Parties** | Architecture team and project/program |
| **Scope** | What is being delivered |
| **Architecture requirements** | Standards, principles, patterns to follow |
| **Deliverables** | Architecture artifacts project must produce |
| **Review schedule** | When governance checkpoints occur |
| **Acceptance criteria** | How compliance is measured |
| **Roles & responsibilities** | Who does what |
| **Escalation** | How disputes are resolved |
| **Success criteria** | How success is measured |

### Contract Lifecycle

```
Draft (Phase F) → Negotiate → Sign → Monitor (Phase G) →
Close (Post-Implementation)
```

---

## Dispensations (Exceptions)

A **dispensation** is formal permission to deviate from architecture standards.

### When Needed

| Situation | Example |
|-----------|---------|
| **Urgent business need** | Regulatory deadline requires quick solution |
| **Technology constraint** | Standard approach not technically feasible |
| **Cost justification** | Compliance cost exceeds benefit for specific case |
| **Temporary exception** | Short-term workaround until permanent solution |

### Dispensation Components

| Component | Description |
|-----------|-------------|
| **Requester** | Project requesting exception |
| **Standard affected** | Which architecture requirement |
| **Justification** | Why exception is needed |
| **Alternatives considered** | What compliant options were explored |
| **Impact assessment** | Consequences of granting exception |
| **Conditions** | Scope, duration, constraints |
| **Mitigation** | How risks will be managed |
| **Approval** | Decision and authority |
| **Expiration** | When dispensation ends |

### Monitoring Dispensations

- **Track** all active dispensations
- **Ensure** conditions are met
- **Prevent proliferation** — avoid creating precedent
- **Review** periodically to end or renew
- **Address root causes** — update standards if many exceptions for same issue

---

## Governance Metrics and KPIs

### Process Metrics

| Metric | Purpose |
|--------|---------|
| **Architecture coverage** | % of projects with architecture review |
| **Review turnaround time** | Days to complete compliance review |
| **Approval rate** | % of projects approved first time |
| **Dispensation rate** | % of projects requiring exceptions |
| **Checkpoint attendance** | Attendance at governance reviews |

### Compliance Metrics

| Metric | Purpose |
|--------|---------|
| **Compliance score** | Average compliance assessment rating |
| **Standard adherence** | % of standards followed |
| **Non-conformances** | Number of compliance violations |
| **Remediation time** | Time to address non-compliance |

### Value Metrics

| Metric | Purpose |
|--------|---------|
| **Cost avoidance** | Redundant investments prevented |
| **Reuse rate** | % of components reused vs. built new |
| **Risk reduction** | High-risk issues identified and mitigated |
| **Time to market** | Project delivery time (architecture impact) |
| **Benefits realization** | Value delivered vs. projected |

---

## Integration with Corporate Governance

Architecture Governance should **align with** and **integrate into** broader corporate governance:

| Corporate Governance | Architecture Governance Integration |
|---------------------|----------------------------------|
| **Board of Directors** | Architecture Board reports on EA strategic alignment |
| **Audit Committee** | Architecture compliance audits |
| **Risk Committee** | Architecture risk management |
| **IT Steering Committee** | Architecture priorities and investment |
| **Project Portfolio Mgmt** | Architecture input to project approvals |
| **Enterprise Risk Mgmt** | Architecture risks in enterprise risk register |

---

## Governance Maturity

### Maturity Levels

| Level | Characteristics |
|-------|-----------------|
| **Level 1: Ad-hoc** | No formal governance, inconsistent reviews |
| **Level 2: Developing** | Some standards, informal reviews |
| **Level 3: Defined** | Documented processes, regular reviews |
| **Level 4: Managed** | Measured performance, proactive governance |
| **Level 5: Optimizing** | Continuous improvement, strategic governance |

### Advancing Maturity

| From | To | Actions |
|------|----|---------|
| **Ad-hoc** | **Developing** | Establish Architecture Board, document principles |
| **Developing** | **Defined** | Formalize processes, mandatory checkpoints |
| **Defined** | **Managed** | Implement metrics, performance tracking |
| **Managed** | **Optimizing** | Continuous improvement, predictive governance |

---

## Common Governance Challenges

| Challenge | Mitigation Strategy |
|-----------|---------------------|
| **Seen as bureaucracy** | Streamline processes, demonstrate value |
| **Lack of authority** | Secure executive sponsorship, clear escalation |
| **Insufficient resources** | Prioritize governance effort, embed in projects |
| **Overly rigid** | Allow justified dispensations, iterative refinement |
| **Poor engagement** | Stakeholder involvement, practical guidance |
| **Slow decision-making** | Empower sub-decisions, streamline approval |

---

## Governance Throughout ADM

| Phase | Governance Activity |
|-------|---------------------|
| **Preliminary** | Establish governance framework, Architecture Board |
| **Phase A** | Approve Architecture Vision and Statement of Work |
| **Phases B,C,D** | Review architecture definitions for completeness |
| **Phase E** | Approve transformation approach and roadmap |
| **Phase F** | Approve implementation plan, sign contracts |
| **Phase G** | Conduct compliance reviews, grant dispensations |
| **Phase H** | Monitor ongoing compliance, manage changes |

Governance is **active throughout the ADM** — it's not a one-time activity.

---

## Exam Tips

- **Architecture Governance** ensures architectures align with strategy and comply with standards
- **Architecture Board** is the primary governance body (review, approve, grant exceptions)
- **Compliance reviews** occur at **checkpoints** throughout project lifecycle
- **Governance checkpoints**: Initiation, Design, Build, Pre-Production, Post-Implementation
- **Architecture Contracts** formalize governance agreements
- **Dispensations** are approved exceptions to standards (with conditions and expiration)
- Compliance levels: **Fully compliant, Conditional, Non-compliant, Dispensation**
- Governance framework includes: **Structure, Processes, Checkpoints, Decision rights, Escalation**
- Governance **integrates with corporate governance** (Board, Audit, Risk, IT Steering)
- **Metrics** track governance effectiveness (coverage, compliance, value)
- Governance maturity: **Ad-hoc → Developing → Defined → Managed → Optimizing**
- Governance is established in **Preliminary**, executed in **Phases G and H**, active throughout ADM
