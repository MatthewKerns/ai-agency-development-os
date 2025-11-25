# Automation Types Master List

**Purpose:** Single source of truth for all automation types we track. This list evolves as new types emerge from networking events.

**Last Updated:** 2025-11-25

---

## How This Works

1. **During Processing:** When you find a NEW automation type in raw notes that's not on this list, ADD IT
2. **Update Index Files:** After adding a new type here, update `developers/index.md`
3. **Track Demand:** Note how many times each type is mentioned to identify trends

---

## Current Automation Types

### Core Automation Types (Established)

| Type | Description | Demand Level | First Seen | Examples from Network |
|------|-------------|--------------|------------|----------------------|
| **Voice Agents/AI** | AI voice systems, phone agents, voice assistants | 🔥 HOT | 2025-11-25 | Josh Packer (voice agent specialist), Bogdan (voice SaaS for sales training) |
| **CRM Automation** | Automated CRM workflows, activity logging, sales tracking | 🔥 HOT | 2025-11-25 | Trent, Chris Andrade, Josh (multiple mentions at US event) |
| **Email Automation** | Email campaigns, automated sequences, email tracking | 📈 GROWING | 2025-11-25 | Trent (campaign automation), Rishi (email tracking via sheets) |
| **RAG Systems** | Chat with documents, knowledge base systems | 📈 GROWING | 2025-11-25 | Trent ("drop document and chat with it") |
| **Document Processing** | OCR, data extraction, classification, technical manuals | 📈 GROWING | 2025-11-25 | Trent (technical manuals processing) |
| **Proposal/Quote Generation** | Automated proposal creation, quote systems | 📈 GROWING | 2025-11-25 | Trent (automated proposal generator) |
| **Lead Capture** | Lead collection, qualification, routing | 📈 GROWING | 2025-11-25 | Multiple mentions |
| **Sales Workflows** | End-to-end sales process automation | 📈 GROWING | 2025-11-25 | Trent, Rishi |
| **Process Automation** | General workflow automation, task automation | 📊 STEADY | 2025-11-24 | Sway Clarke (n8n workflows) |
| **AI Training/Audits** | AI readiness audits, process documentation, training | 💡 EMERGING | 2025-11-24 | Scott (£8k deal), Mekaiel (audit approach) |
| **Custom AI Development** | Bespoke AI solutions, custom models | 📊 STEADY | 2025-11-24 | Simon (salon AI), Scott |
| **Inventory Systems** | Inventory tracking, stock management automation | 📊 STEADY | 2025-11-25 | Chris Andrade (CRM + inventory) |
| **Database Integration** | Automated database updates, triggers | 📊 STEADY | 2025-11-25 | Trent (quote triggers updating database) |
| **Assessment/Quiz Building** | Interactive assessments, quizzes for lead generation and competence demonstration | 💡 EMERGING | 2025-11-11 | Katrina Roddy ("Are You AI Ready?" 7-question assessment), Jacob Marchand (quiz approach) |

---

## Platforms/Tools (Updated as discovered)

| Platform | Type | Expertise Level in Network | First Seen | Examples |
|----------|------|----------------------------|------------|----------|
| **n8n** | No-code automation | 📈 GROWING | 2025-11-24 | Sway Clarke (specialist) |
| **Make.com** | No-code automation | 📊 STEADY | 2025-11-25 | Multiple mentions |
| **Zapier** | No-code automation | 📊 STEADY | 2025-11-25 | Multiple mentions |
| **Claude Code** | AI coding assistant | 📈 GROWING | 2025-11-24 | Simon (enthusiast, 4 deals/4 weeks) |
| **Google Sheets** | Automation connector | 📊 STEADY | 2025-11-24 | Rishi (email tracking) |
| **Custom Code** | Python, Node.js, etc. | 📊 STEADY | Various | Multiple |
| **EventBrite** | Event platform + ads | 💡 EMERGING | 2025-11-11 | Katrina Roddy (500-800 registrations per event) |
| **Score App** | Quiz/assessment builder | 💡 EMERGING | 2025-11-11 | Jacob Marchand (quiz lead gen) |
| **Lovable** | Assessment builder | 💡 EMERGING | 2025-11-11 | Katrina Roddy ("Are You AI Ready?" assessment) |
| **Meetup** | Social networking platform | 💡 EMERGING | 2025-11-11 | Jacob Marchand (considered for events) |

---

## Lead Generation Tactics (Updated as discovered)

| Tactic | Effectiveness | First Seen | Examples |
|--------|--------------|------------|----------|
| **Warm Outreach** | ✅ PROVEN | 2025-11-24 | Nathan, Tomasz (3 customers), multiple confirmations |
| **Event Networking** | ✅ PROVEN | 2025-11-24 | Rishi (4 clients from events) |
| **Content Creation** | 📈 GROWING | 2025-11-24 | Sway (targeting business owners via content) |
| **Referral Networks** | ✅ PROVEN | 2025-11-24 | Senthil (BNI referrals) |
| **Cold Outreach/Automation** | 📊 TESTING | 2025-11-24 | Rishi (automated email tracking) |
| **Community Access** | ✅ PROVEN | 2025-11-24 | Senthil (BNI), Ken (Chamber of Commerce) |
| **Workshop/Training Events** | 💡 EMERGING | 2025-11-25 | Trent (2hr vibe coding workshops) |
| **EventBrite Events + Ads** | ✅ PROVEN | 2025-11-11 | Katrina Roddy (500-800 registrations, 3-week timeline, EventBrite ads) |
| **Quiz/Assessment Lead Magnets** | 💡 EMERGING | 2025-11-11 | Katrina Roddy (AI readiness assessment), Jacob Marchand (competence demonstration) |
| **Demo Video Outreach** | 💡 EMERGING | 2025-11-11 | Andrew Alva ("Film a demo and send it") |

