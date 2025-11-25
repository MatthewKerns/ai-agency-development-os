# Network Contacts & Skills Directory

## Purpose
Strategic contact management system for building an AI automation agency. Track everyone you meet, organized by how they help you reach $50k/mo OBG.

---

## Directory Structure

```
network-contacts/
├── developers/              # P2 Priority - Delegation capability
│   ├── junior-developers.md
│   ├── mid-level-developers.md
│   ├── senior-developers.md
│   ├── specialists.md
│   └── index.md
├── lead-generators/         # P0 Priority - Revenue generation
│   ├── by-niche.md
│   ├── by-network.md
│   └── index.md
├── mentors/                 # Strategic guidance
│   ├── business-mentors.md
│   ├── technical-mentors.md
│   └── index.md
├── coaches/                 # Paid coaching investments
│   ├── business-coaches.md
│   └── index.md
├── content-creators/        # Learning & partnerships
│   ├── by-expertise.md
│   ├── by-platform.md
│   └── index.md
└── general-contacts.md      # Everyone else
```

---

## Relationship Status Tracking

Every contact has a **Relationship Status** field to track where they are in your pipeline:

| Status | Definition | Next Action |
|--------|------------|-------------|
| **Prospective** | Not yet contacted, preparing message | Draft outreach message |
| **Contacted** | Reached out, awaiting response | Follow up if no response in 3-5 days |
| **Active Conversation** | Engaging back and forth | Keep conversation moving |
| **Actively Working With** | Currently doing projects together | Maintain relationship, track performance |
| **Warm/Available** | Good relationship, available when needed | Check in monthly/quarterly |
| **Inactive/Dormant** | Haven't spoken in 3+ months | Reactivation campaign |
| **Not Interested** | Declined or not a fit | Archive, revisit in 6-12 months |

**Usage:**
- Update status whenever relationship changes
- Use index files to see all contacts at each stage
- Focus activation efforts on "Prospective" and "Contacted" stages

---

## The 5 Contact Categories

### 1. Developers (Delegation)
**Purpose:** Build your developer pipeline for P2 priority

**Track by:**
- Experience level (Junior, Mid, Senior)
- Tech stack
- What they've built
- Rate and availability
- Margin potential

**When to use:**
- Finding developers for client projects
- Evaluating cost vs quality
- Building your "bench" of reliable contractors

**Key files:**
- `developers/index.md` - Quick lookup by tech or skill
- Level-specific files for detailed profiles

---

### 2. Lead Generators (Revenue)
**Purpose:** People who can bring you deals - critical for P0 priority

**Track by:**
- Niche they work in
- Networks they're plugged into
- Deal flow potential
- Commission structure

**When to use:**
- Finding people like Linh/Mikael who can bring clients
- Mapping which networks contain your target clients
- Activating referral relationships

**Key files:**
- `lead-generators/by-niche.md` - "Who brings deals in [industry]?"
- `lead-generators/by-network.md` - "Who has access to [community]?"
- `lead-generators/index.md` - Performance tracking

---

### 3. Mentors (Guidance)
**Purpose:** Free/reciprocal guidance from people who've been there

**Track by:**
- Business mentors (agency, sales, ops)
- Technical mentors (AI, development)
- When to reach out to each

**When to use:**
- Stuck on a strategic decision
- Need outside perspective
- Specific challenge in their expertise area

**Key files:**
- `mentors/index.md` - "Who do I ask about [problem]?"

---

### 4. Coaches (Paid Programs)
**Purpose:** Structured paid coaching relationships

**Track:**
- Program costs and ROI
- What's included
- Decision criteria

**When to use:**
- Evaluating coaching investments
- Tracking active coaching ROI
- Deciding if coaching solves current bottleneck

**Key files:**
- `coaches/index.md` - Decision framework + active investments

---

### 5. Content Creators (Learning & Partnerships)
**Purpose:** Learn from experts, potential collaboration opportunities

**Track by:**
- Expertise area
- Platform
- Audience size and overlap
- Partnership potential

**When to use:**
- Finding people to learn from
- Identifying collaboration opportunities
- Mapping creators whose audience = your target clients

**Key files:**
- `content-creators/by-expertise.md` - "Who teaches [topic]?"
- `content-creators/by-platform.md` - Organized by where they create

---

## Weekly Workflow

### After Every Networking Event

1. **Same Day: Categorize & Add**
   - Developers → `developers/[level].md`
   - Potential sales partners → `lead-generators/by-niche.md` or `by-network.md`
   - Mentors → `mentors/[type].md`
   - Content creators → `content-creators/by-expertise.md`
   - Everyone else → `general-contacts.md`

