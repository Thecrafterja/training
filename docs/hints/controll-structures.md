---
title: Kontrollstrukturen
layout: default
parent: Tipps
---

## if-else-Verzweigung
```scala
if j > 18 then
    // Do something
else
    // Do something else
```

[Scala-Dokumentation](https://docs.scala-lang.org/scala3/book/control-structures.html#the-ifthenelse-construct)

## for-Schleife
```scala
for i <- (0 until 10) do
    // Do something
```
Hier durchläuft die for-Schleife die Zahlen 0 bis 9, welche in `i` abgebildet werden. Wird statt `until` die  Methode `to` verwendet, so ist für die letzte Zahl ebenfalls ein Schleifendurchlauf vorgesehen. Der Ausdruck `(0 until 10)` kann auch durch ein Array, eine Liste oder eine Sequence ersetzt werden. In diesem Fall wäre dann `i` der aktuelle Inhalt aus der Datenstruktur.

[Scala-Dokumentation](https://docs.scala-lang.org/scala3/book/control-structures.html#for-loops)