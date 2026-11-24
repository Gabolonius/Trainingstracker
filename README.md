# Trainingstracker

Eine kleine Web-App, um ein physiotherapeutisches Krafttraining am Handy zu begleiten und zu dokumentieren. Sie besteht aus einer einzigen Datei (`index.html`) ohne Server, ohne Anmeldung und ohne externe Abhängigkeiten.

**App öffnen:** https://gabolonius.github.io/Trainingstracker/

## Was die App kann

- **Zwei Einheiten im Wechsel (A und B):** Die App schlägt jeweils die nächste Einheit vor.
- **Ort wählbar (Daheim oder Studio):** Geräteübungen erscheinen nur im Studio. Gewichte und Werte werden pro Ort getrennt geführt.
- **Seitenansicht:** Jede Übung hat eine eigene Seite zum Durchblättern. Alternativ gibt es eine Listenansicht mit allen Übungen.
- **Eingabe:** Wiederholungen und Gewicht stellst du mit +/− ein, dazu das Gerät (Kurzhantel, Kettlebell, Langhantel) und die Variante.
- **Übernahme:** Gewicht, Gerät und Variante werden aus der letzten Einheit übernommen.
- **Steigerung:** Wer in allen Runden 12 Wiederholungen schafft, bekommt einen Hinweis zum Steigern. Danach geht es wieder bei 6 los.
- **Timer:** Es gibt Timer fürs Aufwärmen, für Übungen auf Zeit (z. B. Einbeinstand, links und rechts) und für die Pausen.
- **Infos zu jeder Übung:** Ausführung, worauf zu achten ist, welche Muskeln arbeiten, sowie Links zu kurzen Videos und eine YouTube-Suche.
- **Schmerz-Vermerk während des Trainings** und eine Bewertung am Ende auf 5-stufigen Skalen.
- **Verlauf:** Alle Einheiten mit einer Zusammenfassung zum Kopieren, etwa für die Physiotherapie.

## Am iPhone einrichten

1. Die Adresse oben in **Safari** öffnen.
2. Teilen → **Zum Home-Bildschirm** → Hinzufügen.
3. Die App ab dann **immer über das Icon** öffnen.

Das ist wichtig, weil Safari Daten normaler Websites nach 7 Tagen ohne Besuch löschen kann. Web-Apps am Home-Bildschirm sind davon ausgenommen.

## Wo die Daten liegen

Alle Einträge werden **nur lokal auf dem Gerät** gespeichert, im Browser-Speicher der Web-App. Es wird nichts an GitHub oder einen anderen Server geschickt. Wer die Adresse öffnet, sieht einen leeren Tracker.

Das bedeutet:
- Kein Abgleich zwischen Geräten.
- Die Home-Bildschirm-App und die Seite in Safari haben getrennte Speicher.
- Die Daten gehen verloren, wenn das Icon gelöscht oder die Safari-Websitedaten gelöscht werden.

### Backup

Unter **Verlauf → Sicherung**:
- **Backup erstellen:** speichert alle Einheiten als JSON-Datei, z. B. in iCloud Drive.
- **Backup wiederherstellen:** ergänzt fehlende Einheiten aus einer solchen Datei. Bestehende Einträge werden nicht überschrieben.

Empfehlung: etwa alle ein bis zwei Wochen ein Backup machen, und auf jeden Fall vor größeren Änderungen.

## Updates

Neue Versionen ersetzen einfach `index.html` in diesem Repository. GitHub Pages veröffentlicht sie automatisch nach ein bis zwei Minuten. Die gespeicherten Daten bleiben erhalten, solange die Adresse gleich bleibt.

Worauf man achten sollte:
- Vor dem Update eine offene Einheit abschließen.
- Falls noch die alte Version erscheint, die App ganz schließen und neu öffnen. GitHub Pages speichert Seiten einige Minuten zwischen.
- Das Icon **nicht** löschen und neu anlegen, sonst sind die Daten weg.

## Videos

Die verlinkten Übungsvideos stammen von [Physitrack](https://www.physitrack.com/) und [Sweat](https://sweat.com/exercises). Sie sind auf Englisch und gehören den jeweiligen Anbietern. Die App verlinkt sie nur.

## Hinweis

Die Hinweise zur Ausführung in der App sind allgemein gehalten. Sie ersetzen keine Anleitung durch Physiotherapie oder ärztliche Beratung. Wenn die Therapeutin etwas anderes vorgibt, gilt ihre Anleitung.
