---
layout: default
title: Agile Methoden
tagline: 
group: navigation
nav_order: 3
---
{% include JB/setup %}

<span class="label label-important">
  Entwurf/Draft
</span>

<div class="page-header">
  <h1>Agile Methoden</h1>
</div>

Bisherige Projekte in der Piratenpartei haben unserer Erfahrung nach
sehr häufig folgende Probleme:

-  Mangelhafte Planung
-  Mangelhafte Umsetzung
-  Umsetzung durch eine Person, die sich sozusagen in den Burn-Out
   arbeitet.
-  zu geringe Arbeits- und Wissensverteilung auf mehrere Schultern.
-  kein Peer-Reviewing/Pair-Programming.


## …in der Entwicklung:
Wir setzen daher [Agilen Entwicklungsmethoden](http://de.wikipedia.org/wiki/Agile_Softwareentwicklung) ein und zwar je nach Projekt und
Projektphase einen an [Scrum](http://de.wikipedia.org/wiki/Scrum) angelehnten Entwicklungsprozess mit fester
Sprintlänge oder flexibles [Kanban](http://de.wikipedia.org/wiki/Kanban_in_der_IT).

Damit wollen wir folgendes erreichen:

-  Professionelle Erfassung der Anforderungen, kein "Schuss ins Blaue"
   oder Hellseherei.
-  Ausreichende Definition des zu erreichenden Ziels ohne in Bürokratie
   zu ersticken.
-  gleichzeitig flexibel genug um auf Änderungen zu reagieren
-  Aufteilung der Arbeitspakete in Iterationen (Sprints). Kleine
   Arbeitspakete sind besser zu realisieren und zu verifizieren.
Gleichzeitig ist das Arbeitspensum gedeckelt. Arbeiten lassen sich gut
auf viele Mitarbeiter verteilen und Burn-Out-Risiken
vermeiden!
-  Die Anwendung soll jederzeit in einem funktionsfähigen Zustand sein.
-  Schrittweise Umsetzung in überschaubaren, nachprüfbaren Schritten.

<br/>

### Vereinfachte grafische Darstellung:

<div class="span11" style="text-align: center">
<img src="/images/workflow.png" alt="Schema"/>
</div>


## …in der Qualitätssicherung:

Fehler passieren und sind unvermeidbar. Wer die gleichen Fehler mehrmals
begeht, hat allerdings ein Problem.

Um aus unseren Fehlern zu lernen und schon von Anfang an ein
Sicherheitsnetz zu spannen, entwickeln wir testgetrieben:

[Testgetriebene Entwicklung (TDD)](http://de.wikipedia.org/wiki/Testgetriebene_Entwicklung)

Um den vollen Umfang unserer Anwendung zu testen und um die
implementierten Features auch für Nicht-Entwickler zu dokumentieren,
verwenden wir eine Vorgehensweise, welche unter "Specification by
Example" oder auch "Acceptance Test Driven Development" (ATDD) bekannt ist:

[Specification by example](http://en.wikipedia.org/wiki/Specification_by_example)


### Continuous Integration (CI)

Die geschriebenen Tests werden bei jeder Änderung ausgeführt um den
aktuellen Zustand zu erfassen:

[http://de.wikipedia.org/wiki/Kontinuierliche_Integration](http://de.wikipedia.org/wiki/Kontinuierliche_Integration)

## …im Betrieb (Deployment und DevOps)

Das Ausrollen einer Anwendung muss mit einem Kommando möglich sein.
Das Konfigurieren eines Systems zur Ausführung der Anwendung ebenso.

Hierzu verwenden wir beispielsweise Tools wie 

[Capistrano](https://github.com/capistrano)
und
[Chef](http://www.opscode.com/chef/)

siehe auch: [DevOps](http://en.wikipedia.org/wiki/DevOps)

## …Philosphisches

Die strikten Anforderungen hinsichtlich Entwicklungsmethoden und
Automatisierung erlauben es uns, auf die wirklich wichtigen Dinge,
nämlich die Anwendung zu fokussieren. Wir haben so eine verlässliche,
belastbare Grundlage die einiges aushalten kann.

Weiterhin halten wir folgende Sichtweisen für sehr nützlich:

### KISS

[Keep it simple](http://de.wikipedia.org/wiki/KISS-Prinzip)

Komplexität nur dort, wo sie angebracht ist und nachweislich Vorteile
bringt. Nicht zum Selbstzweck oder der Selbstverwirklichung eines
Entwicklers.


### YAGNI

[You ain't gonna need it](http://de.wikipedia.org/wiki/YAGNI)

Wir brauchen keine Traumschlösser, sondern funktionale Blockhütten!
Unsere Anwendungen sollen sicher und skalierbar sein, ganz bestimmt
werden wie nicht die Skalierungsprobleme von Twitter und Facebook
erreichen… Deshalb brauchen wir hier auch nicht zu viel Zeit investieren.


### DRY

[Don't repeat your self](http://de.wikipedia.org/wiki/Code-Duplizierung)

Doppelte Arbeit nervt. Doppelter Code noch viel mehr: Verringerte
Lesbarkeit, hoher Wartungsaufwand, nachteilige Komplexität.

### Ship it!

Am Ende zählt das Resultat. An Perfektionismus zu scheitern, ist kein erstrebenswertes Resultat!

