# ADM Overview

> The Architecture Development Method (ADM) is the **core** of TOGAF — a tested and repeatable process for developing and managing enterprise architecture.

---

## What is the ADM?

The ADM is a **step-by-step method** for:
- Developing enterprise architecture
- Managing the lifecycle of architecture
- Deriving organization-specific architectures that address business requirements

The ADM is specifically designed to be:
- **Iterative** — can be applied at different levels
- **Cyclical** — continuous improvement through repeated cycles
- **Flexible** — can be adapted to organizational needs

---

## ADM Phases at a Glance

| Phase | Name | Purpose |
|-------|------|---------|
| **Preliminary** | Framework & Principles | Prepare organization for successful EA projects |
| **A** | Architecture Vision | Define scope, stakeholders, and high-level vision |
| **B** | Business Architecture | Develop business capabilities and processes |
| **C** | Information Systems | Develop Data and Application architectures |
| **D** | Technology Architecture | Define required technology platforms |
| **E** | Opportunities & Solutions | Identify implementation approach and projects |
| **F** | Migration Planning | Create detailed implementation roadmap |
| **G** | Implementation Governance | Ensure architecture compliance during delivery |
| **H** | Change Management | Manage architecture changes post-implementation |
| **Requirements** | Requirements Management | Continuous management of architecture requirements |

---

## ADM Cycle Diagram

```
                    Preliminary
                         ↓
    ┌───────────────────────────────────────┐
    │                                       │
    │         A. Architecture Vision        │
    │                  ↓                    │
    │         B. Business Architecture      │
    │                  ↓                    │
    │    C. Information Systems (Data+App)  │
    │                  ↓                    │
    │        D. Technology Architecture     │
    │                  ↓                    │
    │      E. Opportunities & Solutions     │
    │                  ↓                    │
    │         F. Migration Planning         │
    │                  ↓                    │
    │      G. Implementation Governance     │
    │                  ↓                    │
    │       H. Architecture Change Mgmt     │
    │                  ↓                    │
    └───────────────────┬───────────────────┘
                        │
              Requirements Management
                  (Central Hub)
```

---

## Key ADM Characteristics

### 1. Requirements Management is Central
- The **Requirements Management** phase sits at the center of the ADM
- It operates **continuously** throughout all phases
- Requirements are identified, stored, and fed into/out of relevant phases
- Does NOT prioritize requirements — this is done within each ADM phase

### 2. Iteration
The ADM supports iteration at multiple levels:
- **Across phases** — can cycle back to earlier phases based on findings
- **Within a phase** — can iterate within a phase to refine outputs
- **Across the entire cycle** — can run multiple ADM cycles for different scopes

### 3. Levels of Architecture
The ADM can be applied at different levels:
- **Enterprise-wide** — covering the entire organization
- **Segment** — focused on a specific business unit or domain
- **Capability** — addressing a specific business capability
- **Project** — supporting a particular initiative

### 4. Adaptation
Organizations should **adapt the ADM** to their specific needs by:
- Tailoring terminology to match organizational language
- Modifying outputs to align with existing processes
- Adjusting phases based on project scope
- Integrating with other frameworks (e.g., Agile, SCRUM)

---

## Inputs, Steps, and Outputs

Each ADM phase follows a consistent pattern:

| Element | Description |
|---------|-------------|
| **Objectives** | What the phase aims to achieve |
| **Inputs** | Documents and artifacts required to start |
| **Steps** | Sequence of activities to perform |
| **Outputs** | Deliverables and artifacts produced |

Understanding the **inputs → steps → outputs** flow for each phase is critical for the foundation exam.

---

## ADM and Architecture Landscape

The ADM produces architecture at different abstraction levels:

| Level | Description | Horizon |
|-------|-------------|---------|
| **Strategic Architecture** | Long-term, directional view | 3-5 years |
| **Segment Architecture** | Specific business unit or capability | 1-3 years |
| **Capability Architecture** | Detailed architecture for specific capability | 6-12 months |

---

## ADM Guidelines and Techniques

TOGAF provides supporting guidelines and techniques for applying the ADM:

| Guideline/Technique | Purpose |
|---------------------|---------|
| **Architecture Principles** | Guide decision-making throughout ADM |
| **Stakeholder Management** | Identify and engage stakeholders effectively |
| **Architecture Patterns** | Reusable solutions to common problems |
| **Gap Analysis** | Identify differences between baseline and target |
| **Migration Planning** | Create transition architectures and roadmaps |
| **Business Transformation Readiness** | Assess organizational readiness for change |
| **Risk Management** | Identify and mitigate architecture risks |
| **Capability-Based Planning** | Focus on business capabilities |

---

## Exam Tips

- Know the **purpose and objectives** of each phase
- Understand which phase produces which **deliverables**
- Remember that **Requirements Management** is continuous and central
- Recognize that the ADM is **iterative and flexible**
- Be familiar with the **sequence** of phases (Preliminary → A → B → C → D → E → F → G → H)
- Understand the relationship between **baseline** and **target** architectures
- Know that Phase C addresses **both Data and Application** architectures
