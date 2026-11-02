# Stakeholder und Systemkontext — Terminplaner für die THM

<!-- Aufgabe 1 des Übungsblatts. Ersetzen Sie die Platzhalter … und fügen
     Sie so viele Zeilen hinzu, wie Sie benötigen. Löschen Sie die
     Kommentare, sobald Sie fertig sind. -->

## Stakeholder

<!-- Mindestens sechs Stakeholder, je mit einem Satz dazu, worauf sie
     Einfluss haben. -->

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Studierende| Sie beeinlfussen die Bediebarkeit was mobile ist und sorgen||für schnellere Terminbuchungen für Sprechstunden.|
|Lehrende|Sie bestimmen Termine, Buchungen und Buchungsregeln im System.|
|Sekreteriat|Sie nehmen Einfluss auf Vertretungsregeln, Raumvergaben und Vorlaufzeiten bei der Terminplanung.|
|IT-Adminstrator|Hier werden Anforderungen an Benutzerverwaltung, Schnittstellen und IT-Sicherheit gestellt.|
|Datenschutzbeauftragte(r)|Hier wird festgelegt, welche personenbezogenen Daten wie lange gespeichert und verarbeitet werden dürfen.|
|Barrierefreiheitsbeauftragte(r)|Er/Sie hat Einfluss darauf, dass die Benutzeroberfläche nach WCAG/BITV für alle Personen zugänglich ist.|


## Systemkontext

<!-- Mindestens fünf Aspekte. Art: Person, System im Betrieb, Prozess,
     Ereignis oder Dokument. -->

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
|
| Benutzer (Studierende / Lehrende) | Person | Das System muss Schnittstellen und Ansichten bieten, damit Personen Termine buchen und verwalten können. |
| THM-Benutzerdatenbank (LDAP/Active Directory) | System im Betrieb | Das System muss Benutzer authentifizieren, um Rollen und Berechtigungen korrekt zuzuordnen. |
| Prüfungsordnung / Vorlesungsplan | Dokument | Das System muss Terminüberschneidungen mit regulären Lehrveranstaltungen berücksichtigen. |
| Semesterbeginn / Vorlesungsfreie Zeit | Ereignis | Das System muss Terminverfügbarkeiten automatisch an Vorlesungs- und Prüfungsphasen anpassen. |
| Modulhandbuch / Sprechstundenrichtlinie | Richtlinie / Dokument | Das System muss Regeln vorgeben, wie lange Sprechstunden üblicherweise dauern dürfen. |

## Irrelevante Umgebung

<!-- Zwei Dinge, welche es an der THM gibt, die für den Terminplaner jedoch
     keine Rolle spielen, je mit einer kurzen Begründung. -->
| Objekt / Entität | Begründung |
|---|---|
- |Mensa-Speiseplan der THM  — Der Speiseplan ist für die Buchung und Organisation von akademischen Sprechstunden nicht relevant.
- Parkplatzschranken-Steuerung der THM — …
