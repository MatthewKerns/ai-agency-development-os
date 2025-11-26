# Monday Fundamentals Series Overview

**Theme:** Core coding principles that every developer should master

**Publishing Day:** Monday at 9:00 AM

**Target Audience:** Junior to mid-level developers who want to level up their coding fundamentals

---

## Series Objectives

### Primary Goals
1. Teach foundational coding practices from Code Complete 2 and Clean Code
2. Provide before/after code examples showing clear improvement
3. Focus on immediate, actionable changes developers can make today
4. Build confidence in core coding skills

### Success Metrics
- Engagement rate: Highest on code example posts
- Save/share rate: Developers bookmark for reference
- Comment themes: "I didn't know this" or "wish I learned this earlier"

---

## Source Material

**Primary Sources:**
- `01-foundations/VARIABLE_NAMING.md` (36,000 words)
- `01-foundations/FUNCTIONS_AND_ROUTINES.md`
- `01-foundations/ERROR_HANDLING.md`
- `01-foundations/CODE_FORMATTING.md`
- `01-foundations/DEFENSIVE_PROGRAMMING.md`
- `01-foundations/DATA_STRUCTURES.md`

**Secondary Sources:**
- Code Complete 2 (Chapters 5-12)
- Clean Code (Chapters 2-3, 10)

---

## 12-Week Topic Progression

### Weeks 1-4: Naming and Readability
**Focus:** The foundation - if you can't name it well, you can't code it well

**Week 1:** Variable Naming Conventions
- Angle: "Your variable names are lying to you"
- Hook: 60-70% of dev time is reading code, not writing
- Key Principle: Intention-revealing names
- Code Example: d = 14 vs elapsed_days_since_creation = 14

**Week 2:** Function Naming and Design
- Angle: "How long should a function be? (Shorter than you think)"
- Hook: One function, one job, one level of abstraction
- Key Principle: Single Responsibility Principle
- Code Example: 50-line function vs 3 well-named 10-line functions

**Week 3:** Class and Method Naming
- Angle: "Classes are nouns, methods are verbs"
- Hook: Naming reveals design problems
- Key Principle: Domain-driven naming
- Code Example: DataManager vs CustomerAccountRepository

**Week 4:** Context Through Naming
- Angle: "Stop using comments to explain bad names"
- Hook: If you need a comment, the name is wrong
- Key Principle: Self-documenting code
- Code Example: Adding meaningful context without redundancy

### Weeks 5-8: Functions and Structure
**Focus:** How to write functions that don't make future you cry

**Week 5:** Function Length and Complexity
- Angle: "The function that's too long to understand"
- Hook: If you can't see it all on screen, it's too long
- Key Principle: Extract till you drop
- Code Example: Nested conditionals vs extracted methods

**Week 6:** Function Arguments
- Angle: "3 arguments is too many. Here's why."
- Hook: The more arguments, the harder to test
- Key Principle: Flag arguments are evil
- Code Example: processOrder(item, user, discount, tax, shipping) vs processOrder(orderRequest)

**Week 7:** Command-Query Separation
- Angle: "Functions should DO something or ANSWER something, not both"
- Hook: Side effects hide in functions that return values
- Key Principle: Command-Query Separation
- Code Example: saveUser() vs getUser() vs getUserAndSave() (bad)

**Week 8:** Error Handling in Functions
- Angle: "Don't return null. Return an object that represents 'nothing'."
- Hook: Null checks everywhere = code smell
- Key Principle: Use exceptions, not error codes
- Code Example: if (user != null) hell vs Optional pattern

### Weeks 9-12: Data and Defensive Programming
**Focus:** Protect your code from bad data and bad assumptions

**Week 9:** Defensive Programming Basics
- Angle: "Never trust user input (here's why)"
- Hook: Every input is malicious until proven otherwise
- Key Principle: Guard clauses and assertions
- Code Example: Validate everything at boundaries

**Week 10:** Data Structure Selection
- Angle: "Array vs HashMap: Pick the right one or pay the performance price"
- Hook: O(n) vs O(1) lookups matter
- Key Principle: Choose the right tool for the job
- Code Example: Linear search vs hash lookup

**Week 11:** Immutability Patterns
- Angle: "Stop mutating variables. Your future self will thank you."
- Hook: Bugs hide in mutation
- Key Principle: Prefer const/final/readonly
- Code Example: Mutable state bugs vs immutable clarity

**Week 12:** Code Formatting Standards
- Angle: "Let the formatter handle formatting (so you can focus on logic)"
- Hook: Formatting debates are a waste of time
- Key Principle: Automate style, focus on substance
- Code Example: Prettier/Black/gofmt in action

---

## Post Type Patterns

### Type 1: Before/After Code Examples (60% of posts)
**Structure:**
```markdown
**[Hook: Bold problem statement]**

[Why this pattern hurts]

❌ Bad Example:
```code
[10-15 lines of problematic code]
```

✅ Good Example:
```code
[10-15 lines of better code]
```

**Why this matters:** [Explain benefit]

**Apply it today:** [Specific action]

[Engagement question]
```

**Best For:** Variable naming, function design, error handling

**Example Topics:**
- Variable names that require mental mapping
- Functions doing too much
- Error handling that hides failures

### Type 2: Principle + Code Snippet (30% of posts)
**Structure:**
```markdown
**[Hook: Pattern or principle statement]**

[Problem paragraph]

**The principle:** [State it clearly]

**Example:**
```code
[15-20 lines showing principle in action]
```

**Why it works:** [2-3 sentences]

**Apply it:** [Checklist or quick steps]

[Engagement question]
```

**Best For:** Design principles, programming patterns

**Example Topics:**
- Single Responsibility Principle
- Command-Query Separation
- Immutability benefits

