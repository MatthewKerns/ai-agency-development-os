# Coaching Call Notes Processing Workflow

## Purpose
Convert Fathom recordings (summaries + transcripts) into actionable insights, strategic guidance records, and implementation plans. Ensures coaching advice doesn't get lost and gets implemented.

---

## The Funnel

```
Coaching Call (with Fathom recording)
    ↓
Fathom Export (Summary + Transcript)
    ↓
Processing (Within 24 hours)
    ↓
Structured Insights + Action Items
    ↓
Implementation (Next 1-7 days)
    ↓
Outcome Tracking (Ongoing)
```

---

## Step 1: Capture Raw Notes (During Call)

**Timing:** During the call (Fathom auto-records)

**Live capture:**
- Key insights as they're said
- Action items
- Decisions made
- Questions to follow up on
- Ah-ha moments

**Fathom handles:**
- Full transcript
- AI summary
- Key topics
- Action items extraction

**After call ends:**
- Fathom processes automatically
- Summary + transcript available within minutes

---

## Step 2: Export Fathom Notes (Immediately After Call)

**Timing:** Right after call ends (within 1 hour)

**Steps:**
1. Open Fathom call recording
2. Copy summary section
3. Copy transcript
4. Copy action items list

**Save to:** `raw-notes/YYYY-MM-DD-coach-name.md`

**File format:**
```markdown
# Coaching Call: [Coach Name] - [Date]

**Date:** YYYY-MM-DD
**Coach:** [Name]
**Duration:** [X] minutes
**Topic:** [Main topic/problem discussed]
**Status:** [ ] Not Processed

---

## Fathom Summary

[Paste Fathom AI summary here]

---

## Key Topics Discussed

[Fathom auto-extracts these]

---

## Fathom Action Items

[Paste action items here]

---

## Full Transcript

[Paste full transcript here]

---

## Processing Checklist

- [ ] Extract key insights
- [ ] Identify action items
- [ ] Add to by-coach file
- [ ] Add insights to by-topic files
- [ ] Create daily planning todos
- [ ] Mark as PROCESSED
```

---

## Step 3: Processing (Within 24 Hours)

**Timing:** Within 24 hours of call

### 3.1: Extract Key Insights

Read through summary and transcript, identify:

**Strategic Insights:**
- High-level guidance
- Mental models shared
- Frameworks explained
- Pattern recognition

**Tactical Advice:**
- Specific steps to take
- Tools/resources recommended
- Who to talk to
- What to avoid

**Decisions Made:**
- What you decided during call
- Why you decided it
- What alternatives you rejected

**Perspective Shifts:**
- Things you were thinking wrong
- New ways to frame problems
- Assumptions challenged

### 3.2: Extract Action Items

From Fathom action items + your notes:

**Categorize each action:**
- 🔴 **Urgent** (Do today/tomorrow)
- 🟡 **Important** (Do this week)
- 🟢 **Strategic** (Do this month)
- 📝 **Research** (Gather more info)
- 💭 **Think** (Consider/reflect)

**For each action item:**
- What exactly needs to be done?
- Why (what problem does it solve)?
- By when (realistic deadline)?
- What's the first tiny step?

### 3.3: Identify Follow-Up Questions

As you process:
- What wasn't clear?
- What needs more depth?
- What contradicts previous advice?
- What assumptions need validating?

**Save these for:**
- Next coaching call with same coach
- Self-research
- Testing in real world

### 3.4: Create Structured Record (by-coach)

**File:** `by-coach/[coach-name].md`

Add entry using template:

```markdown
---
## [Date] - [Topic]

**Problem Brought:**
[What you asked about]

**Context:**
[Situation/constraints you shared]

**Key Insights:**
1. [Insight 1]
2. [Insight 2]
3. [Insight 3]

**Action Items:**
- 🔴 [Urgent action]
- 🟡 [Important action]
- 🟢 [Strategic action]

**Decisions Made:**
- [Decision 1 + reasoning]
- [Decision 2 + reasoning]

**Perspective Shifts:**
- [What changed in my thinking]

**Follow-Up Questions:**
- [Question 1]
- [Question 2]

**Raw Notes:** `raw-notes/YYYY-MM-DD-coach-name-PROCESSED.md`

**Outcome:** [Fill in after implementing - what actually happened?]

---
```

### 3.5: Add Insights to Topic Files (by-topic)

**File:** `by-topic/[relevant-topic].md`

For each major insight, add to relevant topic file:

