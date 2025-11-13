# TOGAF 10 Foundation Cheat Sheet

> Quick reference for key TOGAF 10 concepts, definitions, and ADM phases for exam preparation.

---

## Core Concepts

### Enterprise Architecture

| Term | Definition |
|------|------------|
| **Enterprise Architecture** | Structure and operation of an organization across four domains: Business, Data, Application, Technology (BDAT) |
| **Baseline Architecture** | Current state, acting as reference for change |
| **Target Architecture** | Desired future state |
| **Transition Architecture** | Intermediate state during transformation |

### TOGAF Standard

| Component | Description |
|-----------|-------------|
| **ADM** | Architecture Development Method — core of TOGAF |
| **Content Framework** | Structure for architecture artifacts (deliverables, artifacts, building blocks) |
| **Enterprise Continuum** | Classification of architecture assets (Foundation → Common → Industry → Org-Specific) |
| **Architecture Repository** | Storage for architecture assets |
| **Reference Models** | TRM (Technical Reference Model), III-RM (Integration) |
| **Architecture Capability** | Organizational ability to practice EA |

---

## ADM Phases Quick Reference

### Preliminary Phase
- **Purpose**: Prepare organization for EA
- **Key Activities**: Define scope, establish EA team, define principles, tailor TOGAF
- **Key Outputs**: Organizational Model for EA, Tailored Framework, Architecture Principles
- **Mantra**: "Where, what, why, who, how" of doing architecture

### Phase A: Architecture Vision
- **Purpose**: Create high-level vision and obtain approval
- **Key Activities**: Identify stakeholders, define scope, develop vision, secure approval
- **Key Outputs**: Statement of Architecture Work, Architecture Vision, Communications Plan
- **Mantra**: "Elevator pitch" — sell the architecture

### Phase B: Business Architecture
- **Purpose**: Develop Business Architecture
- **Key Activities**: Develop baseline/target, gap analysis, define roadmap components
- **Key Outputs**: Draft Architecture Definition Document (Business), Business Roadmap components
- **Focus**: Capabilities, processes, organization, value streams

### Phase C: Information Systems Architectures
- **Purpose**: Develop Data and Application Architectures
- **Two Parts**: Data Architecture + Application Architecture (can be sequential or concurrent)
- **Key Outputs**: Draft Architecture Definition Document (Data + Application), Roadmap components
- **Focus**: Data entities, data flows, application portfolio, integration

### Phase D: Technology Architecture
- **Purpose**: Define technology infrastructure and platforms
- **Key Activities**: Develop baseline/target tech architecture, gap analysis
- **Key Outputs**: Draft Architecture Definition Document (Technology), Tech Roadmap components
- **Focus**: Hardware, platforms, networks, TRM classification

### Phase E: Opportunities & Solutions
- **Purpose**: Identify delivery approach and create initial roadmap
- **Key Activities**: Consolidate gaps, identify solutions, define work packages, create transitions
- **Key Outputs**: Architecture Roadmap (initial), Transition Architectures, Work Package Catalog
- **Mantra**: "How to deliver" — bridge from architecture to implementation

### Phase F: Migration Planning
- **Purpose**: Create detailed implementation plan
- **Key Activities**: Prioritize projects, estimate costs/resources, manage risks, finalize roadmap
- **Key Outputs**: Implementation and Migration Plan (final), Finalized Roadmap, Implementation Governance Model
- **Mantra**: "When, who, and how much"

### Phase G: Implementation Governance
- **Purpose**: Provide architectural oversight during implementation
- **Key Activities**: Conduct compliance reviews, manage dispensations, support projects
- **Key Outputs**: Architecture Contracts (signed), Compliance Assessments, Change Requests
- **Mantra**: "Architecture police" — ensure compliance

### Phase H: Architecture Change Management
- **Purpose**: Manage changes and maintain architecture
- **Key Activities**: Monitor changes, assess impacts, manage change requests, trigger new cycles
- **Key Outputs**: Architecture Updates, Change Requests for new cycles
- **Mantra**: Keep architecture "alive" and aligned with business

### Requirements Management
- **Purpose**: Continuous management of architecture requirements
- **Key Characteristics**: Continuous, central to ADM, dynamic, feeds all phases
- **Key Outputs**: Requirements Repository, Requirements Impact Assessments
- **Important**: Does NOT prioritize requirements — that happens in ADM phases

---

## Key Definitions

### Architecture Artifacts

| Term | Definition |
|------|------------|
| **Deliverable** | Work product formally reviewed and signed off (e.g., Architecture Vision, ADD) |
| **Artifact** | Specific work product (Catalog, Matrix, Diagram) |
| **Catalog** | List of things |
| **Matrix** | Relationships between things |
| **Diagram** | Visual representation |
| **Building Block** | Reusable component of capability |
| **ABB** | Architecture Building Block — "what" is needed (functional specification) |
| **SBB** | Solution Building Block — "how" it's implemented (specific product) |

### Views and Viewpoints

| Term | Definition |
|------|------------|
| **Stakeholder** | Individual or group with interests in architecture |
| **Concern** | Stakeholder interest or objective |
| **Architecture View** | Representation of architecture addressing specific concerns |
| **Architecture Viewpoint** | Conventions for creating and using a view |

### Principles

| Element | Description |
|---------|-------------|
| **Name** | Clear identifier |
| **Statement** | Concise rule |
| **Rationale** | Why it exists |
| **Implications** | Consequences and requirements |

---

## Enterprise Continuum & Repository

### Architecture Continuum

```
Foundation → Common Systems → Industry → Organization-Specific
(Generic ABBs)                            (Specific ABBs)
```

