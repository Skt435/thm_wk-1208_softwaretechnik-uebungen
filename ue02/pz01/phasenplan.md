# Phasenplan — Terminplaner für die THM

Kürzel: pz01

## Studie

**Ergebnis der Phase:** Machbarkeitsstudie mit Bewertung der Lösungsalternativen und grobem Projektplan.

- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt
- Aufwand schätzen und einen Meilensteinplan vorschlagen
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert

## Systemspezifikation

**Ergebnis der Phase:** Abgestimmte Anforderungsspezifikation mit Funktionen, Daten, Schnittstellen und Testkriterien.

- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde

## Systemkonstruktion

**Ergebnis der Phase:** Technischer Systementwurf mit Komponenten, Schnittstellen und Architekturentscheidungen.

- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Datenbank, Programmiersprache und Web-Framework auswählen
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten

## Implementierung

**Ergebnis der Phase:** Programmierte und einzeln getestete Softwarekomponenten.

- Die Komponente „Benachrichtigung“ programmieren
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt

## Integration & Einführung

**Ergebnis der Phase:** Zusammengeführtes, getestetes und eingeführtes Gesamtsystem.

- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt

## Wartung

**Ergebnis der Phase:** Fehlerkorrekturen, Unterstützung und Weiterentwicklung des eingesetzten Systems.

- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen** (Systemspezifikation): Systemspezifikation oder Systemkonstruktion? Hier geht es vor allem darum, mit Studierenden die Anforderungen an die Bedienung abzustimmen.
- **Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert** (Studie): Studie oder Implementierung? Ich ordne ihn der Studie zu, weil damit die technische Machbarkeit überprüft werden soll.
- **Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde** (Systemspezifikation): Systemspezifikation oder Testphase? Die Testfälle werden bereits bei der Spezifikation festgelegt, auch wenn man sie erst später ausführt.

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=studie k03=integration k04=spezifikation k05=wartung k22=spezifikation k06=konstruktion k07=studie k08=integration k09=konstruktion k10=spezifikation k11=wartung k12=implementierung k23=konstruktion k13=studie k14=spezifikation k15=studie k16=integration k17=wartung k18=konstruktion k19=spezifikation k24=integration k20=integration k21=spezifikation | unsicher: k10 k15 k21 -->