---

## How to Add New Types

### When Processing Raw Notes:

**Found a new automation type not on this list?**

1. **Add it to this file** in the appropriate section
2. **Fill in the template:**
   ```
   | **[Type Name]** | [Description] | 💡 NEW | [Today's date] | [Who mentioned it + context] |
   ```

3. **Update `developers/index.md`** - Add new section under "By Automation Type"

4. **Update `junior-developers.md` stats** if it's a common type

5. **Note in processing notes** - This helps track market trends

### Example: Adding "Chatbot Development"

If you meet someone who builds chatbots and it's not on the list:

**Step 1: Add to this file**
```markdown
| **Chatbot Development** | Custom chatbots, conversational AI | 💡 NEW | 2025-11-26 | Jane Doe (builds chatbots for e-commerce) |
```

**Step 2: Add to developers/index.md**
```markdown
### Chatbot Development
- Jane Doe - [E-commerce chatbots] - [Rate] - [Availability]
```

**Step 3: Make note**
```
Found new automation type: Chatbot Development
Source: Jane Doe at US Networking 11/26
Market signal: E-commerce companies need this
```

---

## Demand Level Definitions

| Symbol | Meaning | Action |
|--------|---------|--------|
| 🔥 HOT | 5+ mentions, high urgency | Build specialist pipeline NOW |
| 📈 GROWING | 3-4 mentions, increasing interest | Monitor, prepare to scale |
| 📊 STEADY | 1-2 mentions, consistent demand | Keep on radar |
| 💡 EMERGING | First mention, potential trend | Watch for repeat mentions |
| ⚠️ DECLINING | Was hot, now fading | Deprioritize |

---

## Market Trends Analysis

### Week of 2025-11-24 (2 events: EU + US)

**Hottest Types (5+ mentions):**
1. CRM Automation (6 mentions)
2. Voice Agents (4 mentions)

**Growing Types (3-4 mentions):**
3. Email Automation (3 mentions)
4. Document Processing (3 mentions)
5. AI Audits/Training (2 mentions, but both with revenue proof)

**Strategic Insight:**
- CRM + Voice AI = immediate opportunity (highest demand)
- AI Audit approach (Mekaiel/Scott) = smart positioning (audit before implementation)
- Document processing (Trent mentions) = complement to RAG systems

---

## Weekly Review Checklist

Every week after processing all events:

- [ ] Review new automation types discovered
- [ ] Update demand levels based on mention frequency
- [ ] Identify trends (what's heating up? what's cooling down?)
- [ ] Update strategic priorities based on demand
- [ ] Ensure all new types are added to index files

---

## Notes Section

### 2025-11-25: Initial List Created
- Based on US Networking (11/25) and EU Networking (11/24)
- Total contacts processed: ~16 people
- Clear signals: CRM automation and voice agents are HOT
- Emerging trend: "AI audit first, then implementation" approach (Mekaiel + Scott model)

### 2025-11-11: New Types and Tactics Added
- Based on US Networking (11/11)
- Total contacts processed: 4 people
- **NEW AUTOMATION TYPE:** Assessment/Quiz Building
- **NEW PLATFORMS:** EventBrite, Score App, Lovable, Meetup
- **NEW LEAD GEN TACTICS:** EventBrite Events + Ads (500-800 registrations), Quiz/Assessment Lead Magnets, Demo Video Outreach
- **KEY INSIGHT:** "Can't automate chaos" - process-first philosophy (Katrina Roddy)
- **PROVEN TACTIC:** EventBrite + ads = 500-800 registrations per event (3-week timeline)
- **POTENTIAL CLIENT:** Denis Daigle (voice AI call handling for product business)
- **STRATEGIC TREND:** Assessments as lead magnets + competence demonstration (Katrina + Jacob)

### [Date]: [Your notes on new types, trends, insights]

---

## Contact Examples by Type

### Voice Agents
- **Josh Packer** - Voice agent specialist
- **Bogdan Dragomir** - Voice SaaS for sales agent training (3 months experience)
- **Denis Daigle** - POTENTIAL CLIENT (call handling automation for product business)

### CRM Automation
- **Trent Christopher** - CRM agent log sales activities
- **Chris Andrade** - Basic CRM + inventory integration
- **Josh Packer** - (mentioned in context)

### Email Automation
- **Trent Christopher** - Email campaigns, automated sequences
- **Rishi Gupta** - Email tracking via Google Sheets automation

### Document Processing
- **Trent Christopher** - Technical manuals processing, quote processing triggers

### AI Training/Audits
- **Scott** - AI training, audits, custom dev (£8k deal → retainer)
- **Mekaiel** - AI audit + transformation 2026, phase 1 = audit + refining processes

### RAG Systems
- **Trent Christopher** - "Drop document and chat with it"

### Assessment/Quiz Building
- **Katrina Roddy** - "Are You AI Ready?" assessment (7 questions, 3 categories, process-first)
- **Jacob Marchand** - Quiz approach for competence demonstration + lead gen

### Platform Specialists
- **n8n:** Sway Clarke
- **Claude Code:** Simon (4 deals in 4 weeks)
- **EventBrite:** Katrina Roddy (500-800 registrations per event)
- **Score App:** Jacob Marchand (quiz lead gen)
- **Lovable:** Katrina Roddy (assessment builder)

---

**This list is LIVING. Update it every time you process networking notes and find something new.**
