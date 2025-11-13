# Common Exam Traps

> Common misconceptions, confusing concepts, and frequently missed exam questions in TOGAF 10 Foundation.

---

## Requirements Management Traps

### TRAP 1: Requirements Management Prioritizes Requirements

**Wrong**: Requirements Management phase prioritizes architecture requirements.

**Right**: Requirements Management is the **process** for managing requirements. **Prioritization happens within individual ADM phases**, not in the Requirements Management phase itself.

**Why this trap**: The central position of Requirements Management in the ADM diagram can make it seem like it does more than it actually does.

**Remember**: Requirements Management:
- ✅ Identifies requirements
- ✅ Stores requirements
- ✅ Tracks changes to requirements
- ✅ Feeds requirements to/from phases
- ❌ Does NOT prioritize
- ❌ Does NOT address/resolve requirements

---

### TRAP 2: Requirements Management is a One-Time Phase

**Wrong**: Requirements Management is executed once at the start of the ADM cycle.

**Right**: Requirements Management is **continuous** and operates **throughout all ADM phases**, including during Phase H (ongoing operations).

**Why this trap**: It's labeled as a "phase" like the others.

**Remember**: Requirements Management is:
- At the **center** of the ADM diagram (not in sequence)
- **Always active** — from Preliminary through Phase H
- **Bidirectional** — feeds TO and FROM every phase

---

## Phase C Traps

### TRAP 3: Phase C is Either Data OR Application

**Wrong**: Phase C focuses on either Data Architecture or Application Architecture.

**Right**: Phase C addresses **BOTH** Data and Application architectures. It can be done sequentially (data then application) or concurrently, but both must be addressed.

**Why this trap**: The phase is sometimes referred to as "Information Systems" without emphasis on both components.

**Remember**: Phase C =**D**ata + **A**pplication (both parts of "DA" in BDAT)

---

## Preliminary Phase Traps

### TRAP 4: Preliminary Phase Develops Architecture

**Wrong**: Preliminary Phase develops the enterprise architecture.

**Right**: Preliminary Phase **prepares** the organization for architecture work. It establishes the framework, principles, and capability — but does NOT develop architectures. That happens in Phases A-D.

**Why this trap**: It's a full phase in the ADM, so people assume it produces architecture.

**Remember**: Preliminary answers:
- WHERE do we do architecture? (scope)
- WHAT kind of architecture? (tailored framework)
- WHY do architecture? (drivers, goals)
- WHO does architecture? (team, governance)
- HOW do we do architecture? (processes, tools)

It does NOT answer "WHAT is our architecture?" — that comes later.

---

## Building Block Traps

### TRAP 5: One ABB Maps to Exactly One SBB

**Wrong**: Each Architecture Building Block (ABB) is implemented by exactly one Solution Building Block (SBB).

**Right**: **One ABB can map to multiple SBBs** (alternative implementations), and **one SBB can implement multiple ABBs** (one product fulfilling multiple functions).

**Why this trap**: The relationship seems like it should be simple 1:1.

**Example**:
- ABB: "Customer Relationship Management" → SBBs: Salesforce, Microsoft Dynamics, Custom CRM (multiple options)
- SBB: "Microsoft 365" → ABBs: Email, Collaboration, Document Management, Calendar (multiple functions)

---

### TRAP 6: ABB Defines Implementation; SBB Defines Requirements

**Wrong**: ABBs specify how to implement; SBBs specify what is needed.

**Right**: **OPPOSITE** — ABBs define "**WHAT**" (functional requirements), SBBs define "**HOW**" (specific implementation/product).

**Why this trap**: The terms are easily reversed.

**Remember**:
- **ABB** = **A**rchitecture = **A**bstract = What is needed
- **SBB** = **S**olution = **S**pecific = How to implement

---

## Reference Model Traps

### TRAP 7: TRM is Mandatory and Cannot Be Tailored

**Wrong**: Organizations must use the TOGAF TRM exactly as provided.

**Right**: The TRM is a **Foundation Architecture** meant to be **tailored** to organizational needs. Organizations can add, remove, or modify service categories.

