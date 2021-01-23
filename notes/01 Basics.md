---
tags: [Notebooks/IngMathC1]
title: 01 Basics
created: '2021-01-09T09:10:50.266Z'
modified: '2021-01-09T12:09:00.733Z'
---

# 01 Basics
## Aussagenlogik
Operator | Bedeutung | Erklärung
--- | --- | ---
&A=>B& "Implikation" | Aus A folgt B | Aus wahr folgt wahr; aus falsch kann man alles folgern
&A <=> B& "Äquivalenz" | A ist Äquivalent zu B | A == B; Implikation in beide Richtungen
&A ^^ B& "AND" | A geschnitten mit B | Verknüpfung AND
&A vv B& "OR" | A vereinigt mit B | Verknüpfung OR
&notA& "NOT" | A negiert | Negation
&:=& oder &:<=>& | definiert als; gilt | Definition, keine Wahrheitsaussage
&=& | Aussage | besitzt Wahrheitswert
## Quantoren
Quantor | Bedeutung | Beispiel
--- | --- | ---
&AA& | Für alle | &AAx : A(x);& Für alle &x& gilt &A(x)&
&EE& | Es existiert ein | &EEx : A(x)&; Es gibt ein &x& mit &A(x)&
**Umformung**
&not(AAx:A(x))<=>EEx:notA(x)&
&not(EEx:A(x))<=>AAx:notA(x)&

