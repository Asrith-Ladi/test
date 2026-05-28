# Two Sum

**Easy** · Array · HashMap

---

## Status

| | |
|---|---|
| **Pattern** | Hash Lookup |
| **Status** | Reviewing |
| **Confidence** | 4 / 5 (Good) |
| **Attempts** | 1 |
| **Hints used** | No |
| **Reviewed** | 3 times |
| **Next review** | 2026-06-05 |

## Review history

| Date | Confidence | Interval |
|---|---:|---:|
| 2026-05-28 | 4 — Good | 8 d |
| 2026-05-28 | 4 — Good | 3 d |
| 2026-05-28 | 4 — Good | 1 d |

## Solutions

### Optimal — Python

> O(n) time · O(n) space

```python
def two_sum(nums, target):
    seen = {}
    for i, n in enumerate(nums):
        if target - n in seen:
            return [seen[target - n], i]
        seen[n] = i
```

### Optimal — Python

> O(n) time · O(n) space

```python
def two_sum(nums, target):
    seen = {}
    for i, n in enumerate(nums):
        if target - n in seen:
            return [seen[target - n], i]
        seen[n] = i #test
```

### Optimal — Python

> O(n) time · O(n) space

```python
def two_sum(nums, target):
    seen = {}
    for i, n in enumerate(nums):
        if target - n in seen:
            return [seen[target - n], i]
        seen[n] = i #test123
```

---
<sup>Tracked with **DSA Tracker** · `test · Array` · Generated 2026-05-28</sup>