**Why this trap**: "Reference Model" sounds mandatory.

**Remember**: TRM provides:
- Starting point
- Common vocabulary
- Taxonomy
- But should be **customized** to fit organizational context

---

### TRAP 8: TRM and III-RM Are the Same Thing

**Wrong**: TRM and III-RM are interchangeable or duplicate concepts.

**Right**: They serve **different purposes**:
- **TRM** = Taxonomy of **platform services** (infrastructure focus)
- **III-RM** = Model for **application integration** (interoperability focus)

**Why this trap**: Both are TOGAF reference models.

**Remember**:
- TRM = **T**echnology layers (hardware to application platform)
- III-RM = **I**ntegration and **I**nteroperability

---

## Enterprise Continuum Traps

### TRAP 9: Enterprise Continuum is a Physical Repository

**Wrong**: Enterprise Continuum is the physical storage location for architecture assets.

**Right**: Enterprise Continuum is a **classification scheme** (virtual). The **Architecture Repository** is the physical storage.

**Why this trap**: "Continuum" and "Repository" are discussed together.

**Remember**:
- **Enterprise Continuum** = Classify ("where on the spectrum")
- **Architecture Repository** = Store ("where physically saved")

---

### TRAP 10: Solutions Continuum Contains Only Software

**Wrong**: Solutions Continuum is only for software applications.

**Right**: Solutions Continuum contains **all implementation assets**: software, hardware, products, services, configurations — anything that implements an ABB.

**Why this trap**: "Solutions" is often equated with "software applications."

---

## Architecture Repository Traps

### TRAP 11: Architecture Repository Stores Only Final Architectures

**Wrong**: Architecture Repository contains only approved, finalized architectures.

**Right**: Architecture Repository stores **all architecture work products**: draft architectures, decisions, compliance assessments, contracts, lessons learned, reference materials, etc.

**Why this trap**: "Repository" sounds like an archive for completed work.

**Remember**: Repository has **six components**, each storing different types of content throughout the architecture lifecycle.

---

### TRAP 12: Standards Information Base Stores Only Technology Standards

**Wrong**: The Standards Information Base (SIB) contains only technology standards.

**Right**: SIB contains:
- Technology standards
- Industry standards
- Architecture **principles**
- **Policies**
- Regulatory requirements

**Why this trap**: "Standards" often implies technical specifications.

---

## Governance Traps

### TRAP 13: Architecture Board Only Reviews at Project End

**Wrong**: Architecture Board reviews architecture compliance only after projects are complete.

**Right**: Architecture Board conducts reviews at **multiple checkpoints** throughout the project lifecycle:
1. Project Initiation
2. Architecture Design
3. Build Review
4. Pre-Production
5. Post-Implementation

**Why this trap**: Governance is sometimes thought of as "approval at the end."

**Remember**: **Proactive** governance throughout, not just **reactive** at the end.

---

### TRAP 14: Dispensations Are Architecture Failures

**Wrong**: Granting a dispensation means the architecture or governance has failed.

**Right**: Dispensations are a **legitimate governance mechanism** for handling justified exceptions when compliance cost exceeds benefit or unique circumstances apply.

**Why this trap**: "Exception" sounds negative.

**Remember**: Dispensations are:
- Formally approved
- Time-limited
- Documented with conditions
- Part of good governance (flexibility within control)

---

## Deliverable vs. Artifact Traps

### TRAP 15: All Work Products Are Deliverables

**Wrong**: Everything produced during architecture work is a deliverable.

**Right**: **Deliverables** are work products formally reviewed and signed off. **Artifacts** are specific work products (catalogs, matrices, diagrams) that may be components of deliverables but aren't necessarily formally approved on their own.

**Why this trap**: Both are "delivered" in some sense.

**Remember**:
- **Deliverable** = Formally reviewed, approved, contractual (e.g., Architecture Definition Document)
- **Artifact** = Specific work product, may be part of deliverable (e.g., Process Flow Diagram)

---

### TRAP 16: Architecture Definition Document is Created in Phase A

