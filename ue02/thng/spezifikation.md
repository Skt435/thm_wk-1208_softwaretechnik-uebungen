# Spezifikation des Terminplaners

Mitgearbeitet von: @huong118

Der Terminplaner unterstützt die Organisation und Buchung von
Sprechstunden und Prüfungsterminen.

## 1. Ziel

Ziel des Terminplaners ist es, die Organisation und Buchung von
Sprechstunden und Prüfungsterminen zu vereinfachen.

Studierende sollen freie Termine übersichtlich einsehen und direkt buchen können.

## 2. Benutzer und Berechtigungen

Der Benutzer unterscheidet zwischen Studierenden, Lehrenden und
Sekretariaten. Die jeweiligen Berechtigungen sind wie folgt festgelegt:

- **Studierende** dürfen freie Termine buchen und ihre eigenen Buchungen
  einsehen.
- **Lehrende** dürfen ihre angebotenen Termine erstellen und verwalten.
- **Sekretariate** dürfen Termine für die von ihnen betreuten Bereiche
  verwalten.

## 3. Angaben zu einem Termin

Jeder Termin enthält z.B.:
- eindeutige Termin-ID
- Terminart
- Datum
- Anfangs- und eine Endzeit
- verantwortliche Person
- Ort

*Beispiel:* Sprechstunde am 12. November von 10:00 bis 10:15 Uhr
in Raum A1.0.01.

## 4. Funktionen und Abläufe

### 4.1 Buchen
Freien Termin auswählen → Buchung bestätigen.

### 4.2 Absagen & Ändern
- Studierende können eigene Sprechstundenbuchungen absagen.
- Ändert eine Lehrperson einen gebuchten Termin, werden die betroffenen Studierenden informiert.

### 4.3 Bestätigung erhalten
Nach der Buchung folgt eine E-Mail mit Datum, Uhrzeit und Ort.

## 5. Aufbau der Benutzeroberfläche

Anmelden → freie Termine entdecken → nach Lehrperson filtern.

Unter „Meine Termine“ behalten Studierende ihre Buchungen im Blick.

## 6. Fehler und Sonderfälle

Zwei Personen, ein freier Termin → nur eine Buchung gelingt.

Die andere Person erhält die Meldung: „Termin nicht mehr verfügbar“.

## 7. Anforderungen testen

**Testfall:** Eine Studentin bucht einen freien Sprechstundentermin.

**Erwartetes Ergebnis:** Der Termin erscheint unter „Meine Termine“, der
Platz ist belegt und eine Bestätigung wird per E-Mail verschickt.
