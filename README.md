# Wetterdatenanalyse

Dieses Projekt ruft täglich Wetterdaten für mehrere deutsche Städte ab und speichert diese zur späteren Analyse.

## Städte

* Stuttgart
* Berlin
* Hamburg
* München
* Köln

## Gespeicherte Daten

Pro Stunde werden folgende Werte gespeichert:

* Temperatur
* Luftfeuchtigkeit
* Niederschlag
* Windgeschwindigkeit
* Windrichtung
* Bewölkung
* Wettercode

## Ablauf

```text
Wetter-API → Daten abrufen → Daten speichern → Analyse
```

Der Abruf soll automatisch einmal täglich erfolgen.

## Ziel

Die gespeicherten Wetterdaten sollen später genutzt werden, um beispielsweise Temperatur, Niederschlag und Wetterbedingungen zwischen den Städten zu vergleichen.
