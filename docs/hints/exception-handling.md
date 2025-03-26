---
title: Fehler-Behandlung
layout: default
parent: Tipps
---

Scala hat für die Fehler-Behandlung ein ähnliches Prinzip wie Java. Exceptions können geworfen werden, und durch einen try-catch-Ausdruck abgefangen werden.

## Exceptions werfen
In Scala können Exceptions wie folgt geworfen werden:

```scala
throw new Exception
```
Dabei kann `Exception` durch jede beliebige Exception-Klasse ersetzt werden.