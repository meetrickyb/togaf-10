# Reference Models (TRM & III-RM)

> TOGAF provides **two reference models** as Foundation Architectures: the **Technical Reference Model (TRM)** and the **Integrated Information Infrastructure Reference Model (III-RM)**.

---

## Purpose of Reference Models

Reference models provide:
- **Common vocabulary** for platform services and components
- **Taxonomy** for classifying technology
- **Starting point** for architecture development
- **Completeness check** ensuring all necessary services are considered
- **Vendor-neutral** descriptions of capabilities

---

## Technical Reference Model (TRM)

### Overview

The **TRM** is a Foundation Architecture providing a **taxonomy of generic platform services** that support applications.

### Purpose

The TRM:
- Classifies technology components into categories
- Ensures completeness of technology architecture
- Provides standard terminology
- Acts as starting point for creating organization-specific TRM

### TRM Structure

The TRM organizes platform services into **layers** (from bottom to top):

```
┌─────────────────────────────────────────┐
│        Application Software             │  ← Applications
├─────────────────────────────────────────┤
│      Application Platform Services      │  ← Layer 7
├─────────────────────────────────────────┤
│      Software Engineering Services      │  ← Layer 6
├─────────────────────────────────────────┤
│   Communication & Network Services      │  ← Layer 5
├─────────────────────────────────────────┤
│    Data Management Services             │  ← Layer 4
├─────────────────────────────────────────┤
│   Transaction Processing Services       │  ← Layer 3
├─────────────────────────────────────────┤
│   System & Network Management Services  │  ← Layer 2
├─────────────────────────────────────────┤
│      Security Services                  │  ← Layer 1
├─────────────────────────────────────────┤
│      Operating System Services          │  ← Base
├─────────────────────────────────────────┤
│         Network Infrastructure          │  ← Foundation
├─────────────────────────────────────────┤
│        Hardware (Compute, Storage)      │  ← Physical
└─────────────────────────────────────────┘
```

---

## TRM Layers in Detail

### Layer 0: Hardware

| Service | Description |
|---------|-------------|
| **Compute** | Physical servers, processors, memory |
| **Storage** | Disk arrays, SAN, NAS, storage devices |
| **Network Hardware** | Routers, switches, firewalls, load balancers |

### Layer 1: Network Infrastructure

| Service | Description |
|---------|-------------|
| **Network Services** | TCP/IP, routing, switching, DNS, DHCP |
| **Connectivity** | LAN, WAN, Internet connectivity |

### Layer 2: Operating System Services

| Service | Description |
|---------|-------------|
| **OS Kernel** | Process management, memory management |
| **File System** | File storage and retrieval |
| **Device Drivers** | Hardware interfacing |
| **System Utilities** | Basic OS utilities |

### Layer 3: Security Services

| Service | Description |
|---------|-------------|
| **Authentication** | User identity verification |
| **Authorization** | Access control and permissions |
| **Encryption** | Data protection (in transit and at rest) |
| **Audit/Logging** | Security event tracking |
| **Directory Services** | User and resource directories |

### Layer 4: System & Network Management

| Service | Description |
|---------|-------------|
| **Monitoring** | System health and performance tracking |
| **Configuration Management** | System configuration and provisioning |
| **Backup & Recovery** | Data protection and restoration |
| **Capacity Planning** | Resource utilization and planning |
| **Patch Management** | Software updates and patches |

### Layer 5: Data Management Services

| Service | Description |
|---------|-------------|
| **Database Management** | RDBMS, NoSQL databases |
| **Data Access** | SQL, query engines, ORM |
| **Data Dictionary** | Metadata management |
| **Data Warehousing** | Analytical data stores |
| **Caching** | In-memory data stores |

### Layer 6: Transaction Processing Services

| Service | Description |
|---------|-------------|
| **Transaction Management** | ACID transaction handling |
| **Transaction Coordination** | Distributed transaction management |
| **Messaging** | Message queuing, pub/sub |
| **Workflow** | Business process orchestration |

