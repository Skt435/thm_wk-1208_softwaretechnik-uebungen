# Spezifikation des Terminplaners — Gliederung und Beispiele

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @EMLR1011

<!-- Je Abschnitt Ihrer Gliederung eine Überschrift (## für Abschnitte, ###
     für Unterabschnitte) und darunter ein Beispiel aus dem Terminplaner,
     d.h. so, wie Sie den Sachverhalt in diesem Abschnitt festhalten würden.
     Die beiden Überschriften unten sind lediglich Platzhalter. -->

## 1. Ziel und Zweck des Systems

### 1.1 Ziel des Systems
Die THM möchte einen digitalen Terminplaner für Sprechstunden
und Prüfungstermine bereitstellen. Die Terminvereinbarung
soll dadurch vereinfacht werden.

### 1.2 Anwendungsfälle (Use Cases)
Studierende sollen online freie Sprechstundentermine
bei Lehrenden suchen, buchen und stornieren können.

## 2. Funktionale Anforderungen

### 2.1 Termine buchen
Studierende können einen verfügbaren Termin auswählen
und verbindlich buchen. Doppelbuchungen sind nicht erlaubt.

### 2.2 Verfügbare Zeitfenster
Das System zeigt alle freien Zeitfenster eines Lehrenden
mit Datum und Uhrzeit an.

### 2.3 Termine stornieren
Studierende können ihre eigenen Buchungen stornieren.
Der Termin wird anschließend wieder freigegeben.

## 3. Benutzer und Rollenkonzept

### 3.1 Rollen und Berechtigungen

| Funktion | Studierende | Lehrende | Sekretariat |
|---|---|---|---|
| Termine buchen | Ja | Nein | Ja |
| Termine stornieren | Eigene | Ja | Ja |
| Freie Termine erstellen | Nein | Ja | Ja |
| Termine einsehen | Eigene | Eigene | Zugewiesene |

## 4. Ablauf der Terminbuchung

### 4.1 Buchungsprozess
1. Studierende melden sich mit ihrem THM-Konto an.
2. Sie wählen einen Lehrenden aus.
3. Das System zeigt verfügbare Termine an.
4. Ein freier Termin wird ausgewählt und bestätigt.
5. Das System speichert die Buchung und versendet eine Bestätigung.

## 5. Technische Anforderungen

### 5.1 Datenhaltung
Das System muss Termine, Benutzerdaten und Buchungen
in einer Datenbank speichern.

### 5.2 Schnittstellen
Der Terminplaner muss Termindaten mit dem Kalendersystem
der THM austauschen können.

### 5.3 Sicherheit
Die Anmeldung erfolgt über das THM-Konto.

## 6. Nicht-funktionale Anforderungen

### 6.1 Zuverlässigkeit
Bestätigte Buchungen dürfen nicht
verloren gehen.

### 6.2 Benutzerfreundlichkeit
Die Buchungsoberfläche soll übersichtlich gestaltet
sein.
