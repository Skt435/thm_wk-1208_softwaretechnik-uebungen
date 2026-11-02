# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 |Lehrende können im System Sprechstunden und Prüfungstermine anlegen.|Lehrende| FA
|A02 |Studierende können im System Sprechstunden und Prüfungstermine buchen.|Studierende | FA
|A03 |Das Sekretariat kann im System alle Termine und Buchungen ihres Fachbereichs einsehen. |Sekretariat | FA
| A04 |Lehrende und Studierende können gebuchte Termine als iCal-Datei herunterladen. |Lehrende, Studierende | FA
| A05 |	Die Anmeldung am System erfolgt ausschließlich über das Hochschulkonto der THM. | Rechenzentrum | RB
| A06 |Das System verarbeitet personenbezogene Daten gemäß DSGVO. |Datenschutzbeauftragter | RB
| A07 |Das System reagiert auf jede Eingabe (z. B. Termin buchen) innerhalb von höchstens 2 Sekunden. | Studierende, Lehrende | QA
| A08 |Eine Studentin kann nach der Anmeldung einen freien Termin in höchstens 1 Minute buchen. | Studierende| QA
| A09 |Ein Termin kann nur von einer Person gebucht werden. Ist er belegt, kann ihn niemand anderes mehr buchen. | Lehrende, Studierende| FA (implizit)

## Eine Anforderung, die niemand ausgesprochen hat

 A09: Dass ein Termin nicht doppelt vergeben werden darf, hat im Gespräch niemand gesagt, weil es für alle selbstverständlich ist: Auf der Liste an der Bürotür ist eine belegte Zeile für jeden sichtbar.
