# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: wnga

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.

## Qualitätsanforderung (QA)

- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.

## Randbedingung (RB)

- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Das System wird im Rechenzentrum der THM betrieben.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.

## Keine Anforderung — Lösung (WIE)

- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.
- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=wie k03=rb k04=rb k05=qa k06=rb k07=wie k08=fa k09=rb k10=qa k11=wie k12=wie k13=rb k14=rb k15=rb k16=fa | unsicher: – -->
