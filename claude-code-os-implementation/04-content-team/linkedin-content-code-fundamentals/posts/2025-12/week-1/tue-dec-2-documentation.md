---
**Post:** Week 1 - Tuesday
**Date:** Tuesday, December 2, 2025 @ 9:00 AM
**Series:** Documentation
**Topic:** When to Comment vs Self-Documenting Code
**Source:** `01-foundations/COMMENTS_AND_DOCUMENTATION.md`
**Status:** Draft
---

**"The proper use of comments is to compensate for our failure to express ourselves in code." — Robert C. Martin**

Most developers either over-comment (explaining obvious code) or under-comment (leaving intent unclear).

Here's the rule: **Don't comment bad code. Rewrite it.**

**❌ Bad: Comment tries to explain confusing code**
```python
# Check to see if employee is eligible for full benefits
if (employee.flags & HOURLY_FLAG) and (employee.age > 65):
    # Complex flag checking logic
    pass
```

**✅ Good: Clear code needs no explanation**
```python
if employee.is_eligible_for_full_benefits():
    pass
```

**When to comment:**

**1. Explain WHY, not WHAT**
```python
# We give 10% discount only if customer has no outstanding invoices.
# This prevents customers from placing large orders to get discounts
# while owing us money.
if order.total > 100 and customer.outstanding_balance == 0:
    return order.total * 0.10
```

**2. Warn of consequences**
```python
# WARNING: This immediately invalidates all existing user sessions
# and sends a password change notification email. Cannot be undone.
def reset_user_password(user_id, new_password):
    invalidate_all_sessions(user_id)
    update_password(user_id, new_password)
```

**Apply it today:**

Find a comment in your code that explains WHAT the code does. Can you refactor the code to be self-explanatory? Extract that complex condition into a well-named function.

**When you feel the need to write a comment, first try to refactor the code to make it self-explanatory.**

What's your rule for when to comment?

---
**Hashtags:** #SoftwareDevelopment #CodeDocumentation #TechnicalWriting #CleanCode #DeveloperTips #BestPractices

**Source Material:** ~/workspace/software-development-best-practices-guide/01-foundations/COMMENTS_AND_DOCUMENTATION.md
