# nauty
- run on https://cocalc.com/features/sage
```
!geng 4 -c
v1 = list(graphs.nauty_geng("4 -c"))
print([g.size() for g in v1]) # [3, 3, 4, 4, 5, 6]
```
