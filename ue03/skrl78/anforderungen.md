# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Studierende können freie Sprechstundentermine von Lehrenden einsehen. | Studierende | FA |
| A02 | Studierende können einen verfügbaren Termin bei einer Lehrperson buchen. | Studierende | FA |
| A03 | Lehrende können eigene Sprechstunden und Prüfungstermine erstellen und verwalten. | Lehrende | FA |
| A04 | Sekretariate können die Termine ihres Fachbereichs einsehen und verwalten. | Sekretariat | FA |
| A05 | Gebuchte Termine können als iCal-Datei heruntergeladen werden. | Studierende | FA |
| A06 | Die Bedienung des Systems soll einfach und verständlich sein. | Alle Nutzenden | QA |
| A07 | Das System soll auch bei vielen gleichzeitigen Zugriffen zuverlässig funktionieren. | THM | QA |
| A08 | Die Anmeldung erfolgt über das Hochschulkonto der THM. | THM | RB |
| A09 | Der Betrieb des Terminplaners erfolgt auf einer von der THM-IT verwalteten Infrastruktur. | IT-Administratoren | RB |
| A10 | Das System stellt sicher, dass ein angebotener Termin höchstens einmal vergeben wird. | Studierende und Lehrende | FA |

## Implizite Anforderung

A10 wurde von keinem Stakeholder ausdrücklich genannt. Sie ergibt sich jedoch aus dem Zweck der Terminbuchung: Ein Termin darf nicht gleichzeitig mehreren Personen zugeteilt werden.