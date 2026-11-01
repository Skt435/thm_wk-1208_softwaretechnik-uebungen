# Übung 4 — Einen Coding Agent einrichten

In dieser Übung installieren Sie einen Coding Agent — das Übungsblatt
beschreibt opencode —, verbinden ihn mit einem Sprachmodell und setzen ihn
zum ersten Mal in Ihrem lokalen Klon dieses Repositorys ein. Die Aufgaben stehen im
[Übungsblatt](https://carstenlucke.github.io/thm_wk-1208_softwaretechnik/ue04-coding-agent/).

## Was Sie einreichen

Einzureichen ist ein Verzeichnis `ue04/<benutzername>/` mit zwei Dateien,
und zwar als Pull Request vom Branch `ue04-<benutzername>`. Gemeint ist Ihr
GitHub-Benutzername in Kleinbuchstaben.

| Datei | Aufgabe | Woher |
|---|---|---|
| `einrichtung.md` | 1 und 2 — womit Sie arbeiten, und ob die Antwort des Agenten stimmt | aus `_vorlage/` |
| `sitzung.md` | 2 — die Sitzung mit dem Agenten | entsteht mit `/export` in Ihrem Agenten |

1. Kopieren Sie das Verzeichnis `_vorlage` nach `<benutzername>`. Die Vorlage
   selbst bleibt unverändert.
2. Füllen Sie `einrichtung.md` im Lauf der Übung aus und legen Sie
   `sitzung.md` hinzu. Entfernen Sie dort vor dem Commit Pfade mit dem
   Namen Ihres Kontos auf dem Rechner, Namen und E-Mail-Adressen; das
   Repository ist öffentlich.

Läuft Ihr Agent nicht, reichen Sie trotzdem ein: nur
`einrichtung.md`, mit *nein* oder *teilweise* bei „Läuft der Agent?“ und
einem Beleg im Abschnitt „Wenn es nicht läuft“ — Schritt, Befehl samt Ausgabe (wörtlich)
und was Sie bereits versucht haben.

Das Übungsblatt beschreibt opencode, schreibt es aber nicht vor. Wer schon
mit einem anderen Agenten arbeitet — Claude Code, Codex, GitHub Copilot in
VS Code oder als Copilot CLI, eine andere Erweiterung —, darf ihn verwenden
und trägt ihn in `einrichtung.md` unter „Werkzeug“ ein.

Weitere Dateien, welche der Agent anlegt, gehören nicht in den Pull Request.

> [!IMPORTANT]
> Für diese Übung gibt es 1 Bonuspunkt. Diesen erhält nur, wer bis zur
> Frist im Moodle-Kurs selbst einen Pull Request mit Inhalten gestellt hat.
