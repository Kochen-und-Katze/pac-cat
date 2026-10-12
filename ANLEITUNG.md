# Pac Cat spielen

1. Das Spieler-ZIP herunterladen und vollständig entpacken oder direkt `Pac-Cat.exe` herunterladen.
2. `Pac-Cat.exe` starten. Dieses Programm öffnet das Spiel ohne Entwicklerwerkzeuge.
3. Unter Spielwelten beispielsweise **Gartenwege → Level 3** wählen und spielen.
4. Nach ungefähr acht Sekunden aktiver Spielzeit erscheint der braune Hund. In Level 1 und 2 bleibt er aus; ab Level 3 erscheint er auch in weiteren Leveln und Welten.

Pac Cat wird mit den Pfeiltasten gesteuert; WASD kann in den Optionen aktiviert werden. Sammle die Gegenstände im Labyrinth, nutze den Katzenbaum und beachte das vorhandene Gesundheits- und Lebenssystem. Das Spielmenü bietet die weiteren Einstellungen und die Rückkehr zur Levelauswahl.

## Der neue Hund

- Er verfolgt Pac Cat und kann bei Berührung Gesundheit abziehen.
- Ein Auftritt dauert höchstens 15 Sekunden. In den letzten drei Sekunden zieht er sich ungefährlich zu einem Tunnel zurück und verschwindet spätestens am Zeitlimit.
- Nach seinem Verschwinden oder seiner Niederlage folgen 60 Sekunden Pause bis zum nächsten Auftritt.
- Während aktiver violetter P-Kraft besiegt Pac Cat den Hund durch Berührung ohne Schaden und erhält 75 Punkte.
- Bestehende Schutzmechanismen bleiben wirksam. Menüs und Unterbrechungen zählen nicht als normale aktive Spielzeit.

Die Hundegrafik ist vorläufig. Die Entwicklerfassung kann die Hunderegel pro Welt und Level verändern; die Standard-Spielerfassung benötigt solche Einstellungen nicht.

## Speichern und Weitergabe

Spielstände und gegebenenfalls Audio-Zwischenspeicher liegen im eigenen Windows-Benutzerordner. Das Spiel benötigt keinen Zugriff auf den ursprünglichen Entwicklungsordner. Jede exportierte Spielausgabe verwendet einen eigenen Speicherbereich; Spielstände der alten Veröffentlichung werden nicht automatisch übernommen.

Für eigene Levels brauchst du den getrennten Baukasten-Download. Eine reine Spieler-EXE öffnet keine `.pclevel`-Projekte. Entwickler können ihre Projekte in eine eigenständige Spiel-EXE exportieren.

## Spielgeräusche
Diese Preview enthält kurze, vorläufige Testtöne für Sammeln, Geistkontakt und die Hundeereignisse. Entwickler können sie im vorhandenen Audio-Baukasten ändern. Siehe AUDIO.md. Eigene Klangzuordnungen werden in exportierte Spieler-EXEs eingebettet.