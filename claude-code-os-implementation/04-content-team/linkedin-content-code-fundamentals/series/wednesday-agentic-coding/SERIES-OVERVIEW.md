# Wednesday Agentic Coding Series Overview

**Theme:** How to 10x your productivity with AI coding assistants

**Publishing Day:** Wednesday at 9:00 AM

**Target Audience:** Developers using (or curious about) AI assistants like Claude Code, GitHub Copilot, or ChatGPT for development

---

## Series Objectives

### Primary Goals
1. Teach effective collaboration with AI coding assistants
2. Explain context management strategies for better code generation
3. Provide prompt engineering patterns that work
4. Show real productivity gains (not hype)

### Success Metrics
- Engagement rate: Highest on "context" posts (developers struggling with this)
- Save/share rate: Prompt patterns get bookmarked
- Comment themes: "This unlocked AI for me" or "Now I understand context"

---

## Source Material

**Primary Sources:**
- `07-agentic-coding/context/WHAT_IS_CONTEXT.md`
- `07-agentic-coding/context/WHY_CONTEXT_MATTERS.md`
- `07-agentic-coding/context-filling-strategies/EFFICIENT_CONTEXT_TRANSFER.md`
- `07-agentic-coding/context-filling-strategies/CLARIFYING_QUESTIONS_PROTOCOL.md`
- `07-agentic-coding/optimization/CONTEXT_WINDOW_OPTIMIZATION.md`
- `07-agentic-coding/optimization/PARALLEL_EXECUTION_PATTERNS.md`

**Coverage:**
- 15+ guides in agentic-coding section
- ~50,000 words of content
- Practical, battle-tested patterns

---

## 12-Week Topic Progression

### Weeks 1-3: Context Fundamentals
**Focus:** Understanding the foundation of AI coding

**Week 1:** What Is Context
- Angle: "Why AI gives you bad code (and how to fix it)"
- Hook: AI isn't a search engine—it's working from a context window
- Key Principle: Context = AI's working memory
- Example: Reading 20 files wastes 60K tokens vs targeted grep/read

**Week 2:** Why Context Matters
- Angle: "Give AI this one thing and get 10x better code"
- Hook: Context quality determines code quality
- Key Principle: Specific, relevant context > generic prompts
- Example: Vague request vs context-rich request

**Week 3:** Context Window Limits
- Angle: "Your AI is forgetting things. Here's why."
- Hook: 200K tokens = ~10,000 lines of code
- Key Principle: Context budget management
- Example: Context overflow causing lost information

### Weeks 4-6: Efficient Context Transfer
**Focus:** Getting the right information to the AI

**Week 4:** Search First, Read Selectively
- Angle: "Stop reading entire codebases. Do this instead."
- Hook: Grep → Read specific files = 90% token savings
- Key Principle: Targeted information gathering
- Example: Wasteful reads vs efficient searches

**Week 5:** Clarifying Questions Protocol
- Angle: "Ask AI these questions before it writes code"
- Hook: Good questions prevent bad code
- Key Principle: Alignment before implementation
- Example: Prompt checklist that improves output

**Week 6:** Context Markers and Structure
- Angle: "How to make your code AI-readable"
- Hook: Clear markers = better AI comprehension
- Key Principle: Semantic markers aid retrieval
- Example: Unmarked code vs CRITICAL/SECURITY markers

### Weeks 7-9: Advanced Context Management
**Focus:** Scaling AI collaboration to complex projects

**Week 7:** Context Window Optimization
- Angle: "How to fit a 100K LOC codebase in AI's context"
- Hook: Strategic reading patterns
- Key Principle: Summarize, reference, refresh
- Example: Multi-file refactoring workflow

**Week 8:** Parallel Execution Patterns
- Angle: "How to 10x productivity by running AI tasks in parallel"
- Hook: One AI instance at a time = slow, multiple = fast
- Key Principle: Concurrent task execution
- Example: Serial vs parallel development workflow

**Week 9:** Session Management
- Angle: "When to refresh context and start fresh"
- Hook: 50-turn debug sessions = context pollution
- Key Principle: Know when to reset
- Example: Context refresh checklist

### Weeks 10-12: Prompt Engineering for Code
**Focus:** Patterns that generate production-ready code

