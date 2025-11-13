# Phase B: Business Architecture

> Phase B develops the **Business Architecture** that shows how the enterprise needs to operate to achieve its business goals and respond to strategic drivers.

---

## Purpose

Phase B creates a detailed understanding of the business architecture required to support the Architecture Vision, focusing on:
- Business strategy and capabilities
- Organizational structure and roles
- Business processes and functions
- Information flows and value chains

This phase addresses the **Statement of Architecture Work** and delivers a Target Business Architecture.

---

## Objectives

| Objective | Description |
|-----------|-------------|
| **Develop Baseline Business Architecture** | Document current business capabilities, processes, and organization |
| **Develop Target Business Architecture** | Define future business capabilities and processes aligned to vision |
| **Identify gaps** | Analyze differences between baseline and target |
| **Define roadmap components** | Identify candidate projects and initiatives |
| **Validate with stakeholders** | Ensure business architecture addresses stakeholder concerns |

---

## Inputs

| Input | Source |
|-------|--------|
| **Request for Architecture Work** | Phase A |
| **Architecture Vision** | Phase A |
| **Business principles, goals, drivers** | Phase A |
| **Capability Assessment** | Phase A |
| **Communications Plan** | Phase A |
| **Organizational Model for EA** | Preliminary Phase |
| **Architecture Repository** | Reference models, patterns, frameworks |

---

## Steps

### 1. Select Reference Models, Viewpoints, and Tools
- Choose appropriate reference models (e.g., value chain, capability model)
- Select relevant viewpoints for stakeholders
- Identify modeling tools and techniques
- Review industry frameworks and standards

### 2. Develop Baseline Business Architecture Description
- Document current business strategy
- Capture baseline capabilities
- Model as-is business processes
- Document current organization structure
- Understand current information flows

### 3. Develop Target Business Architecture Description
- Define future business strategy alignment
- Model target business capabilities
- Design to-be business processes
- Define future organizational structure
- Map information flows in target state

### 4. Perform Gap Analysis
- Compare baseline vs. target business architecture
- Identify gaps in capabilities, processes, organization
- Categorize gaps by impact and priority
- Document dependencies between gaps

### 5. Define Roadmap Components
- Identify work packages to address gaps
- Prioritize based on business value and dependencies
- Create high-level implementation sequence
- Align with enterprise portfolio

### 6. Resolve Impacts Across Architecture Landscape
- Assess impact on existing architectures
- Identify conflicts or dependencies
- Ensure consistency with strategic architecture
- Update architecture landscape accordingly

### 7. Conduct Stakeholder Review
- Present business architecture to stakeholders
- Validate that concerns are addressed
- Gather feedback and incorporate changes
- Obtain sign-off on baseline and target

### 8. Finalize Business Architecture
- Update Architecture Definition Document
- Document architecture decisions and rationale
- Complete business architecture views
- Update Architecture Repository

### 9. Create Architecture Definition Document
- Document approved baseline and target architectures
- Include all relevant views and models
- Capture assumptions and constraints
- Record architecture decisions

---

## Outputs

| Output | Description |
|--------|-------------|
| **Draft Architecture Definition Document** | Updated with detailed baseline and target Business Architecture |
| **Draft Architecture Requirements Specification** | Business architecture requirements and constraints |
| **Business Architecture components of Architecture Roadmap** | Work packages and initiatives for business transformation |

---

## Business Architecture Components

### 1. Business Strategy
- Strategic direction and objectives
- Business model and value propositions
- Competitive positioning
- Growth and investment priorities

### 2. Business Capabilities
- What the business is able to do
- Independent of organizational structure
- Hierarchical decomposition
- Mapped to value streams

**Example Business Capabilities:**
- Customer Management
  - Customer Acquisition
  - Customer Service
  - Customer Retention
- Product Management
  - Product Development
  - Product Lifecycle Management
  - Product Marketing

### 3. Value Streams
- End-to-end collection of activities that create value for stakeholders
- Cross-functional and cross-organizational
- Show how capabilities work together to deliver value

**Example Value Stream:** *Order to Cash*
1. Receive Order → 2. Validate Order → 3. Fulfill Order → 4. Deliver Product → 5. Invoice → 6. Receive Payment

