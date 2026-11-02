# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: z-266

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.

## Qualitätsanforderung (QA)

- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.

## Randbedingung (RB)

- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
- Das System wird im Rechenzentrum der THM betrieben.

## Keine Anforderung — Lösung (WIE)

- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=rb k03=rb k04=qa k05=fa k06=rb k07=wie k08=fa k09=rb k10=qa k11=wie k12=fa k13=qa k14=rb k15=rb k16=fa | unsicher: – -->
