# New Automation Type Update Workflow

## Purpose
When you discover a NEW automation type during processing, this workflow ensures it gets added to all the right places so your system stays current with market trends.

---

## When to Use This

**Trigger:** During processing (Step 2.2.5), you find an automation type mentioned in raw notes that's NOT in `AUTOMATION-TYPES-MASTER-LIST.md`

**Examples:**
- Someone mentions "SMS automation" → Not on list → NEW TYPE
- Someone builds "calendar automation" → Not on list → NEW TYPE
- Someone does "blockchain automation" → Not on list → NEW TYPE

---

## The 4-Step Update Process

### Step 1: Add to Master List (Required)

**File:** `AUTOMATION-TYPES-MASTER-LIST.md`

**Location:** Core Automation Types table

**Template:**
```markdown
| **[Type Name]** | [Brief description] | 💡 NEW | [Today's date] | [Who mentioned it + context] |
```

**Example:**
```markdown
| **SMS Automation** | Automated text messages, SMS campaigns, 2-way SMS | 💡 NEW | 2025-11-26 | Jane Doe (builds SMS workflows for restaurants) |
```

**Also add to Contact Examples section:**
```markdown
### SMS Automation
- **Jane Doe** - SMS workflows for restaurants
```

---

### Step 2: Add to Developer Index (Required)

**File:** `developers/index.md`

**Location:** Under "By Automation Type"

**Add new section:**
```markdown
### [Type Name]
- [Name] - [Specialization/Projects] - [Rate] - [Availability]
```

**Example:**
```markdown
### SMS Automation
- Jane Doe - SMS workflows for restaurants - [Rate] - [Availability]
```

**Position:** Add in logical order (group similar types together)

---

### Step 3: Update Stats in Level Files (If Common Type)

**Files:**
- `developers/junior-developers.md`
- `developers/mid-level-developers.md`
- `developers/senior-developers.md`
- `developers/specialists.md`

**Location:** "Quick Stats by Automation Type" section

**Only if this type will be common enough to track:**

```markdown
- **[Type Name]:** 0
```

**Example:**
```markdown
- **SMS Automation:** 1
```

**Skip this step if:** Type is rare/niche and unlikely to have multiple people

---

### Step 4: Make Note in Processing File

**File:** Your current raw notes file being processed

**Location:** "Key Insights" section

**Add:**
```markdown
**NEW AUTOMATION TYPE DISCOVERED:**
- **[Type Name]** - [Description]
- Source: [Person name]
- Market signal: [Why this matters]
- Action: Added to master list + index files
```

**Example:**
```markdown
**NEW AUTOMATION TYPE DISCOVERED:**
- **SMS Automation** - Automated text messaging workflows
- Source: Jane Doe (builds for restaurant industry)
- Market signal: Restaurants need SMS for reservation confirmations, marketing
- Action: Added to master list + index files
```

---

## Complete Example Walkthrough

### Scenario: You meet someone who builds "Chatbot Automation"

**Currently NOT on master list → This is NEW**

### Step-by-Step:

**1. Add to AUTOMATION-TYPES-MASTER-LIST.md:**

```markdown
| **Chatbot Automation** | Customer service bots, conversational AI, chat workflows | 💡 NEW | 2025-11-26 | Mike Chen (e-commerce chatbots, 24/7 support) |
```

Also add to Contact Examples:
```markdown
### Chatbot Automation
- **Mike Chen** - E-commerce chatbots, 24/7 customer support automation
```

**2. Add to developers/index.md:**

Find "By Automation Type" section, add:
```markdown
### Chatbot Automation
- Mike Chen - E-commerce chatbots, 24/7 support - [Rate] - [Availability]
```

**3. Update junior-developers.md stats (if applicable):**

```markdown
## Quick Stats by Automation Type
- **Voice Agents:** 0
- **CRM Automation:** 0
- **Email/Campaigns:** 0
- **RAG/Document Processing:** 0
- **Chatbot Automation:** 1  ← ADD THIS
- **Workflow Automation:** 0
```

