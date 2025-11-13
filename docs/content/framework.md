# Content Framework

> The TOGAF Content Framework provides a **structural model** for architecture content, defining the types of artifacts, deliverables, and building blocks produced during architecture development.

---

## Purpose

The Content Framework ensures:
- **Consistency** in architecture outputs across projects
- **Completeness** of architecture work products
- **Clear terminology** for architecture artifacts
- **Structured approach** to creating architecture content
- **Reusability** of architecture components

---

## Content Metamodel

The **Content Metamodel** defines the **core entities** and their relationships in enterprise architecture.

### Core Entities

| Entity | Description |
|--------|-------------|
| **Actor** | Person, organization, or system performing a role |
| **Role** | Responsibilities assumed by an actor |
| **Business Service** | Service supporting business capabilities |
| **Function** | Unit of business capability |
| **Process** | Sequence of activities delivering value |
| **Event** | Organizational state change triggering action |
| **Product** | Output from processes |
| **Data Entity** | Business information object |
| **Application Component** | Modular, deployable unit of software |
| **Technology Component** | Infrastructure element |

### Extensions

The metamodel can be **extended** to include:
- Organization-specific entities
- Industry-specific concepts
- Detailed specializations

---

## Content Categories

TOGAF organizes architecture content into **three primary categories**:

### 1. Deliverables

**Deliverables** are work products formally reviewed, agreed, and signed off by stakeholders.

| Deliverable | Purpose | Key Phases |
|-------------|---------|------------|
| **Architecture Vision** | High-level aspirational description | Phase A |
| **Architecture Definition Document** | Comprehensive architecture description | Phases B, C, D |
| **Architecture Requirements Specification** | Quantified requirements | Phases B, C, D |
| **Architecture Roadmap** | Timeline for implementation | Phases E, F |
| **Implementation and Migration Plan** | Detailed implementation plan | Phases E, F |
| **Architecture Contract** | Agreement for governance | Phases F, G |
| **Compliance Assessment** | Conformance evaluation | Phase G |
| **Statement of Architecture Work** | Scope and approach | Phase A |

Characteristics of deliverables:
- **Contractual** — Formally approved
- **Reviewed** — Subject to stakeholder sign-off
- **Versioned** — Tracked and baselined
- **Managed** — Under configuration control

### 2. Artifacts

**Artifacts** are specific work products describing an aspect of architecture.

#### Artifact Types

| Type | Description | Examples |
|------|-------------|----------|
| **Catalogs** | Lists of things | Organization Catalog, Application Portfolio, Technology Standards |
| **Matrices** | Relationships between things | Stakeholder Map Matrix, Data Entity/Business Function Matrix |
| **Diagrams** | Visual representations | Business Process Diagram, Application Communication Diagram |

#### Common Artifacts by Domain

**Business Architecture:**
- Organization/Actor Catalog
- Business Service/Function Catalog
- Process Flow Diagram
- Business Interaction Matrix
- Business Capability Map

**Data Architecture:**
- Data Entity/Data Component Catalog
- Conceptual/Logical/Physical Data Models
- Data Entity/Business Function Matrix
- Data Lifecycle Diagram
- Data Security Diagram

**Application Architecture:**
- Application Portfolio Catalog
- Interface Catalog
- Application Communication Diagram
- Application/Function Matrix
- Application Deployment Diagram

**Technology Architecture:**
- Technology Standards Catalog
- Technology Portfolio Catalog
- Technology Infrastructure Diagram
- Network Diagram
- Platform Decomposition Diagram

### 3. Building Blocks

**Building Blocks** represent (potentially reusable) components of architecture.

| Type | Description |
|------|-------------|
| **Architecture Building Block (ABB)** | Functional specification (what) |
| **Solution Building Block (SBB)** | Implementation specification (how) |

See [Building Blocks](building-blocks.md) for detailed information.

---

## Architecture Deliverables in Detail

### 1. Architecture Vision

| Content | Purpose |
|---------|---------|
| Problem description | What problem is being solved? |
| Objectives | What is the goal? |
| Baseline summary | Current state |
| Target summary | Desired future state |
| Value proposition | Business benefits |
| Stakeholder map | Who is involved and their concerns |

### 2. Architecture Definition Document (ADD)

Comprehensive definition containing:

| Section | Content |
|---------|---------|
| **Scope** | Boundaries and constraints |
| **Goals and objectives** | What architecture aims to achieve |
| **Architecture Views** | Multiple perspectives for stakeholders |
| **Baseline Architecture** | Current state (for each domain: B, D, A, T) |
| **Target Architecture** | Future state (for each domain: B, D, A, T) |
| **Gap Analysis** | Differences between baseline and target |
| **Impact Assessment** | Effects of changes |

### 3. Architecture Requirements Specification

| Section | Content |
|---------|---------|
| **Success measures** | KPIs and metrics |
| **Architecture requirements** | Standards, principles, patterns to follow |
| **Business requirements** | What business needs |
| **Data requirements** | Data quality, governance, integration |
| **Application requirements** | Functionality and integration |
| **Technology requirements** | Infrastructure, platforms, non-functional |
| **Constraints** | Budget, time, resource, technical limitations |
| **Assumptions** | Dependencies and pre-conditions |

### 4. Architecture Roadmap

