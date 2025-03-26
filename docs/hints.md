---
title: Tipps
layout: default
nav_order: 5
---

Auf dieser Seite finden sich grundlegende Informationen zur Ordnerstruktur eines Scala-Projekts sowie zur Bedienung von `sbt`. Auf weiteren Unterseiten finden sich Informationen zum Coding in Scala.

## Ordnerstruktur
![Projektstruktur in Scala]({{site.baseurl}}/assets/project-structure.png)

Die `build.sbt` definiert grundlegende Informationen für `sbt`, zum Beispiel die Abhängigkeiten eines Projektes.
Die Programmierung findet in `src/` statt. Unter `main/scala/` befindet sich der Code, der ausgeführt werden soll. Tests werden im Ordner `test/scala/` geschrieben.

## Ausführen des Programms
Bitte beachte die unterschiedlichen Anleitungen für UTM bzw. GitHub Codespaces.

### UTM
Das Scala Build Tool hat unter anderem die Aufgaben, ein Scala-Programm sowie dessen Tests auszuführen.

`sbt run`: Führt das Scala-Programm aus

`sbt test`: Führt alle Tests des Projektes aus

### GitHub Codespaces
Hierzu nutzen wir die VSCode Command Palette. Diese kannst du über `Strg + Shift + P` bzw. `Cmd + Shift + P` öffnen.

Zum Ausführen der Main-Klasse öffne bitte die entsprechende Datei und führe in der Command Palette den Befehl "Metals: run main class or tests in the current file" aus.
Mit diesem Befehl lassen sich auch die Tests ausführen, indem die Testklasse geöffnet wird.