# Phasenplan — Terminplaner für die THM

GitHub-Benutzername: thm-nos

## Studie

**Ergebnis der Phase:** Lastenheft mit Vorschlägen, Empfehlungen und einem ersten Projektplan.

- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Aufwand schätzen und einen Meilensteinplan vorschlagen

## Systemspezifikation

**Ergebnis der Phase:** Erstes Fachkonzept -> Pflichtenheft

- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen

## Systemkonstruktion

**Ergebnis der Phase:** Architektur des Projekts als erster technischer Prototyp  (+ erste Interface-Idee)

- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Datenbank, Programmiersprache und Web-Framework auswählen
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen

## Implementierung

**Ergebnis der Phase:** Programmierte Funktionalitäten,

- Die Komponente „Benachrichtigung“ programmieren
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt

## Integration & Einführung

**Ergebnis der Phase:** Test-loop von Funktionalitäten (bis Zufriedenheit) & App-Prototyp

- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt

## Wartung

**Ergebnis der Phase:** Fertige Application, kontinuierliche Fehlerbehebung & Bug-Fixing

- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen** (Wartung): Einfach nur Unsicher
- **Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten** (Implementierung): Systemspezifikation /Implementierung

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=studie k03=integration k04=spezifikation k05=wartung k22=spezifikation k06=konstruktion k07=studie k08=integration k09=konstruktion k10=spezifikation k11=wartung k12=implementierung k23=konstruktion k13=studie k14=spezifikation k15=konstruktion k16=integration k17=wartung k18=implementierung k19=spezifikation k24=integration k20=integration k21=spezifikation | unsicher: k11 k18 -->
