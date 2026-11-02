# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: anddun

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.

## Qualitätsanforderung (QA)

- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.

## Randbedingung (RB)

- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.

## Keine Anforderung — Lösung (WIE)

- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Das System wird im Rechenzentrum der THM betrieben.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=fa k03=rb k04=qa k05=qa k06=wie k07=fa k08=rb k09=rb k10=qa k11=fa k12=fa k13=qa k14=qa k15=wie k16=fa | unsicher: – -->