**4. Note in raw notes Key Insights:**

```markdown
**NEW AUTOMATION TYPE DISCOVERED:**
- **Chatbot Automation** - Customer service bots, conversational AI
- Source: Mike Chen (builds for e-commerce companies)
- Market signal: E-commerce businesses need 24/7 customer support automation
- Action: Added to master list + developers/index.md
- Strategic opportunity: Could be growing market (watch for repeat mentions)
```

---

## Verification Checklist

After adding a new type, verify:

- [ ] Added to AUTOMATION-TYPES-MASTER-LIST.md (Core table)
- [ ] Added to AUTOMATION-TYPES-MASTER-LIST.md (Contact Examples)
- [ ] Added to developers/index.md (By Automation Type section)
- [ ] Added to contact record using template (with automation expertise fields)
- [ ] Updated stats in level files (if common type)
- [ ] Noted in raw notes Key Insights
- [ ] Updated contact's index entry with new type

---

## Weekly Review: Track New Type Mentions

**At end of week, in AUTOMATION-TYPES-MASTER-LIST.md:**

1. **Find all 💡 NEW types from this week**
2. **Check if they were mentioned again:**
   - Mentioned 2+ times in one week? → Change to 📈 GROWING
   - Mentioned once? → Keep as 💡 EMERGING
3. **Update Market Trends section with new discoveries**

**Example:**
```markdown
### Week of 2025-11-25

**New Types Discovered:**
1. SMS Automation (1 mention - Jane Doe)
2. Chatbot Automation (1 mention - Mike Chen)
3. Calendar Automation (2 mentions - different people)

**Analysis:**
- Calendar Automation mentioned twice → Potential trend, promote to GROWING
- Others: Watch for repeat mentions next week
```

---

## Why This Matters

**Market Intelligence:**
- New types = emerging opportunities
- Repeat mentions = market validation
- Early detection = competitive advantage

**Contact Organization:**
- When client asks "Do you know anyone who does [new type]?" → You can instantly find them
- When you meet 2nd person doing same new type → You recognize the trend

**Strategic Planning:**
- Hot new types = learn them or recruit specialists
- Emerging types = monitor for growth
- Rare types = note but don't prioritize

---

## Common Questions

**Q: How do I know if it's truly NEW vs. just a variation?**
A: Ask yourself:
- Is "SMS automation" different from "Email automation"? YES (different channel) → NEW TYPE
- Is "E-commerce chatbots" different from "Chatbot automation"? NO (same type, different niche) → NOT NEW

**Q: Someone does "AI-powered CRM automation" - is that new?**
A: No. That's CRM automation (already on list). The "AI-powered" is assumed for everything we do.

**Q: What if it's super niche and only 1 person will ever do it?**
A: Still add it! Better to track and later realize it's not important than to miss an emerging trend.

**Q: Do I update this every single time someone mentions the type?**
A:
- First mention: Add as 💡 NEW
- Weekly: Update demand level based on total mentions
- Don't re-add the same type multiple times

**Q: What if I'm not sure what category it falls under?**
A: Add it as best you can. You can recategorize later. Better to capture it imperfectly than lose it.

---

## Time Budget

**Per new type discovered:** ~5 minutes
- 1 min: Add to master list
- 1 min: Add to developers/index.md
- 1 min: Update stats (if needed)
- 2 min: Note in insights + verify

**Worth it?** Absolutely. Early trend detection = strategic advantage.

---

## Remember

**The market tells you what's valuable. Your job is to LISTEN and CAPTURE.**

Every new automation type = potential market opportunity.
Don't filter. Let the data accumulate. Trends emerge over time.

---

**Quick checklist when you find something new:**

```
Found: [Type Name] mentioned by [Person]
□ Is it on master list? → NO → Proceed
□ Add to AUTOMATION-TYPES-MASTER-LIST.md
□ Add to developers/index.md
□ Update stats if common type
□ Note in raw notes insights
□ Done! (5 min total)
```
