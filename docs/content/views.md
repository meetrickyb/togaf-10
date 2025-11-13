# Views & Viewpoints

> Views and Viewpoints enable **stakeholder-specific perspectives** of the architecture, ensuring concerns are addressed and architecture is communicated effectively.

---

## Purpose

Views and Viewpoints provide:
- **Stakeholder-specific** representations of architecture
- **Focused communication** addressing particular concerns
- **Simplified complexity** by showing relevant aspects only
- **Multiple perspectives** of the same architecture
- **Alignment with ISO/IEC/IEEE 42010** standard

---

## Key Concepts

### ISO/IEC/IEEE 42010 Standard

TOGAF embraces the concepts from **ISO/IEC/IEEE 42010:2011** for architectural description:

| Concept | Definition |
|---------|------------|
| **Stakeholder** | Individual, team, or organization with interests in the system |
| **Concern** | Interest, need, or objective regarding the system |
| **Architecture View** | Representation of the architecture from specific perspective |
| **Architecture Viewpoint** | Conventions for creating, interpreting, and using a view |
| **Model Kind** | Conventions for a type of modeling |

---

## Stakeholders

**Stakeholders** are individuals or groups with interests in the architecture.

### Common Stakeholder Types

| Stakeholder | Role | Typical Concerns |
|-------------|------|------------------|
| **CEO/Board** | Strategic direction | Business value, ROI, competitive advantage |
| **CIO** | IT strategy | IT alignment, cost, risk, innovation |
| **Business Leaders** | Business operations | Process efficiency, customer satisfaction, agility |
| **Project Managers** | Delivery | Scope, schedule, resources, dependencies |
| **Architects** | Architecture design | Standards, patterns, technical coherence |
| **Developers** | Implementation | Technical specifications, interfaces, tools |
| **Operations** | Running systems | Availability, performance, supportability |
| **Users** | Using systems | Usability, functionality, reliability |
| **Regulators** | Compliance | Regulatory adherence, data privacy, security |
| **Vendors/Partners** | Collaboration | Integration points, contracts, SLAs |

---

## Concerns

**Concerns** are interests, needs, or objectives stakeholders have regarding the system.

### Examples of Concerns

| Concern Category | Examples |
|------------------|----------|
| **Functional** | What functionality is provided? How are processes supported? |
| **Performance** | Response time, throughput, capacity |
| **Security** | Access control, data protection, compliance |
| **Availability** | Uptime, disaster recovery, resilience |
| **Maintainability** | How easy to modify, support, operate? |
| **Scalability** | Can it grow with business? |
| **Cost** | TCO, ROI, budget constraints |
| **Risk** | What risks exist? How are they mitigated? |
| **Compliance** | Does it meet regulations? |
| **Integration** | How does it connect to other systems? |

Concerns drive the creation of views — **each view addresses specific concerns**.

---

## Architecture Views

An **Architecture View** is a representation of the overall architecture addressing specific stakeholder concerns.

### Characteristics

| Characteristic | Description |
|----------------|-------------|
| **Stakeholder-specific** | Tailored to audience |
| **Concern-driven** | Addresses particular interests |
| **Selective** | Shows only relevant information |
| **Consistent** | Aligned with other views of same architecture |

### Common Views Examples

| View Name | Stakeholders | Focus | Artifacts |
|-----------|--------------|-------|-----------|
| **Business Capability View** | Executives | What can the business do? | Capability Map, Heatmap |
| **Process View** | Business Owners | How work gets done | Process Diagrams, Swimlanes |
| **Information Flow View** | Data Analysts | How information moves | Data Flow Diagrams |
| **Application Portfolio View** | CIO, Portfolio Mgmt | What applications exist? | Application Catalog, Rationalization Matrix |
| **Integration View** | Architects | How systems connect? | Integration Diagram, Interface Catalog |
| **Infrastructure View** | Operations | What infrastructure exists? | Network Diagram, Deployment View |
| **Security View** | Security Officer | How is system secured? | Security Architecture, Access Control |
| **Deployment View** | Operations | Where do things run? | Deployment Diagram, Environment View |

---

## Architecture Viewpoints

An **Architecture Viewpoint** defines the conventions for creating and using a view.

### Viewpoint Components

A viewpoint specification includes:

| Component | Description |
|-----------|-------------|
| **Name** | Identifier for the viewpoint |
| **Stakeholders** | Who uses this view |
| **Concerns** | What concerns does it address |
| **Model Kinds** | What types of models are used (UML, BPMN, ArchiMate) |
| **Conventions** | Notations, standards, modeling languages |
| **Analysis techniques** | How to analyze the view |
| **Sources** | Where information comes from |

### Example Viewpoint: Application Communication Viewpoint

| Element | Description |
|---------|-------------|
| **Name** | Application Communication Viewpoint |
| **Stakeholders** | Application Architects, Integration Architects, Developers |
| **Concerns** | How applications interact, integration complexity, data flows |
| **Model Kinds** | Component diagrams, sequence diagrams, interface catalogs |
| **Conventions** | UML component diagrams or ArchiMate |
| **Analysis** | Identify integration bottlenecks, single points of failure |
| **Sources** | Application Architecture (Phase C), Technology Architecture (Phase D) |

---

## Creating Views and Viewpoints

### Step 1: Identify Stakeholders
- Determine who has interest in the architecture
- Categorize stakeholders by role and influence
- Map stakeholders to architecture domains

