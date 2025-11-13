# Requirements Management

> Requirements Management is a **continuous, dynamic process** that operates throughout all ADM phases to identify, store, and manage architecture requirements.

---

## Purpose

Requirements Management ensures that:
- Architecture requirements are identified and documented
- Requirements are tracked and prioritized
- Changes to requirements are managed
- Requirements flow into and out of ADM phases
- Traceability is maintained from requirements to solutions

This phase sits at the **center of the ADM**, feeding all other phases.

---

## Key Characteristics

### 1. Continuous Process
- **NOT a one-time phase** — operates throughout entire ADM cycle
- Active during every other ADM phase
- Continues even during Phase H (ongoing operations)

### 2. Central to ADM
- Represented by the **circle at the center** of ADM diagram
- Feeds requirements **TO** every phase
- Receives requirements **FROM** every phase
- Ensures alignment across all phases

### 3. Dynamic and Iterative
- Requirements **evolve** as architecture develops
- New requirements emerge during architecture work
- Requirements are refined and elaborated over time
- Changes are tracked and managed

### 4. Process, Not Disposal
- Requirements Management is the **process** for managing requirements
- Does **NOT** prioritize or address requirements — that happens in ADM phases
- Provides **storage, tracking, and change management**

---

## Objectives

| Objective | Description |
|-----------|-------------|
| **Identify requirements** | Capture architecture requirements from stakeholders |
| **Store requirements** | Maintain requirements in a repository |
| **Track requirements** | Monitor status and changes |
| **Prioritize requirements** | Work with phases to determine importance (not RM itself) |
| **Manage changes** | Handle requirement additions, modifications, deletions |
| **Ensure traceability** | Link requirements to architecture and solutions |
| **Feed ADM phases** | Provide relevant requirements to each phase |

---

## Inputs

| Input | Source |
|-------|--------|
| **Business requirements** | Stakeholders, business strategy |
| **Architecture requirements** | ADM phases (A, B, C, D, E, F) |
| **Change requests** | Phases G, H, stakeholders |
| **Requirements from previous cycles** | Architecture Repository |

---

## Steps

### 1. Identify and Document Requirements
- Gather requirements from stakeholders
- Capture requirements from each ADM phase
- Document in standardized format
- Categorize by type and source

### 2. Baseline Requirements
- Establish initial set of requirements
- Create baseline for change tracking
- Version requirements baseline
- Communicate to stakeholders

### 3. Monitor Baseline Requirements
- Track changes to requirements
- Identify new requirements
- Monitor requirement status (proposed, approved, implemented)
- Update requirements repository

### 4. Assess Change Impacts
- Analyze impact of requirement changes
- Identify affected architecture domains
- Determine which ADM phases need revisiting
- Assess cost and benefit of changes

### 5. Prioritize Requirements
- Support ADM phases in prioritizing (not RM itself)
- Consider business value, urgency, dependencies
- Balance stakeholder needs
- Align with architecture objectives

### 6. Manage Approved Changes
- Update requirements repository
- Communicate changes to affected stakeholders
- Trigger appropriate ADM phase iterations
- Maintain requirements traceability

### 7. Update Requirements Repository
- Store all requirement artifacts
- Maintain version history
- Ensure accessibility to architecture team
- Link requirements to architecture elements

---

## Outputs

| Output | Description |
|--------|-------------|
| **Requirements Repository** | Centralized store of all architecture requirements |
| **Requirements Impact Assessment** | Analysis of how changes affect architecture |
| **Updated requirements** | Revised requirements reflecting changes |
| **Requirements Traceability Matrix** | Links between requirements and architecture elements |

---

## Types of Requirements

### 1. Business Requirements

| Type | Description | Example |
|------|-------------|---------|
| **Functional** | What the business needs to do | "Support online ordering" |
| **Process** | How business operates | "Order-to-cash in 24 hours" |
| **Capability** | What business must be able to do | "Serve customers in 15 countries" |

