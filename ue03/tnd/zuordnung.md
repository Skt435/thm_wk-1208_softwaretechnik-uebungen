# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: tnd

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.

## Qualitätsanforderung (QA)

- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.

## Randbedingung (RB)

- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Das System wird im Rechenzentrum der THM betrieben.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.

## Keine Anforderung — Lösung (WIE)

- …

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=qa k03=fa k04=qa k05=fa k06=rb k07=qa k08=fa k09=rb k10=qa k11=fa k12=fa k13=rb k14=qa k15=rb k16=fa | unsicher: – -->
