# Stakeholder und Systemkontext — Terminplaner für die THM

<!-- Aufgabe 1 des Übungsblatts. Ersetzen Sie die Platzhalter … und fügen
     Sie so viele Zeilen hinzu, wie Sie benötigen. Löschen Sie die
     Kommentare, sobald Sie fertig sind. -->

## Stakeholder


| Stakeholder | Worauf hat er Einfluss? |
| --- |---|
| Kunden | intuiitive Benutzeroberfläche, schnelle Buchung und automatische Bestätigungsemails|
| Dienstleister | Bestimmen die Logik für Kalendersynchronisation, Stornierungsfristen und konfigurierbare Zeitfenster. |
|Datenschutzbeauftragter (DSB)| Fordert die Einhaltung der DSGVO, wie DSGVO-konforme Datenspeicherung, Einholung von Einwilligungen und Löschkonzepte. |
|Barrierefreiheits-Beauftragter|Beeinflusst die Anforderungen an eine barrierefreie GUI|
|IT-Sicherheitsbeauftragter (CISO)|Zugriff auf das Admin-Dashboard muss durch Zwei-Faktor-Authentifizierung (2FA)|
|Zahlungsdienstleister|Anforderungen an die Online-Bezahlung, Rechnungserstellung und Stornierungsabwicklung.|

## Systemkontext



| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Benutzer(Mitaarbeiter) | Person | Benutzer tragen Tremine ein und lassen sich ohre Termine anzeigen.|
|Administrator| Person|Der Administrator verwaltet Benutzerkonten und legen ggf. Berechtigungen fest.|
|E-Mail-Dienst|System im Betrieb| Der Terminplaner nutzt einen externen E-Mail-Dienst, um Terminerierungen und Einladungen zu verstehen.|
|Terminvereinbarung|Prozess| Bei einer Terminvereinbarung stimmen sich mehrere Personen über einen passenden Zeitpunkt an.|
|Terminabgabe|Ereignis|Eine Absage muss Terminplaner berücksichtigtwerden, damit der Termin nicht mehr als gültig anzeigt wird.|


## Irrelevante Umgebung
   

- Mensa der THM — Der Terminplaner muss keine Informationen über Speisepläne verwalten, da diese für seine künftige Funktion relevant ist.
- Bibiothek der THM — Der Terminplaner muss keine Bücher ausleihen oder den Rückgabefristen verwalten, da diese nicht seinen vorgesehen Aufgaben gehört.
