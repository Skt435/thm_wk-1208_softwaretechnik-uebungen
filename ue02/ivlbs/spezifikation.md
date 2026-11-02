# Spezifikation des Terminplaners — Gliederung und Beispiele

Mitgearbeitet haben: @ivloic321

<!-- Je Abschnitt Ihrer Gliederung eine Überschrift (## für Abschnitte, ###
     für Unterabschnitte) und darunter ein Beispiel aus dem Terminplaner,
     d.h. so, wie Sie den Sachverhalt in diesem Abschnitt festhalten würden.
     Die beiden Überschriften unten sind lediglich Platzhalter. -->

## 1. Zielsetzung & Zielgruppen
Das System ermöglicht Lehrenden das Anbieten von Sprechstunden und Prüfungsterminen. Studierende buchen Termine über ihr Hochschulkonto, und Sekretariate behalten den Überblick.

## 2. Anwendungsfälle (Use Cases)
- **UC-1: Termin buchen:** Ein Studierender wählt einen freien Slot aus, gibt einen Grund an und bucht den Termin.
- **UC-2: Sprechstunde anlegen:** Eine Lehrkraft trägt verfügbare Zeitfenster ein.

## 3. Benutzerschnittstelle (UI)
- **Buchungsübersicht:** Ein Kalender zeigt freie Slots grün und belegte Slots grau an. Ein Klick öffnet ein Formular zur Bestätigung.

## 4. Objekt- & Datenmodell
Ein **Termin** besteht aus:
- `Termin-ID`, `Datum`, `Uhrzeit_Start`, `Uhrzeit_Ende`
- `Lehrkraft`, `Studierender` (Verknüpfung zum Hochschulkonto)
- `Status` (frei / gebucht / abgesagt)

## 5. Schnittstellen zu Nachbarsystemen
- **iCal-Export:** Generiert eine `.ics`-Datei zum Importieren in persönliche Kalender.
- **KI-Agenten-API:** REST-Schnittstelle zur Abfrage freier Termine und zur Buchung per Chat-Agent.


