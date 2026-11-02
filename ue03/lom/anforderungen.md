# Anforderungen – Terminplaner der THM

Kürzel: lom

| ID | Anforderung | Stakeholder | Typ |
|---|---|---|---|
| A01 | Das System muss Studierenden ihre bevorstehenden gebuchten Termine anzeigen. | Studierende | FA |
| A02 | Das System muss Lehrenden ermöglichen, die maximale Teilnehmerzahl eines Termins festzulegen. | Lehrende | FA |
| A03 | Das System muss Studierenden ermöglichen, eigene Terminbuchungen zu stornieren. | Studierende | FA |
| A04 | Das System muss bei einer ungültigen Eingabe eine verständliche Fehlermeldung direkt am betroffenen Eingabefeld anzeigen. | Studierende | QA |
| A05 | Das System muss bei einer Bildschirmbreite von 360 Pixeln ohne horizontales Scrollen bedienbar sein. | Studierende | QA |
| A06 | Das System muss während der Vorlesungszeit eine monatliche Verfügbarkeit von mindestens 99 Prozent erreichen. | Rechenzentrum der THM | QA |
| A07 | Die Verarbeitung personenbezogener Daten muss den Vorgaben der DSGVO entsprechen. | Datenschutzbeauftragte | RB |
| A08 | Das System muss innerhalb der Infrastruktur des Rechenzentrums der THM betrieben werden. | Rechenzentrum der THM | RB |

## Implizite Anforderung

A03 wird als implizite Anforderung abgeleitet, weil Studierende einen gebuchten Termin möglicherweise nicht wahrnehmen können. Durch die Stornierung wird der Platz wieder für andere Studierende verfügbar.