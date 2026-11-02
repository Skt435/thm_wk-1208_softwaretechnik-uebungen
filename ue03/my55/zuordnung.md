# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: my55

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.

## Qualitätsanforderung (QA)

- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.

## Randbedingung (RB)

- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.

## Keine Anforderung — Lösung (WIE)

- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.
- Das System wird im Rechenzentrum der THM betrieben.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.


