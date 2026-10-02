# Iterators

- `find(x)` → iterator to `x`.
- Not found → `end()`.
- `find(x) != end()` → found.
- `find(x) == end()` → not found.
- Only checking existence? → `count(x)`.

```cpp
for(auto it: v)
    cout << it;
```