### Solutions Continuum

```
Foundation → Common Systems → Industry → Organization-Specific
(Generic Products)                        (Custom Solutions)
```

### Architecture Repository Components

| Component | Content |
|-----------|---------|
| **Architecture Metamodel** | Structure of architecture information |
| **Architecture Landscape** | Strategic, Segment, Capability architectures |
| **Standards Information Base** | Standards, principles, policies |
| **Reference Library** | Patterns, templates, guidelines |
| **Governance Log** | Decisions, compliance, contracts |
| **Solutions Landscape** | Deployed systems and projects |

---

## Reference Models

### TRM (Technical Reference Model)
- **Purpose**: Taxonomy of platform services
- **Structure**: Layers from hardware → OS → network → data → application platform
- **Use**: Classify technology, ensure completeness

### III-RM (Integrated Information Infrastructure RM)
- **Purpose**: Model for application integration
- **Focus**: Boundaryless information flow, interoperability
- **Components**: Business Apps, Infrastructure Apps, Application Platform

---

## Architecture Capability Framework

### Seven Components

1. **Architecture Board** — Governance body
2. **Architecture Compliance** — Ensure conformance
3. **Architecture Contracts** — Formal agreements
4. **Architecture Governance** — Oversight framework
5. **Architecture Maturity Models** — Capability assessment
6. **Architecture Skills Framework** — Required competencies
7. **Architecture Repository** — Asset storage

---

## Governance Quick Reference

### Architecture Board
- **Role**: Oversee, approve, review compliance, grant dispensations
- **Membership**: CIO/Chief Architect (chair), domain architects, business reps

### Compliance Checkpoints
1. Project Initiation
2. Architecture Design
3. Build Review
4. Pre-Production
5. Post-Implementation

### Compliance Levels
- **Fully Compliant** — Approve
- **Compliant with Observations** — Approve with recommendations
- **Conditionally Compliant** — Approve with required changes
- **Non-Compliant** — Reject, require remediation
- **Dispensation** — Exception granted with conditions

### Architecture Contract
- **Parties**: Architecture team and project
- **Content**: Requirements, deliverables, acceptance criteria, review schedule

---

## Common Exam Traps

| Trap | Correct Answer |
|------|----------------|
| "Requirements Management prioritizes requirements" | FALSE — RM is process for managing; phases prioritize |
| "Phase C is only Data or only Application" | FALSE — Phase C covers BOTH |
| "TRM is mandatory and cannot be tailored" | FALSE — Should be customized to organization |
| "ABBs map to exactly one SBB" | FALSE — One ABB can have multiple SBB options |
| "Preliminary Phase develops architecture" | FALSE — Preliminary prepares; A-D develop architecture |
| "Architecture Repository stores only final architectures" | FALSE — Stores all work products, versions, decisions |

---

## Memorization Aids

### ADM Sequence
**"Please A Bunch Can't Dance Every Friday, Go Home"**
- **P**reliminary
- **A**rchitecture Vision
- **B**usiness
- **C**an't (Information Systems)
- **D**ance (Technology)
- **E**very (Opportunities)
- **F**riday (Migration Planning)
- **G**o (Implementation Governance)
- **H**ome (Change Management)
- + **Requirements** (center)

### BDAT Domains
**"Business Data Applicación Technology"**
- Phase B = Business
- Phase C = Data + Application
- Phase D = Technology

### Enterprise Continuum Levels
**"From Common Ideas to Organizational"**
- **F**oundation
- **C**ommon Systems
- **I**ndustry
- **O**rganization-Specific

---

## Key Numbers

| Number | What |
|--------|------|
| **40** | Exam questions |
| **60** | Minutes for exam |
| **60%** | Pass mark (24/40 correct) |
| **4** | Architecture domains (BDAT) |
| **4** | Enterprise Continuum levels |
| **4** | Dimensions of architecture scope |
| **6** | Architecture Repository components |
| **7** | Architecture Capability Framework components |
| **8** | ADM architecture development phases (Prelim + A-H) |
| **10+** | Total ADM phases including Requirements |

---

## Scope Dimensions

1. **Breadth** — Enterprise scope (whole org, business unit, etc.)
2. **Depth** — Level of detail (how much architecture)
3. **Domains** — Which BDAT domains
4. **Time** — Planning horizon (short, medium, long-term)

---

## Common Deliverables by Phase

| Deliverable | Primary Phase |
|-------------|--------------|
| **Architecture Vision** | Phase A |
| **Statement of Architecture Work** | Phase A (approved) |
| **Architecture Definition Document** | Phases B, C, D (draft), E (complete) |
| **Architecture Requirements Specification** | Phases B, C, D |
| **Architecture Roadmap** | Phase E (initial), F (final) |
| **Implementation and Migration Plan** | Phase E (draft), F (final) |
| **Architecture Contract** | Phase F (draft), G (signed) |
| **Compliance Assessment** | Phase G |
| **Change Requests** | Phase G, H |

---

## Final Exam Tips

- **Read carefully** — Questions may have subtle distinctions
- **Eliminate wrong answers** — Narrow down options
- **Look for keywords** — "always", "never", "only" are often wrong
- **Remember ADM sequence** — Know what comes before/after each phase
- **Understand purposes** — Know WHY each phase exists, not just WHAT it does
- **Know key outputs** — Which phases produce which deliverables
- **Requirements Management is special** — Continuous, center, doesn't prioritize
- **Phase C has TWO parts** — Data AND Application
- **BDAT order** — Business, Data, Application, Technology (Phases B, C, D)
- **Think practically** — Architecture serves business, not academic exercise