```markdown
### [Coach Name] - [Date]

**Context:** [When this applies]

**Insight:** [The guidance/framework]

**How to apply:**
1. [Step 1]
2. [Step 2]

**When NOT to use:** [Constraints]

**Source:** [Link to by-coach entry]

---
```

**Common topics:**
- `pricing-strategy.md` - How to price, when to adjust
- `client-delivery.md` - Delivering projects, managing clients
- `developer-management.md` - Finding, evaluating, managing devs
- `agency-growth.md` - Scaling, systems, processes
- `sales-positioning.md` - How to sell, positioning
- `scope-estimation.md` - Scoping projects, estimating work

**Create new topic files as needed**

### 3.6: Add to Daily Planning

**Urgent actions (🔴):**
- Add to today's or tomorrow's daily plan
- Block time for implementation
- Set as high priority

**Important actions (🟡):**
- Add to this week's plan
- Schedule specific day
- Set reminder

**Strategic actions (🟢):**
- Add to monthly planning
- Review in weekly review
- Track progress

**File location:** `01-executive-office/daily-planning/logs/YYYY-MM-DD.md`

### 3.7: Mark as Processed

In raw notes file:
- Check all processing checklist items
- Update status to: `[x] Processed`
- Add processing date
- Rename file to: `YYYY-MM-DD-coach-name-PROCESSED.md`

---

## Step 4: Implementation (Within 1 Week)

**Timing:** Most action items within 1 week

**For each action item:**
1. **Start small** - What's the tiniest first step?
2. **Time block** - When specifically will you do it?
3. **Track** - Check off when complete
4. **Measure** - What changed? Did it work?

**Update coaching call record:**
- Mark action items complete
- Add outcome notes
- Track what worked vs didn't

---

## Step 5: Outcome Tracking (Ongoing)

**1-2 weeks after implementation:**

Return to `by-coach/[coach-name].md` entry:

**Update "Outcome" section:**
```markdown
**Outcome:**
- ✅ [Action 1]: [What happened when you did this]
- ✅ [Action 2]: [Result]
- ❌ [Action 3]: [Why this didn't work / what you learned]
- 🤔 [Action 4]: [Still testing / too early to tell]
```

**Track patterns:**
- Which advice works consistently?
- Which coach is best for which problems?
- What's your success rate on implementation?
- What types of advice do you tend to ignore?

---

## Monthly Review: Coaching ROI

**End of each month:**

1. **Review all coaching calls from the month**
2. **Calculate implementation rate:**
   - How many action items assigned?
   - How many actually implemented?
   - Target: 80%+ implementation

3. **Track outcomes:**
   - What resulted in revenue?
   - What saved time?
   - What prevented mistakes?
   - What shifted strategy?

4. **Identify patterns:**
   - Which coach's advice works best for you?
   - Which topics need more coaching?
   - What problems keep coming up?

5. **Plan next coaching calls:**
   - What's your next stopping point?
   - Which coach to call?
   - What to prepare?

---

## Example: Processing Denis Daigle Call

**Raw Fathom Export:**
```
Discussed agency pricing strategy. Denis recommended focusing on value-based pricing
instead of hourly. Suggested starting with diagnostic calls at $200-500/hr...
```

**Processing:**

**1. Extract Key Insights:**
- Value-based pricing > hourly
- Diagnostic calls = revenue (not free discovery)
- Price based on client outcome, not your time

**2. Extract Action Items:**
- 🔴 Start charging for diagnostic calls ($200-500/hr)
- 🟡 Update agency pitch to emphasize value delivered
- 🟢 Create pricing tier framework

**3. Add to by-coach/denis-daigle.md:**
```markdown
## 2025-11-20 - Pricing Strategy

**Problem Brought:** How to price diagnostic calls and agency services

**Key Insights:**
1. Diagnostic calls have value - charge $200-500/hr
2. Value-based pricing = better margins + better clients
3. Hourly pricing commoditizes your expertise

**Action Items:**
- 🔴 Start charging for next diagnostic call
- 🟡 Update website/pitch materials
- 🟢 Build pricing framework

**Outcome:** [Update after implementation]
```

**4. Add to by-topic/pricing-strategy.md:**
```markdown
### Denis Daigle - 2025-11-20

**Insight:** Diagnostic calls should be billable ($200-500/hr)

**Reasoning:**
- You're providing value (strategic clarity)
- Free calls attract tire-kickers
- Paid calls = serious prospects

**How to apply:**
1. State upfront: "Diagnostic calls are $X/hr"
2. Explain value: "You'll get clarity on..."
3. Offer alternative if price concern: "Or we can jump straight to proposal"

**When NOT to use:** Don't charge if it's just a quick qualifying chat (15 min)
```

