# nauty
- run on https://cocalc.com/features/sage
```
!geng 4 -c
v1 = list(graphs.nauty_geng("4 -c"))
print([g.size() for g in v1]) # [3, 3, 4, 4, 5, 6]
```

## option
- `-c` connected

## memo
- `!geng 1 -c` A001349 Number of simple connected graphs on n unlabeled nodes. 

## format
- Sage에서 시각화 가능
```py
Graph("CF")
```

### `-g` graph6 (default)
```
!geng 1 -c -g
@

!geng 2 -c -g
A_

!geng 3 -c -g
BW
Bw

!geng 4 -c -g
CF
CU
CV
C]
C^
C~
```

### `-s` sparse6
```
!geng 1 -c -s
:@

!geng 2 -c -s
:An

!geng 3 -c -s
:BoN
:BcN

!geng 4 -c -s
:CwI
:Co`
:Co`V
:CoKN
:CoKI
:CcKI
```
