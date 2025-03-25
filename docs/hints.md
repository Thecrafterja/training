---
title: Tipps
layout: default
nav_order: 5
---

Auf dieser Seite finden sich grundlegende Informationen zur Ordnerstruktur eines Scala-Projekts sowie zur Bedienung von `sbt`. Auf weiteren Unterseiten finden sich Informationen zum Coding in Scala.

## Ordnerstruktur
scala-training/

├── project/

│   └── ...

├── src/

│   ├── main/

│   │   └── scala/

│   │       ├── Main.scala

│   │       └── ...

│   └── test/

│       └── scala/

│           └── ...

├── .gitignore

├── README.md

└── build.sbt

Die `build.sbt` definiert grundlegende Informationen für `sbt`, zum Beispiel die Abhängigkeiten eines Projektes.
Die Programmierung findet in `src/` statt. Unter `main/scala/` befindet sich der Code, der ausgeführt werden soll. Tests werden im Ordner `test/scala/` geschrieben.

## sbt (Scala Build Tool)
Das Scala Build Tool hat unter anderem die Aufgaben, ein Scala-Programm sowie dessen Tests auszuführen.

`sbt run`: Führt das Scala-Programm aus
`sbt test`: Führt alle Tests des Projektes aus