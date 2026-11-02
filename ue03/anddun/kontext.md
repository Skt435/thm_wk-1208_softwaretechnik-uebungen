# Stakeholder und Systemkontext — Terminplaner für die THM

<!-- Aufgabe 1 des Übungsblatts. Ersetzen Sie die Platzhalter … und fügen
     Sie so viele Zeilen hinzu, wie Sie benötigen. Löschen Sie die
     Kommentare, sobald Sie fertig sind. -->

## Stakeholder

<!-- Mindestens sechs Stakeholder, je mit einem Satz dazu, worauf sie
     Einfluss haben. -->

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Terminanbieter | Legen fest, welche Terminarten, Dauern, Öffnungszeiten und Stornoregeln das System abbilden muss. |
Terminbucher | Bestimmen die Anforderungen an Barrierefreiheit, Suchfunktionen, Erinnerungen.|
Mitarbeitende der Anbieter | Beeinflussen, wie Arbeitszeiten, Urlaube, etc. im System verwaltet werden. |
Systemadministrator | Stellt Anforderungen an Benutzerverwaltung, Rechtevergabe, Monitoring, Backup und Betrieb. |
Datenschutzbeauftragte | Bestimmen Anforderunegn an Einwilligung und Datenspeicherung, Löschfristen und Zugriffsschutz nach DSGVO. |
Auftraggeber | Setzen Budget, Zeitrahmen und Funktionsumfang und Prioritäten der Andorderungen. |







## Systemkontext

<!-- Mindestens fünf Aspekte. Art: Person, System im Betrieb, Prozess,
     Ereignis oder Dokument. -->

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Externer Kalenderdienst | System im Betrieb | Der Terminplaner muss Termine mit diesem fremden System abgleichen, kann es aber weder ändern noch steuern. |
Kunden | Person | Sie nutzen das System von außen und bringen unvorhergesehenes Verhalten ein, z.B. Tippfehler. |
Telefonische oder persönliche Terminvergabe | Parallel zum System bestehende Buchungswege können Termine belegen, die das System kennen und berücksichtigen muss. |
Stornierung oder Absage durch den Anbieter | Ereignis | Das System muss auf solche Ereignisse reagieren, z.B. Umbuchung, Benachrichtigung, aber kann sie nicht verhindern oder auslösen. |
Feiertage und Ferienzeiten | Ereignis | Sie bestimmen, wann keine Termine möglich sind und ändern sich nicht unabhängig vom System.

## Irrelevante Umgebung

<!-- Zwei Dinge, welche es an der THM gibt, die für den Terminplaner jedoch
     keine Rolle spielen, je mit einer kurzen Begründung. -->

- Mensa mit Speiseplan und Bezahlsystem — Der künftige Terminplaner hat weder eine Funktion zu Essen oder Bezahlung noch eine Schnittstelle zum Mensasystem.
- Bibliothek mit Medienausleihe — Im SOLL ist weder Ausleihe noch Rückgabe von Medien vorgesehen, und es gibt keinen Datenaustausch mit dem Bibliothekssystem.