### Layer 7: Communication & Network Services

| Service | Description |
|---------|-------------|
| **Web Services** | HTTP, REST, SOAP |
| **Integration** | ESB, API gateway, message broker |
| **Collaboration** | Email, messaging, conferencing |
| **Remote Access** | VPN, remote desktop |

### Layer 8: Software Engineering Services

| Service | Description |
|---------|-------------|
| **Development Tools** | IDEs, compilers, debuggers |
| **Version Control** | Git, source code management |
| **Build & Deploy** | CI/CD pipelines |
| **Testing** | Test frameworks, test automation |
| **Documentation** | Code documentation, wikis |

### Layer 9: Application Platform Services

| Service | Description |
|---------|-------------|
| **Application Servers** | Java EE, .NET, Node.js runtime |
| **Web Servers** | Apache, Nginx, IIS |
| **Container Platforms** | Docker, Kubernetes |
| **Serverless** | Function-as-a-service platforms |
| **API Management** | API gateways, management platforms |

### Layer 10: Application Software

Business applications built on the platform services below.

---

## Using the TRM

### In Architecture Development

| Activity | How TRM Helps |
|----------|---------------|
| **Classify technology** | Map existing and planned technologies to TRM categories |
| **Identify gaps** | Find missing platform services |
| **Ensure completeness** | Check all necessary services are addressed |
| **Communication** | Use TRM terminology for clarity |
| **Planning** | Structure technology roadmap using TRM layers |

### Example: Mapping Technologies to TRM

| Technology | TRM Layer | TRM Service |
|------------|-----------|-------------|
| PostgreSQL | Data Management | Database Management |
| Kubernetes | Application Platform | Container Platform |
| Active Directory | Security | Authentication, Directory Services |
| MuleSoft | Communication & Network | Integration |
| Jenkins | Software Engineering | Build & Deploy |
| Prometheus | System & Network Management | Monitoring |

### Customizing the TRM

Organizations can **tailor the TRM** by:
- Adding organization-specific service categories
- Defining approved products for each service
- Specifying standards and versions
- Extending with industry-specific services

---

## Integrated Information Infrastructure Reference Model (III-RM)

### Overview

The **III-RM** focuses on **application and data integration** — how applications share and exchange information.

### Purpose

The III-RM:
- Provides model for **boundaryless information flow**
- Addresses **interoperability** challenges
- Guides **integration architecture**
- Supports **data sharing** across applications

### III-RM Structure

The III-RM has **three main components**:

#### 1. Business Applications

Applications providing business functionality:
- ERP systems
- CRM systems
- HR systems
- Financial systems
- Custom business applications

#### 2. Infrastructure Applications

Applications supporting the IT infrastructure:
- System management tools
- Network management
- Security management
- Development tools

#### 3. Application Platform

Services enabling applications to interoperate:

| Service Category | Services |
|------------------|----------|
| **Data Exchange** | Data transformation, mapping, routing |
| **Data Management** | Data integration, master data management |
| **Communication** | Messaging, publish/subscribe, request/reply |
| **Process Integration** | Workflow, orchestration, choreography |
| **Common Services** | Authentication, authorization, logging |

---

## III-RM Qualities

The III-RM emphasizes **boundaryless information flow** through:

### 1. Interoperability

| Quality | Description |
|---------|-------------|
| **Technical interoperability** | Systems can exchange data (protocols, formats) |
| **Semantic interoperability** | Data has consistent meaning across systems |
| **Organizational interoperability** | Processes align across organizational boundaries |

### 2. Integration Patterns

| Pattern | Use Case |
|---------|----------|
| **Point-to-point** | Simple, direct integration between two systems |
| **Hub-and-spoke** | Centralized integration through middleware |
| **Event-driven** | Systems react to events asynchronously |
| **Service-oriented** | Capabilities exposed as reusable services |
| **API-first** | APIs as primary integration interface |

