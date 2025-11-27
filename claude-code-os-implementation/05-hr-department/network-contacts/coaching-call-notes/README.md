# Coaching Call Notes

**Purpose:** Capture insights, strategic guidance, and action items from coaching calls (AAA Network and others)

**Source:** Fathom recordings with summaries and transcripts

---

## Directory Structure

```
coaching-call-notes/
├── README.md                          # This file
├── PROCESSING-WORKFLOW.md             # How to process coaching calls
├── TEMPLATE.md                        # Template for each call note
├── raw-notes/                         # Fathom summaries & transcripts
│   ├── README.md
│   ├── YYYY-MM-DD-coach-name.md      # Raw Fathom export
│   └── YYYY-MM-DD-coach-name-PROCESSED.md
├── by-coach/                          # Organized by coach
│   ├── richard.md                    # All Richard coaching sessions
│   ├── denis-daigle.md               # All Denis sessions
│   └── [other-coaches].md
└── by-topic/                          # Organized by strategic topic
    ├── agency-growth.md
    ├── client-delivery.md
    ├── pricing-strategy.md
    └── developer-management.md
```

---

## Quick Start

### The Fathom Link Flow

```
1. Coaching call ends
   ↓
2. IMMEDIATELY send Fathom link to coach (courtesy + accountability)
   ↓
3. Export Fathom summary + transcript
   ↓
4. Save to raw-notes/YYYY-MM-DD-coach-name.md
   ↓
5. Process with Claude within 24 hours
   ↓
6. Extract: Action items, Roadmap additions, Insights
   ↓
7. Prioritize: 🔴 Urgent → Daily plan | 🟡 Important → This week | 🟢 Strategic → Monthly
   ↓
8. Schedule important items in calendar
   ↓
9. Mark as PROCESSED
```

### Detailed Steps

1. **After coaching call:** Send Fathom link to coach, export summary + transcript
2. **Save to:** `raw-notes/YYYY-MM-DD-coach-name.md`
3. **Process within 24 hours** (see PROCESSING-WORKFLOW.md)
4. **Extract:**
   - Key insights
   - Action items (categorized by urgency)
   - Strategic guidance
   - Roadmap additions
   - Decisions made
5. **Prioritize & Schedule:**
   - 🔴 Urgent items → Add to today's/tomorrow's daily plan
   - 🟡 Important items → Schedule specific day this week
   - 🟢 Strategic items → Add to monthly objectives
6. **Add to:**
   - `by-coach/[coach-name].md` (chronological record)
   - `by-topic/[relevant-topic].md` (thematic organization)
7. **Mark as processed:** Rename to `YYYY-MM-DD-coach-name-PROCESSED.md`

---

## Available Coaches (AAA Network - FREE)

### Richard
**Expertise:** [TBD - fill in from coaching calls]
**Best for:** [TBD]
**Coaching calls:** See `by-coach/richard.md`
**Status:** Need to book first call TODAY

### Denis Daigle
**Expertise:** [TBD - fill in from coaching calls]
**Best for:** [TBD]
**Coaching calls:** See `by-coach/denis-daigle.md`
**Status:** Have Fathom notes to upload

---

## When to Book a Coaching Call

✅ **Book a call when:**
- You have a genuine problem or stopping point
- You've thought through the details yourself
- You need high-level strategic input
- You're at a decision point and need perspective
- You want validation/challenge on your approach

❌ **Don't book a call if:**
- You haven't tried to solve it yourself
- You need tactical help (not strategic)
- You're looking for someone to do the thinking for you
- Question can be answered with research

**Remember:** AAA Network coaching is FREE, but respect their time. Come prepared.

---

## How to Prepare for a Coaching Call

1. **Define the problem clearly**
   - What's the specific issue?
   - What have you tried?
   - Where are you stuck?

2. **Prepare context**
   - What's your current situation?
   - What are the constraints?
   - What's the goal?

3. **Draft specific questions**
   - Not "what should I do?"
   - Instead "I'm considering X vs Y because of Z, what am I missing?"

4. **Set up Fathom recording**
   - Ensure Fathom is recording
   - You'll get summary + transcript automatically

5. **Take live notes**
   - Key insights as they happen
   - Action items
   - Follow-up questions

---

## Post-Call Workflow

1. **Download Fathom export** (summary + transcript)
2. **Save to** `raw-notes/YYYY-MM-DD-coach-name.md`
3. **Process within 24 hours** using PROCESSING-WORKFLOW.md
4. **Implement action items** (add to daily planning)
5. **Track outcomes** (what worked? what didn't?)
6. **Update coach expertise** in this README as you learn

---

## Topics Covered (Index)

As you have coaching calls, track topics here:

| Topic | Coach | Date | Key Insight | Status |
|-------|-------|------|-------------|--------|
| [Topic] | [Coach] | YYYY-MM-DD | [1-line insight] | [ ] Action items pending / [x] Implemented |

---

## Success Metrics

You're using coaching effectively when:
- ✅ You come prepared with specific problems
- ✅ Calls result in clear action items
- ✅ You implement advice within 1 week
- ✅ You track outcomes and learnings
- ✅ You can see patterns in guidance across coaches
- ✅ Your decisions improve over time
- ✅ You know which coach to call for which problem

---

## Integration with Daily Planning

After each coaching call:
1. Add action items to daily planning todo list
2. Block time for implementation
3. Set follow-up reminder to report results (if applicable)
4. Update strategic priorities if guidance changes direction

---

## Pending Actions

**As of 2025-11-27:**
- [ ] Book Richard coaching call
- [ ] Upload Denis Daigle Fathom notes to raw-notes/
- [ ] Process Denis Daigle notes within 24 hours

---

## Claude Processing Prompt

Use this prompt when processing coaching calls with Claude:

```
Process these coaching call notes and extract:

1. **KEY INSIGHTS** - Strategic guidance, mental models, frameworks

2. **ACTION ITEMS** - List each with:
   - Task description
   - Priority: 🔴 Urgent (today/tomorrow), 🟡 Important (this week), 🟢 Strategic (this month)
   - First step to take

3. **ROADMAP ADDITIONS** - Ideas/initiatives to add to strategic priorities

4. **DECISIONS MADE** - What was decided and why

5. **FOLLOW-UP QUESTIONS** - Things to research or ask next time

[PASTE FATHOM NOTES HERE]
```

---

**Last Updated:** 2025-11-27
