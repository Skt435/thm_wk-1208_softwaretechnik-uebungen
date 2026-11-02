# Anforderung oder Lösung? — Terminplaner für die THM

Kürzel: uwar

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

- **Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.** (Randbedingung (RB)): RB, weil die THM das Hochschulkonto vorgibt und keine eigene Benutzerverwaltung zulässt; als FA ließe es sich lesen, weil Anmelden etwas ist, das das System tut.
- **Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.** (Keine Anforderung — Lösung (WIE)): WIE, weil Komponenten und ihr Zusammenspiel erst in der Konstruktion entstehen; dahinter steckt die Anforderung, dass ein Termin nicht doppelt gebucht wird , die gehört in die Spezifikation, der Weg dorthin nicht.
- **Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.** (Qualitätsanforderung (QA)): QA, weil Last und Antwortzeit angegeben und damit messbar sind; für eine FA fehlt eine Funktion, es wird nur beschrieben, wie gut eine bestehende arbeitet.
- **Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.** (Keine Anforderung — Lösung (WIE)): WIE, weil Protokoll und Datenformat technische Festlegungen der Konstruktion sind; als RB ließe es sich lesen, falls die THM REST für alle Systeme vorschreibt.

<!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=wie k03=rb k04=qa k05=fa k06=rb k07=wie k08=fa k09=rb k10=qa k11=wie k12=fa k13=qa k14=fa k15=rb k16=fa | unsicher: k03 k07 k10 k11 -->
