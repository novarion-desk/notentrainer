# Notentrainer CH – Notenlesen & Musiktheorie

Live-App: https://novarion-desk.github.io/notentrainer/

## Aufbau

| Pfad | Inhalt |
|---|---|
| `index.html` | Aktuelle Version der App |
| `manifest.webmanifest`, `sw.js`, `icons/` | Installierbar als App und offline nutzbar (Chrome: Menü → «App installieren») |
| `tailwind.css` | Design (aus Tailwind v3 gebaut, nur die benutzten Klassen). Bei neuen Tailwind-Klassen in `index.html` neu bauen |
| `versions/vX/` | Archiv älterer Versionen – jede ist direkt aufrufbar |
| `CHANGELOG.md` | Was sich in welcher Version geändert hat |

## Zu einer älteren Version zurück

- Version 2.3: (aktuell, Hauptversion)
- Version 2.2: https://novarion-desk.github.io/notentrainer/versions/v2.2/
- Version 2.1: https://novarion-desk.github.io/notentrainer/versions/v2.1/
- Version 2: https://novarion-desk.github.io/notentrainer/versions/v2/
- Version 1: https://novarion-desk.github.io/notentrainer/versions/v1/

Funktioniert die aktuelle Version nicht, den Link der vorherigen Version öffnen.
Danach Claude sagen, dass die alte Version wieder zur Hauptversion werden soll.

## Daten

Keine Anmeldung. Fortschritt und Bestwerte werden nur lokal auf dem Gerät gespeichert (localStorage `nt-prog`) und können in der App zurückgesetzt werden.

## Feedback
Der Knopf «💬 Feedback» öffnet ein externes, anonymes Formular bei Tally (Fehler, Wünsche, Inhalte). Nur dann werden Angaben gesendet – zusammen mit App-Name, Version und Gerätetyp. Namen werden nicht abgefragt.