**Week 10:** The Prompt Pattern That Works
- Angle: "The prompt pattern that gets production-ready code"
- Hook: Structure matters more than words
- Key Principle: Context → Task → Constraints → Examples
- Example: Weak prompt vs structured prompt

**Week 11:** AI Code Review Collaboration
- Angle: "Use AI as your code review buddy"
- Hook: AI catches different bugs than humans
- Key Principle: AI for patterns, humans for intent
- Example: AI code review workflow

**Week 12:** AI Pair Programming Workflow
- Angle: "Pair programming with AI: The workflow that works"
- Hook: Driver-Navigator model with AI
- Key Principle: Human strategy, AI implementation
- Example: Full development cycle with AI

---

## Post Type Patterns

### Type 1: Context Problem → Solution (40% of posts)
**Structure:**
```markdown
**[Hook: Context problem statement]**

[Why developers hit this issue]

**The problem:**
❌ [What most developers do - wasteful approach]
[Example of inefficient pattern]

**The solution:**
✅ [Better approach]
[Example of efficient pattern]

**Real numbers:** [Token savings, time savings]

**Apply it:** [Specific action]

[Engagement question]
```

**Best For:** Context management, efficiency improvements

### Type 2: Workflow/Pattern (30% of posts)
**Structure:**
```markdown
**[Hook: Productivity claim or workflow benefit]**

[Problem with traditional approach]

**The pattern:**

**Step 1:** [Name]
[What to do and why]

**Step 2:** [Name]
[What to do and why]

**Step 3:** [Name]
[What to do and why]

**Example workflow:**
```code or description
[Real example showing pattern]
```

**Result:** [Time saved, quality improved]

[Engagement question]
```

**Best For:** Parallel execution, prompt patterns, workflows

### Type 3: Before/After Prompts (30% of posts)
**Structure:**
```markdown
**[Hook: Prompt quality determines output quality]**

[Why vague prompts fail]

**❌ Weak Prompt:**
```
[Generic, context-free request]
```

**Result:** [Mediocre code, wrong assumptions]

**✅ Strong Prompt:**
```
[Context-rich, specific request]
```

**Result:** [Production-ready code, correct assumptions]

**The difference:** [What changed and why it matters]

**Apply it:** [Prompt template or checklist]

[Engagement question]
```

**Best For:** Prompt engineering, clarifying questions

---

## Key Principles to Cover

### Context Management
- [ ] Context window = AI's working memory
- [ ] Token budget matters (200K limit)
- [ ] Search first, read selectively
- [ ] Targeted information > complete information
- [ ] Context refresh after 20-30 turns
- [ ] Semantic markers improve retrieval

### Effective Prompting
- [ ] Specific > vague requests
- [ ] Context → Task → Constraints → Examples structure
- [ ] Clarifying questions before implementation
- [ ] Include success criteria in prompts
- [ ] Reference existing patterns in codebase

### Productivity Patterns
- [ ] Parallel execution for independent tasks
- [ ] AI for patterns, humans for intent
- [ ] Iterative refinement workflow
- [ ] Session management strategies
- [ ] Human strategy, AI implementation

---

## Hook Patterns for Agentic Coding

### Pattern 1: Productivity Claim
- "How to 10x productivity with AI coding assistants"
- "This one context trick saves 90% of tokens"
- "Stop using AI like Google. Do this instead."

### Pattern 2: Problem Recognition
- "Why AI gives you bad code (and how to fix it)"
- "Your AI is forgetting things. Here's why."
- "Context overflow is killing your code quality"

### Pattern 3: Workflow Benefit
- "The prompt pattern that gets production-ready code"
- "How to fit a 100K LOC codebase in AI's context"
- "Pair programming with AI that actually works"

### Pattern 4: Contrast Hook
- "AI isn't a search engine—it's working from a context window"
- "Vague prompts = mediocre code. Specific prompts = production code."
- "One AI instance = slow. Multiple instances = 10x faster."

---

## Engagement Strategies

### Questions That Spark Discussion
- "How do you manage context when working with AI?"
- "What's your biggest AI coding productivity win?"
- "Have you hit the context window limit? What happened?"
- "Do you prompt engineer or just ask naturally?"
- "What's the worst code AI has generated for you?"

### Call-to-Actions
- "Next time you use AI: Search first (grep), then read selectively"
- "Try this prompt pattern on your next feature request"
- "Add semantic markers (CRITICAL, SECURITY) to your code"
- "Run two AI tasks in parallel instead of serial this week"
- "Refresh your AI session after 20+ turns of debugging"

