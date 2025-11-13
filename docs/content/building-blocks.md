# Building Blocks

> Building Blocks are **reusable components** of business, IT, or architectural capability that can be combined to deliver architectures and solutions.

---

## Purpose

Building Blocks enable:
- **Reusability** — Leverage existing components
- **Modularity** — Decompose complex systems into manageable units
- **Clarity** — Clear definition of architectural components
- **Communication** — Common language for architects and implementers
- **Traceability** — Link architecture to implementation

---

## What is a Building Block?

A **Building Block** represents a **potentially reusable component** of enterprise capability.

### Characteristics

| Characteristic | Description |
|----------------|-------------|
| **Package of functionality** | Delivers specific capability |
| **Well-defined interfaces** | Clear boundaries and interactions |
| **Interoperable** | Works with other building blocks |
| **Potentially reusable** | Can be leveraged across multiple contexts |
| **Replaceable** | Can be swapped with alternative implementations |
| **Published specification** | Documented capabilities and interfaces |

Building Blocks exist at **multiple levels of abstraction** — from high-level business capabilities to specific technology products.

---

## Types of Building Blocks

### 1. Architecture Building Blocks (ABBs)

**Architecture Building Blocks** define **WHAT** functionality is required.

| Aspect | Description |
|--------|-------------|
| **Definition** | Specification of required capability |
| **Focus** | Functional requirements and interfaces |
| **Abstraction** | Technology-independent where possible |
| **Source** | Architecture Continuum |
| **Purpose** | Define architecture requirements |
| **Examples** | "Customer Management Service", "Order Processing Function", "Data Integration Service" |

ABB Characteristics:
- **Functional specification** (what it does)
- **Interfaces** (how it interacts)
- **Interoperability requirements** (what it connects to)
- **Not** tied to specific products or implementation

### 2. Solution Building Blocks (SBBs)

**Solution Building Blocks** define **HOW** functionality is implemented.

| Aspect | Description |
|--------|-------------|
| **Definition** | Implementation of ABB requirements |
| **Focus** | Specific products, technologies, configurations |
| **Abstraction** | Concrete, implementation-specific |
| **Source** | Solutions Continuum |
| **Purpose** | Implement architecture |
| **Examples** | "Salesforce CRM", "SAP ERP Order Module", "MuleSoft ESB" |

SBB Characteristics:
- **Product or code specification** (vendor, version)
- **Implementation details** (configuration, customization)
- **Performance characteristics** (non-functional specifics)
- **Deployment details** (where and how it runs)

---

## Relationship Between ABBs and SBBs

```
Architecture Building Block (ABB)
         ↓
    "What" is needed
         ↓
   (maps to one or more)
         ↓
Solution Building Block (SBB)
         ↓
     "How" it's implemented
```

### Example Mapping

| ABB | Description | Possible SBBs |
|-----|-------------|---------------|
| **Customer Relationship Mgmt** | Capability to manage customer interactions | Salesforce CRM, Microsoft Dynamics 365, Custom CRM Application |
| **Authentication Service** | Capability to verify user identity | Active Directory, Okta, Auth0, Custom IAM |
| **Data Integration** | Capability to move data between systems | MuleSoft, Dell Boomi, Apache Camel, Custom ETL |

**One ABB** may be realized by **multiple SBBs** (alternatives or combinations).

**One SBB** may realize **multiple ABBs** (a product fulfilling several capabilities).

---

## Building Block Specification

Each Building Block should be documented with:

### ABB Specification

| Element | Description |
|---------|-------------|
| **Name** | Clear identifier |
| **Description** | What it does and why |
| **Functionality** | Specific capabilities provided |
| **Interfaces** | How it interacts (inputs, outputs, protocols) |
| **Dependencies** | Other building blocks it requires |
| **Attributes** | Key characteristics (performance, security, etc.) |
| **Constraints** | Limitations or requirements |

### SBB Specification

| Element | Description |
|---------|-------------|
| **Name** | Product or component name |
| **Version** | Specific version or release |
| **Vendor** | Provider of the solution |
| **Implementation details** | Configuration, customization |
| **Performance characteristics** | Actual non-functional performance |
| **Deployment model** | On-premise, cloud, SaaS, etc. |
| **Interfaces** | Technical integration points (APIs, protocols) |
| **Dependencies** | Other SBBs or infrastructure required |
| **Cost** | Licensing, operational costs |

---

## Building Blocks by Architecture Domain

### Business Building Blocks

| Type | ABB Example | SBB Example |
|------|-------------|-------------|
| **Business Service** | Customer Onboarding Service | Onboarding Portal + CRM Integration |
| **Business Process** | Order Fulfillment Process | Fulfillment Workflow in ERP System |
| **Business Function** | Inventory Management | SAP Inventory Module |

### Data Building Blocks

| Type | ABB Example | SBB Example |
|------|-------------|-------------|
| **Data Entity** | Customer Master Data | Customer Table in PostgreSQL |
| **Data Service** | Customer Data Access Service | Customer API (REST) |
| **Data Component** | Product Catalog | Product Database + Cache Layer |

### Application Building Blocks

| Type | ABB Example | SBB Example |
|------|-------------|-------------|
| **Application Service** | Payment Processing Service | Stripe Payment Gateway |
| **Application Component** | Shopping Cart | E-commerce Platform Cart Module |
| **Application Function** | Search Capability | Elasticsearch Service |

### Technology Building Blocks

| Type | ABB Example | SBB Example |
|------|-------------|-------------|
| **Platform Service** | Application Runtime | Kubernetes Cluster |
| **Infrastructure Service** | Compute Service | AWS EC2 Instances |
| **Network Service** | Load Balancing | AWS Application Load Balancer |

