# Network Contacts & Skills Directory

## Purpose
Track everyone you meet at networking events, conferences, and professional gatherings. Build a searchable database of people and their skills so you can later ask "who knows how to do X?"

## How It Works

### 1. After Every Event
Add contacts to `contacts-database.md` using the template below

### 2. Update Skills Index
The `skills-index.md` file organizes people by what they can do

### 3. Quick Search
Use grep or search to find:
- "Who knows React?" → Search skills-index.md
- "Who did I meet at EU event?" → Search contacts-database.md
- "Who works in AI automation?" → Search by industry/specialty

## Contact Entry Template

```markdown
---
### [Full Name]
**Met:** [Date] at [Event Name]
**Location:** [City/Country]
**Contact:** [Email/LinkedIn/Phone]

**What They Do:**
[Their business/role/company]

**Skills & Expertise:**
- [Skill 1]
- [Skill 2]
- [Skill 3]

**Potential Value:**
[How they might help you or you might help them]

**Next Steps:**
- [ ] Send connection message
- [ ] Follow up about [specific topic]

**Notes:**
[Any important context, conversation highlights, mutual connections]

---
```

## Usage Examples

### After Event
1. Open `contacts-database.md`
2. Add each person using the template
3. Update `skills-index.md` with their skills
4. Add follow-up tasks to your daily plan

### When Looking for Help
1. Search skills-index.md for the skill you need
2. Find people who have that capability
3. Reach out with specific request

### Weekly Review
- Check pending follow-ups
- Send connection messages
- Move conversations forward
- Archive completed connections

## Quick Commands

```bash
# Find who knows a specific skill
grep -i "react" claude-code-os-implementation/05-hr-department/network-contacts/skills-index.md

# Find contacts from specific event
grep -i "eu networking" claude-code-os-implementation/05-hr-department/network-contacts/contacts-database.md

# List all pending follow-ups
grep -A 3 "Next Steps:" claude-code-os-implementation/05-hr-department/network-contacts/contacts-database.md
```

## Integration with Agency Flow

- **For Trevor-type projects:** Find developers, designers, specialists
- **For client acquisition:** Find businesses that need automation
- **For partnerships:** Find complementary service providers
- **For hiring:** Find potential team members (future Sales, Biz Dev)
