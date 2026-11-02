# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: javu

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.
- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.

## Qualitätsanforderung (QA)

- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.

## Randbedingung (RB)

- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Das System wird im Rechenzentrum der THM betrieben.

## Keine Anforderung — Lösung (WIE)

- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=wie k03=qa k04=fa k05=qa k06=rb k07=wie k08=fa k09=rb k10=qa k11=wie k12=fa k13=fa k14=fa k15=rb k16=fa | unsicher: – -->