### 4. Business Processes
- Sequence of activities that transform inputs to outputs
- May be automated or manual
- Support one or more capabilities

### 5. Organization Structure
- Business units and divisions
- Roles and responsibilities
- Reporting relationships
- Governance structures

### 6. Business Functions
- Grouping of activities by skill or resource
- May map to organizational units
- Examples: Finance, HR, Marketing, Operations

### 7. Business Services
- Well-defined business functionality
- Consumed by customers, partners, or other services
- Examples: Credit Check Service, Pricing Service

### 8. Information Flows
- How information moves through the business
- What information is exchanged between processes
- Information creation, usage, and archival

---

## Key Modeling Techniques

### 1. Business Capability Mapping
Create hierarchical map of business capabilities.

```
Enterprise Capabilities
├── Customer Management
│   ├── Customer Acquisition
│   ├── Customer Onboarding
│   ├── Customer Service
│   └── Customer Retention
├── Product Management
│   ├── Product Development
│   ├── Product Marketing
│   └── Product Lifecycle
└── Operations Management
    ├── Supply Chain
    ├── Manufacturing
    └── Quality Assurance
```

### 2. Value Stream Mapping
Map end-to-end value delivery:

| Stage | Activities | Capabilities Used | Information Exchanged |
|-------|------------|-------------------|----------------------|
| Initiate | Receive customer request | Customer Management | Order details |
| Validate | Check inventory, credit | Inventory Mgmt, Finance | Stock levels, credit score |
| Execute | Fulfill and ship | Operations, Logistics | Shipping details |
| Complete | Invoice and collect | Finance, Collections | Invoice, payment |

### 3. Business Process Modeling
Model processes using BPMN or similar:
- Swimlanes for roles/systems
- Activities and decision points
- Information inputs and outputs
- Exception handling

### 4. Organizational Charts
- Show reporting structures
- Indicate roles and responsibilities
- Map to capabilities and processes

---

## Gap Analysis

Identify what needs to change:

| Baseline State | Target State | Gap | Impact | Priority |
|----------------|--------------|-----|--------|----------|
| Manual order processing | Automated order processing | Requires new system | High efficiency gain | High |
| Regional customer data | Centralized customer data | Data consolidation needed | Improved customer view | Medium |
| Product-centric organization | Customer-centric organization | Org redesign required | Cultural change needed | High |

Gap categories:
- **New capability** — Not present in baseline
- **Enhanced capability** — Exists but needs improvement
- **Eliminated capability** — Present in baseline, not needed in target
- **Unchanged capability** — Remains the same

---

## Business Architecture Views

Create views for different stakeholders:

| Viewpoint | Stakeholders | Focus |
|-----------|--------------|-------|
| **Business Capability Map** | Executives, Strategy | What the business can do |
| **Value Stream View** | Business Leaders | How value is created |
| **Process Flow View** | Process Owners | How work gets done |
| **Organization View** | HR, Management | Who does what |
| **Business Service View** | Business Analysts | What services are offered |
| **Information Flow View** | Data Architects | What information flows where |

---

## Relationship to Other Phases

| Phase | Relationship |
|-------|-------------|
| **Phase A** | Vision guides business architecture scope and direction |
| **Phase C** | Business architecture drives data and application requirements |
| **Phase D** | Business processes influence technology platform needs |
| **Phase E** | Business roadmap components inform solution planning |
| **Requirements Mgmt** | Business requirements are captured and managed continuously |

Phase B may iterate back to Phase A if:
- Business architecture reveals new scope or constraints
- Stakeholder concerns change
- Business drivers shift during development

---

## Exam Tips

- Phase B develops **Business Architecture** — how the enterprise operates
- Focus on **capabilities, processes, organization, value streams**
- Business **capabilities** are "what" the business can do (org-independent)
- **Value streams** show end-to-end value delivery
- Business **processes** are "how" work gets done
- Key output: **Draft Architecture Definition Document** with baseline + target
- **Gap analysis** identifies differences between baseline and target
- Business architecture **drives** data and application requirements
- Common viewpoints: **Capability Map, Value Stream, Process Flow, Organization**
- Phase B addresses the **"B" in BDAT** (Business, Data, Application, Technology)