### Type 3: Common Mistakes (10% of posts)
**Structure:**
```markdown
**[Hook: "3 mistakes..." or "5 ways..."]**

**Mistake #1:** [Name it]
❌ [What it looks like]
✅ [How to fix it]
**Cost:** [Impact]

**Mistake #2:** [Name it]
...

**The fix:** [Quick checklist or action plan]

[Engagement question]
```

**Best For:** Aggregating related anti-patterns

**Example Topics:**
- 3 variable naming mistakes
- 5 function design errors
- 4 defensive programming failures

---

## Key Principles to Cover

### From Code Complete 2
- [ ] Optimal variable name length (10-16 characters)
- [ ] Name length proportional to scope
- [ ] Use computed value qualifiers consistently
- [ ] Functions should be 1-2 screens max
- [ ] Limit function arguments to 3-4
- [ ] Guard clauses for defensive programming
- [ ] Choose data structures based on access patterns

### From Clean Code
- [ ] Intention-revealing names
- [ ] Avoid disinformation in names
- [ ] Make meaningful distinctions
- [ ] Use pronounceable names
- [ ] Use searchable names
- [ ] Avoid mental mapping
- [ ] One level of abstraction per function
- [ ] Extract till you drop
- [ ] Don't return null

---

## Hook Patterns for Fundamentals

### Pattern 1: Stat/Research Hook
- "Developers spend 60-70% of their time reading code..."
- "Studies show the optimal function length is..."
- "Research proves that X lines of code..."

### Pattern 2: Bold Claim
- "Your variable names are lying to you."
- "If you can't see it all on screen, it's too long."
- "3 arguments is too many."

### Pattern 3: Common Pain Point
- "You've written this function. You'll regret it in 6 months."
- "Every time you see 'temp' or 'data' you lose 10 seconds..."
- "Null checks everywhere = code smell"

### Pattern 4: Before/After Contrast
- "Here's what junior devs do vs senior devs..."
- "This code works. This code works AND is readable."
- "Both compile. Only one is maintainable."

---

## Engagement Strategies

### Questions That Spark Discussion
- "What's the worst variable name you've encountered?"
- "How long is too long for a function?"
- "What fundamentals do you wish you'd learned earlier?"
- "Do you use a formatter? Which one?"
- "What's your rule for number of function arguments?"

### Call-to-Actions
- "Pick one function you wrote this week and apply this principle"
- "Find variables named 'temp' or 'data' in your code today"
- "Run a linter/formatter on your project this week"
- "Refactor one long function today"
- "Review your latest PR for these patterns"

---

## Content Rotation Strategy

### Cycle 1 (Weeks 1-4): Introduction
- Present each principle once
- Focus on "what" and "why"
- Simple, clear examples
- Build foundational understanding

### Cycle 2 (Weeks 5-8): Application
- Same principles, different angles
- Real-world scenarios
- More complex examples
- Show edge cases and exceptions

### Cycle 3 (Weeks 9-12): Mastery
- Advanced techniques
- Principle combinations
- Refactoring case studies
- Performance implications

**After Week 12:** Repeat cycle with new examples, different languages, community questions

---

## Multi-Language Examples

To maximize reach, rotate languages across weeks:

**Week 1:** Python example
**Week 2:** TypeScript example
**Week 3:** Java example
**Week 4:** Python example
*[Continue rotation]*

**Languages to Feature:**
- Python (most accessible, concise syntax)
- TypeScript (web dev audience, type safety)
- Java (enterprise audience, verbosity shows problems clearly)
- Go (growing popularity, simplicity)
- JavaScript (largest developer audience)

---

## Success Indicators

### Week 1-4 Baseline
- Likes: 20-50 per post
- Comments: 5-10 per post
- Shares: 2-5 per post

### Week 5-8 Growth
- Likes: 50-100 per post
- Comments: 10-20 per post
- Shares: 5-10 per post

### Week 9-12 Established
- Likes: 100-200 per post
- Comments: 20-30 per post
- Shares: 10-20 per post

### Quality Metrics
- Comments saying "I didn't know this"
- Developers sharing with their teams
- Questions about how to apply principles
- Examples from their own code

---

## Topics to Avoid

- Overly theoretical concepts without code examples
- Language wars (Python vs Java debates)
- Framework-specific patterns (keep it fundamental)
- Advanced algorithms (save for different series)
- Controversial practices without nuance

---

## Quick Reference: Week-by-Week Topics

| Week | Topic | Source File | Post Type |
|------|-------|-------------|-----------|
| 1 | Variable Naming | VARIABLE_NAMING.md | Before/After |
| 2 | Function Design | FUNCTIONS_AND_ROUTINES.md | Before/After |
| 3 | Error Handling | ERROR_HANDLING.md | Before/After |
| 4 | Code Formatting | CODE_FORMATTING.md | Principle + Code |
| 5 | Function Length | FUNCTIONS_AND_ROUTINES.md | Before/After |
| 6 | Function Arguments | FUNCTIONS_AND_ROUTINES.md | Common Mistakes |
| 7 | Variable Naming (advanced) | VARIABLE_NAMING.md | Principle + Code |
| 8 | Error Handling (patterns) | ERROR_HANDLING.md | Before/After |
| 9 | Defensive Programming | DEFENSIVE_PROGRAMMING.md | Before/After |
| 10 | Data Structures | DATA_STRUCTURES.md | Principle + Code |
| 11 | Immutability | Multiple sources | Before/After |
| 12 | Code Formatting (automation) | CODE_FORMATTING.md | Quick Win |

---

**Last Updated:** 2025-11-25
**Status:** Active series, Week 1 posts created
**Next Review:** After Week 4 (assess engagement and adjust)
