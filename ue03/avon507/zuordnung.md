# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: avon507

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.

## Qualitätsanforderung (QA)

- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.

## Randbedingung (RB)

- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Das System wird im Rechenzentrum der THM betrieben.

## Keine Anforderung — Lösung (WIE)

- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Termine werden in einer PostgreSQL-Datenbank gespeichert.** (Keine Anforderung — Lösung (WIE)): Könnte auch RB sein, wenn Verwendung PSQL zwingend vorgeschrieben wird.
- **Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.** (Funktionale Anforderung (FA)): Könnte auch QA sein, Vermeidung von Doppelbuchung Zuverlässigkeit Systems dient.
- **Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.** (Keine Anforderung — Lösung (WIE)): Könnte auch FA sein, das system muss prüfen ob der Termin frei ist. Behandelt eher das Wie und nicht Was
- **Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.** (Funktionale Anforderung (FA)): Könnte auch QA sein, eine Anforderung an die Bedienbarkeit oder Übersichtlichkeit für das Sekretariat

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=wie k03=rb k04=qa k05=fa k06=rb k07=wie k08=fa k09=rb k10=qa k11=wie k12=fa k13=qa k14=fa k15=rb k16=fa | unsicher: k02 k05 k07 k14 -->