**Wrong**: The Architecture Definition Document (ADD) is completed in Phase A.

**Right**: The ADD is **drafted** in Phases B, C, D (for each domain) and **completed** in Phase E. Phase A produces the **Architecture Vision**, which is different.

**Why this trap**: Phase A is the first to produce architecture content.

**Remember**:
- Phase A → **Architecture Vision** (high-level)
- Phases B, C, D → **Architecture Definition Document** (detailed, by domain)

---

## Scope Traps

### TRAP 17: Architecture Scope Has Only Two Dimensions

**Wrong**: Architecture scope is defined by breadth and depth only.

**Right**: Architecture scope has **four dimensions**:
1. **Breadth** — Enterprise scope (what part of org)
2. **Depth** — Level of detail
3. **Architecture Domains** — Which of BDAT
4. **Time Period** — Planning horizon

**Why this trap**: Breadth and depth are most commonly mentioned.

---

## Phase Sequence Traps

### TRAP 18: ADM Phases Must Be Executed in Strict Sequential Order

**Wrong**: ADM phases must always be executed sequentially without iteration.

**Right**: ADM is **iterative** and **flexible**:
- Can iterate within a phase
- Can cycle back to earlier phases
- Can run partial ADM cycles
- Can execute at different levels (enterprise, segment, capability)

**Why this trap**: The diagram shows a sequence.

**Remember**: The sequence provides **default order**, but iteration is expected and encouraged.

---

### TRAP 19: Every ADM Cycle Must Include All Phases

**Wrong**: All phases from Preliminary through H must be executed in every ADM cycle.

**Right**: Organizations can run:
- **Full ADM cycles** (all phases)
- **Partial cycles** (selected phases, e.g., B, C, D only)
- **Single phase iterations** (e.g., re-do Phase C for application changes)

**Why this trap**: The full cycle is presented as the standard approach.

---

## Views and Viewpoints Traps

### TRAP 20: Views and Viewpoints Are the Same Thing

**Wrong**: Architecture View and Architecture Viewpoint are interchangeable terms.

**Right**:
- **Viewpoint** = Convention/template for creating a view
- **View** = Actual representation created using a viewpoint

**Why this trap**: The terms sound similar.

**Remember**:
- **Viewpoint** = How to create (template)
- **View** = What is created (actual artifact)

**Analogy**: Recipe (viewpoint) vs. Meal (view)

---

## Capability Framework Traps

### TRAP 21: Architecture Capability Framework Has Five Components

**Wrong**: The Architecture Capability Framework has five components.

**Right**: It has **seven** components:
1. Architecture Board
2. Architecture Compliance
3. Architecture Contracts
4. Architecture Governance
5. Architecture Maturity Models
6. Architecture Skills Framework
7. Architecture Repository

**Why this trap**: Easy to forget one or two components.

**Remember**: **7** components (same number as days in a week)

---

## Maturity Traps

### TRAP 22: Architecture Maturity Only Measures Technical Skills

**Wrong**: Architecture maturity models assess only technical capabilities.

**Right**: Maturity models assess **holistic EA capability**:
- Processes
- Governance
- Skills
- Tools
- Organizational support
- Value delivery
- Continuous improvement

**Why this trap**: "Maturity" in IT contexts often focuses on technical proficiency.

---

## Phase-Specific Output Traps

### TRAP 23: Architecture Roadmap is Finalized in Phase E

**Wrong**: Phase E produces the final Architecture Roadmap.

**Right**:
- Phase E produces **initial** Architecture Roadmap
- Phase F produces **finalized** Architecture Roadmap

**Why this trap**: Phase E creates the roadmap, so it seems complete.

**Remember**:
- Phase E = "Opportunities & Solutions" → **identifies** approach, **creates initial** roadmap
- Phase F = "Migration Planning" → **details** plan, **finalizes** roadmap

---

### TRAP 24: Implementation and Migration Plan is Created in Phase G

**Wrong**: Phase G creates the Implementation and Migration Plan.

