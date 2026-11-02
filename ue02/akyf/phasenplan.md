# Phasenplan — Terminplaner für die THM

Kürzel: akyf

## Studie

**Ergebnis der Phase:** Gesammelte Daten wurden bewertet und haben Antworten auf offenen Fragen oder Hypothesen geliefert.

- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt

## Systemspezifikation

**Ergebnis der Phase:** hier ist es ganz klar, was vom System erwartet wird.

- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde
- Aufwand schätzen und einen Meilensteinplan vorschlagen
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen

## Systemkonstruktion

**Ergebnis der Phase:** Es wurde hier festgestellt, wie der System gebaut werden wird.

- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Datenbank, Programmiersprache und Web-Framework auswählen
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden
- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen

## Implementierung

**Ergebnis der Phase:** Der theoretische Plan ist in der Praxis umgesetzt worden.

- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Die Komponente „Benachrichtigung“ programmieren
- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten

## Integration & Einführung

**Ergebnis der Phase:** die einzelnen Teile des Systems sind zu einem Ganzen zusammengebaut worden.

- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen

## Wartung

**Ergebnis der Phase:** entweder funktioniert das System oder nicht.

- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert
- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

Keine Karte markiert.

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=implementierung k03=integration k04=integration k05=wartung k22=konstruktion k06=konstruktion k07=studie k08=integration k09=konstruktion k10=studie k11=integration k12=wartung k23=implementierung k13=spezifikation k14=spezifikation k15=wartung k16=integration k17=konstruktion k18=konstruktion k19=konstruktion k24=wartung k20=studie k21=spezifikation | unsicher: – -->
