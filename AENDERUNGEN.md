# v0.5.0-preview

- Neue Comic-Hundedarstellung aus dem bereitgestellten Entwurf, mit transparentem Hintergrund für das Labyrinth.
- Liegende PLATZ-Pose aus demselben Entwurf abgeleitet; Zustandsanzeige und verbleibende PLATZ-Zeit bleiben sichtbar.
- Bewegungsdarstellung mit Blickrichtung und leichtem Wippen. Eine vollständige Animation aus mehreren Laufbildern ist noch nicht enthalten.
- Hundestrategie, goldene Knochen, P-Schutz, Gesundheitsregeln und Zeitsteuerung aus v0.4.0-preview bleiben erhalten.
- Der gemeinsame Entwicklerbaukasten und eigenständige Spielerexporte enthalten dieselbe Hundegrafik. Levelprojekte, Audiozuordnungen und bestehende Werkzeuge behalten ihren bisherigen Aufbau.

Grafik und praktische Vergleichsschritte: [HUND-GRAFIK.md](HUND-GRAFIK.md).

Bisherige Releases einschließlich v0.4.0-preview bleiben unverändert. Quellcode bleibt lokal; es gibt kein automatisches Update.

## v0.4.0-preview

- Ab Level 4 standardmäßig fünf erreichbare goldene statt brauner Knochen; Gesamtzahl bleibt gleich.
- Goldene Knochen sind harmlos. Aktiver Hund macht vier Sekunden PLATZ mit Liegepose, Anzeige und gemeinsamer Audiozuordnung.
- PLATZ verlängert nicht die Hundezeit: Rückzug ab Sekunde 12, höchstens 15 Sekunden Anwesenheit, danach 60 Sekunden Pause.
- P schützt ab Level 4 vor Hundebissen, ohne Hundesieg oder 75-Punkte-Bonus. Level 3 und Geister-P-Kraft behalten ihr bisheriges Verhalten.
- Knocheneditor in der vorhandenen Levelprojektoberfläche: Automatik mit vier/fünf Knochen, AUS und sichere eigene Knochenstellen per Mausklick.
- Projekt-Speicherung, normale Levelstarts und eigenständige Exporte übernehmen die Goldregeln.
- Zwei neue Audioereignisse; bisherige Zuordnungen und Werkzeuge bleiben erhalten. Vorläufige Testtöne können ersetzt werden.

Details, Bedienung und Prüfumfang: [GOLDENE-KNOCHEN.md](GOLDENE-KNOCHEN.md).

Bisherige Releases bleiben unverändert. Quellcode bleibt lokal; es gibt kein automatisches Update.