**Right**:
- Phase E produces **draft** Implementation and Migration Plan
- Phase F produces **final** Implementation and Migration Plan
- Phase G **executes** the plan (governance during implementation)

**Why this trap**: Phase G is about implementation, so plan creation seems to fit there.

**Remember**: Phase G **governs**, it doesn't plan.

---

## Principle Traps

### TRAP 25: Architecture Principles Have Three Components

**Wrong**: Architecture principles consist of name, statement, and rationale.

**Right**: Architecture principles have **four** components:
1. Name
2. Statement
3. Rationale
4. **Implications**

**Why this trap**: Implications are often forgotten.

**Remember**: Name, Statement, Rationale, **Implications** (NSRI)

---

## Transition Architecture Traps

### TRAP 26: Transition Architectures Are Optional

**Wrong**: Transition architectures are optional nice-to-haves.

**Right**: Transition architectures are a **key concept** in TOGAF for:
- Reducing risk (smaller incremental changes)
- Enabling early value delivery
- Managing complexity
- Maintaining operations during transformation

**Why this trap**: The focus is often on baseline and target, with transitions seeming secondary.

**Remember**: **Baseline → Transition(s) → Target** is the recommended approach for major transformations.

---

## Architecture Landscape Traps

### TRAP 27: Architecture Landscape Has Two Levels

**Wrong**: Architecture Landscape contains baseline and target architectures.

**Right**: Architecture Landscape has **three levels** organized by abstraction/horizon:
1. **Strategic Architecture** (3-5+ years)
2. **Segment Architecture** (1-3 years)
3. **Capability Architecture** (6-12 months)

Each level can have baseline, target, and transition architectures.

**Why this trap**: Baseline and target are most commonly discussed.

---

## Exam-Taking Traps

### TRAP 28: Questions with "Always" or "Never" Are Always Wrong

**Wrong**: Any question with absolute words like "always" or "never" must be false.

**Right**: While absolutes are **often** incorrect in TOGAF questions, some statements with absolutes are true (e.g., "Requirements Management is always active throughout ADM").

**Why this trap**: Test-taking strategy from other exams.

**Remember**: Evaluate each question on its merits, don't rely solely on word presence.

---

### TRAP 29: The Longest Answer is Usually Correct

**Wrong**: Pick the longest answer when unsure.

**Right**: TOGAF exam answers vary in length independent of correctness. Focus on **content accuracy**, not length.

**Why this trap**: Common test-taking myth.

---

### TRAP 30: First Instinct is Always Right

**Wrong**: Never change your answer; go with your first choice.

**Right**: If you have a good reason to change your answer after careful reconsideration, do so. However, don't second-guess yourself excessively.

**Why this trap**: General test-taking advice often oversimplified.

---

## Summary: Most Common Exam Mistakes

| Rank | Common Mistake |
|------|----------------|
| 1    | Confusing ABB and SBB (which is "what" vs. "how") |
| 2    | Thinking Requirements Management prioritizes requirements |
| 3    | Forgetting Phase C includes BOTH Data and Application |
| 4    | Confusing Enterprise Continuum (classification) with Architecture Repository (storage) |
| 5    | Not remembering architecture principles have **four** components (forgetting Implications) |
| 6    | Thinking Preliminary Phase develops architecture (it only prepares) |
| 7    | Confusing which phase produces which version of deliverables (draft vs. final) |
| 8    | Forgetting Requirements Management is **continuous**, not one-time |
| 9    | Thinking TRM cannot be tailored |
| 10   | Confusing Views and Viewpoints |

---

## Final Exam Advice

1. **Read each question twice** — Carefully and slowly
2. **Identify key words** — "always", "never", "primary", "best", "first"
3. **Eliminate obvious wrongs** — Narrow down before guessing
4. **Trust your preparation** — If you've studied, trust your knowledge
5. **Watch the clock** — Don't spend too long on any one question
6. **Review flagged questions** — Come back to uncertainties if time permits
7. **Don't overthink** — The exam tests fundamental understanding, not tricks
8. **Stay calm** — 60% to pass is achievable with good preparation

**Good luck with your TOGAF 10 Foundation exam!**
