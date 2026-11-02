# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Dozenten können feste Sprechstunden für bestimmte Wochentage im System freigeben. | Dozenten | FA |
| A02 | Studierende können sich einfach einen freien Termin für eine Sprechstunde buchen. | Studierende | FA |
| A03 | Wenn eine Sprechstunde ausfällt, bekommen alle angemeldete Personen automatisch eine kurze Nachricht. | Studierende | FA |
| A04 | Nach einer Sprechstunde können Dozenten Notizen direkt im System apspeichern.  | Dozenten | FA |
| A05 | Die Bedienung der Seite muss auf dem Handy genauso gut funktionieren wie am Laptop | Alle Nutzer | QA |
| A06 | Jede Buchung muss sofort vom Server bestätigt werden, ohne dass man lange warten muss. | Alle Nutzer | QA |
| A07 | Der LOGIN läuft ausschließlich über den ganz normalen Hochschulaccount. | Rechenzentrum | RB |
| A08 | Das Aussehen der Seite muss sich an die offiziellen Vorgaben der Hochschule halten. | Fachbereichsverwaltung | RB

## Eine Anforderung, die niemand ausgesprochen hat

- A09: Zwei Termine für dieselbe Person dürfen sich zeitlich niemals überschneiden.
- Begründung: Das hat im Gespräch niemand extra erwähnt, weil es für jeden Menschen völlig logisch ist, dass man zur selben Uhrzeit nicht an zwei verschiedenen Orten sein kann. Für das System ist das aber eine wichtige Regel, die trotzdem automatisch gelten muss.
