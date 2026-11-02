# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: andel0

## Funktionale Anforderung (FA)

- Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
- Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
- Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
- Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.

## Qualitätsanforderung (QA)

- Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
- Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
- Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.

## Randbedingung (RB)

- Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
- Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
- Das System wird im Rechenzentrum der THM betrieben.
- Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
- Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.

## Keine Anforderung — Lösung (WIE)

- Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.
- Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.
- Termine werden in einer PostgreSQL-Datenbank gespeichert.
- Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.** (Keine Anforderung — Lösung (WIE)): Die Wörter API und KI-Agenten klingen mir etwas zu sehr technisch. Daher denke ich nicht, dass diese Aussage der Kategorie FA zugehört sondern eher WIE.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=wie k03=rb k04=qa k05=qa k06=rb k07=wie k08=fa k09=rb k10=qa k11=wie k12=fa k13=rb k14=fa k15=rb k16=wie | unsicher: k16 -->
