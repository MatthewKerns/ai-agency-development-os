# Raw Notes → Structured Contacts Processing Workflow

## Purpose
Convert messy networking event notes into structured, actionable contact records. This ensures no one falls through the cracks and every contact is categorized for strategic value.

---

## The Funnel

```
Raw Event Notes (Day of event)
    ↓
Processing (Within 24 hours)
    ↓
Categorized Contact Records (Permanent)
    ↓
Follow-Up Actions (Next day)
    ↓
Relationship Building (Ongoing)
```

---

## Step 1: Capture Raw Notes (During/After Event)

**Timing:** During event or immediately after (same day)

**File:** `raw-notes/YYYY-MM-DD-event-name.md`

**What to capture:**
- Name (get spelling right!)
- What they do
- **Automation platforms they use** (n8n, Make.com, Zapier, etc.)
- **Types of automations they build** (email, CRM, voice agents, RAG, lead capture, etc.)
- **Specific projects/builds mentioned**
- **Lead generation tactics they use**
- Pain points mentioned
- Ideas discussed
- Contact info (LinkedIn, email, phone)
- Anything memorable about them

**Rules:**
- Don't filter, just capture everything
- One section per person
- It's OK if it's messy
- Get it down fast while memory is fresh
- **AI/Automation specific:** Note what platforms, automation types, and projects they mention

---

## Step 2: Processing (Next Day)

**Timing:** Within 24 hours of event

**For each contact in your raw notes:**

### 2.1: Gather Missing Info

If you don't have their contact info:
- LinkedIn search
- Ask mutual connections
- Check event attendee list

### 2.2: Categorize the Contact

Ask: "How does this person help me reach $50k/mo OBG?"

| If they are... | Category | File |
|----------------|----------|------|
| Can bring deals/clients | Lead Generator | `lead-generators/by-niche.md` or `by-network.md` |
| Can build things for clients | Developer | `developers/[level].md` |
| Can give strategic guidance | Mentor | `mentors/business-mentors.md` or `technical-mentors.md` |
| Create content I can learn from | Content Creator | `content-creators/by-expertise.md` |
| Run paid coaching programs | Coach | `coaches/business-coaches.md` |
| Don't fit above but valuable | General | `general-contacts.md` |

**⚠️ IMPORTANT: Multiple Categories**

**People can (and often do) fit multiple categories. Add them to ALL relevant categories.**

**Examples:**
- Developer who creates content → Add to BOTH `developers/` AND `content-creators/`
- Lead generator who is also a mentor → Add to BOTH `lead-generators/` AND `mentors/`
- Developer who can also bring deals → Add to BOTH `developers/` AND `lead-generators/`

**How to decide:**
1. Read their full raw notes
2. Identify ALL ways they can provide value
3. Add them to EVERY category where they have expertise
4. In each file, emphasize the relevant expertise for that category

**Example: Sway Clarke**
- "Strongest forte is making content" → `content-creators/`
- "Loves doing that on n8n" → `developers/`
- Result: Add to BOTH, emphasizing different aspects in each file

### 2.2.5: Check for NEW Automation Types ⚠️ IMPORTANT

**Before moving forward, scan raw notes for automation types not in our master list.**

1. **Open:** `AUTOMATION-TYPES-MASTER-LIST.md`
2. **Compare:** Automation types mentioned in raw notes vs. master list
3. **If NEW type found:**
   - Add to master list with template:
     ```
     | **[Type Name]** | [Description] | 💡 NEW | [Today's date] | [Who mentioned it + context] |
     ```
   - Add to `developers/index.md` under "By Automation Type"
   - Make note in processing summary: "NEW TYPE FOUND: [Type Name]"

**Examples of what counts as "new":**
- Someone mentions "inventory automation" and it's not on the list → ADD IT
- Someone does "SMS automation" and it's not on the list → ADD IT
- Someone builds "chatbots" and it's not on the list → ADD IT

**Why this matters:** The market tells us what's valuable. New automation types = market opportunities.

### 2.3: Extract Key Details

From your raw notes, identify:
- **Contact info:** Email, LinkedIn, phone
- **What they do:** Business/role
- **AI/Automation expertise:**
  - Platforms they use (n8n, Make.com, Zapier, Claude Code, etc.)
  - Automation types they build (email automation, CRM, voice agents, RAG systems, lead capture, workflows, etc.)
  - Specific projects/builds they've done
  - Specializations (e.g., "voice agent specialist", "CRM automation expert")