2. **Next Day: Follow Up**
   - Send personalized connection messages
   - Update index files for quick lookup
   - Add to daily plan for specific follow-up tasks

3. **Weekly: Review**
   - Check pending follow-ups
   - Move conversations forward
   - Update relationship status
   - Activate high-value relationships

---

## Quick Search Examples

```bash
# Find developers by technology
grep -i "react" claude-code-os-implementation/05-hr-department/network-contacts/developers/index.md

# Find lead generators in specific niche
grep -i "e-commerce" claude-code-os-implementation/05-hr-department/network-contacts/lead-generators/by-niche.md

# Find who has access to a network
grep -i "mastermind" claude-code-os-implementation/05-hr-department/network-contacts/lead-generators/by-network.md

# Find mentor for specific problem
grep -i "pricing" claude-code-os-implementation/05-hr-department/network-contacts/mentors/index.md

# Find content creators teaching specific topic
grep -i "AI automation" claude-code-os-implementation/05-hr-department/network-contacts/content-creators/by-expertise.md
```

---

## Strategic Alignment with OBG ($50k/mo)

### P0: Revenue (Lead Generators)
**Most important right now**
- Track everyone who can bring deals
- Map networks where target clients hang out
- Activate referral partnerships
- Commission structures clear

### P2: Developer Pipeline (Developers)
**Critical for delegation**
- Build bench of reliable contractors
- Know who to call for each tech stack
- Evaluate margin potential
- Never scramble to find developers

### Learning & Growth (Mentors, Coaches, Content Creators)
**Support the journey**
- Get unstuck faster
- Learn from people ahead of you
- Make better strategic decisions
- Potential collaboration opportunities

---

## Integration with Agency Flow

```
Lead Generator brings opportunity
   ↓
You run diagnostic call ($200-500/hr)
   ↓
You prototype solution
   ↓
Client says YES
   ↓
You find developer from your pipeline (developers/index.md)
   ↓
You price with margin
   ↓
You deliver and collect
```

**This system ensures:**
- You always know who to call for what
- Your network grows systematically
- Every person is categorized by value
- Nothing falls through cracks

---

## Maintenance Rules

### Daily
- Add contacts from events same day
- Send follow-up messages next day

### Weekly
- Review pending follow-ups
- Update index files
- Activate high-priority relationships

### Monthly
- Audit each category
- Reach out to dormant valuable contacts
- Update relationship statuses
- Remove irrelevant contacts

### Quarterly
- Full directory review
- Track ROI from each category
- Identify gaps in network
- Strategic relationship building

---

## Pro Tips

1. **Add context immediately** - Details fade fast, add contacts same day
2. **Use templates consistently** - Makes searching/comparing easier
3. **Update index files** - Quick lookups save massive time
4. **Track reciprocity** - What can you give, not just get
5. **Relationship stages matter** - Don't burn new relationships with big asks
6. **Quality over quantity** - 10 solid contacts > 100 weak ones
7. **Activate strategically** - Focus on P0 (lead generators) first

---

## Common Use Cases

### "I need a React developer for a $5k project"
1. Open `developers/index.md`
2. Search for React
3. Filter by availability and rate
4. Check margin potential
5. Reach out to top 2-3

### "I want deals in e-commerce niche"
1. Open `lead-generators/by-niche.md`
2. Find e-commerce section
3. See who's already plugged in
4. If none, attend e-commerce events to meet connectors

### "I'm stuck on pricing this deal"
1. Open `mentors/index.md`
2. Find business mentor who knows pricing
3. Reach out with specific question
4. Get unstuck fast

### "I want to learn more about AI agents"
1. Open `content-creators/by-expertise.md`
2. Find AI/automation section
3. Follow top creators
4. Learn systematically

---

## Success Metrics

**You'll know this system is working when:**
- You never say "I wish I knew someone who..."
- You can fill any role within 48 hours
- Lead flow is consistent from network
- You have mentors to call when stuck
- Your network compounds week over week

---

## Getting Started

### Today (After EU Event)
1. Add all EU contacts to appropriate categories
2. Send connection messages tomorrow
3. Update index files

### This Week
1. Identify gaps (e.g., "I have no lead generators in SaaS")
2. Attend events to fill gaps
3. Activate 2-3 high-value relationships

### This Month
1. Have 5+ developers in pipeline
2. Have 3+ lead generators activated
3. Have 2+ mentors relationship established
4. System becomes routine

---

**Remember:** Your network is an asset that compounds. Every week you maintain this system, your network becomes more valuable. The Architect doesn't build everything - they know who to call.
