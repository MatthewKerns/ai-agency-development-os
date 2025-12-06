# Phase 0: Discovery - Business Functions Mapping

## Overview

Phase 0 is the **foundation** of every client engagement. Before writing any code or building any systems, you must understand the business's operational landscape.

---

## Purpose

**Map the business functions → Generate structured report → Visualize with diagrams**

This phase ensures:
- Clear understanding of how the business operates
- Identification of gaps and risks
- Alignment on scope before building
- Foundation for accurate pricing and scoping

---

## The Phase 0 Process

```
1. Discovery Call (45-60 min)
   ↓
2. Business Functions Mapping Interview
   ↓
3. Generate JSON Report + Summary
   ↓
4. Create Visual Diagrams (draw.io)
   ↓
5. Review with Client
   ↓
6. Move to Phase 1 (Technical Scoping)
```

---

## Components

### 1. Business Functions Mapping Agent

**File:** `business-functions-mapping-agent.md`

**Purpose:** Interview framework to map all 10 core business functions

**Output:**
- Structured JSON with complete business function mapping
- Human-readable summary (8-10 bullets)
- Risk assessment for each function
- Quick wins and 90-day priorities

**Time:** 45-60 minutes (30-45 min interview + 15-20 min processing)

---

### 2. Draw.io Diagram Generation (Coming Soon)

**Purpose:** Visual representation of business functions and workflows

**Output:**
- Org chart showing function ownership
- Workflow diagrams for key processes
- Risk heat map visualization
- Integration map (systems and tools)

**Integration:** Takes JSON output from Business Functions Mapping Agent

---

## When to Use Phase 0

**✅ Use Phase 0 for:**
- Every new client engagement
- Initial discovery calls
- Before scoping or pricing any project
- When client says "I need automation" but unclear on specifics

**❌ Don't use Phase 0 when:**
- Client has already completed detailed business documentation
- You're already mid-project and need technical scoping (use Phase 1)
- Simple, well-defined project scope (e.g., "just need a chatbot on my website")

---

## Phase 0 Deliverables

### Client Receives:
1. **Business Functions Map (JSON)** - Complete structured data
2. **Executive Summary** - 8-10 bullet point overview
3. **Visual Diagrams** - draw.io diagrams showing structure and workflows
4. **Gap Analysis** - Risk assessment and prioritized recommendations
5. **Roadmap Preview** - High-level 30/90-day action plan

### Internal Use:
1. **Scoping Foundation** - Input for Phase 1 technical scoping
2. **Pricing Data** - Hours per function inform pricing
3. **Proposal Development** - Recommendations become project scope
4. **Client Alignment** - Shared understanding before building

---

## Integration with Project Management

After Phase 0 is complete, the output is stored in:

```
/02-operations/project-management/active-projects/
  └── {client-name}/
      └── phase-0-discovery/
          ├── business-functions-map.json
          ├── executive-summary.md
          └── diagrams/
              ├── org-chart.drawio
              ├── workflow-map.drawio
              └── risk-heatmap.drawio
```

---

## Workflow Summary

### Step 1: Schedule Discovery Call
- Block 60 minutes
- Send calendar invite
- Prep: Review any pre-call materials client provided

### Step 2: Conduct Interview
- Use Business Functions Mapping Agent prompts
- Take notes during call (or use Fathom/Fireflies)
- Ask all 4 phases of questions

### Step 3: Generate Report
- Use agent to process notes → JSON
- Generate executive summary
- Assign risk levels to each function

### Step 4: Create Diagrams
- Use draw.io agent workflow (coming soon)
- Generate org chart, workflows, risk map
- Export as PNG/PDF for client review

### Step 5: Client Review
- Send deliverables 24-48 hours after call
- Schedule 30-min review meeting
- Get client sign-off on accuracy

### Step 6: Move to Phase 1
- Use Phase 0 output as input for technical scoping
- Begin workflow mapping for high-risk functions
- Start scoping AI/automation solutions

---

## Success Metrics

**Phase 0 is successful when:**
- [ ] All 10 business functions are mapped
- [ ] Client confirms accuracy of the map
- [ ] Top 3 risks and opportunities are identified
- [ ] Quick wins (30-day) and 90-day priorities are clear
- [ ] Client understands the value of proceeding to Phase 1
- [ ] You have enough information to scope and price Phase 1

---

## Key Reminders

1. **Charge for Phase 0** - This is billable work ($200-500 diagnostic fee)
2. **Don't skip this step** - Even if client seems "simple"
3. **Use the agent framework** - Don't wing it, follow the prompts
4. **Get client sign-off** - Phase 0 deliverables are a contract baseline
5. **Store everything** - JSON, summary, diagrams all go in project folder

---

## Next Steps

After Phase 0 is complete:
- **Phase 1: Technical Scoping** - Workflow mapping and bottleneck analysis
- **Phase 2: Proposal Development** - Scope, pricing, timeline
- **Phase 3: Build** - Implement solutions based on Phase 0/1 findings

---

**Owner:** Operations Department
**Status:** Active
**Version:** 1.0
**Last Updated:** December 6, 2025