- **Lead gen tactics:** How they get clients (warm outreach, events, content, referrals, etc.)
- **Pain points:** What problems do they have?
- **Opportunities:** How can you help them? How can they help you?
- **Relationship stage:** Most new contacts = "Prospective" (not yet contacted)
- **Follow-up priority:** High/Medium/Low

### 2.4: Create Structured Record

1. Open the appropriate category file
2. Find the template in that file
3. Copy template
4. Fill in details from raw notes
5. Set **Relationship Status** to "Prospective" (unless you already messaged them)
6. Add to appropriate section in the file

### 2.5: Update Index Files

After adding contact to category file:

**For Developers/Builders:**
- Update `developers/index.md`
- Add to "By Relationship Stage" → "Prospective" section
- Add to **"By Automation Type"** section (voice agents, CRM, email, RAG, etc.)
- Add to **"By Platform"** section if they specialize (n8n, Make.com, Claude Code, etc.)
- Note their **specialization** (e.g., "Voice agent specialist", "CRM automation expert")

**For Lead Generators:**
- Update `lead-generators/index.md`
- Add to "By Relationship Stage" → "Prospective" section
- Add to "By Niche Coverage" section
- Note their **lead gen tactics** (warm outreach, events, content, etc.)

### 2.6: Draft Follow-Up Message

**For high-priority contacts:**

