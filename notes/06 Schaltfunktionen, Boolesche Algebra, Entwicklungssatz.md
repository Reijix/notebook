---
attachments: [Screenshot_7.png]
tags: [Notebooks/GTI]
title: '06 Schaltfunktionen, Boolesche Algebra, Entwicklungssatz'
created: '2021-01-02T17:20:11.063Z'
modified: '2021-01-06T08:29:31.968Z'
---

# 06 Schaltfunktionen, Boolesche Algebra, Entwicklungssatz
## Boolesche Algebra
### Regeln
Name | Anwendung
-------|-------------
**XOR:** | &x o+ y = xbar y + barx y&
**Idempotenz:** | &x + x = x " || " x * x = x&
**Absorption:** | &x(x + y) = x " || " x + (xy) = x&
**Konsensus** | &(xy) + (barxz) + (yz) = (xy) + (barxz)& <br>&->& Ergibt sich aus Absorption (Erweitern und kürzen..)
**Distribution** | &x * (y + z) = xy * xz" || " x + (y * z) = (x+y) * (x+z)&

## Entwicklungssatz
Nützlich zur Bestimmung von BDDs
Bsp:
&F = xy + barxbary&
&F = x * F(x=1) + barx * F(x=0)&  //Entwicklung nach x
&F(x=1) = y" "" "||" "" "F(x=0) = bary&
&y = y * 1 + bary * 0" "" "||" "" "bary = y * 0 + bary * 1& //Entwicklung nach y
Daraus folgt: (x1 = x; x2 = y)
![](@attachment/Screenshot_7.png)



