# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: ecib

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
- Das System wird im Rechenzentrum der THM betrieben.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.

## Qualitätsanforderung (QA)

- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.

## Randbedingung (RB)

- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.

## Keine Anforderung — Lösung (WIE)

- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=qa k03=fa k04=wie k05=rb k06=wie k07=fa k08=qa k09=qa k10=qa k11=fa k12=fa k13=fa k14=rb k15=fa k16=fa | unsicher: – -->
