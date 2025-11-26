---
**Post:** Week 1 - Friday
**Date:** Friday, December 5, 2025 @ 9:00 AM
**Series:** Testing
**Topic:** TDD Workflow Basics
**Source:** `04-quality-through-testing/TDD_WORKFLOW.md`
**Status:** Draft
---

**TDD in 3 words: Red. Green. Refactor.**

Most developers write code first, tests later (if at all). Then wonder why refactoring feels dangerous.

**Test-Driven Development (TDD) inverts this: Write the test BEFORE the code.**

**The Red-Green-Refactor Cycle:**

**🔴 RED (< 1 minute):** Write a failing test
```python
def test_empty_string_has_zero_length():
    result = string_length("")  # Function doesn't exist yet!
    assert result == 0

# Run test → FAILS (good!)
```

**🟢 GREEN (< 1 minute):** Write minimal code to pass
```python
def string_length(s):
    return 0  # Hardcoded! But it passes.

# Run test → PASSES
```

**🔵 REFACTOR (< 2 minutes):** Write next test, force real implementation
```python
def test_single_character_has_length_one():
    result = string_length("a")
    assert result == 1  # Now hardcoded 0 fails

# Implement real solution:
def string_length(s):
    return len(s)

# All tests pass → Clean up code
```

**Total cycle: 2-4 minutes per behavior**

**Why TDD works:**

1. **Design pressure** - Hard-to-test code is poorly designed code
2. **Minimal code** - You only write what's needed to pass tests
3. **Fearless refactoring** - Tests catch regressions immediately
4. **Living documentation** - Tests show how code should behave

**The mindset shift:**

"I'm not a great programmer; I'm just a good programmer with great habits." — Kent Beck

**Apply it today:**

Next function you write: Write the test first. Start with the simplest case (empty input, zero, null). See it fail. Then write code to pass it.

If a cycle takes longer than 5 minutes, your test is too big.

Do you practice TDD? What's your biggest challenge with it?

---
**Hashtags:** #TDD #UnitTesting #TestDrivenDevelopment #SoftwareQuality #CleanCode #DeveloperTips

**Source Material:** ~/workspace/software-development-best-practices-guide/04-quality-through-testing/TDD_WORKFLOW.md