**5. Add to daily plan:**
```markdown
### Tomorrow
- [ ] Update agency pitch: diagnostic calls are $200-500/hr (30 min)
- [ ] Prepare script for next discovery call (15 min)
```

**6. Mark processed:**
- Rename: `2025-11-20-denis-daigle-PROCESSED.md`
- Status: [x] Processed on 2025-11-20

**7. Implement & track:**
- Week 1: Updated pitch, quoted $300 for next diagnostic
- Week 2: Closed first paid diagnostic call
- Outcome: ✅ Client paid $300, moved to proposal phase. Denis was right.

---

## Common Mistakes to Avoid

❌ **Not processing within 24 hours** - Insights fade, lose context
❌ **Just reading the summary** - Transcript has gold, dig deeper
❌ **Not implementing** - Coaching is useless if you don't act
❌ **Implementing everything at once** - Start with 1-2 urgent items
❌ **Not tracking outcomes** - You won't learn which advice works
❌ **Forgetting to update coach expertise** - Track what each coach is great at
❌ **Not preparing follow-up questions** - You'll ask same things twice

---

## Time Budget

| Task | Time | When |
|------|------|------|
| Coaching call | 30-60 min | Scheduled |
| Export Fathom notes | 5 min | Right after call |
| Process call notes | 30-45 min | Within 24 hours |
| Add to daily planning | 10 min | Same day as processing |
| Implement action items | Varies | Within 1 week |
| Track outcomes | 15 min | 1-2 weeks after |
| **Total per call** | **~2 hours** | **Over 2-3 weeks** |

**Worth it?** Free expert strategic guidance + accountability = massive ROI

---

## Success Metrics

You're using coaching effectively when:
- ✅ 80%+ of action items get implemented
- ✅ You can see clear before/after from coaching
- ✅ You know which coach to call for which problem
- ✅ You're not asking the same questions twice
- ✅ Coaching leads to measurable results (revenue, time saved, better decisions)
- ✅ You come prepared and use time efficiently
- ✅ You can track patterns in what works for you

---

## Quick Reference Card

```
DURING CALL:
□ Fathom is recording
□ Take live notes on key insights
□ Note action items as they're mentioned
□ Ask follow-up questions in real-time

RIGHT AFTER CALL (within 1 hour):
□ Export Fathom summary + transcript
□ Save to raw-notes/YYYY-MM-DD-coach-name.md

WITHIN 24 HOURS (Processing):
□ Read summary + scan transcript
□ Extract key insights
□ Extract action items (categorize by urgency)
□ Add entry to by-coach/[coach-name].md
□ Add insights to relevant by-topic files
□ Add urgent/important items to daily planning
□ Mark raw notes as PROCESSED

WITHIN 1 WEEK (Implementation):
□ Complete urgent actions (🔴)
□ Complete important actions (🟡)
□ Start strategic actions (🟢)
□ Track what happens

1-2 WEEKS AFTER:
□ Update "Outcome" section in by-coach file
□ Note what worked vs didn't
□ Identify follow-up questions for next call

MONTHLY:
□ Review all coaching calls
□ Calculate implementation rate
□ Track ROI (revenue, time, decisions)
□ Plan next coaching calls
```

---

## Questions?

- **"Do I need to process every coaching call?"** → Yes, or you'll forget insights
- **"What if the call didn't result in action items?"** → Still process for insights and mental models
- **"Should I share outcomes with coach?"** → Yes! They love hearing what worked
- **"What if I disagree with the advice?"** → Note it, test small, track result. Not all advice fits every situation
- **"How often should I book coaching calls?"** → When you have a genuine stopping point. Could be weekly or monthly depending on stage
- **"What if two coaches give conflicting advice?"** → Test both (small), see what works for your situation
- **"Do I need to implement everything?"** → No, prioritize. But track WHY you skip things

---

## Integration with Other Systems

**Daily Planning:**
- Coaching action items → daily todo lists
- Time blocking for implementation

**Project Management:**
- Strategic guidance → update project approach
- Tactical advice → add to project templates

**Network Contacts:**
- Coach recommendations → add contacts to network
- Referred tools/resources → research & adopt

**Agency Infrastructure:**
- Frameworks learned → codify in templates
- Processes recommended → build into workflows

---

**Last Updated:** 2025-11-25