Create draft message (don't send yet - review first):

```
Template for Initial Reach-Out:

Hi [Name],

Great meeting you at [Event] yesterday. [Specific thing you discussed] really resonated with me.

[One sentence about your background/business]

[Specific value you can offer based on their pain point] - would love to explore if there's a fit.

Would you be open to a quick call this week?

[Your name]
```

**Save draft in:**
- Lead generators: In their contact record under "Next Steps"
- Developers: In their contact record under "Next Steps"
- Others: In their contact record

### 2.7: Mark Raw Notes as Processed

In the raw notes file:
- Check off each person in the processing checklist
- Fill in "Follow-Up Priority" section
- Add key insights
- Rename file to `YYYY-MM-DD-event-name-PROCESSED.md`

---

## Step 3: Execute Follow-Ups (Day After Processing)

**Timing:** Day after processing (2 days after event max)

1. Review all drafted messages
2. Personalize each one
3. Send to high-priority contacts first
4. Update contact record:
   - Change "Relationship Status" from "Prospective" to "Contacted"
   - Add "Last Contact" date
   - Add follow-up reminder (3-5 days if no response)

---

## Step 4: Track Responses

As people respond:

**Update Relationship Status:**
- "Contacted" → "Active Conversation" (they replied)
- "Active Conversation" → "Actively Working With" (project started)
- "Active Conversation" → "Warm/Available" (good convo, no immediate project)

**Update Last Contact date** every time you interact

---

## Example: Processing a Contact

**Raw notes:**
```
Trent Christopher
Automated proposal generator
Workforce email
CRM agent log sales activities easily
Short sprint for 2 weeks, work with them til we can get results
```

**Processing Questions:**
1. **Category?** → Could be Lead Generator (has clients who need automation) OR potential client himself
2. **What's the opportunity?** → Sounds like he does similar work - could be collaborator/lead generator
3. **Priority?** → High - he mentioned specific automation needs
4. **Missing info?** → Need LinkedIn, email, clarity on what his business is

**Action:**
1. LinkedIn search for "Trent Christopher"
2. Determine if he's a lead generator or potential client
3. Add to appropriate file using template
4. Draft follow-up message
5. Update index file
6. Plan to reach out tomorrow

---

## Common Mistakes to Avoid

❌ **Waiting too long to process** - Memory fades fast, process within 24 hours
❌ **Not categorizing** - Just putting everyone in general-contacts defeats the purpose
❌ **Perfect over done** - Don't spend 30 min per contact, 5 min max
❌ **Not following up** - Processing is useless if you don't reach out
❌ **Following up too late** - More than 3 days = you're just another person
❌ **Generic messages** - Reference specific conversation points
❌ **Asking for too much too soon** - Start with value, not asks

---

## Time Budget

| Task | Time | When |
|------|------|------|
| Capture raw notes | 15-30 min | During/after event |
| Process 10 contacts | 45-60 min | Next day |
| Draft 3-5 messages | 20-30 min | Next day |
| Send messages | 10 min | Day after processing |
| **Total per event** | **~2 hours** | **Over 2-3 days** |

**Worth it?** One good lead generator = 5+ deals = $50k+ revenue
ROI on 2 hours of follow-up work = potentially massive

---

## Weekly Review

Every Friday:
- Review "Contacted" contacts who haven't responded
- Send follow-up to non-responders
- Move to "Not Interested" if 2 follow-ups with no response
- Update "Prospective" contacts you haven't reached out to yet

---

## Weekly Review: Market Intelligence Update

**Timing:** End of week after processing all events

### Update Automation Types Master List

1. **Open:** `AUTOMATION-TYPES-MASTER-LIST.md`
2. **Review this week's events:**
   - How many times was each automation type mentioned?
   - Any new types discovered?
   - Update demand levels (🔥 HOT, 📈 GROWING, 📊 STEADY, 💡 EMERGING)

3. **Update Market Trends section:**
   ```markdown
   ### Week of [Date]

   **Hottest Types (5+ mentions):**
   - [Type] ([X] mentions)

   **Growing Types (3-4 mentions):**
   - [Type] ([X] mentions)

   **Strategic Insight:**
   - [What the market is telling you]
   ```

4. **Check for patterns:**
   - Same automation type mentioned at multiple events? → Market signal
   - Multiple people doing the same thing? → Competitive intelligence
   - New platform everyone's using? → Learn it or recruit specialist

### Example Weekly Review

```
Week of 2025-11-24: Processed EU (11/24) + US (11/25)
- Total contacts: 16 people
- NEW types found: None (all matched existing list)
- Hottest types: CRM (6 mentions), Voice Agents (4 mentions)
- Strategic action: Build CRM + voice agent specialist pipeline
- Market trend: "AI audit before implementation" approach emerging
```

---

## Success Metrics

You're doing this right when:
- ✅ No contacts are lost (everyone gets filed)
- ✅ Follow-up happens within 48 hours
- ✅ Every contact knows their category and value
- ✅ Index files stay current
- ✅ Automation types master list is updated weekly
- ✅ You can see market trends emerging
- ✅ Your network is growing systematically
- ✅ Deals start coming from your network

---

## Quick Reference Card

```
DAY OF EVENT:
□ Capture raw notes in raw-notes/YYYY-MM-DD-event.md
□ Get contact info for everyone interesting
□ Note automation types, platforms, projects mentioned

DAY AFTER EVENT (Processing):
□ Open AUTOMATION-TYPES-MASTER-LIST.md
□ Check for NEW automation types not on list
□ If new type found → Add to master list + index files
□ Process each contact (5 min per person)
□ Categorize and add to appropriate file
□ Update index files (by automation type, platform, lead gen tactic)
□ Draft high-priority follow-up messages
□ Mark raw notes as PROCESSED

2 DAYS AFTER EVENT:
□ Send follow-up messages
□ Update contacts to "Contacted" status
□ Set follow-up reminders

END OF WEEK (After all events processed):
□ Update automation types demand levels
□ Update market trends in master list
□ Identify strategic opportunities
□ Follow up with non-responders
□ Update relationship statuses
□ Plan next moves for active conversations
```

---

## Questions?

- "I met 20+ people, do I process all of them?" → Yes, but prioritize. Process high-value contacts first.
- "What if I can't categorize someone?" → Put in general-contacts.md temporarily, recategorize later when clearer
- "Do I need LinkedIn for everyone?" → Not required, but helpful. Email is minimum.
- "Should I connect on LinkedIn before reaching out?" → Yes, connect + message together
- "What if they don't respond?" → Follow up once after 3-5 days, then move to "Not Interested" after 2nd no response
- **"How do I know if an automation type is NEW?"** → Check AUTOMATION-TYPES-MASTER-LIST.md. If it's not listed, it's new. Add it!
- **"What if someone mentions multiple automation types?"** → Add them to all relevant sections in developers/index.md
- **"Someone builds 'blockchain automation' - is that new?"** → If not on master list, YES. Add it. Market tells us what matters.

---

## The 24-Hour Rule

**Most important rule: Process within 24 hours.**

Why? Because:
- Memory fades fast
- Other people are following up faster
- You lose momentum
- They forget who you are
- Opportunities disappear

Set a calendar reminder: **"Process [Event] contacts"** for the day after every networking event.
