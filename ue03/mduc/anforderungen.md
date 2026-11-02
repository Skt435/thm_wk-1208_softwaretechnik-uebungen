# Anforderungen Terminplaner THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Dozierende können im System freie Zeiten für ihre Sprechstunden und Prüfungen anlegen. | Lehrende | FA |
| A02 | Studierende können offene Termine im System auswählen und fest für sich buchen. | Studierende | FA |
| A03 | Sekretariate können eine Liste aller gebuchten und noch freien Termine aufrufen. | Sekretariate | FA |
| A04 | Das System muss eine Buchung blockieren, wenn der Termin bereits von einer anderen Person gebucht wurde. | Lehrende | FA |
| A05 | Ein Termin muss von den Studierenden in höchstens drei Klicks gebucht werden können. | Studierende | QA |
| A06 | Das System muss die iCal-Datei zum Herunterladen in weniger als zwei Sekunden erzeugen. | Rechenzentrum | QA |
| A07 | Das System darf für den Login nur das normale Hochschulkonto der THM zulassen. | Rechenzentrum | RB |
| A08 | Die Software muss im Webbrowser laufen, ohne dass die Nutzer ein zusätzliches Programm installieren müssen. | Hochschulleitung | RB |

## Eine Anforderung, die niemand ausgesprochen hat

Bei der Anforderung A04 handelt es sich um eine implizite Anforderung. Im Gespräch hat niemand explizit gesagt, dass Doppelbuchungen verhindert werden müssen, weil es für alle völlig selbstverständlich ist, dass ein Terminplaner genau das tut. Ohne diese Sperre wäre das System unbrauchbar, weshalb niemand extra darauf hingewiesen hat.