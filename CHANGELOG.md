# Changelog

## Version 2.4 – 25.11.2026
- Neu: **Offline nutzbar.** Die App wird beim ersten Öffnen auf dem Gerät zwischengespeichert und läuft danach auch ohne Netz. Ist Netz da, kommt immer die neueste Version.
- Das Design (Tailwind) liegt jetzt als Datei `tailwind.css` in der App statt von `cdn.tailwindcss.com` geladen zu werden: keine Verbindung zu fremden Servern mehr, kein Ausfallrisiko. Nur der Knopf «💬 Feedback» braucht Netz.

## Version 2.3 – 22.11.2026
- Neu: Fortschritt und Bestwerte (Punkte, Genauigkeit, Zeit pro Note) pro Einstellung, nur auf diesem Gerät gespeichert. Auf dem Startbildschirm, mit Zurücksetzen-Knopf.
- Neu: Meldung in der Auswertung bei neuer Bestleistung.
- Neu: «🖨 Arbeitsblatt zum Ausdrucken»: Noten nach den aktiven Einstellungen (8–18 Noten), Seite 1 Aufgaben mit Namen/Datum, Seite 2 Lösungen.

## Version 2.2 – 21.11.2026
- Neu: Zurück-Geste / Zurück-Taste (Handy, Tablet) geht einen Schritt zurück (Training → Start, Theorie/Einstellungen → Üben, Auswertung schliessen) statt die App zu schliessen.

## Version 2.1 – 21.11.2026
- Neuer Knopf «💬 Feedback» in der Navigation: öffnet ein anonymes Formular für Fehler, Inhaltsfehler und Wünsche. Version und Gerät werden automatisch mitgegeben; es werden keine Namen abgefragt.

## Version 2 – 17.11.2026
- **Fehler behoben:** Im Bassschlüssel standen alle Noten eine Stufe zu tief (unterste Linie war A statt G). Betraf Training und Bass-Übersicht.
- Zoomen mit zwei Fingern auf Handy/Tablet wieder möglich.
- Klaviertasten klingen in der Oktave der angezeigten Note.
- Vorzeichen-Wahl wirkt während einer laufenden Runde sofort auch auf die Kreuz-/B-Knöpfe.
- Gemischter Modus: Zusammenfassung zeigt beide Tonumfänge.
- Nachschlage-Übersicht: Schweizer Oktavschreibweise (c, c', c'') statt C3/C4.
- Als App installierbar (Chrome auf Android, Tablet, Mac): Manifest, Service Worker (speichert nichts zwischen), Achtelnoten-Icon.

## Version 1
- Archiv unter `versions/v1/`.