### Step 2: Identify Concerns
- Gather stakeholder concerns through interviews, workshops
- Document specific interests and objectives
- Prioritize concerns by importance and impact

### Step 3: Select or Define Viewpoints
- Choose existing viewpoints addressing concerns
- Define new viewpoints if needed
- Ensure viewpoints align with stakeholder needs

### Step 4: Create Views
- Apply viewpoint conventions to create view
- Use appropriate modeling tools and notations
- Ensure view addresses targeted concerns

### Step 5: Validate Views
- Review with stakeholders
- Confirm concerns are addressed
- Refine based on feedback

---

## Relationship Between Views, Viewpoints, and Architecture

```
Architecture (Complete Description)
        │
        ├── View 1 (addresses Concern A, B)
        │   └── Created using Viewpoint X
        │
        ├── View 2 (addresses Concern C, D)
        │   └── Created using Viewpoint Y
        │
        └── View 3 (addresses Concern E, F)
            └── Created using Viewpoint Z
```

- **One architecture**, many views
- **Views** are projections of the architecture
- **Viewpoints** are templates for creating views
- **All views** must be consistent with each other

---

## TOGAF Viewpoint Library

TOGAF doesn't mandate specific viewpoints but provides guidance.

### Common Viewpoint Categories

| Category | Focus | Examples |
|----------|-------|----------|
| **Business Viewpoints** | Business operations | Process, Organization, Capability |
| **Data Viewpoints** | Information structure | Conceptual/Logical/Physical Data Model |
| **Application Viewpoints** | Software systems | Portfolio, Communication, Deployment |
| **Technology Viewpoints** | Infrastructure | Network, Platform, Security |

Organizations can:
- Use industry-standard viewpoints (e.g., from frameworks)
- Adopt modeling language viewpoints (ArchiMate, UML)
- Create custom viewpoints for specific needs

---

## ArchiMate Integration

**ArchiMate** is an open standard modeling language for enterprise architecture complementary to TOGAF.

### ArchiMate Viewpoints

ArchiMate defines 15+ standard viewpoints:

| Viewpoint | Purpose |
|-----------|---------|
| **Organization Viewpoint** | Organizational structure and roles |
| **Business Process Viewpoint** | Business processes and events |
| **Application Cooperation Viewpoint** | Application interactions |
| **Application Usage Viewpoint** | Services applications provide to business |
| **Technology Viewpoint** | Infrastructure and platforms |
| **Layered Viewpoint** | All layers (Business, Application, Technology) |
| **Migration Viewpoint** | Transition from baseline to target |

ArchiMate provides:
- **Standard notation** for architecture modeling
- **Predefined viewpoints** addressing common concerns
- **Tool support** for creating and maintaining views
- **Alignment with TOGAF** content framework

---

## Stakeholder Management Using Views

### Stakeholder Map Matrix

| Stakeholder | Key Concerns | Views Provided | Engagement Level |
|-------------|--------------|----------------|------------------|
| CFO | Cost, ROI | Business Case, Cost/Benefit Analysis | High — Approve funding |
| CIO | IT strategy, risk | Technology Roadmap, Risk Assessment | High — Sponsor |
| Business Unit Leaders | Process efficiency | Process View, Capability Heatmap | Medium — Review and input |
| Developers | Technical details | Application Design, Interface Specs | Low — Implement |

Views enable **targeted communication** — each stakeholder gets information relevant to their concerns.

---

## View Consistency

All views of the same architecture must be **mutually consistent**.

### Consistency Checks

| Check | Purpose |
|-------|---------|
| **Element consistency** | Same element represented consistently across views |
| **Relationship consistency** | Relationships between elements valid in all views |
| **Constraint consistency** | Constraints satisfied across views |
| **Naming consistency** | Consistent terminology and naming |

### Managing Consistency

- Use **single source of truth** (Architecture Repository)
- Employ **modeling tools** with consistency checking
- Perform **cross-view reviews**
- Maintain **traceability** between views

---

## Views in ADM Phases

| Phase | Key Views Developed |
|-------|---------------------|
| **Phase A** | Stakeholder Map, High-Level Business Capability View |
| **Phase B** | Organization View, Process View, Business Service View, Capability Map |
| **Phase C (Data)** | Conceptual Data Model, Logical Data Model, Data Flow View |
| **Phase C (App)** | Application Portfolio, Application Communication, Application-to-Function Matrix |
| **Phase D** | Infrastructure View, Network Diagram, Platform Decomposition, Deployment View |
| **Phase E** | Transition Architecture Views |
| **Phase F** | Migration View, Implementation Roadmap |

---

## Exam Tips

- **Views** are stakeholder-specific representations of architecture
- **Viewpoints** are conventions/templates for creating views
- **Concerns** are stakeholder interests that views address
- TOGAF embraces **ISO/IEC/IEEE 42010** standard for views and viewpoints
- **One architecture, multiple views** — each addressing different concerns
- Views must be **mutually consistent**
- Common viewpoint types: **Business, Data, Application, Technology**
- **ArchiMate** provides standard notation and viewpoints complementing TOGAF
- Viewpoints define: **stakeholders, concerns, model kinds, conventions, analysis techniques**
- Views enable **targeted communication** to stakeholders
- Stakeholders have **concerns** → Viewpoints define **how to create views** → Views **address concerns**
- Views are created throughout **ADM phases** to address stakeholder needs
