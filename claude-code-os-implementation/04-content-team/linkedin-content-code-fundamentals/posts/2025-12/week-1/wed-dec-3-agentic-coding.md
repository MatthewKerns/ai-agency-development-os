---
**Post:** Week 1 - Wednesday
**Date:** Wednesday, December 3, 2025 @ 9:00 AM
**Series:** Agentic Coding
**Topic:** What Is Context (AI Coding Fundamentals)
**Source:** `07-agentic-coding/context/WHAT_IS_CONTEXT.md`
**Status:** Draft
---

**Why does AI give you bad code? You forgot to give it context.**

Most developers treat AI like Google: ask a question, get an answer. But LLMs aren't search engines—they're working from a **context window**.

**Context = Everything the AI can "see" during your conversation**

Think of it as the AI's working memory. When you paste code, ask questions, or read files—all of that fills the context window.

**The problem:** When context is full (200K tokens for Claude Sonnet), older information gets truncated. Critical setup details vanish. The AI "forgets" earlier decisions.

**Common context killers:**

❌ Reading 20 files you don't need (60K tokens wasted)
❌ Long debugging sessions without refresh (100K tokens of history)
❌ Buried information with no semantic markers

**How to 10x your AI code quality:**

✅ **Search first, read selectively**
```python
# Instead of reading everything:
Grep("def process_email", "src/")  # Find it first
Read("src/email_processor.py")     # Then read ONLY what you need
```

✅ **Use clear markers in code**
```python
# CRITICAL: This handles payment processing
# SECURITY: Validates all inputs before processing
def process_payment(amount, card_token):
    ...
```

✅ **Refresh context after long sessions**
After 20+ turns, summarize and start fresh with key decisions documented.

**Real numbers:**
- 200K token window = ~10,000-15,000 lines of code
- One file read = 3,000-5,000 tokens
- 50-turn debug session = 50K-100K tokens before any files

**The fix?** Treat context like a budget. Spend it wisely. The AI can only work with what it can "see."

How do you manage context when working with AI?

---
**Hashtags:** #AICoding #AIAssistedDevelopment #PromptEngineering #DeveloperProductivity #SoftwareDevelopment #CleanCode

**Source Material:** ~/workspace/software-development-best-practices-guide/07-agentic-coding/context/WHAT_IS_CONTEXT.md
