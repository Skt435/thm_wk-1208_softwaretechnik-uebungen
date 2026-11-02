# Anforderung oder Lösung? — Terminplaner für die THM
Kürzel: iaa

## Funktionale Anforderung (FA)
- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.

## Qualitätsanforderung (QA)
- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.

## Randbedingung (RB)
- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Das System wird im Rechenzentrum der THM betrieben.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.

## Keine Anforderung — Lösung (WIE)
- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?
- „Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.“: Randbedingung, wenn die THM die Schnittstelle vorgibt. Wenn das Entwicklungsteam das selbst entscheidet, wäre es WIE.
- „Das System wird im Rechenzentrum der THM betrieben.“: Randbedingung, weil der Betriebsort von der THM vorgegeben wird. Als Deployment-Entscheidung des Teams wäre es WIE.