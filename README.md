# PrICoBE

## Problem
* In Softwareanwendungen, die von mehreren Personengruppen verwendet werden, wird die Softwareanwendungen, durch die von der aktuellen Personengruppe nicht benötigten Oberflächenelemente, unübersichtlich.
  * Manchmal benötigt eine Person Zugriff auf ein Oberflächenelement, das für seine aktuelle Personengruppe gesperrt ist.
  * Es gibt Oberflächenelemente, die aus Sicherheitsgründen nicht jeder Person angezeigt werden dürfen.
* Wenn kein keine dynamischen Änderungen an den Berechtigungen durchgeführt werden können, muss bei einem Benutzerwechsel die Softwareanwendung neu gestartet werden. Dies entspricht nicht dem gewünschten industriellen Arbeitsablauf.
* Bisherige Lösungen sind nicht direkt für Eclipse 4 vorgesehen.
## Research questions
* Welche Ansätze zur dynamischen Rekonfiguration von Benutzeroberflächen gibt es.
* Wie kann die Benutzeroberfläche von Eclipse 4 Anwendungen dynamisch rekonfiguriert werden.
  * Wie aufwendig ist das Implementieren eines Authority Mechanismus in einer bestehende Eclipse 4 Anwendung.
## Idea
* Enwicklung eines Ansatzes für die dynamische Rekonfiguration der Benutzeroberfläche von Eclipse 4.
  * Untersuchung verschiedener Ansätze
## Contribution
* Überblick und Vergleich über bestehende Methoden zur Rekonfiguration von Benutzeroberflächen.
* Neuer spezifischer Ansatz für Eclipse 4
  * Eigenschaften
## Benefits
* Ein Authority Mechanismus für Eclipse 4 mit Eclipse 3 Komponenten.
* Der Authority Mechanismus reagiert dynamisch auf Veränderungen an Berechtigungen.
* Das Auswählen und Implementieren eines Authority Mechanismus ist vereinfacht.
## Evaluation
* Implementierung der Ansätze in PREEvision. (einer Eclipse 4 Anwendung mit Eclipse 3 Komponenten von der Vector Informatik GmbH)
* Die Implementierung auf die funktionalen und nichtfunktionalen Anforderungen testen.
* Die Implementierung auf folgende Metriken testen.
  * Performance
  * Aufwand einer Implementierung
