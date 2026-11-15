# Ladelog

Ladelog ist ein persönliches Logbuch für das Laden eines Elektroautos. Die Seite hält jede Ladung fest, vergleicht die Kosten mit einem Benziner und zeigt eine Ladekarte für Deutschland. Sie läuft als einzelne Datei über GitHub Pages und lässt sich auf dem iPhone als App auf den Homescreen legen.

**Aktuelle Version: 2.4.2 vom 15.11.2026**

## Versionsverlauf

### 2.4 · Ladekarte mit amtlichen Daten

| Version | Datum | Änderung |
|---|---|---|
| 2.4.2 | 15.11.2026 | Versionsnummer in der Fußzeile und Versionsverlauf in der Seite |
| 2.4.1 | 15.11.2026 | Neue Reaktor-Einheiten: Stunden PlayStation 5 und Kilometer mit der Berliner S-Bahn |
| 2.4.0 | 14.11.2026 | Ladekarte nutzt das amtliche Ladesäulenregister der Bundesnetzagentur, abgeglichen mit OpenStreetMap |

### 2.3 · Trophäen

| Version | Datum | Änderung |
|---|---|---|
| 2.3.2 | 13.11.2026 | Ladekarte: mehrere Quellen, tägliche Daten aus diesem Repo und Quellenanzeige |
| 2.3.1 | 13.11.2026 | Ladekarte: stabileres Laden und Anzeige des Datenstands |
| 2.3.0 | 13.11.2026 | 54 Trophäen mit Detailansicht und Fortschritt |

### 2.2 · Ladekarte und Automatik

| Version | Datum | Änderung |
|---|---|---|
| 2.2.1 | 13.11.2026 | Ladekarte: eigener Standort, AC/DC und Filter für passende Anschlüsse |
| 2.2.0 | 13.11.2026 | Ladekarte, automatischer Benzinpreis, Runterziehen zum Aktualisieren, Kilometer nach Kilometerstand, Duell-Balken nach Kosten |

### 2.1 · Auswertungen

| Version | Datum | Änderung |
|---|---|---|
| 2.1.1 | 12.11.2026 | Zielflagge im Duell entfernt |
| 2.1.0 | 12.11.2026 | Winter-Malus, Ladetyp, Hall of Fame, Wrapped, neue Reaktor-Einheiten, Vollbild-Layout |

### 2.0 · Reaktor

| Version | Datum | Änderung |
|---|---|---|
| 2.0.1 | 12.11.2026 | App-Icon für den Homescreen |
| 2.0.0 | 12.11.2026 | Neues Reaktor-Design, CO₂-Bilanz, Historie und GitHub-Sync aus Version 1 übernommen |

### 1.0 · Erste Version

| Version | Datum | Änderung |
|---|---|---|
| 1.0 | November 2026 | Ladungen erfassen, Kostenvergleich mit dem Benziner, Sicherung und Abgleich über ein privates Repository |

## So wird gezählt

| Stelle | Wird erhöht bei |
|---|---|
| Erste Zahl | neuem Design oder einem Bruch mit alten Daten |
| Zweite Zahl | größeren neuen Funktionen |
| Dritte Zahl | kleinen Ergänzungen und Korrekturen |

Im Kopf der Seite stehen die ersten zwei Stellen, in der Fußzeile die volle Nummer mit Datum. Ein Tipp auf die Nummer in der Fußzeile öffnet den Versionsverlauf auch in der Seite.

## Dateien in diesem Repo

| Datei oder Ordner | Zweck |
|---|---|
| `index.html` | Die komplette Seite |
| `apple-touch-icon.png`, `icon-192.png` | App-Icons für Homescreen und Browser-Tab |
| `.github/workflows/ladekarte.yml` | Automat, der jede Nacht die Daten für die Ladekarte baut |
| `ladepunkte/` | Vom Automaten erzeugte Kartendaten. Die Dateien mit Unterstrich am Anfang sind Zwischenspeicher und bleiben liegen |
| `README.md` | Diese Übersicht |

Die eigenen Ladedaten liegen nicht in diesem Repo. Sie bleiben im Browser und, wenn der Abgleich eingerichtet ist, in einem separaten privaten Repository.

## Datenquellen der Ladekarte

- Ladesäulenregister: Bundesnetzagentur.de, Lizenz CC BY 4.0
- Kartenbild und Ladestationen: © OpenStreetMap-Mitwirkende, Lizenz ODbL
- Preisangaben: Open Charge Map
- Benzinpreis: benzinpreis-aktuell.de

---

Copyright by GrizzBln
