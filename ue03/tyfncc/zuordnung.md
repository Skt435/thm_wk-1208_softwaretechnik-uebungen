# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: tyfncc

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

## Keine Anforderung — Lösung (WIE)

- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.** (Randbedingung (RB)): Die Anmeldung könnte auch eine funktionale Anforderung sein, da sie eine Funktion des Systems beschreibt. Ich habe mich für eine Randbedingung entschieden, weil die Nutzung des bestehenden Hochschulkontos verbindlich vorgegeben ist und keine andere Anmeldemöglichkeit erlaubt wird.
- **Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.** (Randbedingung (RB)): Ich war zwischen Qualitätsanforderung und Randbedingung unsicher. Ich habe mich für eine Randbedingung entschieden, da die DSGVO eine gesetzliche Vorgabe ist, die das System zwingend einhalten muss.
- **Das System wird im Rechenzentrum der THM betrieben.** (Randbedingung (RB)): ch war zwischen Randbedingung und Systemkonstruktion unsicher. Ich habe mich für eine Randbedingung entschieden, weil der Betriebsort vorgegeben ist, ohne die konkrete technische Umsetzung des Systems festzulegen.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=wie k03=rb k04=qa k05=fa k06=rb k07=wie k08=fa k09=rb k10=qa k11=wie k12=fa k13=qa k14=fa k15=rb k16=fa | unsicher: k03 k09 k15 -->
