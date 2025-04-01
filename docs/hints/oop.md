---
title: OOP
layout: default
parent: Tipps
---

## Objekt orientierte Programmierung
In Scala können, wie in Java, Objekte einer Klasse erstellt werden. Beispielhaft erstellen wir hier eine neue Instanz der Klasse `Dog`:
```scala
var dogObject = new Dog()
```

Dabei wird über die Klammern der Konstruktor aufgerufen, welcher ggfs. auch Paramter nimmt. Hierbei kann man mit `pName = <CONTENT>` explizit die Parameter angeben. Alternativ kann man diese explizite Angabe weglassen, sodass der Compiler dann automatisch nach der Reihenfolge der Paramter die Zuweisungen vornimmt.
```scala
var dog2 = new Dog(name = "Bello")
```

[Scala-Dokumentation](https://docs.scala-lang.org/scala3/book/domain-modeling-oop.html#classes)