---
**Post:** Week 1 - Monday
**Date:** Monday, December 1, 2025 @ 9:00 AM
**Series:** Fundamentals
**Topic:** Variable Naming Conventions
**Source:** `01-foundations/VARIABLE_NAMING.md`
**Status:** Draft
---

**Your variable names are lying to you.**

Most developers spend 60-70% of their time reading code, not writing it. Yet we rush through naming variables like it doesn't matter.

Here's the problem: poor names create mental mapping. Every time you read `d = 14` or `temp = calculate()` you pause to translate what that actually means.

**❌ Bad Example:**
```python
# What is 'd'? Days? Distance? Data?
d = 14
temp = calculate()
list1 = get_items()
```

**✅ Good Example:**
```python
# Clear intent and meaning
elapsed_days_since_creation = 14
monthly_revenue_total = calculate()
active_user_accounts = get_items()
```

**Why this matters:**

Developers spend 60-70% of their time reading code. Unclear names directly impact this majority activity.

Studies show the sweet spot is 10-16 characters for variable names—long enough to be clear, short enough to be readable.

**Apply it today:**

Pick one function you wrote this week. Find variables named `temp`, `data`, `result`, or single letters. Rename them to reveal intent.

If a variable name needs a comment to explain it, the name doesn't reveal its intent.

**What's the worst variable name you've encountered in production code?**

---
**Hashtags:** #SoftwareDevelopment #CleanCode #DeveloperTips #CodingFundamentals #CodeQuality #BestPractices

**Source Material:** ~/workspace/software-development-best-practices-guide/01-foundations/VARIABLE_NAMING.md
