# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Studierende sollen online sehen können, welche Sprechstundentermine noch frei sind. | Studierende | FA |
| A02 | Studierende sollen einen freien Termin direkt über das System buchen können. | Studierende | FA |
| A03 | Lehrende sollen ihre Sprechstunden selbst eintragen und ändern können. | Lehrende | FA |
| A04 | Nach einer Buchung soll man eine Bestätigung bekommen. | Studierende | FA |
| A05 | Mindestens 8 von 10 Studierenden sollen einen Termin ohne Hilfe buchen können. | Studierende | QA |
| A06 | Das System soll bei normaler Nutzung freie Termine innerhalb von 3 Sekunden anzeigen. | Studierende | QA |
| A07 | Die Anmeldung soll mit dem Hochschulkonto der THM funktionieren. | Rechenzentrum der THM | RB |
| A08 | Das System soll auf den Servern der THM laufen können. | Rechenzentrum der THM | RB |
| A09 | Das System darf keine Termine anbieten, die schon in der Vergangenheit liegen. | Studierende | FA |

## Eine Anforderung, die niemand ausgesprochen hat

A09 ist implizit, weil es eigentlich klar ist, dass man keine Termine buchen kann, die schon vorbei sind. Deswegen hat es wahrscheinlich niemand extra erwähnt, aber das System muss trotzdem darauf achten, dass solche Termine nicht mehr angeboten werden.