### 3. Data Sharing Principles

| Principle | Description |
|-----------|-------------|
| **Single source of truth** | Master data maintained in one authoritative location |
| **Data synchronization** | Consistent data across systems |
| **Data quality** | Accurate, complete, timely data |
| **Data governance** | Policies and stewardship for data management |

---

## Using the III-RM

### In Architecture Development

| Activity | How III-RM Helps |
|----------|---------------|
| **Design integrations** | Identify required integration services |
| **Plan data sharing** | Define data exchange mechanisms |
| **Ensure interoperability** | Check for semantic and technical compatibility |
| **Select integration patterns** | Choose appropriate integration approach |
| **Define MDM strategy** | Plan master data management |

### Example: Applying III-RM

**Scenario:** Integrating CRM with ERP for customer and order data.

| III-RM Component | Application |
|------------------|-------------|
| **Business Applications** | Salesforce (CRM), SAP (ERP) |
| **Application Platform** | MuleSoft (integration), MDM Hub (master data) |
| **Data Exchange** | REST APIs, JSON format |
| **Data Management** | Customer MDM for single source of truth |
| **Communication** | Synchronous API calls for real-time, async messaging for batch |
| **Common Services** | OAuth for authentication, centralized logging |

---

## TRM vs. III-RM

| Aspect | TRM | III-RM |
|--------|-----|--------|
| **Focus** | Platform services and infrastructure | Application integration and data sharing |
| **Scope** | All technology layers | Application and integration layers |
| **Primary Use** | Classify technology, ensure platform completeness | Design integration, enable interoperability |
| **Audience** | Infrastructure architects, technology planners | Application architects, integration architects |

Both models **complement each other**:
- **TRM** provides the **platform foundation**
- **III-RM** leverages the platform for **application integration**

---

## Relationship to Architecture Continuum

Both TRM and III-RM are **Foundation Architectures** in the Architecture Continuum:

```
Architecture Continuum:
Foundation (TRM, III-RM) → Common Systems → Industry → Org-Specific
```

Organizations:
1. **Start with** TRM and III-RM
2. **Adopt** common systems architectures (e.g., IAM patterns)
3. **Apply** industry models (e.g., BIAN for banking)
4. **Customize** for specific organizational needs

---

## Tailoring Reference Models

Organizations should **adapt** reference models:

| Tailoring Activity | Example |
|-------------------|---------|
| **Add services** | Include cloud-native services (serverless, containers) |
| **Remove irrelevant** | Eliminate unused legacy services |
| **Define standards** | Specify approved products for each service |
| **Extend taxonomy** | Add organization-specific categories |
| **Industry-specific** | Incorporate industry standards and services |

---

## Reference Models in ADM

| Phase | Reference Model Use |
|-------|---------------------|
| **Preliminary** | Select and tailor TRM and III-RM |
| **Phase A** | Reference models inform scope and vision |
| **Phase B** | III-RM guides application requirements |
| **Phase C** | III-RM shapes integration architecture |
| **Phase D** | TRM structures technology architecture |
| **Phase E** | Reference models guide solution selection |

---

## Exam Tips

- TOGAF provides **two reference models**: TRM and III-RM
- **TRM (Technical Reference Model)** provides **taxonomy of platform services**
- TRM has **layers** from hardware → OS → security → data → network → application platform
- TRM used to **classify technology** and **ensure completeness**
- **III-RM (Integrated Information Infrastructure RM)** focuses on **application integration**
- III-RM addresses **boundaryless information flow** and **interoperability**
- III-RM has three components: **Business Apps, Infrastructure Apps, Application Platform**
- Both models are **Foundation Architectures** (most generic level)
- **TRM** = platform/infrastructure; **III-RM** = integration/interoperability
- Organizations should **tailor** reference models to their needs
- Reference models provide **common vocabulary** and **vendor-neutral** descriptions
