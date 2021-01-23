---
attachments: [Screenshot_8.png]
tags: [Notebooks/GTI]
title: '04 Informationsgehalt, Codierung'
created: '2021-01-05T10:52:58.940Z'
modified: '2021-01-09T11:36:02.625Z'
---

# 04 Informationsgehalt, Codierung
## Begriffe
Begriff | Erklärung
---|---
Informationsgehalt | Methode zur Bewertung des technischen Darstellungsaufwands eines Zeichens
Entropie | Durchschnittlicher Informationsgehalt aller Codewörter
Codewort | Bsp 10011
Hamming-Distanz | Unterschiedliche Stellen benachbarter Codewörter
Optimale Codes | Codes mit minimaler durchschnittl. Codewortlänge

## Informationsgehalt
Zweck: Bewertung von Zeichen bzw. deren technischer Darstellungsaufwand
### Formeln
&"Informationsgehalt " = I(x) = ld(1 / (p(x)))&
&"Entropie" = O/"-"I(x) = overset(N)(underset(i=1)(sum))(p(x_i) * I(x))&
## Codierung
### Gray-Code
Einschrittiger und zyklischer Code
**Konstruktion:**
Spiegeln an x-Achse und neue Spalte konstruieren
&[[0],[1]]& &->& &[[0,color(red)(0)],[0,color(red)(1)],[1,1],[1,0]]& &->& &[[0,color(green)(0),color(green)(0)],[0,color(green)(0),color(green)(1)],[0,color(green)(1),color(green)1],[0,color(green)1,color(green)0],[1,1,0],[1,1,1],[1,0,1],[1,0,0]]&
Um Gray-Code von Länge 6 zu erhalten:
Nehme Gray-Code Länge 8 und entferne erste und letzte **Zeile**
### Austausch-Codes
Bsp.
- ASCII
- 7 - Segment


