# Auftragsbuch

Auftraggeber- und Auftragsverwaltung der Werkbank Unverricht – eine einzelne HTML-Datei,
ohne Abhängigkeiten, lauffähig über GitHub Pages.

**Live:** https://maikunverricht.github.io/Auftragsbuch/

## Funktionen

- Auftraggeber als Visitenkarten im Halbkreis – ziehen, wischen, Mausrad oder Pfeiltasten
- Auswahl über A–Z-Leiste, Filter (alle / aktiv / inaktiv) und Volltextsuche
- Aufträge je Auftraggeber mit Status (geplant, aktiv, pausiert, abgeschlossen, abgerechnet),
  Budget in Stunden und Euro, Zeitraum, Projektnummer und optionalem Einzel-Stundensatz
- Kennzahlen über alle Auftraggeber und Summen der offenen Budgets je Kunde
- Hell/Dunkel, vollständig auf dem Handy bedienbar

## Daten

Die Inhalte liegen in einer eigenen JSON-Datei an einem Ort deiner Wahl (lokale Platte,
NAS, Cloud-Ordner). Über den Knopf oben rechts wird sie verknüpft; jede Änderung wird
sofort dorthin geschrieben, die Verknüpfung überlebt einen Neustart des Browsers.

Das direkte Schreiben in Dateien beherrschen Chrome und Edge am Rechner. In Firefox,
Safari und auf dem Handy liegen die Daten im Browser des Geräts und werden über
**Export** / **Import** gesichert – gleiches JSON-Format, also frei austauschbar.

Es werden keine Daten an Server übertragen.

## Einrichtung als GitHub Pages

1. Repository anlegen, `index.html` in den Wurzelordner legen
2. Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, Ordner: `/ (root)`
