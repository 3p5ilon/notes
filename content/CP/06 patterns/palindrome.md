---
title: Palindrome
---

- Even length → `0` odd frequencies.
- Odd length → `≤ 1` odd frequency.
- General condition → `odd_count <= 1`.
- With `k` deletions: `odd_count - k <= 1`.
- Therefore: `odd_count <= k + 1`.
