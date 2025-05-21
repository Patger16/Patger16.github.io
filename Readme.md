# Fitness Tracker - Material Design

Dies ist ein Frontend-Mockup für einen Fitness Tracker im Material Design.
Es dient als Grundlage für die Entwicklung einer voll funktionsfähigen Webanwendung.

## Geplante Funktionen

* Dashboard mit Fortschrittsübersicht
* Eingabe und Verwaltung von persönlichen Daten (Alter, Gewicht, Größe) und Zielen (Zielgewicht)
* Automatische Berechnung von BMI, BMR und TDEE
* Interaktives Aktivitätslevel mit Trainingsempfehlungen (konzeptionell)
* Tägliche Kalorienzufuhr-Protokollierung
* Wöchentlicher Essensplan:
    * Auswahl aus 4 vordefinierten Plänen (kein Schweinefleisch)
    * Anzeige von Mahlzeiten und Kalorien
    * Verlinkung zu Rezepten
* Rezeptbereich
* Fortschrittstracking (Gewicht, BMI) und Prognose (konzeptionell)

## Struktur

* `index.html`: Hauptseite, die die Sektionen lädt.
* `css/style.css`: Basis-Styling und Material Design Anlehnungen.
* `js/`: JavaScript-Dateien für Logik und Interaktion.
    * `app.js`: Hauptanwendungslogik und Navigation.
    * `ui.js`: Funktionen zur Aktualisierung der Benutzeroberfläche.
    * `calculations.js`: Funktionen für BMI, BMR, TDEE Berechnungen.
    * `data.js`: Beispieldaten für Essenspläne und Rezepte.
* `sections/`: HTML-Templates für die verschiedenen Bereiche der Anwendung.

## Setup (Lokal)

1.  Klone dieses Repository.
2.  Öffne `index.html` in deinem Webbrowser.

## Nächste Schritte (Entwicklung)

* Integration einer Material Design Komponentenbibliothek (z.B. Material Components for Web, MUI, Angular Material, Vuetify).
* Implementierung der vollständigen UI-Logik für alle Interaktionen.
* Entwicklung eines Backends zur Speicherung von Benutzerdaten, Plänen und Rezepten.
* Anbindung des Frontends an das Backend über APIs.
* Implementierung von Authentifizierung.
* Erstellung von Diagrammen für die Fortschrittsanzeige (z.B. mit Chart.js).
* Ausführliche Tests.