### 2. Architecture Requirements

| Type | Description | Example |
|------|-------------|---------|
| **Principle** | Guiding rules | "Data is an asset" |
| **Standard** | Technology or approach mandates | "Use REST APIs for integration" |
| **Pattern** | Architectural solution templates | "Microservices architecture" |

### 3. Technical Requirements

| Type | Description | Example |
|------|-------------|---------|
| **Non-functional** | Quality attributes | "99.9% uptime" |
| **Constraints** | Limitations | "Must run on existing infrastructure" |
| **Interface** | Integration specifications | "Integrate with SAP via OData" |

### 4. Stakeholder Requirements

| Type | Description | Example |
|------|-------------|---------|
| **Concerns** | Stakeholder interests | "Minimize disruption during migration" |
| **Preferences** | Stakeholder desires | "Prefer cloud-based solutions" |
| **Constraints** | Stakeholder limitations | "Budget cannot exceed $2M" |

---

## Requirements Lifecycle

Requirements progress through states:

```
Proposed → Analyzed → Validated → Approved → Implemented → Verified
```

| State | Description |
|-------|-------------|
| **Proposed** | Requirement identified but not yet analyzed |
| **Analyzed** | Impact and feasibility assessed |
| **Validated** | Confirmed with stakeholders |
| **Approved** | Accepted for implementation |
| **Implemented** | Built into architecture/solution |
| **Verified** | Confirmed as met |
| **Rejected** | Determined not to pursue |
| **Deferred** | Postponed to future cycle |

---

## Requirements Repository

The **Requirements Repository** stores all architecture requirements.

### Repository Contents

| Content | Description |
|---------|-------------|
| **Requirements catalog** | List of all requirements |
| **Requirements details** | Full specification for each requirement |
| **Relationships** | Dependencies between requirements |
| **Traceability** | Links to architecture and solutions |
| **Change history** | Versions and changes over time |
| **Approval status** | Current state and approvals |
| **Priority and ranking** | Importance and sequence |

### Repository Structure

```
Requirements Repository
├── Business Requirements
│   ├── Functional
│   ├── Process
│   └── Capability
├── Architecture Requirements
│   ├── Principles
│   ├── Standards
│   └── Patterns
├── Technical Requirements
│   ├── Non-Functional
│   ├── Constraints
│   └── Interfaces
└── Stakeholder Requirements
    ├── Concerns
    ├── Preferences
    └── Constraints
```

---

## Requirements Traceability

Traceability ensures requirements are **linked to architecture elements and solutions**.

### Traceability Matrix Example

| Requirement ID | Requirement | Addressed By | Architecture Element | Solution Component | Status |
|----------------|-------------|--------------|----------------------|-------------------|--------|
| REQ-001 | Online ordering | Business Process | Order Management Process | E-commerce Platform | Implemented |
| REQ-002 | 99.9% uptime | Infrastructure | High Availability Architecture | Load Balancer + Redundancy | Implemented |
| REQ-003 | Customer 360 view | Data Architecture | Customer MDM | MDM Platform | In Progress |

Traceability answers:
- Which requirements are addressed by which architecture elements?
- Which solutions implement which requirements?
- Are all requirements covered?
- Which requirements are not yet implemented?

---

## Change Management

Requirements Management handles **changes to requirements**:

### Change Types

| Change Type | Description | Handling |
|-------------|-------------|----------|
| **New requirement** | Stakeholder identifies new need | Assess impact; determine which ADM phase to engage |
| **Modified requirement** | Existing requirement changes | Evaluate impact on current architecture; re-engage affected phases |
| **Deleted requirement** | Requirement no longer valid | Remove or mark as obsolete; assess if architecture simplification possible |
| **Prioritization change** | Importance shifts | Update roadmap and implementation sequence |

### Change Process

