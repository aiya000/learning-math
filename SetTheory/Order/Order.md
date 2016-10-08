# Notation
a is element
```mermaid
graph LR
    a
```

f is mapping element to element ( |-> )
```mermaid
graph LR
    a--f-->b
```


# Order
- 反射的であるということ

∀s∈S, s |-> s
```mermaid
graph TD
    subgraph S
    s-->s
    t-->t
    k-->k
    end
```

- 順序集合の上限、下限
    - 上限
        - s,t,k,j∈S
        - (s ≤ j) ∧ (t ≤ j)
        - ∀k, (s≤k ∧ t≤k) → j≤k
    - 下限
        - jの逆

```mermaid
graph LR
    s-- =< -->j
    t-- =< -->j
    j-- =< -->k
```