| Content | Purpose |
|---------|---------|
| **Work packages** | Grouped initiatives |
| **Transition architectures** | Intermediate states |
| **Timeline** | When initiatives occur |
| **Dependencies** | Sequencing constraints |
| **Milestones** | Key decision/delivery points |

### 5. Implementation and Migration Plan

| Section | Content |
|---------|---------|
| **Project portfolio** | List of implementation projects |
| **Resource plan** | Staffing and budget |
| **Schedule** | Detailed timeline with Gantt chart |
| **Risk register** | Risks and mitigation strategies |
| **Business case** | ROI and value justification |
| **Communications plan** | Stakeholder engagement approach |

---

## Artifacts: Catalogs, Matrices, Diagrams

### Catalogs (Lists)

Catalogs provide **inventories** of architectural elements:

| Catalog | Purpose |
|---------|---------|
| **Organization Catalog** | Organizational units, locations, actors |
| **Role Catalog** | Roles and responsibilities |
| **Business Service Catalog** | Services provided to customers |
| **Application Portfolio Catalog** | All applications in enterprise |
| **Technology Portfolio Catalog** | Technology products in use |
| **Standards Catalog** | Approved standards and versions |

### Matrices (Relationships)

Matrices show **relationships** between architectural elements:

| Matrix | Relates | Purpose |
|--------|---------|---------|
| **Stakeholder Map Matrix** | Stakeholders ↔ Concerns | Ensure concerns are addressed |
| **Actor/Role Matrix** | Actors ↔ Roles | Show who performs what |
| **Business Service/Function Matrix** | Services ↔ Functions | Map services to functions |
| **Data Entity/Function Matrix** | Data ↔ Functions | Show which functions use which data |
| **Application/Function Matrix** | Applications ↔ Functions | Map applications to business functions |
| **Application Communication Matrix** | Applications ↔ Applications | Show integration points |

### Diagrams (Visuals)

Diagrams provide **visual representations**:

| Diagram Type | Purpose | Example |
|--------------|---------|---------|
| **Process Flow** | Show business process steps | Order-to-cash process |
| **Organizational** | Depict structure and reporting | Organization chart |
| **Data Flow** | Show data movement | Data flows between systems |
| **Application Communication** | Show application integration | Integration architecture |
| **Network** | Show network topology | Network diagram |
| **Deployment** | Show where things run | Application deployment view |

---

## Tailoring the Content Framework

Organizations should **adapt** the Content Framework:

### What to Tailor

| Element | Adaptation |
|---------|------------|
| **Deliverables** | Select relevant deliverables for context |
| **Artifacts** | Choose artifacts addressing stakeholder concerns |
| **Level of detail** | Adjust depth based on scope and audience |
| **Terminology** | Use organizational language |
| **Templates** | Create standardized templates |
| **Metamodel** | Extend with organization-specific concepts |

### Tailoring Principles

- **Fit for purpose** — Create only what adds value
- **Stakeholder-driven** — Address stakeholder concerns
- **Proportionate** — Detail appropriate to scope
- **Reusable** — Leverage existing content
- **Consistent** — Follow organizational standards

---

## Architecture Repository Integration

Content Framework outputs are stored in the **Architecture Repository**:

| Repository Component | Content Stored |
|---------------------|----------------|
| **Architecture Metamodel** | Content metamodel and extensions |
| **Architecture Landscape** | Baseline and target architectures |
| **Standards Information Base** | Standards catalogs and specifications |
| **Reference Library** | Templates, patterns, guidelines |
| **Governance Log** | Decisions, compliance assessments, contracts |

---

## Content Framework and ADM

How Content Framework applies across ADM:

| Phase | Key Deliverables | Key Artifacts |
|-------|-----------------|---------------|
| **Preliminary** | Tailored Architecture Framework | Principles Catalog, Stakeholder Map |
| **Phase A** | Architecture Vision, Statement of Architecture Work | Stakeholder Map, Business Capability Map |
| **Phase B** | Architecture Definition Document (Business) | Process Flow, Organization Diagram, Capability Map |
| **Phase C** | Architecture Definition Document (Data + Application) | Data Models, Application Portfolio, Interface Catalog |
| **Phase D** | Architecture Definition Document (Technology) | Network Diagram, Platform Decomposition |
| **Phase E** | Architecture Roadmap (draft) | Work Package Catalog, Transition Architectures |
| **Phase F** | Implementation and Migration Plan | Project Portfolio, Gantt Chart, Business Case |
| **Phase G** | Compliance Assessments, Architecture Contracts | Compliance Reports |
| **Phase H** | Architecture Updates | Change Requests, Lessons Learned |

---

## Exam Tips

- **Content Framework** defines structure for architecture artifacts
- **Three main categories**: Deliverables, Artifacts, Building Blocks
- **Deliverables** are formally reviewed and signed off
- **Artifacts** are specific work products (Catalogs, Matrices, Diagrams)
- **Catalogs** = lists, **Matrices** = relationships, **Diagrams** = visuals
- **Key deliverables**: Architecture Vision, Architecture Definition Document, Requirements Specification, Roadmap, Implementation Plan, Architecture Contract
- **Architecture Definition Document** contains baseline + target for all domains (BDAT)
- **Content Metamodel** defines core entities (Actor, Role, Function, Process, Data Entity, Application, Technology)
- Content Framework can be **tailored** to organizational needs
- Deliverables are stored in **Architecture Repository**
