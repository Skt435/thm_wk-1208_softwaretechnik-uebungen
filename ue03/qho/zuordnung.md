# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: qho

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.

## Qualitätsanforderung (QA)

- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Das System wird im Rechenzentrum der THM betrieben.

## Randbedingung (RB)

- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.

## Keine Anforderung — Lösung (WIE)

- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

