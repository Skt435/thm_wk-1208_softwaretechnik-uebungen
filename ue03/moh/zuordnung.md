# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: moh

## Funktionale Anforderung (FA)

- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
- Das System wird im Rechenzentrum der THM betrieben.

## Qualitätsanforderung (QA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.

## Randbedingung (RB)

- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.

## Keine Anforderung — Lösung (WIE)

- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=qa k02=wie k03=rb k04=qa k05=fa k06=wie k07=wie k08=fa k09=rb k10=fa k11=fa k12=qa k13=fa k14=fa k15=fa k16=qa | unsicher: – -->
