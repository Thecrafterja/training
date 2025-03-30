---
title: Variablen
layout: default
parent: Tipps
---

## Variablen deklarieren und initialisieren
Eine Variable wird in Scala mit dem Schlüsselwort `var` deklariert. Darauf folgen der Variablenname und der initiale Wert.
```scala
var a = 1
```

Auch ist es möglich, den Typ der Variablen explizit anzugeben:
```scala
var a: Int = 1
```

Wichtig ist, dass es sich hierbei um den primären Datentyp Int handelt (wie `int` in Scala), und nicht um eine Wrapper-Klasse.