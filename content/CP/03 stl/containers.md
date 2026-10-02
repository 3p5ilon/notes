## pair

- Stores 2 related values.
- `pair<int,int>, pair<char, int>`
- `p.first`, `p.second`
- Useful with `vector`, `set`, `map`.

```cpp
map<pair<int, int>> p;

for(auto it: mp)
    cout << p.first << p.second;
```

## array

- Fixed-size sequence.
- Small fixed range → prefer array
- `a[26]` → common for `a-z`.
- Frequency: `freq[c - 'a']++`

## vector

- Dynamic array.
- Keeps order + allows duplicates.
- `push_back(x)` → add
- `pop_back()` → remove last
- pair → `vector<pair<int,int>>`

## map

- Stores `key → value`.
- Common: `value → frequency`.
- `mp[x]++` → frequency counting.
- Arbitrary keys → `map`.
- Small fixed range → array instead.

## set

- Stores **unique** values.
- Sorted automatically.
- Duplicate insertion → ignored.
- pair → `set<pair<int,int>>`
- Existence → `s.count(x)`
- `s.find(x) != s.end()` → found
