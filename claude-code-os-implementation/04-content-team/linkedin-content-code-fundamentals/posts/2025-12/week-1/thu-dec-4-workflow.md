---
**Post:** Week 1 - Thursday
**Date:** Thursday, December 4, 2025 @ 9:00 AM
**Series:** Workflow Process
**Topic:** Code Review Checklist
**Source:** `06-collaborative-construction/CODE_REVIEWS.md`
**Status:** Draft
---

**Code reviews catch 60-90% of defects before production. Here's how to make yours actually work.**

Most teams do code reviews wrong: they scan for style issues and rubber-stamp approvals. Then wonder why bugs still ship.

**The problem:** No systematic approach. Reviewers check whatever they remember to check.

**The solution:** Review in 4 passes, each with a specific focus.

**Pass 1: High-Level Architecture** (10-15% of time)
- Does the solution fit the architecture?
- Are the right patterns used?
- Are boundaries respected?

**Pass 2: Logic and Correctness** (50-60% of time)
- Does the code actually work?
- Are edge cases handled?
- Is error handling appropriate?
- Do tests cover the main paths?

**Pass 3: Code Quality** (20-30% of time)
- Are names clear and intention-revealing?
- Are functions small and focused?
- Is the code readable and maintainable?
- Are there code smells?

**Pass 4: Details** (10% of time)
- Formatting consistency
- Comment quality
- Documentation completeness
- Missing test cases

**Why this works:**

Studies show review effectiveness drops sharply above 400 lines of code. Reviewers fatigue, miss defects, give superficial feedback.

**Real numbers:**
- Defect found in review: costs 10-100x less than production
- Review rate: 150-200 LOC/hour for thorough review
- Optimal PR size: 200-400 lines

**Apply it today:**

Pick a pull request you're reviewing this week. Go through it in 4 passes instead of one scan. Watch how many issues you catch that you would have missed.

**Focus on the code, not the person.** The goal is better code, not proving you're smart.

What's your code review process?

---
**Hashtags:** #CodeReview #SoftwareEngineering #CleanCode #DeveloperTips #TeamCollaboration #BestPractices

**Source Material:** ~/workspace/software-development-best-practices-guide/06-collaborative-construction/CODE_REVIEWS.md