---

## Building Block Development Process

### From ABB to SBB

1. **Define ABB** (during Phases B, C, D)
   - Specify required functionality
   - Define interfaces and dependencies
   - Document constraints and attributes

2. **Identify Candidate SBBs** (during Phase E)
   - Reuse existing SBBs from portfolio
   - Purchase COTS products
   - Build custom SBBs

3. **Select SBB** (during Phases E, F)
   - Evaluate alternatives (make vs. buy vs. reuse)
   - Assess fit with ABB requirements
   - Consider cost, risk, alignment

4. **Implement SBB** (during Phase G)
   - Configure or develop SBB
   - Integrate with other SBBs
   - Validate against ABB specification

---

## Building Block Reuse

### Benefits of Reuse

| Benefit | Description |
|---------|-------------|
| **Reduced cost** | Avoid redevelopment of existing capability |
| **Faster delivery** | Leverage proven components |
| **Lower risk** | Use battle-tested solutions |
| **Consistency** | Standardize across enterprise |
| **Interoperability** | Components designed to work together |
| **Ease of maintenance** | Centralized updates benefit all users |

### Reuse Strategy

**Reuse before Buy, Buy before Build** — a common architecture principle.

| Approach | When to Use | Example |
|----------|-------------|---------|
| **Reuse** | Existing SBB meets requirements | Reuse enterprise authentication service |
| **Buy (COTS)** | No existing solution, commercial option available | Purchase CRM SaaS |
| **Build** | Unique requirements, strategic differentiator | Develop proprietary pricing algorithm |

---

## Building Block Patterns

Common architectural patterns as building blocks:

| Pattern | Description | Use Case |
|---------|-------------|----------|
| **Layered** | Organize into presentation, business, data layers | Traditional enterprise applications |
| **Microservices** | Fine-grained, independent services | Cloud-native, scalable applications |
| **API Gateway** | Centralized entry point for APIs | API management, security, routing |
| **Event-Driven** | Components communicate via events | Real-time processing, decoupled systems |
| **Service Mesh** | Infrastructure layer for service communication | Microservices observability, security |

---

## Building Blocks and Enterprise Continuum

Building Blocks relate to the **Enterprise Continuum**:

| Continuum Level | Building Blocks |
|-----------------|-----------------|
| **Foundation** | Generic ABBs applicable across industries |
| **Common Systems** | ABBs for common IT functions (identity, integration) |
| **Industry** | Industry-specific ABBs (banking, healthcare) |
| **Organization-Specific** | ABBs tailored to enterprise needs |

SBBs follow a similar continuum in the **Solutions Continuum**.

See [Enterprise Continuum & Repository](continuum-repo.md) for details.

---

## Building Blocks and ADM Phases

| Phase | Building Block Activity |
|-------|------------------------|
| **Phase A** | Identify high-level building block requirements |
| **Phase B** | Define business building blocks (ABBs) |
| **Phase C** | Define data and application building blocks (ABBs) |
| **Phase D** | Define technology building blocks (ABBs) |
| **Phase E** | Identify candidate solution building blocks (SBBs); make vs. buy decisions |
| **Phase F** | Plan implementation of selected SBBs |
| **Phase G** | Implement, integrate, and validate SBBs |
| **Phase H** | Monitor and optimize building blocks |

Building block definition **progresses iteratively** — starting high-level in Phase A and becoming detailed through Phases B, C, D.

---

## Building Block Catalog

Maintain a **Building Block Catalog** in the Architecture Repository:

| Catalog | Purpose |
|---------|---------|
| **ABB Catalog** | List of architecture building blocks |
| **SBB Catalog** | Inventory of available solution building blocks |
| **Mapping Matrix** | Relationships between ABBs and SBBs |

Catalog benefits:
- **Discoverability** — Architects find reusable components
- **Standardization** — Promote approved building blocks
- **Portfolio management** — Track investment in building blocks
- **Rationalization** — Identify redundant or underutilized components

---

## Common Pitfalls

| Pitfall | Consequence | Prevention |
|---------|-------------|------------|
| **Too coarse-grained** | Building blocks too large to reuse | Decompose into finer-grained components |
| **Too fine-grained** | Excessive complexity, overhead | Consolidate into cohesive units |
| **Unclear interfaces** | Difficult to integrate | Define clear, published interfaces |
| **Tight coupling** | Dependencies hinder reuse | Minimize dependencies, use loose coupling |
| **Lack of documentation** | Cannot understand or reuse | Document specifications thoroughly |
| **No reuse culture** | Everyone builds from scratch | Promote reuse through governance and incentives |

---

## Exam Tips

- **Building Blocks** are reusable components of enterprise capability
- **Two types**: ABB (Architecture) and SBB (Solution)
- **ABB** = "What" is needed (functional specification)
- **SBB** = "How" it's implemented (specific product/code)
- **One ABB** can map to **multiple SBBs** (alternative implementations)
- **One SBB** can realize **multiple ABBs** (one product, many functions)
- ABBs relate to **Architecture Continuum**; SBBs relate to **Solutions Continuum**
- **Reuse before Buy, Buy before Build** — common principle
- Building blocks have **well-defined interfaces** and are **interoperable**
- Building block definition **progresses through ADM phases** (A → B, C, D → E → G)
- ABBs defined in **Phases B, C, D**; SBBs selected in **Phase E**; implemented in **Phase G**
- Building blocks span **all domains**: Business, Data, Application, Technology