1. **Change Requested** — Stakeholder or phase identifies need
2. **Impact Assessed** — Evaluate effect on architecture
3. **Reviewed** — Architecture team or board evaluates
4. **Decision Made** — Approve, defer, or reject
5. **Implemented** — If approved, update requirements and trigger ADM phases
6. **Communicated** — Inform stakeholders

---

## Requirements Management and ADM Phases

How Requirements Management interacts with each phase:

| Phase | RM Interaction |
|-------|----------------|
| **Preliminary** | Establish requirements management process |
| **Phase A** | Capture initial stakeholder requirements and concerns |
| **Phase B** | Receive business requirements; feed business architecture requirements to C |
| **Phase C** | Receive data/app requirements; feed technical requirements to D |
| **Phase D** | Receive technology requirements; feed constraints back to C |
| **Phase E** | Consolidate all requirements; validate completeness |
| **Phase F** | Ensure requirements are addressed in implementation plan |
| **Phase G** | Verify requirements are met in implementations |
| **Phase H** | Manage requirement changes triggering new cycles |

**Key Point:** Requirements flow **bidirectionally** — phases provide requirements TO RM, and RM provides requirements TO phases.

---

## Requirements Management Tools

Common tools and techniques:

| Tool/Technique | Purpose |
|----------------|---------|
| **Requirements repository** | Central storage (e.g., Jira, Azure DevOps, Confluence) |
| **Traceability matrix** | Link requirements to architecture and solutions |
| **Business scenarios** | Discover and elaborate requirements through scenarios |
| **Stakeholder analysis** | Identify and prioritize stakeholder requirements |
| **MoSCoW prioritization** | Must-have, Should-have, Could-have, Won't-have |
| **Impact assessment** | Evaluate effects of requirement changes |

---

## Requirements in Architecture Repository

Requirements are stored in the **Architecture Repository** as part of:

| Repository Component | Requirements Content |
|---------------------|---------------------|
| **Governance Log** | Requirement decisions and approvals |
| **Architecture Landscape** | Requirements driving architectures |
| **Standards Information Base** | Standard and principle requirements |
| **Reference Library** | Requirement patterns and templates |

---

## Common Pitfalls

| Pitfall | Consequence | Prevention |
|---------|-------------|------------|
| **Requirements not updated** | Architecture misalignment | Regular reviews and updates |
| **No traceability** | Unclear if requirements are met | Maintain traceability matrix |
| **Requirements not prioritized** | Everything is "high priority" | Formal prioritization process |
| **Changes not assessed** | Architecture impact unknown | Mandatory impact analysis |
| **Poor stakeholder engagement** | Missing or incorrect requirements | Continuous stakeholder involvement |
| **No change control** | Scope creep | Formal change management process |

---

## Relationship to Other Phases

Requirements Management is **unique** — it doesn't follow other phases; it **operates alongside** all phases.

```
        Requirements Management (Continuous)
                     ↕
    Preliminary → A → B → C → D → E → F → G → H
        ↕         ↕   ↕   ↕   ↕   ↕   ↕   ↕   ↕
    Requirements flow to and from every phase
```

---

## Exam Tips

- Requirements Management is **continuous**, not a one-time phase
- Sits at the **center** of ADM, feeding all other phases
- It's a **process** for managing requirements, not for prioritizing them
- Requirements **flow bidirectionally** — TO and FROM each ADM phase
- Handles requirement **identification, storage, tracking, change management**
- Does **NOT** prioritize or address requirements — that's done in ADM phases
- **Three types** of requirements: Business, Architecture, Technical (+ Stakeholder)
- **Requirements Repository** stores all requirements with traceability
- Requirements have a **lifecycle**: Proposed → Analyzed → Validated → Approved → Implemented
- **Change management** for requirements triggers appropriate ADM phase iterations
- **Traceability** links requirements to architecture elements and solutions
- Requirements Management establishes the **Requirements Repository** in Architecture Repository
