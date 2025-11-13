# Phase C: Information Systems Architectures

> Phase C develops the **Information Systems Architecture** — comprising both **Data Architecture** and **Application Architecture** — to support the Business Architecture and Architecture Vision.

---

## Overview

Phase C addresses the **information systems** required to support business operations:
- **Data Architecture** — Structure and management of organizational data assets
- **Application Architecture** — Individual applications and their interactions

Phase C can be performed in two approaches:
1. **Sequential** — Data Architecture first, then Application Architecture
2. **Concurrent** — Both developed in parallel

The two architectures are closely related, as applications create, use, and manage data.

---

## Part 1: Data Architecture

### Purpose

Define **how enterprise data is structured, stored, managed, and accessed** to support business requirements and enable effective decision-making.

### Objectives

| Objective | Description |
|-----------|-------------|
| **Develop Baseline Data Architecture** | Document current data assets, structures, and flows |
| **Develop Target Data Architecture** | Define future data structures aligned to business needs |
| **Identify gaps** | Analyze differences between baseline and target data |
| **Define roadmap components** | Identify data-related projects and initiatives |

### Inputs

| Input | Source |
|-------|--------|
| **Request for Architecture Work** | Phase A |
| **Architecture Vision** | Phase A |
| **Business Architecture** | Phase B |
| **Data principles** | Preliminary / Phase A |
| **Architecture Repository** | Reference models, data standards |

### Key Activities

1. **Select Reference Models and Standards**
   - Industry data models (e.g., banking, healthcare)
   - Data management standards
   - Regulatory data requirements

2. **Develop Baseline Data Architecture**
   - Data entities and relationships
   - Current data storage locations
   - Data ownership and stewardship
   - Data quality and governance state

3. **Develop Target Data Architecture**
   - Future data entities and relationships
   - Logical and physical data models
   - Data integration and migration approach
   - Master data management strategy

4. **Perform Gap Analysis**
   - Compare baseline vs. target data architecture
   - Identify data quality, integration, and governance gaps
   - Prioritize data initiatives

### Data Architecture Components

| Component | Description |
|-----------|-------------|
| **Data Entities** | Business objects (Customer, Product, Order) |
| **Data Attributes** | Properties of entities (Customer Name, Order Date) |
| **Relationships** | How entities relate (Customer places Order) |
| **Data Flow** | Movement of data between systems and processes |
| **Data Governance** | Rules, ownership, quality standards |
| **Data Security** | Access controls, classification, privacy |
| **Master Data** | Single source of truth for critical entities |
| **Reference Data** | Lookup values and code lists |

### Data Architecture Views

| View | Purpose | Stakeholders |
|------|---------|--------------|
| **Conceptual Data Model** | High-level entities and relationships | Business stakeholders |
| **Logical Data Model** | Detailed entities, attributes, relationships | Business analysts, architects |
| **Physical Data Model** | Database schemas and storage design | DBAs, developers |
| **Data Flow Diagram** | How data moves through systems | Integration architects |
| **Data Lineage** | Data sources, transformations, destinations | Data governance |
| **Data Security View** | Classification and access controls | Security, compliance |

### Outputs

| Output | Description |
|--------|-------------|
| **Draft Architecture Definition Document** | Updated with baseline and target Data Architecture |
| **Draft Architecture Requirements Specification** | Data requirements and constraints for technology layer |
| **Data Architecture Roadmap Components** | Data migration, integration, MDM projects |

---

## Part 2: Application Architecture

### Purpose

Define **which applications are needed, their interactions, and how they support business functions** to enable efficient and effective operations.

### Objectives

| Objective | Description |
|-----------|-------------|
| **Develop Baseline Application Architecture** | Document current application portfolio and interactions |
| **Develop Target Application Architecture** | Define future application landscape and integration |
| **Identify gaps** | Analyze differences in application capabilities |
| **Define roadmap components** | Identify application development, acquisition, and retirement |

### Inputs

| Input | Source |
|-------|--------|
| **Request for Architecture Work** | Phase A |
| **Architecture Vision** | Phase A |
| **Business Architecture** | Phase B |
| **Data Architecture** | Phase C (if sequential) |
| **Application principles** | Preliminary / Phase A |
| **Architecture Repository** | Reference models, application patterns |

### Key Activities

1. **Select Reference Models and Patterns**
   - Application architecture patterns (microservices, SOA, etc.)
   - Industry reference architectures
   - Integration patterns

2. **Develop Baseline Application Architecture**
   - Current application inventory
   - Application capabilities and functions
   - Application interfaces and integration
   - Application-to-business process mapping

3. **Develop Target Application Architecture**
   - Future application portfolio
   - Application rationalization decisions
   - Target integration architecture
   - Cloud and SaaS strategy

