
# Spezifikation des Terminplaners – Gliederung und Beispiele

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @PokerBuddie

## 1. Ziel und Zweck

### Beispiel
Der Terminplaner soll Studierenden ermöglichen, Sprechstunden und Prüfungstermine online zu buchen, ohne dafür E-Mails schreiben zu müssen.

## 2. Benutzergruppen und Rollen

### Beispiel
Studierende können freie Termine buchen und absagen. Lehrende können ihre verfügbaren Sprechstunden verwalten. Sekretariate erhalten eine Übersicht über die Termine.

## 3. Funktionale Anforderungen

### Beispiel
Das System zeigt verfügbare Termine an. Nach einer Buchung erhält der Studierende eine Bestätigung. Bereits gebuchte Termine können nicht erneut vergeben werden.

## 4. Anmeldung und Berechtigungen

### Beispiel
Die Anmeldung erfolgt über das Hochschulkonto der THM. Studierende dürfen nur ihre eigenen Buchungen bearbeiten, während Lehrende ihre angebotenen Termine verwalten können.

## 5. Daten und Datenverwaltung

### Beispiel
Zu jedem Termin werden Datum, Uhrzeit, Lehrperson, Raum und Buchungsstatus gespeichert. Die personenbezogenen Daten sollen nur für berechtigte Nutzer sichtbar sein.

## 6. Schnittstellen

### Beispiel
Gebuchte Termine können als iCal-Datei heruntergeladen werden. Über eine API sollen KI-Agenten später freie Termine abfragen und Buchungen ausführen können.

## 7. Nichtfunktionale Anforderungen

### Beispiel
Die Anwendung soll übersichtlich und auch auf Smartphones nutzbar sein. Außerdem soll sie zuverlässig funktionieren und persönliche Daten schützen.

## 8. Test und Abnahme

### Beispiel
Es wird geprüft, ob Studierende freie Termine buchen und wieder absagen können. Außerdem wird getestet, ob eine doppelte Buchung verhindert wird und die Anmeldung über das Hochschulkonto funktioniert.
