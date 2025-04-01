---
title: Aufgabe 1
layout: default
nav_order: 3
---

Um diese Aufgabe zu bearbeiten, führe bitte zuerst `git switch task1` im Terminal aus.

## Aufgabenstellung
In dieser Aufgabe musst Du die Klasse Calculator vervollständigen und die main-Methode schreiben.

Die Methode `add(x, y)` ist bereits in der Klasse Calculator implementiert. Du sollst nun die Methoden `subtract(x, y)`, `divide(x, y)` und `factorial(a)` implementieren. Bei der Methode `divide` soll eine `IllegalArgumentException` geworfen werden, falls durch 0 geteilt wird. Außerdem soll bei der Fakultät auch der Sonderfall 0! = 1 beachtet werden. Alle Bedingungen sind über die Tests abgedeckt, sodass über das Auführen der Tests jederzeit kontrolliert werden kann, ob diese erfüllt sind.

Im Anschluss daran muss die main-Methode implementiert werden. Dabei soll mithilfe des Calculator folgende Ausgabe im Terminal erzeugt werden:
```
Calculator starting...
5 - 3 = 2
4! = 24
```