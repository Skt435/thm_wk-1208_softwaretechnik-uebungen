# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Der selbe Termin kann nicht mehrmals gebucht werden. | Studenten | FA |
| A02 | Die Anmedlung erfolgt über ein verschlüsseltes Internetprotokol (HTTPS). | IT-Abteilung | RB | 
| A03 | Termine können nur Werktags, Montag bis Freitag von 8:00 Uhr bis 17:10 Uhr stattfinden. | Sudierendensekretariat | RB |
| A04 | Der Terminplaner muss rund um die Uhr verfügbar sein. | Studenten | QA |
| A05 | Die Bestätigung der Buchung, Stornierung oder Absage erfolgt höhsten nache einer Minute per E-mail. | Studenten/Lehrende | QA |
| A05 | Der Terminplaner soll eine API enthalten, sodass er über KI-Agenten stuerbar ist, z.B. Abfrage von freien Terminen eines Lehrenden. | Student | FA |
| A07 | Ein gebuchter Termin kann über eine iCal-Datei in den persönlichen Kalender eingebuden werden. | Lehrende/Studenten | FA |
| A08 | Der Terminplaner soll über das Hochschulkonto bedienbar sein. | Studenten | FA |

## Eine Anforderung, die niemand ausgesprochen hat

A01 gilt, da dies als Fehler sofort auffallen würde und falls nicht eingebaut, zu Doppelbuchungen führen kann. Sie hat niemand angesprochen, da es für ein Buchungssystem grundlegend ist, dass es von grund auf Doppelbuchungen verhindert. 
