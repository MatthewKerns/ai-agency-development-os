---
**Post:** Week 1 - Friday
**Topic:** Common Process Documentation Mistakes
**Process Doc:** 03-documentation-mistakes-to-avoid.md
**Infographic:** week-1-post-3.png (to be created via NotebookLM)
**Scheduled:** Friday, December 6, 2025 @ 9:00 AM
---

**Three process documentation mistakes that turn a $5k project into a $14k nightmare:**

**Mistake #1: You specify HOW to build instead of WHAT you need**

❌ "Set up a webhook that POSTs to /api/customers with JSON payload..."

✅ "When a customer submits the form, save their info so my sales team can follow up"

**The problem:** You're doing the developer's job (implementation) instead of yours (business requirements).

**The cost:** Developer follows your spec even when there's a better way. Or your spec doesn't solve the actual problem.

**Mistake #2: You forget edge cases**

Your process: "Send follow-up 3 days after quote"

**Reality:**
• Customer already responded → Gets redundant email
• Customer already purchased → Gets "any questions?" (confusing)
• Customer opted out → Compliance violation (expensive)

**The cost:** $2-5k to fix after launch + damaged relationships

**Mistake #3: Vague success criteria**

❌ "Should work correctly and customers should be happy"

✅ "20% response rate, zero compliance violations, sales team saves 8 hours/week"

**The problem:** Developer thinks they're done. You think they're not. "Almost done" drags for weeks.

**Real numbers:** One client made all three mistakes. Result? $9k over budget, 6 weeks late.

**The fix?** 10-minute checklist before handoff:
□ Described WHAT, not HOW
□ Thought through "what if" scenarios
□ Wrote measurable success criteria

That 10 minutes prevents weeks of rebuilds and thousands in extra costs.

Which mistake do you catch yourself making most?

---
**Hashtags:** #ProcessDocumentation #ProjectManagement #BusinessSystems #SoftwareDevelopment #ProcessImprovement

**Infographic Points for NotebookLM:**
(Input process doc sections: "The Compound Effect" + "Quick Fix Checklist")

Visual should show:
- 3 mistakes as columns or sections
- Each with:
  - Bad example (X)
  - Good example (✓)
  - Cost impact ($X)
- Bottom section: "10-minute checklist prevents weeks of rebuilds"
- Numbers: "$9k over budget, 6 weeks late" (real example callout)