4. **Perform Gap Analysis**
   - Compare baseline vs. target applications
   - Identify redundant, missing, or inadequate applications
   - Prioritize application initiatives

### Application Architecture Components

| Component | Description |
|-----------|-------------|
| **Application Services** | Functional capabilities provided by applications |
| **Application Components** | Modular functional units within applications |
| **Application Interfaces** | APIs, integration points, user interfaces |
| **Application Interactions** | How applications communicate (sync, async, batch) |
| **Application Data** | Data created and used by applications |
| **Application Platform** | Runtime environment (cloud, on-premise, hybrid) |

### Application Architecture Views

| View | Purpose | Stakeholders |
|------|---------|--------------|
| **Application Portfolio** | List of all applications | IT leadership, PMO |
| **Application Capability Map** | What each application can do | Business, architects |
| **Application Communication** | Integration points and protocols | Integration architects |
| **Application-to-Business Matrix** | Which apps support which processes | Business analysts |
| **Application Deployment** | Where applications run | Infrastructure teams |
| **Application Interface Catalog** | All APIs and integration points | Developers, architects |

### Application Patterns

Common architectural patterns:

| Pattern | Description | Use Case |
|---------|-------------|----------|
| **Monolithic** | Single, integrated application | Simple, small-scale applications |
| **Service-Oriented (SOA)** | Coarse-grained services | Enterprise integration |
| **Microservices** | Fine-grained, independent services | Scalable, cloud-native apps |
| **Event-Driven** | Publish-subscribe messaging | Real-time processing |
| **API-First** | APIs as primary interface | Integration ecosystems |

### Outputs

| Output | Description |
|--------|-------------|
| **Draft Architecture Definition Document** | Updated with baseline and target Application Architecture |
| **Draft Architecture Requirements Specification** | Application requirements and constraints for technology layer |
| **Application Architecture Roadmap Components** | Application development, purchase, retirement initiatives |

---

## Data and Application Integration

Data and Application architectures are **interdependent**:

| Relationship | Description |
|--------------|-------------|
| **Applications manage data** | Applications create, update, and delete data |
| **Data drives application design** | Data requirements influence application structure |
| **Integration depends on both** | Data flows through application interfaces |
| **Master data needs application support** | MDM requires application integration |

---

## Gap Analysis

### Data Gaps

| Gap Type | Example |
|----------|---------|
| **Missing data** | Customer segmentation data not captured |
| **Poor data quality** | Duplicate customer records, inconsistent formats |
| **Data silos** | Customer data scattered across 15 systems |
| **Lack of governance** | No data ownership or quality standards |

### Application Gaps

| Gap Type | Example |
|----------|---------|
| **Missing capability** | No CRM system to support sales process |
| **Redundant applications** | Three overlapping inventory systems |
| **Poor integration** | Manual data entry between systems |
| **Legacy technology** | Mainframe applications difficult to maintain |

---

## Roadmap Components from Phase C

Phase C identifies work packages:

| Initiative Type | Example |
|----------------|---------|
| **Data Migration** | Consolidate customer data from 5 databases to 1 |
| **Master Data Management** | Implement MDM for customer and product |
| **Application Development** | Build new customer portal |
| **Application Purchase** | Select and implement CRM SaaS solution |
| **Application Retirement** | Decommission legacy order management system |
| **Integration Development** | Build API gateway for system integration |

---

## Relationship to Other Phases

| Phase | Relationship |
|-------|-------------|
| **Phase B** | Business architecture drives data and application requirements |
| **Phase D** | Information systems requirements influence technology platform choices |
| **Phase E** | Data and application roadmap components inform solution planning |
| **Phase F** | Data migration and application rollout sequenced in migration plan |
| **Requirements Mgmt** | Information systems requirements managed continuously |

Phase C may iterate:
- Between data and application architecture development
- Back to Phase B if new business requirements emerge
- With Phase D as technology constraints become apparent

---

## Exam Tips

- Phase C covers **both Data and Application** architectures (the "DA" in BDAT)
- Can be done **sequentially** (Data then Application) or **concurrently**
- **Data Architecture** = structure, storage, management of data assets
- **Application Architecture** = applications and their interactions
- Data and Application architectures are **interdependent**
- Key outputs: Updated **Architecture Definition Document** with both architectures
- **Gap analysis** identifies what needs to change (new, enhanced, eliminated, unchanged)
- Phase C produces **roadmap components** for data and application initiatives
- Common data views: **Conceptual/Logical/Physical data models, Data flow diagrams**
- Common application views: **Portfolio, Capability map, Integration diagram**
- Phase C builds on **Business Architecture** from Phase B
- Phase C requirements feed into **Technology Architecture** in Phase D
