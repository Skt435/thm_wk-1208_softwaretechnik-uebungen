# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Die Studierenden können nach der Buchung eines Termin, sich diesen als eine iCal-Datei herunterladen. | Studierende | FA |
| A02 | Wenn die Lehrperson einen Termin absagt, wird automatsich eine Nachricht an den Studierenden gesendet, um diesen darüber zu informieren. | Lehrende | FA |
| A03 | Die Mitarbeiter des Sekreteriats haben einen Überblick über alle Termine die bereits gebucht wurden oder noch gebucht werden können. | Sekreteriat | FA |
| A04 | Menschen, die durch eine Einschränkung auf einen Screenreader angewiesen sind, sollen den Terminplaner genauso nutzen können. | Menschen mit Behinderung | QA |
| A05 | Die Buchung der Termine soll einfach, schnell und übersichtlich in maximal 3 Schritten erfolgen. | Studierende | QA |
| A06 | Damit ein schnelles Buchen von Terminen möglich ist, erfordert es ein schnell reagierendes System, das eine Seite in höchstens 2 Sekunden öffnet, auch wenn mehrere tausend Studenten das System gleichzeitig nutzen wollen. | Studierende | QA |
| A07 | Das System soll im eigenen Rechenzentrum der THM betrieben werden, damit Kosten gespart werden. | Hochschul-IT | RB |
| A08 | Es muss darauf geachtet werden, dass die Daten der Benutzer, nach den Vorgaben der EU-DSGVO verarbeitet werden. | Datenschutzbeauftragte | RB |
| A09 |  Ein Termin kann nur einmal gebucht werden, auch wenn zwei Personen gleichzeitig versuchen einen Termin zu buchen, wird die Buchung nur bei einer Person erfolgreich klappen und bei der anderen wird eine Meldung auftauchen, dass der Termin bereits vergeben ist. | Studierende | FA |

## Eine Anforderung, die niemand ausgesprochen hat

Anforderung A 09 - Vermeidung von Doppelbuchungen
1. Zwei Studierende versuchen gleichzeitg einen Termin zu buchen.
2. Das System prüft, ob der Termin noch frei ist.
3. Nur bei einer Person kann die Buchung bestätigt werden, während die andere Person eine Fehlermeldung erhalten wird.

Diese Anforderung wurde nicht konkret angesprochen, weil es ja eigentlich selbstverständlich ist, dass ein Termin nur einmal gebucht wird und man nicht darüber nachgedacht hat, was passiert wenn zwei Leute gleichzeitig denselben Termin haben wollen.