---

## Content Rotation Strategy

### Cycle 1 (Weeks 1-3): Foundations
- Explain context window concept
- Show why context matters
- Build fundamental understanding

### Cycle 2 (Weeks 4-6): Efficiency
- Teach context transfer strategies
- Provide prompt engineering basics
- Show token-saving techniques

### Cycle 3 (Weeks 7-9): Scale
- Advanced context management
- Parallel execution patterns
- Multi-file refactoring

### Cycle 4 (Weeks 10-12): Mastery
- Production-ready code patterns
- AI collaboration workflows
- Full development cycles

**After Week 12:** Advanced topics (multi-agent systems, specialized AI tools, integration patterns)

---

## Real Numbers to Include

### Token Metrics
- Context window: 200K tokens (Claude Sonnet)
- Average file: 3,000-5,000 tokens
- 50-turn session: 50K-100K tokens
- Efficient search: 50 tokens vs 60K token file dump

### Time Savings
- Context-aware prompts: 50-80% reduction in iterations
- Parallel execution: 3-5x faster for independent tasks
- Proper context: First-try success rate 60% vs 20%

### Code Quality
- Specific prompts: 70% less boilerplate
- Context markers: 40% better AI comprehension
- Clarifying questions: 50% fewer refactors needed

---

## Common Misconceptions to Address

### Misconception 1: "AI is magic"
**Reality:** AI is a tool. Quality in = quality out. Context matters.

### Misconception 2: "Just paste all the code"
**Reality:** Context overflow wastes tokens and degrades quality.

### Misconception 3: "AI replaces developers"
**Reality:** AI augments developers. Human strategy + AI implementation.

### Misconception 4: "Prompting doesn't matter"
**Reality:** Prompt quality directly impacts code quality.

### Misconception 5: "AI knows my codebase"
**Reality:** AI only knows what's in context. You must transfer knowledge.

---

## Success Indicators

### Week 1-3 Baseline
- Likes: 30-60 per post (high interest in AI)
- Comments: 10-20 per post (developers share experiences)
- Shares: 5-10 per post

### Week 4-6 Growth
- Likes: 60-120 per post
- Comments: 20-30 per post (prompt patterns spark discussion)
- Shares: 10-20 per post

### Week 7-9 Established
- Likes: 120-200 per post
- Comments: 30-50 per post
- Shares: 20-30 per post (workflow posts get shared heavily)

### Quality Metrics
- Developers sharing their AI workflows
- Questions about specific use cases
- Examples of before/after prompts from community
- Reports of productivity improvements

---

## Topics to Avoid

- AI hype without substance
- Tool wars (Claude vs Copilot vs ChatGPT)
- Unrealistic productivity claims without evidence
- "AI will replace developers" narratives
- Theoretical AI concepts without practical application

---

## Quick Reference: Week-by-Week Topics

| Week | Topic | Source File | Post Type |
|------|-------|-------------|-----------|
| 1 | What Is Context | WHAT_IS_CONTEXT.md | Problem → Solution |
| 2 | Why Context Matters | WHY_CONTEXT_MATTERS.md | Workflow/Pattern |
| 3 | Context Window Limits | CONTEXT_LIMITS.md | Problem → Solution |
| 4 | Search First Strategy | EFFICIENT_CONTEXT_TRANSFER.md | Before/After |
| 5 | Clarifying Questions | CLARIFYING_QUESTIONS_PROTOCOL.md | Workflow/Pattern |
| 6 | Context Markers | Multiple sources | Before/After |
| 7 | Context Optimization | CONTEXT_WINDOW_OPTIMIZATION.md | Problem → Solution |
| 8 | Parallel Execution | PARALLEL_EXECUTION_PATTERNS.md | Workflow/Pattern |
| 9 | Session Management | Multiple sources | Workflow/Pattern |
| 10 | Prompt Patterns | Multiple sources | Before/After Prompts |
| 11 | AI Code Review | Multiple sources | Workflow/Pattern |
| 12 | AI Pair Programming | Multiple sources | Workflow/Pattern |

---

**Last Updated:** 2025-11-25
**Status:** Active series, Week 1 post created
**Next Review:** After Week 3 (assess interest in context topics)
**Note:** This is the most innovative series—no existing best practices guide covers this well yet.
