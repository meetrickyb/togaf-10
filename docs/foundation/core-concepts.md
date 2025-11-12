# Core Concepts & Terminology

> The TOGAF® Standard, 10th Edition defines *what* enterprise architecture is, *why* it matters, and *how* to manage it consistently across the enterprise.

---

## What is Enterprise Architecture (EA)

**Enterprise Architecture** describes the structure and operation of an organization through four primary architecture domains:

| Domain | Focus | Example |
|---------|--------|---------|
| **Business** | Strategy, organization, processes, governance | Target Operating Model, Business Capability Map |
| **Data** | Logical & physical data assets, relationships, governance | Data Models, Data Flow Diagrams |
| **Application** | Individual systems and their interactions | Application Portfolio, Integration Map |
| **Technology** | Infrastructure, platforms, and networks | Cloud Topology, Network Architecture |

TOGAF often abbreviates this model as **BDAT** (Business, Data, Application, Technology).
Entire Enterprise or one or more specific areas of interest
TOGAF standard consideres Enterprise as a **system**
**Architecture** is the fundamental concepts or properties of a system in its environment embodied in its elements, relationshipts and in the principles of its design & evolution [ISO/IEC/IEEE 42010: 2011]

![Architecture Domains](image.png)
---

## Architecture States

| State | Definition | 
|-------|------------|
|**Baseline Architecture**| Current state acting as reference for all change|
|**Resting Architecture** | State where the entperprise receives value if all change activity is suspended |


## The Architecture Development Method (ADM)
ADM is the **core of TOGAF** — a step-by-step approach for developing and managing enterprise architecture.

**Phases:**
- Preliminary – Prepare & define architecture capability  
- **A. Architecture Vision** – Set goals, scope, and stakeholders  
- **B. Business Architecture** – Model business processes, capabilities  
- **C. Information Systems Architecture** – Split into Data + Application  
- **D. Technology Architecture** – Identify required technology platforms  
- **E. Opportunities & Solutions** – Create initial implementation roadmap  
- **F. Migration Planning** – Prioritize and sequence transitions  
- **G. Implementation Governance** – Ensure solutions conform to architecture  
- **H. Architecture Change Management** – Maintain architecture through change  
- **Requirements Management** – Central hub interacting with every phase

Key points to remember for the exam:
- ADM is **iterative** and **cyclical**.  
- Each phase has **inputs**, **steps**, and **outputs (deliverables)**.  
- The **Requirements Management** phase feeds and is fed by all others.

---
## Architecture Scope
- Four dimensions define and limit the scope of an architecture
- **A. Enterprise Scope (Breadth)** - What is the full extent of the enterprise and what part of that extent will tis architecting effort deal with?
        - Organizations
        - Business Unit
        - Departments
        - Processes
- **B. Level of Detail (Depth)** - To what level of detail should the architecting effort go?
        - How much architecture is enough?
- **C. Architecture Domains** - Which domains should be looked at?
        - Business
        - Data
        - Application
        - Technology
- **D. Time Period (Planning Horizon)** - What is the time period that needs to be articulated for the Architecture Vision?
---

## Key TOGAF Concepts

| Concept | Description |
|----------|--------------|
| **Architecture Views / Viewpoints** | A *viewpoint* defines how to look at the system from a stakeholder’s perspective; a *view* is the actual representation. |
| **Building Block** | Reusable component of business, data, application, or technology architecture. |
| **Artifact** | Individual work product such as a diagram, matrix, or catalog. |
| **Deliverable** | Packaged output (report, model, specification) reviewed and approved. |
| **Architecture Repository** | Central store of all architectural outputs and assets. |
| **Enterprise Continuum** | A classification of architectural assets from generic → specific. |
| **Architecture Capability** | Organizational ability (roles, processes, tools, governance) to perform EA. |
| **Architecture Governance** | Framework and processes to ensure compliance, accountability, and traceability. |

---

## Architecture Principles

A principle = *guiding statement* for decision-making.  
Each should have: **Name, Statement, Rationale, Implications.**

Examples:
- *Data is an Enterprise Asset*  
- *Reuse before Buy, Buy before Build*  
- *Security by Design*

---

## Iteration and Levels

TOGAF 10 emphasizes flexibility:
- **Iteration** across ADM cycles (e.g., revisit Vision after B–D).  
- **Levels** – corporate, segment, capability, or project.  
- **Partitioning** – breaking architecture into manageable sections.

---

### Quick Exam Reminders

- Learn **terminology** precisely — TOGAF is vocabulary-driven.  
- Understand **purpose, objectives, inputs, and outputs** of each ADM phase.  
- Remember that **Requirements Management** is central and continuous.  
- Differentiate between **view**, **viewpoint**, **artifact**, **deliverable**, and **building block**.
