# Liste des instructions ARM

## MOV
> MOV R1, R2

> MOV R1, #0x1

> MOV R0, R1, LSL#0x1 (decale R1 de 1 bit vers gauche, R1 --> R0)
---

## LDR
> LDR R1, [R2]

> LDR R0, [R2, #0x4]

> LDR R0, [R2, R3]

> LDR R0, [R1, R2, LSL#0x2]

> LDR R1, [R0, #0x4]! (modifie avant)

> LDR R1, [R0], #0x4 (modifie apres)

---

## STR
> STR R1, [R2]

> STR R1,

> STR R1, [R0, #0x4]
---

## ADD
> ADD R1, R1, R2

> ADD R1, R1, #0x1



---

## SUB
> SUB R1, R1, R2

> SUB R1, R1, #0x1

---

## JZE
> JZE R0, R1 (si R0 == 0, PC <-- R1)

> JZE R0, #0x2

## LSL
> LSL R0, R0, #0x1

> LSR R0, R0, #0x1

> ASR R0, R0, #0x1

## RSB
> RSB R0, R0, #0 (R0 <-- 0 - R0)

> RSB R0, R0, R1

## AND

## OR

## CMP

## (S)

## B