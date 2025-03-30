---
title: Listen
layout: default
parent: Tipps
---

## Arbeiten mit Listen
Eine neue Liste kann in Scala sowohl ohne explizite Typenangabe als auch mit dieser erstellt werden.
```scala
var l = List(1, 2, 3)
var l2: List[Int] = List(1, 2, 3)
```

Eine leere Liste wird wie folgt erstellt:
```scala
var l_empty: List[Int] = List()
```

Auf bestimmte Elemente einer Liste kann über den Index (von 0 beginnend) zugegriffen werden.
```scala
l(0) //Rückgabe: 1
```

Neue Elemente können an die Liste über die Methode `:+` angehangen werden.
```scala
l = l :+ 4
println(l) //Output: 1, 2, 3, 4
```

[Scala-Dokumentation](https://docs.scala-lang.org/scala3/book/collections-classes.html#list)
